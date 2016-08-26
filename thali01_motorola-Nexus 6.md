#### Test 82894682a24f9af_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 17:37:16.295  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:16.308  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 17:37:16.312  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 17:37:16.358  1543  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 17:37:16.358  1543  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 17:37:16.358  1543  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:16.359  1543  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 17:37:16.400  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 17:37:16.401  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 17:37:16.402  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 17:37:16.930  3788  3788 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 17:37:16.936  3788  3788 D AndroidRuntime: CheckJNI is OFF
08-26 17:37:16.980  3788  3788 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 17:37:17.032  3788  3788 I Radio-JNI: register_android_hardware_Radio DONE
08-26 17:37:17.053  3788  3788 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 17:37:17.057   874  1462 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 17:37:17.086  2043  2055 W SearchService: Abort, client detached.
08-26 17:37:17.090  3788  3788 D AndroidRuntime: Shutting down VM
08-26 17:37:17.098  2043  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fd63577
08-26 17:37:17.099  2043  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 17:37:17.099  2043  2043 I HotwordDetector: Closing mic
08-26 17:37:17.111   874   885 I ActivityManager: Start proc 3797:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 17:37:17.153   375  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 17:37:17.154   375  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 17:37:17.158   375  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 17:37:17.161  2043  2351 I MicroRecognitionRnrImpl: Detection finished
08-26 17:37:17.161  2043  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 17:37:17.189  3797  3797 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 17:37:17.211  3797  3797 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 17:37:17.219  3797  3797 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9952-9955)
08-26 17:37:17.219  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:17.237  3797  3797 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b37ea25}
08-26 17:37:17.238  3797  3797 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:17.238  3797  3797 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 17:37:17.264  3797  3797 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 17:37:17.270  3797  3797 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 17:37:17.294  3797  3797 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 17:37:17.310  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 17:37:17.310  3797  3797 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 17:37:17.310  3797  3797 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 17:37:17.310  3797  3797 I Adreno  : Build Date                       : 10/20/15
08-26 17:37:17.310  3797  3797 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 17:37:17.310  3797  3797 I Adreno  : Local Branch                     : M14
08-26 17:37:17.310  3797  3797 I Adreno  : Remote Branch                    : 
08-26 17:37:17.310  3797  3797 I Adreno  : Remote Branch                    : 
08-26 17:37:17.310  3797  3797 I Adreno  : Reconstruct Branch               : 
,08-26 17:37:17.370   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@691aac0:true
,08-26 17:37:17.421  3797  3797 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 17:37:17.440  3797  3797 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 17:37:17.546  3797  3836 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 17:37:17.558  3797  3822 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 17:37:17.595  3797  3836 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 17:37:17.680   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +589ms
,08-26 17:37:17.683  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-26 17:37:17.792  3797  3797 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3797
,08-26 17:37:17.945   874  1998 I ActivityManager: Killing 2978:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 17:37:17.960  3797  3797 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 17:37:18.002   874  1998 I ActivityManager: Killing 3191:com.google.android.gm/u0a78 (adj 15): empty #18
,08-26 17:37:18.129  3797  3838 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1714816720
,08-26 17:37:18.135  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 17:37:18.135  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 17:37:18.135  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 17:37:18.135  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 17:37:18.135  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 17:37:18.136  3797  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c23399 added. We now have 1 listener(s)
,08-26 17:37:18.140  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 17:37:18.142  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-26 17:37:18.142  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:18.142  3797  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 17:37:18.146  3797  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ebff0c added. We now have 1 listener(s)
08-26 17:37:18.146  3797  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:18.151   874  1316 D WifiService: New client listening to asynchronous messages
08-26 17:37:18.151  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:18.151  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 17:37:18.152  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
,08-26 17:37:18.152  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-26 17:37:18.152  3797  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 17:37:18.154  3797  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:18.156  3797  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 17:37:18.162  3797  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:18.162  3797  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:18.162  3797  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 17:37:18.162  3797  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:18.164  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:18.165  3797  3838 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 17:37:18.166  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:18.204  3797  3797 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 17:37:19.040  3797  3846 W jxcore-log: Initializing JXcore engine
,08-26 17:37:19.040  3797  3846 W jxcore-log: JXcore engine is ready
,08-26 17:37:19.075  3846  3846 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 17:37:19.075  3846  3846 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10686]" dev="sockfs" ino=10686 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 17:37:19.075  3846  3846 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 17:37:19.075  3846  3846 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26796]" dev="sockfs" ino=26796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 17:37:19.089  3797  3846 W jxcore-log: Starting JXcore engine
,08-26 17:37:19.168  3797  3846 W jxcore-log: Platform android
08-26 17:37:19.168  3797  3846 W jxcore-log: 
08-26 17:37:19.168  3797  3846 W jxcore-log: Process ARCH arm
08-26 17:37:19.168  3797  3846 W jxcore-log: 
,08-26 17:37:19.441  3797  3846 I jxcore-log: JXcore Cordova bridge is ready!
08-26 17:37:19.441  3797  3846 I jxcore-log: 
,08-26 17:37:19.441  3797  3846 W jxcore-log: JXcore engine is started
,08-26 17:37:19.448  3797  3838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 17:37:19.451  3797  3797 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 17:37:19.561   874  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 17:37:23.719  3042  3854 V KeepSync: Connecting to GoogleApiClient
,08-26 17:37:23.720   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 17:37:23.771  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:23.773  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:23.789  1543  2218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 17:37:23.790  1543  2218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 17:37:23.790  1543  2218 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 17:37:23.790  1543  2218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:23.799  1740  3855 V BaseAuthAsyncOperation: access token request failed
,08-26 17:37:23.800  3042  3854 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 17:37:23.840  1543  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 17:37:23.840  1543  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 17:37:23.840  1543  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 17:37:23.840  1543  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:23.858  3042  3854 E KeepSync: IOException
08-26 17:37:23.858  3042  3854 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 17:37:23.858  3042  3854 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 17:37:23.858  3042  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 17:37:23.858  3042  3854 E KeepSync: 	... 10 more
,08-26 17:37:23.858  3042  3854 W KeepSync: Sync result 2
,08-26 17:37:23.865   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 126335, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-26 17:37:28.282   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 17:37:29.310  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 17:37:29.310  3797  3846 I jxcore-log: 
,08-26 17:37:29.313  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 17:37:29.313  3797  3846 I jxcore-log: 
,08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:29.324  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:29.328  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:29.331  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 17:37:29.331  3797  3846 I jxcore-log: 
,08-26 17:37:29.333  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 17:37:29.333  3797  3846 I jxcore-log: 
,08-26 17:37:29.832  3797  3846 D executeNativeTests: Running unit tests
,08-26 17:37:29.889  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:29.890  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 added. We now have 2 listener(s)
,08-26 17:37:29.891  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:29.891  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:29.891  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:29.891  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:29.891  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae added. We now have 2 listener(s)
08-26 17:37:29.891  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:29.892  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:29.893  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:29.907  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:29.912  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:29.913  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:29.915  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:29.916  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:29.920  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 17:37:29.923  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 17:37:29.923  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:29.925  3797  3846 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 17:37:29.925  3797  3846 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 17:37:29.925  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:29.925  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 17:37:29.925  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:29.926  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:29.926  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:29.926  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:29.927  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:29.927  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:29.927  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:29.927  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:29.927  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 removed from the list
,08-26 17:37:29.927  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:29.927  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae removed from the list
,08-26 17:37:29.927  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:29.927  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.928  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:29.928  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.930  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:29.930  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:29.930  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:29.930  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:29.932  3797  3846 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 17:37:29.934  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:29.934  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:29.934  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:29.934  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:29.934  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.934  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.935  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
,08-26 17:37:29.935  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:29.935  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:29.935  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:29.935  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.935  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:29.935  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.935  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.936  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:29.936  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:29.936  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:29.936  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 17:37:29.944  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 17:37:29.945  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 17:37:29.946  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:29.946  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:29.946  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:29.946  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:29.947  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:29.947  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.947  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.947  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:29.947  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:29.947  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:29.947  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:29.947  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.947  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.947  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:29.947  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:29.948  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:29.948  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:29.948  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:29.948  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:29.949  3797  3846 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 17:37:29.951  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:29.957  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:29.960  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:29.960  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:29.960  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:29.961  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:29.961  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:29.961  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:29.961  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:29.962  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:29.964  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:29.966  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 17:37:29.966  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:29.971  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:29.973  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 17:37:29.974  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:29.976  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:29.979  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:29.979  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 17:37:29.979  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:29.980  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 17:37:29.981  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:29.986  2684  2696 D BtGatt.GattService: registerClient() - UUID=ba1e12d5-4516-4cd1-91e1-d83e6f708b6c
08-26 17:37:29.986  2684  2709 D BtGatt.GattService: onClientRegistered() - UUID=ba1e12d5-4516-4cd1-91e1-d83e6f708b6c, clientIf=5
08-26 17:37:29.987  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 17:37:29.988  2684  2697 D BtGatt.GattService: start scan with filters
08-26 17:37:29.991  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:29.991  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:29.991  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:29.991  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 17:37:29.992  2684  2712 D BtGatt.ScanManager: handling starting scan
08-26 17:37:29.993  2684  2712 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
08-26 17:37:29.994  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:29.994  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:29.995  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:29.996  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 17:37:29.999  3797  3846 I io.jxcore.node.ConnectionHelper: start: OK
08-26 17:37:30.000  2684  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 17:37:30.000  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.000  2684  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 17:37:30.002  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.002  3797  3846 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:30.002  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.002  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:30.002  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.002  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:30.003  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:30.003  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:30.003  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:30.003  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:30.004  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:30.004  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:30.004  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 17:37:30.004  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.005  2684  2712 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:30.005  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:30.005  2684  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 17:37:30.005  2684  2697 D BtGatt.GattService: stopScan() - queue size =1
08-26 17:37:30.006  2684  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 17:37:30.006  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:30.006  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:30.006  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:30.007  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:30.007  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 17:37:30.008  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.008  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:30.008  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:30.008  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:30.009  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.011  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.011  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.011  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.011  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.011  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.011  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.011  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.011  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.011  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.011  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.012  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.012  3797  3846 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 17:37:30.014  2684  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 17:37:30.014  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.014  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.018  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.019  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 17:37:30.019  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.020  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.020  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:30.020  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:30.020  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:30.020  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:30.020  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:30.020  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:30.024  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 17:37:30.024  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:30.024  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.026  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 17:37:30.026  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.026  2684  2712 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:30.026  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.029  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:30.030  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 17:37:30.030  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:30.033  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 17:37:30.033  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.033  2684  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 17:37:30.034  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 17:37:30.034  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:30.034  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 17:37:30.035  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:30.037  2684  3860 D BtGatt.GattService: registerClient() - UUID=e9cae2cf-913c-4e86-84de-e7d2a4f04a29
08-26 17:37:30.038  2684  2709 D BtGatt.GattService: onClientRegistered() - UUID=e9cae2cf-913c-4e86-84de-e7d2a4f04a29, clientIf=5
08-26 17:37:30.038  2684  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 17:37:30.038  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.038  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 17:37:30.038  2684  2697 D BtGatt.GattService: start scan with filters
,08-26 17:37:30.042  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:30.042  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:30.042  2684  2712 D BtGatt.ScanManager: handling starting scan
08-26 17:37:30.042  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:30.042  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 17:37:30.044  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:30.044  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:30.045  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:30.046  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 17:37:30.047  2684  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 17:37:30.047  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.048  2684  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 17:37:30.049  3797  3846 I io.jxcore.node.ConnectionHelper: start: OK
08-26 17:37:30.051  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.051  3797  3846 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:30.051  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.051  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:30.051  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.051  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:30.051  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:30.051  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:30.051  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:30.051  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:30.051  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:30.051  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:30.052  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:30.052  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 17:37:30.052  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.052  2684  3860 D BtGatt.GattService: stopScan() - queue size =1
08-26 17:37:30.052  2684  2712 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:30.053  2684  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 17:37:30.053  2684  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 17:37:30.053  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:30.053  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:30.053  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:30.053  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:30.053  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 17:37:30.055  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.055  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:30.055  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:30.055  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:30.055  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.057  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.057  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.057  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.057  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.057  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.057  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.057  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.057  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.058  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.058  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.058  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.058  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.058  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.059  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.059  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.059  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.059  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list,
08-26 17:37:30.060  3797  3846 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 17:37:30.062  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:30.064  2684  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 17:37:30.064  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.067  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:30.069  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:30.069  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:30.070  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:30.070  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 17:37:30.071  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:30.071  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:30.071  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:30.071  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 17:37:30.071  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.071  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.074  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.075  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 17:37:30.075  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:30.079  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:30.080  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 17:37:30.080  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.080  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 17:37:30.080  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:30.080  2684  2712 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:30.085  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 17:37:30.086  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:30.086  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:30.086  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:30.088  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 17:37:30.088  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.088  2684  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 17:37:30.090  2684  2697 D BtGatt.GattService: registerClient() - UUID=5ae4e22c-e449-4034-b9d6-e11e1253b2fe
,08-26 17:37:30.090  2684  2709 D BtGatt.GattService: onClientRegistered() - UUID=5ae4e22c-e449-4034-b9d6-e11e1253b2fe, clientIf=5
08-26 17:37:30.090  3797  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 17:37:30.091  2684  2816 D BtGatt.GattService: start scan with filters
,08-26 17:37:30.095  2684  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 17:37:30.095  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.095  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:30.095  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:30.096  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:30.096  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:30.097  2684  2712 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:30.099  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:30.099  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:30.099  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:30.102  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:30.103  2684  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 17:37:30.103  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.104  2684  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 17:37:30.105  3797  3846 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 17:37:30.105  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.106  3797  3846 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:30.106  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:30.106  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:30.106  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.106  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:30.106  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:30.106  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:30.106  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:30.106  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 17:37:30.107  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:30.107  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:30.108  3797  3846 D BluetoothAdapter: STATE_ON
,08-26 17:37:30.108  2684  2816 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:30.109  2684  3860 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 17:37:30.109  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:30.109  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:30.109  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:30.109  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:30.110  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:30.110  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 17:37:30.110  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.110  2684  2712 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:30.110  2684  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 17:37:30.111  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.111  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:30.111  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 17:37:30.111  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:30.111  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.112  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.112  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.112  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.112  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.112  3797  3846 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:30.113  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:30.113  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.113  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.113  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.113  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:30.113  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.113  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.113  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.113  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.113  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.114  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.114  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.115  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.115  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.115  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.115  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.115  3797  3846 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 17:37:30.116  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.116  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.116  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.116  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.116  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.116  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.116  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.117  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.117  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.117  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.117  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.117  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.117  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.117  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.118  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.118  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.118  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.118  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.119  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:30.119  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.119  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.120  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.120  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.120  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.120  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.120  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.120  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.120  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.120  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.120  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.120  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.120  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.120  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.121  2684  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 17:37:30.121  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.122  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.122  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.122  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.122  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.122  3797  3846 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 17:37:30.123  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.123  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.123  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.123  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.123  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.123  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.123  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.123  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.123  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.123  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.123  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.123  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.124  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.124  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.124  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.124  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:30.124  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.124  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.125  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 17:37:30.125  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.125  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.125  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.125  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.125  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.125  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.126  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.126  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.126  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.126  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.126  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.126  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.126  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.126  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.127  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.127  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.127  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.127  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.127  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 17:37:30.128  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.128  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:30.128  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:30.128  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 17:37:30.128  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:30.129  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:30.129  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:30.129  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.129  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.129  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.129  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:30.129  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.129  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.129  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
,08-26 17:37:30.129  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.129  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.129  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.130  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.130  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.130  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.130  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.131  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.131  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.131  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.131  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.132  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 17:37:30.132  3797  3846 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 17:37:30.132  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:30.136  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-26 17:37:30.136  3797  3846 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-26 17:37:30.136  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:30.137  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:30.138  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:30.139  2684  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 17:37:30.139  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:30.139  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 17:37:30.139  2684  2712 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:30.139  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:30.139  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-26 17:37:30.139  3797  3846 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:30.140  3797  3846 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 17:37:30.140  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:30.141  3797  3846 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:30.141  3797  3846 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 17:37:30.141  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 17:37:30.141  3797  3846 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:30.141  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:30.145  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 17:37:30.145  2684  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 17:37:30.145  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.145  2684  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 17:37:30.146  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 17:37:30.146  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 17:37:30.146  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55,
08-26 17:37:30.146  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-26 17:37:30.146  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-26 17:37:30.147  3797  3846 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 17:37:30.147  3797  3846 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 17:37:30.147  3797  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
,08-26 17:37:30.147  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.148  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.148  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:30.148  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.148  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.148  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.148  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 17:37:30.149  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
,08-26 17:37:30.149  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.149  3797  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:30.149  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.149  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.149  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:30.149  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.149  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.149  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.150  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.150  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.150  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.151  2684  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 17:37:30.151  2684  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:30.150  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.152  3797  3846 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 17:37:30.152  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:30.152  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.152  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:30.153  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.153  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.153  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.153  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.153  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.153  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.153  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.153  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.153  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 17:37:30.153  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.153  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.154  3797  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-26 17:37:30.154  3797  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
08-26 17:37:30.154  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:30.154  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.154  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.154  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.154  2684  2813 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 17:37:30.154  3797  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
08-26 17:37:30.154  3797  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
,08-26 17:37:30.155  3797  3846 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 17:37:30.155  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.155  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.155  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.155  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:30.155  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.155  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.155  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.155  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.155  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.155  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.155  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.155  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.155  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.156  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.157  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.157  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.157  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.157  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.157  3797  3846 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 17:37:30.157  3797  3846 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 17:37:30.157  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:30.158  3797  3846 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 17:37:30.158  3797  3846 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:30.158  3797  3846 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-26 17:37:30.158  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:30.158  3797  3846 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 17:37:30.158  3797  3846 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:30.158  3797  3846 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 17:37:30.158  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 17:37:30.158  3797  3846 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 17:37:30.158  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.158  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:30.158  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.159  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.159  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.159  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.159  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
,08-26 17:37:30.159  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.159  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.159  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.159  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.159  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.160  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.160  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.161  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.161  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.161  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.161  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.162  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.162  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.162  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.162  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
,08-26 17:37:30.162  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.162  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.162  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.162  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.162  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.162  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.162  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.163  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.163  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.163  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.163  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.163  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.163  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.163  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.163  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:30.163  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.163  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.163  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.163  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.163  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.164  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.164  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.164  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.164  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.164  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.165  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 17:37:30.165  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.165  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.165  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list,
08-26 17:37:30.166  3797  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 17:37:30.166  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:30.167  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 17:37:30.167  3797  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 17:37:30.167  3797  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 17:37:30.168  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-26 17:37:30.168  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 17:37:30.168  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:30.168  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:30.168  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 17:37:30.168  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 17:37:30.168  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 17:37:30.168  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:30.168  3797  3846 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 17:37:30.169  3797  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:30.169  3797  3797 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 17:37:30.169  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.169  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.169  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:30.169  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:30.169  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:30.169  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.169  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.170  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:30.170  3797  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 17:37:30.170  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.170  3797  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 17:37:30.171  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:30.171  3797  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 17:37:30.171  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:30.171  3797  3797 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 17:37:30.171  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.171  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:30.171  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.171  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.171  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.171  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.171  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.172  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.172  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.172  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.172  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.172  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.172  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.172  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.172  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.173  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.173  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:30.173  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.173  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.174  3797  3846 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 17:37:30.174  3797  3846 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 17:37:30.174  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:30.174  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:30.174  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:30.175  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.175  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.175  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.175  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.175  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.175  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.175  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.175  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.175  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:30.175  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.175  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.175  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.175  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.176  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.176  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.176  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.176  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.179  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.179  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.180  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.180  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.180  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.180  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.180  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.180  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.180  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.180  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.180  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.180  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.180  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.180  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.181  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.181  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:30.181  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.181  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.182  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:30.182  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:30.182  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:30.182  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:30.182  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.182  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.182  3797  3846 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a137229 not in the list
08-26 17:37:30.182  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:30.182  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
,08-26 17:37:30.182  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:30.183  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.183  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.183  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:30.183  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:30.184  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:30.184  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:30.184  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:30.184  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc649ae not in the list
08-26 17:37:30.185  3797  3846 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 17:37:30.185  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:30.185  3797  3846 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 17:37:30.185  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:30.185  3797  3846 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 17:37:30.185  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:30.187  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:30.187  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 17:37:30.187  3797  3846 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-26 17:37:30.187  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:30.187  3797  3846 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 17:37:30.188  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:30.188  3797  3846 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 17:37:30.188  3797  3846 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 17:37:30.188  3797  3846 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 17:37:30.188  3797  3846 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 17:37:30.189  3797  3846 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 17:37:30.189  3797  3846 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 17:37:30.189  3797  3846 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 17:37:30.189  3797  3846 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-26 17:37:30.190  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:30.190  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf808e0 added. We now have 2 listener(s)
08-26 17:37:30.190  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:30.191  3797  3846 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 17:37:30.192   874  3105 D WifiService: setWifiEnabled: true pid=3797, uid=10000
08-26 17:37:30.192   874  3105 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 17:37:30.192  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:30.193  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5903799 added. We now have 3 listener(s)
08-26 17:37:30.193  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:30.197  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:30.197  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ae7a5e added. We now have 4 listener(s)
08-26 17:37:30.197  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:30.198  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:30.198  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e46ee3f added. We now have 5 listener(s)
08-26 17:37:30.198  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:30.200   874  3101 D WifiService: setWifiEnabled: false pid=3797, uid=10000
08-26 17:37:30.200   874  3101 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:30.207  2684  2705 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 17:37:30.207  2684  2705 D BluetoothAdapterProperties: Setting state to 13
08-26 17:37:30.207  2684  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 17:37:30.207  2684  2705 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 17:37:30.208  2684  2705 I BluetoothAdapterState: Entering PendingCommandState
,08-26 17:37:30.210  2684  2709 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:30.210  2684  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 17:37:30.211  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:30.212  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 17:37:30.214   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 17:37:30.214   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{3}, ntable=[]
08-26 17:37:30.214   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 17:37:30.214   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:30.215  2684  2684 D HeadsetService: Received stop request...Stopping profile...
08-26 17:37:30.220  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.220  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.220  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.221  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.221   874  1893 D DhcpClient: Clearing IP address
08-26 17:37:30.222   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:30.225   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:30.226  1543  3462 V NativeCrypto: Read error: ssl=0x9ad7a600: I/O error during system call, Connection timed out
08-26 17:37:30.229  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.229  1543  3462 V NativeCrypto: SSL shutdown failed: ssl=0x9ad7a600: I/O error during system call, Broken pipe
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.229  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.230  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.230  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:30.230  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:30.231   874  1998 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-26 17:37:30.232   874  1877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 17:37:30.232  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.232  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.233  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.233  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:30.236   874  1877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-26 17:37:30.237  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:30.237  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.237   874   887 I ActivityManager: Start proc 3867:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 17:37:30.237   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-26 17:37:30.237   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-26 17:37:30.238   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 17:37:30.239  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.239  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:30.240   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-26 17:37:30.241   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 17:37:30.244   371   872 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:30.244   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:30.244   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:30.244   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:30.246  1369  1382 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:30.246  2684  2684 D BluetoothMapService: onReceive
,08-26 17:37:30.246  2684  2684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:30.246  2684  2684 D BluetoothMapService: STATE_TURNING_OFF
08-26 17:37:30.246   394   394 E Parcel  : Reading a NULL string not supported here.
,08-26 17:37:30.247  2684  2684 D A2dpService: Received stop request...Stopping profile...
08-26 17:37:30.247  2684  2819 D A2dpStateMachine: Exit Disconnected: -1
08-26 17:37:30.247  1954  2262 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:30.240   874  1894 D DhcpClient: Receive thread stopped
08-26 17:37:30.250   874   874 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:30.250  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.251  2684  2684 V BluetoothAdapterState: isTurningOff()=true
,08-26 17:37:30.251  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.251  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:30.251  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:30.252  2684  2684 D HidService: Received stop request...Stopping profile...
08-26 17:37:30.252  2684  2684 D HidService: Stopping Bluetooth HidService
08-26 17:37:30.254   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 17:37:30.254   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-26 17:37:30.254  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.257  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:30.257  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:30.257   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-26 17:37:30.257  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 17:37:30.257  2684  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 17:37:30.258  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:30.258  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:30.258  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 17:37:30.259  2684  2709 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 17:37:30.261  1369  1369 D HeadsetProfile: Bluetooth service disconnected
08-26 17:37:30.259  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:30.262  2684  2684 D BluetoothMapService: MAP Service closeService in
08-26 17:37:30.263  2684  2684 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 17:37:30.263  2684  2684 D ObexServerSockets0: shutdown(block = true)
08-26 17:37:30.263  1369  1369 D BluetoothA2dp: Proxy object disconnected
,08-26 17:37:30.263  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 17:37:30.263  2684  2836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 17:37:30.263  2684  2837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-26 17:37:30.264  2684  2813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-26 17:37:30.264  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 17:37:30.264   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 17:37:30.264  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:30.264  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:30.265  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:30.265  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:30.267  2684  2684 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:30.267  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:30.267  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:30.267  2684  3426 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 17:37:30.267  2684  3426 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 17:37:30.268  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:30.268  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:30.265  1369  1369 D BluetoothInputDevice: Proxy object disconnected
08-26 17:37:30.268  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:30.268  1369  1369 D HidProfile: Bluetooth service disconnected
,08-26 17:37:30.268  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.269  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:30.269  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:30.273  2684  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 17:37:30.273  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:30.273  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:30.273  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 17:37:30.274  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:30.274  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:30.274  2684  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:30.274  2684  2684 D HealthService: Received stop request...Stopping profile...
,08-26 17:37:30.275  2684  2684 V BluetoothAdapterState: isTurningOff()=true
,08-26 17:37:30.275  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.275  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:30.275  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:30.275  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 17:37:30.275  2684  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 17:37:30.275  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:30.276  2684  2684 D PanService: Received stop request...Stopping profile...
,08-26 17:37:30.277  2148  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:30.277  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 17:37:30.277  1369  1369 D PanProfile: Bluetooth service disconnected
08-26 17:37:30.278  2684  2684 D BluetoothMapService: Received stop request...Stopping profile...
08-26 17:37:30.278  2684  2684 D BluetoothMapService: stop()
08-26 17:37:30.278  2684  2684 D BluetoothMapAppObserver: deinitObservers()
,08-26 17:37:30.278  2684  2684 D BluetoothMapAppObserver: removeReceiver()
08-26 17:37:30.279  1369  1369 D BluetoothMap: Proxy object disconnected
08-26 17:37:30.279  1369  1369 D MapProfile: Bluetooth service disconnected
08-26 17:37:30.280  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:30.280  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.280  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:30.280  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:30.281  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:30.281  2684  2709 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 17:37:30.281  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:30.281  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:30.281  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.281  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:30.281  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:30.282   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 17:37:30.283  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 17:37:30.283  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 17:37:30.285  2684  2684 D BluetoothMapService: MAP Service closeService in
08-26 17:37:30.285  2684  2684 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:30.285  2684  2684 V BluetoothAdapterState: isTurningOn()=false
,08-26 17:37:30.285  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:30.285  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:30.287  2684  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 17:37:30.287  2684  2705 D BluetoothAdapterProperties: Setting state to 15
,08-26 17:37:30.287  2684  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-26 17:37:30.288  2684  2705 I BluetoothAdapterState: Entering BleOnState
,08-26 17:37:30.288  2684  2684 D BluetoothMapService: cleanup()
,08-26 17:37:30.288  2684  2684 D BluetoothMapService: MAP Service closeService in
08-26 17:37:30.293   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 17:37:30.294   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:30.294   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:30.295  1369  1388 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 17:37:30.296  1954  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:30.296  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:30.296  1369  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:30.297  1369  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-26 17:37:30.297   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:30.297  1369  2062 D BluetoothPan: onBluetoothStateChange on: false
08-26 17:37:30.298  1369  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 17:37:30.298   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:30.298  2684  2705 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 17:37:30.299  2684  2705 D BluetoothAdapterProperties: Setting state to 16
08-26 17:37:30.299  2684  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 17:37:30.301  2684  2705 D BluetoothAdapterProperties: onBleDisable
08-26 17:37:30.301  2684  2705 I BluetoothAdapterState: Entering PendingCommandState
08-26 17:37:30.301  2684  2706 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 17:37:30.302  2684  2797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 17:37:30.302  2684  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:30.302  2684  2709 D BluetoothAdapterProperties: Scan Mode:20
08-26 17:37:30.303  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.304  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.305  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.306  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.327   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:30.328   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 17:37:30.329   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:30.331   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-26 17:37:30.332  3374  3374 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4c23399 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 17:37:30.332  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:30.334  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.347  3867  3867 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 17:37:30.357  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:30.361   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1484674:true
,08-26 17:37:30.362  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:30.376   874  3105 I ActivityManager: Start proc 3886:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 17:37:30.385   371   872 E Netd    : netlink response contains error (No such file or directory)
,08-26 17:37:30.386   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 17:37:30.389  3867  3867 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 17:37:30.391  3867  3867 D BluetoothMap: Create BluetoothMap proxy object
,08-26 17:37:30.396  3867  3867 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 17:37:30.403  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:30.405   874  3102 I ActivityManager: Killing 3374:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 17:37:30.418  3886  3886 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 17:37:30.505  2684  2709 I bt_hci  : shut_down
,08-26 17:37:30.505  2684  2713 D bt_hwcfg: hw_epilog_process
,08-26 17:37:30.507  2684  2713 I bt_vendor: low_power_mode_cb
,08-26 17:37:30.532  2684  2713 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 17:37:30.533  2684  2713 I bt_vendor: epilog_cb
,08-26 17:37:30.533  2684  2713 I bt_hci  : epilog_finished_callback
,08-26 17:37:30.541  2684  2709 I bt_hci_h4: hal_close
,08-26 17:37:30.542  2684  2709 I bt_userial_vendor: device fd = 51 close
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.599  3886  3886 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:30.599  3886  3886 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:30.642   874  1462 I ActivityManager: Start proc 3916:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 17:37:30.649   874  1462 I ActivityManager: Killing 3560:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-26 17:37:30.672  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 17:37:30.690  2684  2706 D bt_stack_manager: event_shut_down_stack finished.
,08-26 17:37:30.691  2684  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 17:37:30.695  2684  2705 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 17:37:30.695  2684  2684 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:30.696  2684  2684 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 17:37:30.696  2684  2684 D BtGatt.GattService: stop()
08-26 17:37:30.696  2684  2684 D BtGatt.AdvertiseManager: advertise clients cleared,
08-26 17:37:30.697  2684  2684 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:30.697  2684  2684 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:30.697  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:30.697  2684  2684 V BluetoothAdapterState: isBleTurningOff()=true
08-26 17:37:30.697  2684  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 17:37:30.698  2684  2705 D BluetoothAdapterProperties: Setting state to 10
08-26 17:37:30.698  2684  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 17:37:30.698  2684  2705 I BluetoothAdapterState: Entering OffState
08-26 17:37:30.700   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.,
,08-26 17:37:30.701  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 17:37:30.717  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 17:37:30.717  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 17:37:30.717  2684  2684 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 17:37:30.718  2684  2706 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 17:37:30.721  2684  2706 D bt_stack_manager: event_clean_up_stack finished.
,08-26 17:37:30.734  2684  2684 I art     : System.exit called, status: 0
,08-26 17:37:30.734  2684  2684 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 17:37:30.771  3916  3916 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 17:37:30.797  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:30.819   874  1900 I ActivityManager: Process com.android.bluetooth (pid 2684) has died
,08-26 17:37:30.842   874  3102 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 17:37:30.849  3867  3867 D DockEventReceiver: finishStartingService: stopping service,
08-26 17:37:30.851   874  1998 I ActivityManager: Killing 3601:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-26 17:37:30.897  3886  3904 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 17:37:30.914   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f01664b:true
,08-26 17:37:30.987  3944  3944 D AdapterServiceConfig: Adding HeadsetService
,08-26 17:37:30.987  3944  3944 D AdapterServiceConfig: Adding A2dpService
,08-26 17:37:30.987  3944  3944 D AdapterServiceConfig: Adding HidService
,08-26 17:37:30.988  3944  3944 D AdapterServiceConfig: Adding HealthService
08-26 17:37:30.988  3944  3944 D AdapterServiceConfig: Adding PanService
,08-26 17:37:30.988  3944  3944 D AdapterServiceConfig: Adding GattService
,08-26 17:37:30.988  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 17:37:30.993  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:31.010  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 17:37:31.017  1740  1740 D SystemUpdateService: onCreate
,08-26 17:37:31.031  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 17:37:31.039  1740  3957 I SystemUpdateService: active receiver: enabled
,08-26 17:37:31.048  1740  3957 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 17:37:31.050  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 17:37:31.052  1740  3957 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 17:37:31.052  1740  3957 I SystemUpdateService: now status is 0 (complete)
08-26 17:37:31.052  1740  3957 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 17:37:31.052  1740  3957 I SystemUpdateService: file has been verified
08-26 17:37:31.053  1740  3957 I SystemUpdateService: OTA package size = 12249756
,08-26 17:37:31.054  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 17:37:31.056  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 17:37:31.058  1740  3957 I SystemUpdateService: showing system update notification
08-26 17:37:31.058  1740  2430 I iu.UploadsManager: num queued entries: 0
,08-26 17:37:31.058  1740  2430 I iu.UploadsManager: num updated entries: 0
08-26 17:37:31.059  1740  2430 I iu.SyncManager: NEXT; no task
,08-26 17:37:31.080   874  1974 I ActivityManager: Start proc 3959:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 17:37:31.082  1740  1740 D SystemUpdateService: onDestroy
,08-26 17:37:31.114  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 17:37:31.116  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:31.121  3959  3959 D SprintDMHelper: simOperator: 
08-26 17:37:31.121  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 17:37:31.146   874  1998 I ActivityManager: Start proc 3971:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 17:37:31.147   874  1998 I ActivityManager: Killing 3447:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 17:37:31.268  2467  3985 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 17:37:31.297   874   884 I ActivityManager: Start proc 3986:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 17:37:31.301   874  1900 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-26 17:37:31.351  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 17:37:31.398  3986  3986 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 17:37:31.398  3986  3986 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 17:37:31.398  3986  3986 I GAv4    :   adb logcat -s GAv4
,08-26 17:37:31.411  3986  3986 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:31.416  3986  3986 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:31.437  3986  4003 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:31.549  3986  3986 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 17:37:31.590  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 17:37:31.598  3986  3986 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4331-4334)
,08-26 17:37:31.598  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 17:37:31.612  3986  3986 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ea3509}
,08-26 17:37:31.612  3986  3986 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 17:37:31.612  3986  3986 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 17:37:31.621  3986  3986 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 17:37:31.623  3986  3986 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 17:37:31.637  3986  3986 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 17:37:31.653  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 17:37:31.653  3986  3986 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 17:37:31.654  3986  3986 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 17:37:31.654  3986  3986 I Adreno  : Build Date                       : 10/20/15
08-26 17:37:31.654  3986  3986 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 17:37:31.654  3986  3986 I Adreno  : Local Branch                     : M14
08-26 17:37:31.654  3986  3986 I Adreno  : Remote Branch                    : 
08-26 17:37:31.654  3986  3986 I Adreno  : Remote Branch                    : 
08-26 17:37:31.654  3986  3986 I Adreno  : Reconstruct Branch               : 
,08-26 17:37:31.720  3986  3986 I NSApplication: Starting up...
,08-26 17:37:31.731  3986  4032 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 17:37:31.758   874  1918 I ActivityManager: Start proc 4037:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 17:37:31.760   874  1918 I ActivityManager: Killing 3678:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 17:37:31.837  4037  4037 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 17:37:32.032   874  1900 I ActivityManager: Killing 3693:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 17:37:33.233   874  1900 D WifiService: setWifiEnabled: true pid=3797, uid=10000
,08-26 17:37:33.233   874  1900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:33.250   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 17:37:33.260  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:33.261  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:33.261  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:33.261  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:33.265  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:33.265  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:33.265  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:33.266  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:33.300   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 17:37:33.301   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 17:37:33.302   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 17:37:33.303   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 17:37:33.303   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 17:37:33.303   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 17:37:33.303   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 17:37:33.316   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 17:37:33.316   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=12.88 delta 1000 -> 994
08-26 17:37:33.317   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:33.318   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 17:37:33.318   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 17:37:33.325   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 17:37:33.325   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:33.333   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 17:37:33.334   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 17:37:33.364   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 17:37:33.406   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 17:37:33.407  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 17:37:33.827  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 17:37:33.874  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 17:37:33.874  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 17:37:33.882   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 17:37:33.893   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 17:37:33.893   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:33.894   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 17:37:33.911   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:33.925   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:33.926   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 17:37:33.938   874  1317 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 17:37:33.940   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 17:37:33.968   874  4063 D DhcpClient: Receive thread started
,08-26 17:37:34.053   874  1315 E native  : do suspend false
,08-26 17:37:34.075   874  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 17:37:34.096   874  4063 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-26 17:37:34.097   874  1893 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
08-26 17:37:34.100   874  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 17:37:34.118   874  4063 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 17:37:34.119   874  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 17:37:34.125   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:34.136   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 17:37:34.138   874  1893 D DhcpClient: Scheduling renewal in 86399s
,08-26 17:37:34.158   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 17:37:34.161   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
08-26 17:37:34.161   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:34.162   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 17:37:34.166   874  1317 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 17:37:34.185   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 17:37:34.223   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 17:37:34.223   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 17:37:34.226   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 17:37:34.230   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 17:37:34.234   874  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 17:37:34.243   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:34.250   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 17:37:34.250   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:34.250   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 17:37:34.250   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:34.251   874  1317 D ConnectivityService:    accepting network in place of null
08-26 17:37:34.251   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 17:37:34.252   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -59]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 17:37:34.262   874  4062 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 17:37:34.294   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:34.329   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:34.336   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 17:37:34.336   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:34.344   874  4061 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:80f::200e
,08-26 17:37:34.344   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 17:37:34.345   874   891 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:34.356  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:34.356  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:34.356  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.356  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:34.358  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:34.358  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:34.359  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:34.359  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:34.417   874   886 I ActivityManager: Start proc 4073:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-26 17:37:34.443  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 17:37:34.454   874  4061 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 15:37:34 GMT], X-Android-Received-Millis=[1472225854453], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472225854408]}
,08-26 17:37:34.455  4073  4073 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-26 17:37:34.461  1740  1740 D SystemUpdateService: onCreate
,08-26 17:37:34.462   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 17:37:34.462   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 17:37:34.462   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:34.463   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 17:37:34.473  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-26 17:37:34.476  1740  4087 I SystemUpdateService: active receiver: enabled
08-26 17:37:34.479  1740  4087 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 17:37:34.488  1740  4087 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 17:37:34.488  1740  4087 I SystemUpdateService: now status is 0 (complete)
08-26 17:37:34.488  1740  4087 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 17:37:34.488  1740  4087 I SystemUpdateService: file has been verified
,08-26 17:37:34.490  1740  4087 I SystemUpdateService: OTA package size = 12249756
,08-26 17:37:34.497  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 17:37:34.499  1740  2430 I iu.UploadsManager: num queued entries: 0
,08-26 17:37:34.503  1740  2430 I iu.UploadsManager: num updated entries: 0
,08-26 17:37:34.507  1740  4087 I SystemUpdateService: showing system update notification
,08-26 17:37:34.512  1740  4090 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 17:37:34.512  1740  4090 W BaseAppContext: Using Auth Proxy for data requests.
08-26 17:37:34.513  1740  4090 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-26 17:37:34.515  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 17:37:34.517  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 17:37:34.506  1740  2430 I iu.SyncManager: NEXT; no task
,08-26 17:37:34.519  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:34.522  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 17:37:34.523  3959  3959 D SprintDMHelper: simOperator: 
08-26 17:37:34.523  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 17:37:34.525  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:34.531  1740  1740 D SystemUpdateService: onDestroy
,08-26 17:37:34.568  4073  4073 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 17:37:34.582  4073  4073 I BooksApp: Created application version: 3.6.9 (30609)
,08-26 17:37:34.594  1543  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 17:37:34.594  1543  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 17:37:34.594  1543  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:34.595  1543  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:34.606  1740  4090 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-26 17:37:34.621  1543  2135 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 17:37:34.621  1543  2135 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 17:37:34.621  1543  2135 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:34.621  1543  2135 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:34.635  3548  4092 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 17:37:34.635  3548  4092 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jdm.a(PG:82)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jcs.o(PG:406)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jcn.a(PG:1379)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jcs.i(PG:143)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at blb.a(PG:3937)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at czp.a(PG:18188)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at czp.a(PG:9081)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at czq.run(PG:1686)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 17:37:34.635  3548  4092 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jdj.a(PG:4091)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jdj.a(PG:1125)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jdm.a(PG:77)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	... 12 more
08-26 17:37:34.635  3548  4092 E HttpOperation: Caused by: faj: BadAuthentication
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at fal.a(PG:38)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	at jdj.a(PG:4089)
08-26 17:37:34.635  3548  4092 E HttpOperation: 	... 14 more
,08-26 17:37:34.667  4073  4104 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 17:37:34.669  1543  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 17:37:34.669  1543  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 17:37:34.669  1543  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:34.669  1543  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:34.677  3548  4092 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 17:37:34.677  3548  4092 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jdm.a(PG:82)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jcs.o(PG:406)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jcn.a(PG:1379)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jcs.i(PG:143)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at hec.a(PG:42)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at hee.a(PG:102)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at czr.a(PG:65)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at kka.a(PG:108)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at czp.a(PG:19176)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at czp.a(PG:9081)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at czq.run(PG:1686)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 17:37:34.677  3548  4092 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jdj.a(PG:4091)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jdj.a(PG:1125)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jdm.a(PG:77)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	... 15 more
08-26 17:37:34.677  3548  4092 E HttpOperation: Caused by: faj: BadAuthentication
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at fal.a(PG:38)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	at jdj.a(PG:4089)
08-26 17:37:34.677  3548  4092 E HttpOperation: 	... 17 more
,08-26 17:37:34.678  3548  4092 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 17:37:34.678  3548  4092 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at hec.a(PG:42)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at hee.a(PG:102)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at czr.a(PG:65)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at kka.a(PG:108)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	... 15 more
08-26 17:37:34.678  3548  4092 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at fal.a(PG:38)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 17:37:34.678  3548  4092 E ExperimentLoader: 	... 17 more
,08-26 17:37:34.714  2467  4097 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 17:37:34.798  4073  4113 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 17:37:34.827   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 128748, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 17:37:34.849  1543  1559 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 17:37:34.849  1543  1559 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 17:37:34.849  1543  1559 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:34.849  1543  1559 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:34.894  1543  2218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 17:37:34.894  1543  2218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 17:37:34.894  1543  2218 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:34.894  1543  2218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:34.905  4073  4113 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-26 17:37:34.907  4073  4104 E BooksSync: Soft error
08-26 17:37:34.907  4073  4104 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 17:37:34.907  4073  4104 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-26 17:37:34.907  4073  4104 E BooksSync: Sync error
08-26 17:37:34.907  4073  4104 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 17:37:34.907  4073  4104 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-26 17:37:34.907  4073  4104 I BooksSync: Finished books sync
,08-26 17:37:34.962   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127165, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 17:37:34.970   874  1914 I ActivityManager: Killing 2228:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 17:37:35.336   874  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 17:37:36.086   874  1974 I ActivityManager: Killing 3717:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 17:37:36.245   874  1462 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,08-26 17:37:36.245   874  1462 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:36.275  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 17:37:36.282   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 17:37:36.282   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 17:37:36.282   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 17:37:36.283   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:36.302   874  1893 D DhcpClient: Clearing IP address
,08-26 17:37:36.302   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:36.305   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:36.317  1543  4106 V NativeCrypto: Read error: ssl=0x9ad9b000: I/O error during system call, Connection timed out
,08-26 17:37:36.318   874  4063 D DhcpClient: Receive thread stopped
,08-26 17:37:36.321  1543  4106 V NativeCrypto: SSL shutdown failed: ssl=0x9ad9b000: I/O error during system call, Broken pipe
,08-26 17:37:36.321   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 17:37:36.322   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 17:37:36.330   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 17:37:36.343   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 17:37:36.346   394   394 E Parcel  : Reading a NULL string not supported here.
,08-26 17:37:36.348   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:36.353   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 17:37:36.355   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 17:37:36.359  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:36.359  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:36.359  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:36.359  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:36.360  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:36.360  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:36.360  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:36.360  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:36.361  2148  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:36.362   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 17:37:36.383   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:36.408   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:36.408   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 17:37:36.409   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:36.412   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-26 17:37:36.414  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:36.415  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:36.418  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 17:37:36.423  1740  1740 D SystemUpdateService: onCreate
,08-26 17:37:36.425  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 17:37:36.433  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 17:37:36.437  1740  4124 I SystemUpdateService: active receiver: enabled
,08-26 17:37:36.439  1740  2430 I iu.UploadsManager: num queued entries: 0
,08-26 17:37:36.439  1740  2430 I iu.UploadsManager: num updated entries: 0
08-26 17:37:36.439  1740  2430 I iu.SyncManager: NEXT; no task
,08-26 17:37:36.442  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 17:37:36.443  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 17:37:36.445  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:36.450  3959  3959 D SprintDMHelper: simOperator: 
,08-26 17:37:36.450  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 17:37:36.451  1740  4124 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-26 17:37:36.452  1740  4124 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 17:37:36.452  1740  4124 I SystemUpdateService: now status is 0 (complete)
08-26 17:37:36.452  1740  4124 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 17:37:36.452  1740  4124 I SystemUpdateService: file has been verified
,08-26 17:37:36.452  1740  4124 I SystemUpdateService: OTA package size = 12249756
,08-26 17:37:36.467  1740  4124 I SystemUpdateService: showing system update notification
,08-26 17:37:36.470  2467  4129 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 17:37:36.485   371   872 E Netd    : netlink response contains error (No such file or directory)
,08-26 17:37:36.492  1740  1740 D SystemUpdateService: onDestroy
,08-26 17:37:39.282   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2deb469:true
,08-26 17:37:39.284  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 17:37:39.293  3944  4131 I BluetoothAdapterState: Entering OffState
,08-26 17:37:39.293  3944  3944 I bt_bluedroid: init
,08-26 17:37:39.299  3944  4132 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 17:37:39.300  3944  4132 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 17:37:39.300  3944  4132 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 17:37:39.301  3944  4132 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 17:37:39.302  3944  3944 I bt_bluedroid: get_profile_interface socket
,08-26 17:37:39.306  3944  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 17:37:39.308  3944  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 17:37:39.313  3944  3944 I bt_bluedroid: get_profile_interface sdp
,08-26 17:37:39.317  3944  3955 I bt_bluedroid: config_hci_snoop_log
,08-26 17:37:39.321   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 17:37:39.331  3944  4131 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 17:37:39.332  3944  4131 D BluetoothAdapterProperties: Setting state to 14
,08-26 17:37:39.332  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 17:37:39.334  3944  4131 D BluetoothBondStateMachine: make
,08-26 17:37:39.337  3944  4136 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 17:37:39.343  3944  4131 I BluetoothAdapterState: Entering PendingCommandState
,08-26 17:37:39.344  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 17:37:39.346  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:39.347  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 17:37:39.348  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
08-26 17:37:39.348  3944  3944 D BtGatt.GattService: start()
08-26 17:37:39.348  3944  3944 I bt_bluedroid: get_profile_interface gatt
,08-26 17:37:39.349  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
08-26 17:37:39.349  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,08-26 17:37:39.357  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:39.357  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:39.358  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
08-26 17:37:39.358  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:39.359  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 17:37:39.361  3944  4131 I bt_bluedroid: enable
,08-26 17:37:39.361  3944  4132 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 17:37:39.362  3944  4132 I bt_hci  : start_up
,08-26 17:37:39.373  3944  4132 I bt_vendor: alloc value 0xb3939189
,08-26 17:37:39.374  3944  4132 I bt_vendor: init
,08-26 17:37:39.374  3944  4132 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 17:37:39.374  3944  4132 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 17:37:39.482  3944  4132 D bt_hci  : start_up starting async portion
,08-26 17:37:39.483  3944  4139 I bt_hci  : event_finish_startup,
08-26 17:37:39.484  3944  4139 I bt_hci_h4: hal_open
,08-26 17:37:39.484  3944  4139 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 17:37:39.491  3944  4139 I bt_userial_vendor: device fd = 51 open
,08-26 17:37:39.524  3944  4139 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 17:37:39.556  3944  4139 D bt_hwcfg: Chipset BCM4354A2
08-26 17:37:39.556  3944  4139 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 17:37:39.557  3944  4139 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 17:37:39.582  4073  4098 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 17:37:40.125  3944  4139 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 17:37:40.127  3944  4139 D bt_hwcfg: Settlement delay -- 100 ms
08-26 17:37:40.127  3944  4139 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 17:37:40.244  3944  4139 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 17:37:40.245  3944  4139 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 17:37:40.275  3944  4139 I bt_hwcfg: vendor lib fwcfg completed
08-26 17:37:40.275  3944  4139 I bt_vendor: firmware callback
08-26 17:37:40.276  3944  4139 I bt_hci  : firmware_config_callback
,08-26 17:37:40.287  3944  4143 I bt_btu  : btu_task pending for preload complete event
,08-26 17:37:40.287  3944  4143 I bt_btu_task: Bluetooth chip preload is complete
,08-26 17:37:40.287  3944  4143 I bt_btu  : btu_task received preload complete event
,08-26 17:37:40.299  3944  4143 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 17:37:40.299  3944  4143 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:40.299  3944  4143 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 17:37:40.300  3944  4143 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 17:37:40.300  3944  4143 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 17:37:40.300  3944  4143 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:40.300  3944  4143 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 17:37:40.301  3944  4143 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 17:37:40.301  3944  4143 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:40.301  3944  4143 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:40.301  3944  4143 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 17:37:40.302  3944  4143 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:40.302  3944  4143 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:40.302  3944  4143 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 17:37:40.303  3944  4143 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 17:37:40.431  3944  4143 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-26 17:37:40.431  3944  4143 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-26 17:37:40.440  3944  4135 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 17:37:40.443  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 17:37:40.443  3944  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 17:37:40.444  3944  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 17:37:40.445  3944  4135 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:40.445  3944  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 17:37:40.445  3944  4135 D bt_hci  : do_postload posting postload work item
,08-26 17:37:40.447  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.447  3944  4139 I bt_hci  : event_postload
,08-26 17:37:40.447  3944  4139 I bt_vendor: sco_config_cb
08-26 17:37:40.447  3944  4135 D bt_bte_conf: Device ID record 1 : primary
,08-26 17:37:40.447  3944  4135 D bt_bte_conf:   vendorId            = 000f
,08-26 17:37:40.448  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.448  3944  4135 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 17:37:40.450  3944  4135 D bt_bte_conf:   product             = 1200
,08-26 17:37:40.453  3944  4135 D bt_bte_conf:   version             = 1436
08-26 17:37:40.447  3944  4139 I bt_hci  : sco_config_callback postload finished.
08-26 17:37:40.453  3944  4135 D bt_bte_conf:   clientExecutableURL = 
08-26 17:37:40.453  3944  4135 D bt_bte_conf:   serviceDescription  = 
,08-26 17:37:40.453  3944  4135 D bt_bte_conf:   documentationURL    = 
,08-26 17:37:40.453  3944  4135 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 17:37:40.453  3944  4132 D bt_stack_manager: event_start_up_stack finished
,08-26 17:37:40.454  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 17:37:40.454  3944  4131 D BluetoothAdapterProperties: Setting state to 15
08-26 17:37:40.454  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 17:37:40.462  3944  4131 I BluetoothAdapterState: Entering BleOnState
,08-26 17:37:40.463  3944  4131 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 17:37:40.463  3944  4131 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:40.463  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 17:37:40.464  3944  4139 I bt_vendor: low_power_mode_cb
,08-26 17:37:40.467  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
08-26 17:37:40.469  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:40.470  3944  3944 D HeadsetService: Received start request. Starting profile...
08-26 17:37:40.471  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:40.473  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 17:37:40.473  3944  3944 D HeadsetStateMachine: make
08-26 17:37:40.479  3944  4131 I BluetoothAdapterState: Entering PendingCommandState
,08-26 17:37:40.484  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
,08-26 17:37:40.484  3944  3944 I bt_bluedroid: get_profile_interface handsfree
08-26 17:37:40.484  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 17:37:40.484  3944  4135 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 17:37:40.488  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:40.489  3944  3944 D A2dpService: Received start request. Starting profile...
08-26 17:37:40.489  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 17:37:40.489  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:40.489  3944  3944 I bt_bluedroid: get_profile_interface avrcp
,08-26 17:37:40.497  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 17:37:40.497  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 17:37:40.497  3944  3944 D A2dpStateMachine: make
,08-26 17:37:40.498  3944  3944 I bt_bluedroid: get_profile_interface a2dp
,08-26 17:37:40.500  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 17:37:40.501  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 17:37:40.502  3944  4152 D A2dpStateMachine: Enter Disconnected: -2
,08-26 17:37:40.502  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:40.504  3944  3944 D HidService: Received start request. Starting profile...
08-26 17:37:40.504  3867  3867 D BluetoothInputDevice: Proxy object connected
,08-26 17:37:40.504  3944  3944 I bt_bluedroid: get_profile_interface hidhost
08-26 17:37:40.504  3944  4135 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-26 17:37:40.505  3944  3944 D HidService: setHidService(): set to: null
08-26 17:37:40.505  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 17:37:40.505  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 17:37:40.505  3867  3867 D HidProfile: Bluetooth service connected
,08-26 17:37:40.506  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
08-26 17:37:40.506  3944  3944 D HealthService: Received start request. Starting profile...
,08-26 17:37:40.508  3944  3944 I bt_bluedroid: get_profile_interface health
,08-26 17:37:40.508  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 17:37:40.509  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:40.510  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:40.510  3944  3944 D PanService: Received start request. Starting profile...
,08-26 17:37:40.510  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 17:37:40.510  3944  3944 I bt_bluedroid: get_profile_interface pan
,08-26 17:37:40.510  3867  3867 D PanProfile: Bluetooth service connected
08-26 17:37:40.511  3944  4135 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 17:37:40.514  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:40.515  3867  3867 D BluetoothMap: Proxy object connected
,08-26 17:37:40.515  3867  3867 D MapProfile: Bluetooth service connected
08-26 17:37:40.514  3944  3944 D BluetoothMapService: Received start request. Starting profile...
08-26 17:37:40.515  3944  3944 D BluetoothMapService: start()
08-26 17:37:40.515  3867  3867 D BluetoothMap: getConnectedDevices()
08-26 17:37:40.516  3867  3867 D BluetoothMap: Bluetooth is Not enabled
08-26 17:37:40.517  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 17:37:40.517  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 17:37:40.517  3944  3944 D BluetoothMapAppObserver: createReceiver()
,08-26 17:37:40.518  3944  3944 D BluetoothMapAppObserver: initObservers()
08-26 17:37:40.518  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 17:37:40.523  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:40.523  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:40.523  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:40.523  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:40.525  3944  4150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false,
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:40.527  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:40.528  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:40.528  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-26 17:37:40.528  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:40.528  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:40.528  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 17:37:40.528  3944  4131 D BluetoothAdapterProperties: ScanMode =  20
08-26 17:37:40.528  3944  4131 D BluetoothAdapterProperties: State =  11
08-26 17:37:40.528  3944  4131 D BluetoothAdapterProperties: Setting state to 12
,08-26 17:37:40.528  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 17:37:40.529   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:40.529   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:40.529  3944  4135 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:40.529  1369  1388 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 17:37:40.530  3944  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:40.530  3944  4131 I BluetoothAdapterState: Entering OnState
08-26 17:37:40.531  3867  3882 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 17:37:40.531   874   874 D BluetoothA2dp: Proxy object connected
08-26 17:37:40.532  3867  3878 D BluetoothMap: onBluetoothStateChange: up=true
08-26 17:37:40.532  1954  2262 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:40.532  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:40.533  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:40.534  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:40.534  1369  1369 D BluetoothA2dp: Proxy object connected
08-26 17:37:40.535  1369  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:40.535  3867  3882 D BluetoothPan: onBluetoothStateChange on: true
,08-26 17:37:40.535  1369  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:40.537  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:40.537  1369  1369 D BluetoothMap: Proxy object connected
08-26 17:37:40.537  1369  1369 D MapProfile: Bluetooth service connected
08-26 17:37:40.538  1369  1369 D BluetoothMap: getConnectedDevices()
,08-26 17:37:40.538   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:40.538  1369  1388 D BluetoothPan: onBluetoothStateChange on: true
08-26 17:37:40.538  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:40.539  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:40.539  1369  1369 D PanProfile: Bluetooth service connected
,08-26 17:37:40.539  1369  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 17:37:40.540  1369  1369 D BluetoothInputDevice: Proxy object connected
08-26 17:37:40.540  1369  1369 D HidProfile: Bluetooth service connected
08-26 17:37:40.540  3867  3878 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 17:37:40.542  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 17:37:40.543  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 17:37:40.544   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:40.544  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:40.545   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 17:37:40.547  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.548  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:40.548  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.548  3867  3867 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 17:37:40.549  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
,08-26 17:37:40.549  3944  3944 D ObexServerSockets0: startAccept()
08-26 17:37:40.549  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-26 17:37:40.551  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 17:37:40.551  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 17:37:40.551  3944  3944 D BluetoothMapService: onReceive
08-26 17:37:40.551  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:40.551  3944  3944 D BluetoothMapService: STATE_ON
08-26 17:37:40.552  3944  4159 D ObexServerSockets0: Accepting socket connection...
08-26 17:37:40.552  3944  4160 D ObexServerSockets0: Accepting socket connection...
,08-26 17:37:40.552  3867  3867 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 17:37:40.560  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:40.562  3867  3867 D BluetoothA2dp: Proxy object connected
,08-26 17:37:40.566  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:40.573  1369  1369 D BluetoothPbap: Proxy object connected
08-26 17:37:40.573  1369  1369 D PbapServerProfile: Bluetooth service connected
,08-26 17:37:40.574  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:40.574  3867  3867 D BluetoothPbap: Proxy object connected
,08-26 17:37:40.575  3867  3867 D PbapServerProfile: Bluetooth service connected
,08-26 17:37:40.577  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 17:37:40.577  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-26 17:37:40.582  3944  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:40.592  3944  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:40.593  3944  4168 I BtOppRfcommListener: Accept thread started.
,08-26 17:37:40.630   874   874 D BluetoothHeadset: Proxy object connected
08-26 17:37:40.630   874   874 D BluetoothHeadset: Proxy object connected
08-26 17:37:40.630   874   874 D BluetoothHeadset: Proxy object connected
08-26 17:37:40.631  1369  2062 D BluetoothHeadset: Proxy object connected
08-26 17:37:40.631  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:40.634  1954  1966 D BluetoothHeadset: Proxy object connected
08-26 17:37:40.634  1954  1966 D BluetoothHeadset: Proxy object connected
,08-26 17:37:40.635  1369  1388 D BluetoothHeadset: Proxy object connected
,08-26 17:37:40.635  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:40.638   874   891 D BluetoothHeadset: Proxy object connected
,08-26 17:37:40.644   874   891 D BluetoothHeadset: Proxy object connected
,08-26 17:37:40.656  3867  3878 D BluetoothHeadset: Proxy object connected
,08-26 17:37:40.659  3867  3867 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:41.490  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:41.501  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:41.507  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:41.544  1543  2218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 17:37:41.544  1543  2218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 17:37:41.545  1543  2218 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:41.546  1543  2218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:41.581  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 17:37:41.582  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 17:37:41.583  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 17:37:42.255   874  1317 D ConnectivityService: handlePromptUnvalidated 101
,08-26 17:37:42.263  3944  4131 D BluetoothAdapterState: Current state: ON, message: 23
08-26 17:37:42.263  3944  4131 D BluetoothAdapterProperties: Setting state to 13
,08-26 17:37:42.263  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 17:37:42.265  3944  4131 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 17:37:42.274  3944  3944 D BluetoothMapService: onReceive
,08-26 17:37:42.274  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:42.275  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
,08-26 17:37:42.275  3944  3944 D BluetoothMapService: MAP Service closeService in
08-26 17:37:42.276  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 17:37:42.276  3944  3944 D ObexServerSockets0: shutdown(block = true)
08-26 17:37:42.281  3944  4159 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 17:37:42.284  3944  4131 I BluetoothAdapterState: Entering PendingCommandState
08-26 17:37:42.284  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 17:37:42.285  3944  4160 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 17:37:42.287  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:42.287  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:42.289  3944  4145 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 17:37:42.291  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:42.291  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:42.291  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 17:37:42.291  3944  4135 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:42.291  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 17:37:42.292  3944  3944 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:42.292  3944  4168 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 17:37:42.295  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 17:37:42.295  3944  4168 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 17:37:42.296  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:42.296  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:42.297  3797  3797 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:42.297  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:42.299  3944  3944 D HeadsetService: Received stop request...Stopping profile...
08-26 17:37:42.299  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:42.301   874   874 D BluetoothHeadset: Proxy object disconnected
,08-26 17:37:42.301   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:42.301   874   874 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:42.301  3944  3944 D A2dpService: Received stop request...Stopping profile...,
08-26 17:37:42.301  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:42.302  3944  4152 D A2dpStateMachine: Exit Disconnected: -1
08-26 17:37:42.302  1369  1382 D BluetoothHeadset: Proxy object disconnected
,08-26 17:37:42.304  1954  2262 D BluetoothHeadset: Proxy object disconnected
08-26 17:37:42.304  1369  1369 D HeadsetProfile: Bluetooth service disconnected
08-26 17:37:42.305  3867  3882 D BluetoothHeadset: Proxy object disconnected
,08-26 17:37:42.305  3944  3944 D HidService: Received stop request...Stopping profile...
08-26 17:37:42.305  3944  3944 D HidService: Stopping Bluetooth HidService
08-26 17:37:42.305   874   874 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:42.304  1369  1369 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:42.310  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:42.310  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 17:37:42.310  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:42.310  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:42.311  1369  1369 D BluetoothInputDevice: Proxy object disconnected
08-26 17:37:42.311  1369  1369 D HidProfile: Bluetooth service disconnected
08-26 17:37:42.311  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 17:37:42.311  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 17:37:42.312  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:42.312  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:42.312  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:42.313  3944  4135 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 17:37:42.313  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:42.314  3944  3944 V BluetoothAdapterState: isTurningOff()=true
,08-26 17:37:42.314  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:42.314  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:42.314  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:42.315  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 17:37:42.315  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 17:37:42.316  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:42.316  3944  4143 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:42.316  3944  4143 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:42.316  3944  4143 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:42.316  3944  4143 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:42.316  3944  3944 D HealthService: Received stop request...Stopping profile...
,08-26 17:37:42.318  3944  3944 D PanService: Received stop request...Stopping profile...
08-26 17:37:42.320  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:42.320  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 17:37:42.320  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:42.320  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:42.320  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:42.321  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 17:37:42.321  1369  1369 D PanProfile: Bluetooth service disconnected
,08-26 17:37:42.322  3867  3867 D BluetoothA2dp: Proxy object disconnected
,08-26 17:37:42.323  3867  3867 D HeadsetProfile: Bluetooth service disconnected
,08-26 17:37:42.323  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:42.323  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
08-26 17:37:42.323  3944  3944 D BluetoothMapService: stop()
08-26 17:37:42.324  3867  3867 D BluetoothInputDevice: Proxy object disconnected
08-26 17:37:42.324  3867  3867 D HidProfile: Bluetooth service disconnected
08-26 17:37:42.324  3867  3867 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 17:37:42.324  3867  3867 D PanProfile: Bluetooth service disconnected
08-26 17:37:42.326  3944  3944 D BluetoothMapAppObserver: deinitObservers()
08-26 17:37:42.326  3944  3944 D BluetoothMapAppObserver: removeReceiver()
08-26 17:37:42.329  1369  1369 D BluetoothMap: Proxy object disconnected
08-26 17:37:42.329  1369  1369 D MapProfile: Bluetooth service disconnected
08-26 17:37:42.330  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 17:37:42.330  3944  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 17:37:42.330  3867  3867 D BluetoothMap: Proxy object disconnected
08-26 17:37:42.330  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:42.330  3867  3867 D MapProfile: Bluetooth service disconnected
,08-26 17:37:42.331  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:42.331  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:42.331  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:42.331  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:42.332  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:42.332  3944  4135 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 17:37:42.332  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 17:37:42.333  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:42.333  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:42.333  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:42.333  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:42.333  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-26 17:37:42.333  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 17:37:42.335  3867  3867 D BluetoothPbap: Proxy object disconnected
,08-26 17:37:42.335  3867  3867 D PbapServerProfile: Bluetooth service disconnected
,08-26 17:37:42.336  1369  1369 D BluetoothPbap: Proxy object disconnected
08-26 17:37:42.336  1369  1369 D PbapServerProfile: Bluetooth service disconnected
08-26 17:37:42.337  3944  3944 D BluetoothMapService: MAP Service closeService in
08-26 17:37:42.337  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 17:37:42.337  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 17:37:42.337  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:42.337  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:42.338  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 17:37:42.338  3944  4131 D BluetoothAdapterProperties: Setting state to 15
08-26 17:37:42.338  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 17:37:42.339  3944  4131 I BluetoothAdapterState: Entering BleOnState
08-26 17:37:42.339  3944  3944 D BluetoothMapService: cleanup()
08-26 17:37:42.339  3944  3944 D BluetoothMapService: MAP Service closeService in
,08-26 17:37:42.340   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:42.340  3867  3882 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:42.340   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:42.340  1369  1388 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 17:37:42.341  3867  3878 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 17:37:42.342  3867  3882 D BluetoothMap: onBluetoothStateChange: up=false
08-26 17:37:42.343  1954  1967 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 17:37:42.343  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:42.344  3867  3878 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:42.345  1369  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 17:37:42.345  3867  3882 D BluetoothPan: onBluetoothStateChange on: false
08-26 17:37:42.346  1369  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-26 17:37:42.347   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 17:37:42.347  1369  2062 D BluetoothPan: onBluetoothStateChange on: false
,08-26 17:37:42.348  1369  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 17:37:42.348  3867  3878 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 17:37:42.348   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 17:37:42.349  3944  4131 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 17:37:42.349  3944  4131 D BluetoothAdapterProperties: Setting state to 16
08-26 17:37:42.349  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 17:37:42.349  3944  4131 D BluetoothAdapterProperties: onBleDisable
08-26 17:37:42.350  3944  4131 I BluetoothAdapterState: Entering PendingCommandState
08-26 17:37:42.350  3944  4132 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 17:37:42.351  3944  4143 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 17:37:42.351  3944  4143 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 17:37:42.352  3944  4135 D BluetoothAdapterProperties: Scan Mode:20
08-26 17:37:42.352  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:42.352  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:42.355  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:42.357  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:42.358  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:42.358  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:42.368  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:42.552  3944  4135 I bt_hci  : shut_down
,08-26 17:37:42.572  3944  4139 D bt_hwcfg: hw_epilog_process
,08-26 17:37:42.572  3944  4139 I bt_vendor: low_power_mode_cb
,08-26 17:37:42.593  3944  4139 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 17:37:42.594  3944  4139 I bt_vendor: epilog_cb
08-26 17:37:42.594  3944  4139 I bt_hci  : epilog_finished_callback
,08-26 17:37:42.601  3944  4135 I bt_hci_h4: hal_close
,08-26 17:37:42.603  3944  4135 I bt_userial_vendor: device fd = 51 close
,08-26 17:37:42.720  3944  4132 D bt_stack_manager: event_shut_down_stack finished.
,08-26 17:37:42.722  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 17:37:42.728  3944  4131 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 17:37:42.728  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:42.730  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 17:37:42.730  3944  3944 D BtGatt.GattService: stop()
08-26 17:37:42.730  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 17:37:42.736  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:42.736  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 17:37:42.737  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 17:37:42.737  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
08-26 17:37:42.738  3944  4131 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 17:37:42.738  3944  4131 D BluetoothAdapterProperties: Setting state to 10
,08-26 17:37:42.738  3944  4131 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 17:37:42.740  3944  4131 I BluetoothAdapterState: Entering OffState
08-26 17:37:42.741   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 17:37:42.759  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 17:37:42.760  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 17:37:42.760  3944  4132 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 17:37:42.767  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 17:37:42.776  3944  4132 D bt_stack_manager: event_clean_up_stack finished.
,08-26 17:37:42.782  3944  3944 I art     : System.exit called, status: 0
,08-26 17:37:42.782  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 17:37:42.857   874  1974 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,08-26 17:37:44.668  3509  3519 D Finsky  : [264] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-26 17:37:44.695  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:44.772  1543  3309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-26 17:37:44.773  1543  3309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-26 17:37:44.774  1543  3309 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 17:37:44.775  1543  3309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:44.820  3509  3519 D Finsky  : [264] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-26 17:37:45.260  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:45.260  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:47.489   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 17:37:47.509  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-26 17:37:47.521   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 17:37:47.521   874   894 I Adreno  : Build Date                       : 10/20/15
08-26 17:37:47.521   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 17:37:47.521   874   894 I Adreno  : Local Branch                     : M14
08-26 17:37:47.521   874   894 I Adreno  : Remote Branch                    : 
08-26 17:37:47.521   874   894 I Adreno  : Remote Branch                    : 
08-26 17:37:47.521   874   894 I Adreno  : Reconstruct Branch               : 
,08-26 17:37:47.584   280   299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (409 us)
,08-26 17:37:48.262  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 17:37:48.263  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 17:37:48.264  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:48.264  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c23b455 added. We now have 6 listener(s)
,08-26 17:37:48.264  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:48.266  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:48.266  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae3de6a added. We now have 7 listener(s)
,08-26 17:37:48.267  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:48.267  3797  3846 I System.out: IsBluetoothEnabled
,08-26 17:37:48.301   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 17:37:48.302  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cc5b23 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c62f5b, 16908290=android.view.AbsSavedState$1@c62f5b}, android:focusedViewId=100}]}]
08-26 17:37:48.302  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 17:37:48.302  3797  3797 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 17:37:48.302  3797  3797 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 17:37:48.310  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:48.316   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 17:37:48.321   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 17:37:48.321   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-26 17:37:48.321   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 17:37:48.326   874   883 I art     : Background partial concurrent mark sweep GC freed 19052(1616KB) AllocSpace objects, 10(392KB) LOS objects, 33% free, 29MB/43MB, paused 5.144ms total 93.320ms
,08-26 17:37:48.337   874   891 I ActivityManager: Start proc 4182:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding HeadsetService
08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding A2dpService
08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding HidService
08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding HealthService
08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding PanService
08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding GattService
,08-26 17:37:48.392  4182  4182 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 17:37:48.402   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@81c370e:true
08-26 17:37:48.402  4182  4182 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 17:37:48.404  4182  4182 I bt_bluedroid: init,
08-26 17:37:48.404  4182  4194 I BluetoothAdapterState: Entering OffState
,08-26 17:37:48.407  4182  4195 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 17:37:48.407  4182  4195 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 17:37:48.407  4182  4195 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 17:37:48.407  4182  4195 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 17:37:48.408  4182  4182 I bt_bluedroid: get_profile_interface socket
08-26 17:37:48.409  4182  4182 I bt_bluedroid: get_profile_interface sdp
,08-26 17:37:48.412  4182  4193 I bt_bluedroid: config_hci_snoop_log
,08-26 17:37:48.413   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 17:37:48.413  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 17:37:48.415  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 17:37:48.416  4182  4194 D BluetoothAdapterState: Current state: OFF, message: 0
08-26 17:37:48.416  4182  4194 D BluetoothAdapterProperties: Setting state to 14
08-26 17:37:48.416  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 17:37:48.417  4182  4194 D BluetoothBondStateMachine: make
08-26 17:37:48.419  4182  4199 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 17:37:48.421  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,08-26 17:37:48.422  4182  4182 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 17:37:48.424  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:48.424  4182  4182 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:48.424  4182  4182 D BtGatt.GattService: Received start request. Starting profile...
,08-26 17:37:48.424  4182  4182 D BtGatt.GattService: start()
,08-26 17:37:48.424  4182  4182 I bt_bluedroid: get_profile_interface gatt
,08-26 17:37:48.425  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:48.425  4182  4182 D BtGatt.AdvertiseManager: advertise manager created
,08-26 17:37:48.432  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:48.432  4182  4182 V BluetoothAdapterState: isTurningOn()=false
,08-26 17:37:48.432  4182  4182 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 17:37:48.432  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:48.433  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 17:37:48.433  4182  4194 I bt_bluedroid: enable
,08-26 17:37:48.433  4182  4195 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 17:37:48.434  4182  4195 I bt_hci  : start_up
,08-26 17:37:48.451  4182  4195 I bt_vendor: alloc value 0xb39ad189
,08-26 17:37:48.451  4182  4195 I bt_vendor: init
08-26 17:37:48.451  4182  4195 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 17:37:48.451  4182  4195 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 17:37:48.559  4182  4195 D bt_hci  : start_up starting async portion
,08-26 17:37:48.559  4182  4202 I bt_hci  : event_finish_startup
,08-26 17:37:48.559  4182  4202 I bt_hci_h4: hal_open
08-26 17:37:48.562  4182  4202 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 17:37:48.573  4182  4202 I bt_userial_vendor: device fd = 51 open
,08-26 17:37:48.575   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 17:37:48.577   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 17:37:48.577   874  1339 D SurfaceControl: Excessive delay in setPowerMode(): 256ms
,08-26 17:37:48.585   874   894 I DreamManagerService: Entering dreamland.
08-26 17:37:48.586   874   894 I PowerManagerService: Dozing...
,08-26 17:37:48.586   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 17:37:48.600  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 17:37:48.631   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 17:37:48.632   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 17:37:48.632  4182  4202 D bt_hwcfg: Chipset BCM4354A2
,08-26 17:37:48.632  4182  4202 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 17:37:48.633  4182  4202 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
08-26 17:37:48.634   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 17:37:48.637   874  1315 E native  : do suspend false
,08-26 17:37:48.657  1939  4205 D NfcService: Discovery configuration equal, not updating.
,08-26 17:37:48.674   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 17:37:48.678   874  1315 E native  : do suspend true
,08-26 17:37:48.766   375  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 17:37:48.767   375  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 17:37:49.292  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 17:37:49.293  4182  4202 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 17:37:49.294  4182  4202 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 17:37:49.410  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 17:37:49.412  4182  4202 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 17:37:49.441  4182  4202 I bt_hwcfg: vendor lib fwcfg completed
,08-26 17:37:49.441  4182  4202 I bt_vendor: firmware callback
,08-26 17:37:49.442  4182  4202 I bt_hci  : firmware_config_callback
,08-26 17:37:49.453  4182  4209 I bt_btu  : btu_task pending for preload complete event
,08-26 17:37:49.453  4182  4209 I bt_btu_task: Bluetooth chip preload is complete
08-26 17:37:49.454  4182  4209 I bt_btu  : btu_task received preload complete event
,08-26 17:37:49.463  4182  4209 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 17:37:49.463  4182  4209 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:49.463  4182  4209 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 17:37:49.464  4182  4209 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 17:37:49.464  4182  4209 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 17:37:49.464  4182  4209 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:49.465  4182  4209 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 17:37:49.465  4182  4209 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 17:37:49.465  4182  4209 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:49.465  4182  4209 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:49.466  4182  4209 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 17:37:49.466  4182  4209 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:49.466  4182  4209 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:49.466  4182  4209 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 17:37:49.467  4182  4209 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 17:37:49.602  4182  4209 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392ad9d
,08-26 17:37:49.603  4182  4209 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392ad9d 
,08-26 17:37:49.613  4182  4198 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 17:37:49.614  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 17:37:49.615  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 17:37:49.623  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 17:37:49.625  4182  4198 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:49.627  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 17:37:49.627  4182  4198 D bt_hci  : do_postload posting postload work item
,08-26 17:37:49.627  4182  4202 I bt_hci  : event_postload
,08-26 17:37:49.627  4182  4202 I bt_vendor: sco_config_cb
08-26 17:37:49.628  4182  4202 I bt_hci  : sco_config_callback postload finished.
,08-26 17:37:49.630  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:49.631  4182  4198 D bt_bte_conf: Device ID record 1 : primary
,08-26 17:37:49.632  4182  4198 D bt_bte_conf:   vendorId            = 000f
,08-26 17:37:49.632  4182  4198 D bt_bte_conf:   vendorIdSource      = 0001
08-26 17:37:49.632  4182  4198 D bt_bte_conf:   product             = 1200
,08-26 17:37:49.632  4182  4198 D bt_bte_conf:   version             = 1436
,08-26 17:37:49.632  4182  4198 D bt_bte_conf:   clientExecutableURL = 
,08-26 17:37:49.632  4182  4198 D bt_bte_conf:   serviceDescription  = 
,08-26 17:37:49.633  4182  4198 D bt_bte_conf:   documentationURL    = 
08-26 17:37:49.633  4182  4198 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 17:37:49.633  4182  4195 D bt_stack_manager: event_start_up_stack finished
,08-26 17:37:49.634  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 17:37:49.635  4182  4194 D BluetoothAdapterProperties: Setting state to 15
08-26 17:37:49.635  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 17:37:49.635  4182  4202 I bt_vendor: low_power_mode_cb
,08-26 17:37:49.637  4182  4194 I BluetoothAdapterState: Entering BleOnState
,08-26 17:37:49.643  4182  4194 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 17:37:49.643  4182  4194 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:49.643  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 17:37:49.658  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:49.658  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:49.661  4182  4182 D HeadsetService: Received start request. Starting profile...
,08-26 17:37:49.670  4182  4182 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 17:37:49.670  4182  4182 D HeadsetStateMachine: make
,08-26 17:37:49.672  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,08-26 17:37:49.681  4182  4182 D HeadsetStateMachine: max_hf_connections = 1
,08-26 17:37:49.681  4182  4182 I bt_bluedroid: get_profile_interface handsfree
,08-26 17:37:49.681  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 17:37:49.682  4182  4198 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 17:37:49.686  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:49.686  4182  4182 D A2dpService: Received start request. Starting profile...
,08-26 17:37:49.687  4182  4182 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 17:37:49.688  4182  4182 I bt_bluedroid: get_profile_interface avrcp
,08-26 17:37:49.697  4182  4182 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 17:37:49.697  4182  4182 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 17:37:49.698  4182  4182 D A2dpStateMachine: make
,08-26 17:37:49.700  4182  4182 I bt_bluedroid: get_profile_interface a2dp
,08-26 17:37:49.701  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 17:37:49.702  4182  4217 D A2dpStateMachine: Enter Disconnected: -2
,08-26 17:37:49.705  4182  4182 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 17:37:49.706  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:49.708  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:49.708  4182  4182 D HidService: Received start request. Starting profile...
08-26 17:37:49.708  4182  4182 I bt_bluedroid: get_profile_interface hidhost
08-26 17:37:49.709  4182  4182 D HidService: setHidService(): set to: null
,08-26 17:37:49.709  4182  4198 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390c3e5
08-26 17:37:49.709  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 17:37:49.709  4182  4182 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 17:37:49.710  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:49.711  4182  4182 D HealthService: Received start request. Starting profile...
,08-26 17:37:49.714  4182  4182 I bt_bluedroid: get_profile_interface health
,08-26 17:37:49.715  4182  4182 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 17:37:49.716  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
,08-26 17:37:49.716  4182  4182 D PanService: Received start request. Starting profile...
,08-26 17:37:49.717  4182  4182 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 17:37:49.717  4182  4182 I bt_bluedroid: get_profile_interface pan
08-26 17:37:49.718  4182  4198 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 17:37:49.720  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87
08-26 17:37:49.721  4182  4182 D BluetoothMapService: Received start request. Starting profile...
08-26 17:37:49.721  4182  4182 D BluetoothMapService: start()
,08-26 17:37:49.723  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 17:37:49.724  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER,
,08-26 17:37:49.724  4182  4182 D BluetoothMapAppObserver: createReceiver(),
08-26 17:37:49.725  4182  4182 D BluetoothMapAppObserver: initObservers()
,08-26 17:37:49.725  4182  4182 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 17:37:49.734  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:49.734  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:49.734  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.734  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:49.737  4182  4215 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 17:37:49.738  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:49.738  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:49.738  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.738  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 17:37:49.739  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,08-26 17:37:49.739  4182  4182 V BluetoothAdapterState: isTurningOn()=true
,08-26 17:37:49.739  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.739  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:49.740  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:49.740  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isTurningOn()=true
,08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.741  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:49.742  4182  4182 V BluetoothAdapterState: isTurningOff()=false
08-26 17:37:49.742  4182  4182 V BluetoothAdapterState: isTurningOn()=true
08-26 17:37:49.742  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
08-26 17:37:49.742  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
08-26 17:37:49.743  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 17:37:49.743  4182  4194 D BluetoothAdapterProperties: ScanMode =  20
,08-26 17:37:49.743  4182  4194 D BluetoothAdapterProperties: State =  11
08-26 17:37:49.744  4182  4194 D BluetoothAdapterProperties: Setting state to 12
08-26 17:37:49.744  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 17:37:49.745   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:49.745  3867  3882 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 17:37:49.745  4182  4198 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:49.745  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:49.746   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:49.746  4182  4194 I BluetoothAdapterState: Entering OnState
08-26 17:37:49.747  1369  1388 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 17:37:49.748   874   874 D BluetoothA2dp: Proxy object connected
08-26 17:37:49.749  3867  3878 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:49.751  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:49.752  3867  3882 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 17:37:49.753  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 17:37:49.753  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:49.754  4182  4182 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 17:37:49.754  1954  2262 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:49.755  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:49.755  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:49.758  1369  1369 D BluetoothA2dp: Proxy object connected
08-26 17:37:49.758  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 17:37:49.759  3867  3878 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:49.762  3867  3867 D BluetoothA2dp: Proxy object connected
,08-26 17:37:49.763  4182  4182 D ObexServerSockets: Succeed to create listening sockets 
,08-26 17:37:49.763  4182  4182 D ObexServerSockets0: startAccept()
,08-26 17:37:49.764  1369  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:49.764  4182  4182 D ObexServerSockets0: prepareForNewConnect()
08-26 17:37:49.765  3867  3882 D BluetoothPan: onBluetoothStateChange on: true,
,08-26 17:37:49.768  1369  2062 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 17:37:49.769   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:49.769  1369  1382 D BluetoothPan: onBluetoothStateChange on: true
,08-26 17:37:49.771  1369  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 17:37:49.772  4182  4182 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 17:37:49.772  4182  4182 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 17:37:49.773  3867  3878 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 17:37:49.773  4182  4224 D ObexServerSockets0: Accepting socket connection...
08-26 17:37:49.773  4182  4225 D ObexServerSockets0: Accepting socket connection...
,08-26 17:37:49.775  1369  1369 D BluetoothInputDevice: Proxy object connected
08-26 17:37:49.775  1369  1369 D HidProfile: Bluetooth service connected
08-26 17:37:49.775   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 17:37:49.777  3867  3867 D BluetoothInputDevice: Proxy object connected
08-26 17:37:49.777  3867  3867 D HidProfile: Bluetooth service connected
08-26 17:37:49.777   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 17:37:49.782  1369  1369 D BluetoothMap: Proxy object connected
,08-26 17:37:49.782  1369  1369 D MapProfile: Bluetooth service connected
08-26 17:37:49.782  1369  1369 D BluetoothMap: getConnectedDevices()
08-26 17:37:49.783  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:49.783  3867  3867 D BluetoothMap: Proxy object connected
08-26 17:37:49.783  3867  3867 D MapProfile: Bluetooth service connected
08-26 17:37:49.784  3867  3867 D BluetoothMap: getConnectedDevices()
08-26 17:37:49.784  4182  4182 D BluetoothMapService: onReceive
08-26 17:37:49.784  4182  4182 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:49.784  4182  4182 D BluetoothMapService: STATE_ON
08-26 17:37:49.786  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:49.786  1369  1369 D PanProfile: Bluetooth service connected
,08-26 17:37:49.790  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:49.793  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 17:37:49.793  3867  3867 D PanProfile: Bluetooth service connected
,08-26 17:37:49.796  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:49.796  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:49.806  3867  3867 D BluetoothPbap: Proxy object connected
08-26 17:37:49.807  1369  1369 D BluetoothPbap: Proxy object connected
,08-26 17:37:49.807  1369  1369 D PbapServerProfile: Bluetooth service connected
08-26 17:37:49.807  3867  3867 D PbapServerProfile: Bluetooth service connected
,08-26 17:37:49.814  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 17:37:49.814  4182  4182 D ObexServerSockets0: prepareForNewConnect()
,08-26 17:37:49.816  4182  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:49.835  4182  4236 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:49.838  4182  4236 I BtOppRfcommListener: Accept thread started.
,08-26 17:37:49.846   874   874 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.846   874   874 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.846   874   874 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.846  1369  2062 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.847  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:49.847  1954  1967 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.848  3867  3878 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.849  3867  3867 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:49.855  1954  1966 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.867  1369  1382 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.867  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:49.870   874   891 D BluetoothHeadset: Proxy object connected
,08-26 17:37:49.876   874   891 D BluetoothHeadset: Proxy object connected
,08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:50.331  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:50.338  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:50.341  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:50.341  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23213f8 added. We now have 8 listener(s)
08-26 17:37:50.342  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:50.348   874  1974 D WifiService: setWifiEnabled: false pid=3797, uid=10000
,08-26 17:37:50.348   874  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:50.361  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:50.362   874  1998 D WifiService: setWifiEnabled: true pid=3797, uid=10000
08-26 17:37:50.362   874  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 17:37:50.378   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:50.396  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:50.404  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:50.409   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 17:37:50.410   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 17:37:50.411   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 17:37:50.412   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 17:37:50.412   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 17:37:50.412   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 17:37:50.412   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 17:37:50.429   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 17:37:50.430   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,08-26 17:37:50.430   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-26 17:37:50.431   371   872 D CommandListener: Setting iface cfg
08-26 17:37:50.431   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 17:37:50.431   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 17:37:50.442   874  1315 E native  : do suspend true
,08-26 17:37:50.443   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 17:37:50.451   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 17:37:50.462   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 17:37:50.463   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 17:37:50.493   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 17:37:50.544   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 17:37:50.546  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 17:37:50.984  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 17:37:51.035  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 17:37:51.037  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 17:37:51.045   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 17:37:51.058   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 17:37:51.060   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 17:37:51.061   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:51.090   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:51.110   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:51.112   874  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 17:37:51.119   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 17:37:51.173   874  4244 D DhcpClient: Receive thread started
,08-26 17:37:51.261   874  1315 E native  : do suspend false
,08-26 17:37:51.283   874  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 17:37:51.299   874  4244 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 17:37:51.300   874  1893 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 17:37:51.304   874  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 17:37:51.318   874  4244 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 17:37:51.319   874  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 17:37:51.324   371   872 D CommandListener: Setting iface cfg
,08-26 17:37:51.332   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 17:37:51.334   874  1893 D DhcpClient: Scheduling renewal in 86399s
,08-26 17:37:51.335   874  1315 E native  : do suspend true
,08-26 17:37:51.359   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 17:37:51.363   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 17:37:51.365   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 17:37:51.367   874  1317 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:51.383  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:51.384   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 17:37:51.387  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:51.389  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 17:37:51.390  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 17:37:51.395  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cc5b23 Bundle[{}]
08-26 17:37:51.395  3797  3846 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 17:37:51.396  3797  3846 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 17:37:51.396  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 17:37:51.396  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 17:37:51.397  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 17:37:51.397  3797  3846 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 17:37:51.401  3797  3846 I System.out: Running OutgoingSocketThread
,08-26 17:37:51.403  3797  4249 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 419)
,08-26 17:37:51.405  3797  4249 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49974
08-26 17:37:51.405  3797  4249 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 17:37:51.408   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 17:37:51.409   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 17:37:51.409   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 17:37:51.410   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 17:37:51.411   874  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 17:37:51.418   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 17:37:51.421   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 17:37:51.422   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 17:37:51.422   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-26 17:37:51.422   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 17:37:51.422   874  1317 D ConnectivityService:    accepting network in place of null
,08-26 17:37:51.422   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 17:37:51.422   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 17:37:51.434   874  4243 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 17:37:51.448   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:51.487   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 17:37:51.489   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 17:37:51.490   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:51.492   874   891 D Tethering: MasterInitialState.processMessage what=3
08-26 17:37:51.491   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:51.501  3797  3797 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:51.503  3797  3797 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:51.504   874  4242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:4001:80f::200e
,08-26 17:37:51.512  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 17:37:51.519  1740  1740 D SystemUpdateService: onCreate
,08-26 17:37:51.523  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 17:37:51.530  1740  4256 I SystemUpdateService: active receiver: enabled
,08-26 17:37:51.540  1740  4256 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 17:37:51.544  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 17:37:51.552  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 17:37:51.554  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 17:37:51.556  3959  3959 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:51.554  1740  4256 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 17:37:51.558  1740  4256 I SystemUpdateService: now status is 0 (complete)
08-26 17:37:51.560  1740  4256 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 17:37:51.561  1740  4259 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 17:37:51.561  1740  4259 W BaseAppContext: Using Auth Proxy for data requests.
08-26 17:37:51.561  3959  3959 D SprintDMHelper: simOperator: 
08-26 17:37:51.561  3959  3959 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 17:37:51.566  1740  4259 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 17:37:51.578   874  4242 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 15:37:51 GMT], X-Android-Received-Millis=[1472225871577], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472225871548]}
,08-26 17:37:51.580   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 17:37:51.581   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 17:37:51.581   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 17:37:51.582   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 17:37:51.587  1740  2430 I iu.UploadsManager: num queued entries: 0
,08-26 17:37:51.560  1740  4256 I SystemUpdateService: file has been verified
,08-26 17:37:51.589  1740  4256 I SystemUpdateService: OTA package size = 12249756
,08-26 17:37:51.592  1740  2430 I iu.UploadsManager: num updated entries: 0
,08-26 17:37:51.594  1740  2430 I iu.SyncManager: NEXT; no task
,08-26 17:37:51.599  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:51.605  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 17:37:51.621  1740  4256 I SystemUpdateService: showing system update notification
,08-26 17:37:51.641  1740  1740 D SystemUpdateService: onDestroy
,08-26 17:37:51.654  1543  2135 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 17:37:51.654  1543  2135 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 17:37:51.654  1543  2135 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 17:37:51.654  1543  2135 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 17:37:51.675  1740  4259 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-26 17:37:51.724  2467  4261 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 17:37:52.404  3797  3846 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 420)
,08-26 17:37:52.405  3797  3846 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 420)
,08-26 17:37:52.414  3797  3846 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 425)
,08-26 17:37:52.416  3797  3846 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 17:37:52.417  3797  3846 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-26 17:37:52.422  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.422  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3840d1 added. We now have 2 listener(s)
,08-26 17:37:52.424  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.424  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.424  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:52.425  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.425  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d597736 added. We now have 9 listener(s)
,08-26 17:37:52.425  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.425  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:52.428  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.435  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:52.437  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:52.438  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:52.438  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.439  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7077a4 added. We now have 3 listener(s)
08-26 17:37:52.440  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.443  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.448  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 17:37:52.449  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.449  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:52.451  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.451  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f190d added. We now have 10 listener(s)
08-26 17:37:52.451  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.452  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:52.452  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:52.452  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:52.453  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.453  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.453  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.453  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.454  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3840d1 removed from the list
,08-26 17:37:52.454  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.454  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d597736 removed from the list
08-26 17:37:52.454  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:52.455  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:52.456  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.456  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:52.457  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.457  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.457  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.458  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d597736 not in the list
08-26 17:37:52.458  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.458  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.459  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.459  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.459  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.459  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f190d removed from the list
08-26 17:37:52.459  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.459  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.459  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.459  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.459  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7077a4 removed from the list
08-26 17:37:52.460  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.460  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abdd0c2 added. We now have 2 listener(s)
08-26 17:37:52.462  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.462  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.462  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.462  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.462  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@792ed3 added. We now have 9 listener(s)
08-26 17:37:52.463  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.463  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:52.466  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.471  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:52.473  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.474  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:52.475  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.475  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3413909 added. We now have 3 listener(s)
08-26 17:37:52.476  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.479  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.481  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 17:37:52.482  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.482  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:52.483  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.483  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81c370e added. We now have 10 listener(s)
,08-26 17:37:52.484  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:52.484  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:52.484  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 17:37:52.485  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:52.485  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.485  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:52.490  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 17:37:52.490  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:52.490   874  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 17:37:52.494  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:52.495  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 17:37:52.495  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:52.499  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:52.499  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 17:37:52.499  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:52.499  3797  3846 D BluetoothAdapter: STATE_ON
,08-26 17:37:52.503  4182  4193 D BtGatt.GattService: registerClient() - UUID=9e8ef317-80f0-4260-b990-00ff5495ee9a
,08-26 17:37:52.504  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=9e8ef317-80f0-4260-b990-00ff5495ee9a, clientIf=5
,08-26 17:37:52.505  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 17:37:52.506  4182  4226 D BtGatt.GattService: start scan with filters
,08-26 17:37:52.510  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 17:37:52.510  4182  4201 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:52.511  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:52.511  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 17:37:52.511  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 17:37:52.512  4182  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e06d87,
,08-26 17:37:52.520  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:52.520  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:52.521  4182  4198 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 17:37:52.520  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 17:37:52.521  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.522  4182  4201 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 17:37:52.527  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:52.534  3797  3846 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 17:37:52.534  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:52.535  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 17:37:52.535  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.535  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,08-26 17:37:52.536  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 17:37:52.536  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.536  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 17:37:52.536  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 17:37:52.536  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 17:37:52.536  4182  4201 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:52.536  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 17:37:52.536  4182  4201 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 17:37:52.537  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 17:37:52.537  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:52.539  3797  3846 D BluetoothAdapter: STATE_ON
,08-26 17:37:52.541  4182  4193 D BtGatt.GattService: stopScan() - queue size =1
08-26 17:37:52.544  4182  4226 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 17:37:52.544  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-26 17:37:52.544  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 17:37:52.544  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 17:37:52.544  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 17:37:52.545  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:52.546  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:52.546  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 17:37:52.546  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 17:37:52.546  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:52.546  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:52.548  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:52.548  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:52.548  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:52.554  4182  4198 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 17:37:52.554  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.556  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:52.557  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:52.557  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:52.557  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.557  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.557  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:52.557  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:52.557  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abdd0c2 removed from the list
,08-26 17:37:52.557  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.558  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@792ed3 removed from the list
,08-26 17:37:52.558  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:52.558  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.558  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.558  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:52.559  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.559  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:52.559  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.560  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@792ed3 not in the list
08-26 17:37:52.560  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.560  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:52.561  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 17:37:52.561  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-26 17:37:52.561  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.561  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:52.561  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.561  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81c370e removed from the list
08-26 17:37:52.561  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.561  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.561  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.561  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.561  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3413909 removed from the list
08-26 17:37:52.562  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.562  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8b61a added. We now have 2 listener(s)
08-26 17:37:52.564  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.564  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.564  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.565  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.565  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ada54b added. We now have 9 listener(s)
08-26 17:37:52.565  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.565  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:52.568  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.570  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 17:37:52.570  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.571  4182  4201 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.576  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:52.579  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:52.579  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:52.580  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-26 17:37:52.580  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.580  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 17:37:52.581  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.581  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa0041 added. We now have 3 listener(s)
,08-26 17:37:52.583  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.585  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.587  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 17:37:52.587  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.587  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 17:37:52.588  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.588  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.588  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.588  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cc19e6 added. We now have 10 listener(s)
,08-26 17:37:52.589  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:52.589  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:52.591  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:52.591  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 17:37:52.591  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:52.591  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 17:37:52.592  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-26 17:37:52.599  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 17:37:52.599  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:52.603  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:52.603  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 17:37:52.603  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:52.607  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:52.607  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:52.607  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 17:37:52.608  3797  3846 D BluetoothAdapter: STATE_ON
,08-26 17:37:52.610  4182  4193 D BtGatt.GattService: registerClient() - UUID=d5c11d64-1618-41a1-82c7-e3ef050b7d53
,08-26 17:37:52.611  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=d5c11d64-1618-41a1-82c7-e3ef050b7d53, clientIf=5
08-26 17:37:52.611  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 17:37:52.612  4182  4227 D BtGatt.GattService: start scan with filters
,08-26 17:37:52.615  4182  4201 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:52.615  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 17:37:52.615  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:52.615  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 17:37:52.615  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:52.620  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:52.621  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:52.621  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 17:37:52.622  4182  4198 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 17:37:52.622  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.622  4182  4201 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-26 17:37:52.624  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:52.628  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 17:37:52.629  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:52.629  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.629  3797  3846 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 17:37:52.629  4182  4201 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 17:37:52.629  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:52.629  4182  4201 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 17:37:52.630  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:52.630  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:52.630  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.630  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.630  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 17:37:52.631  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:52.631  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8b61a removed from the list
,08-26 17:37:52.631  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.631  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ada54b removed from the list
,08-26 17:37:52.631  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:52.631  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:52.632  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.632  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 17:37:52.632  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.632  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:52.634  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.634  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 17:37:52.634  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.635  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ada54b not in the list
08-26 17:37:52.635  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 17:37:52.635  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 17:37:52.635  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 17:37:52.635  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 17:37:52.635  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:52.637  3797  3846 D BluetoothAdapter: STATE_ON,
08-26 17:37:52.637  4182  4227 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:52.638  4182  4226 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 17:37:52.639  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:52.639  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 17:37:52.639  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 17:37:52.640  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:52.640  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:52.641  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:52.642  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:52.642  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-26 17:37:52.642  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:52.642  4182  4198 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 17:37:52.642  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.644  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.646  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:52.646  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:52.646  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:52.646  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.646  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.647  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.647  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cc19e6 removed from the list
08-26 17:37:52.647  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.647  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.647  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.647  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.647  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa0041 removed from the list
08-26 17:37:52.648  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.648  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92fee72 added. We now have 2 listener(s)
08-26 17:37:52.650  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.650  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 17:37:52.650  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.650  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.651  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.651  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.651  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b72c3 added. We now have 9 listener(s)
08-26 17:37:52.652  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.652  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:52.655  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.658  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 17:37:52.658  4182  4198 D BtGatt.ScanM,anager: callback done for clientIf - 5 status - 0
08-26 17:37:52.658  4182  4201 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.660  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:52.662  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:52.662  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:52.663  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.663  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ad7679 added. We now have 3 listener(s)
,08-26 17:37:52.664  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 17:37:52.664  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.664  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 17:37:52.665  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:52.665  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.665  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.665  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.666  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.666  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a7fbe added. We now have 10 listener(s)
08-26 17:37:52.666  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.666  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:52.666  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:52.666  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:52.666  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:52.666  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:52.667  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:52.669  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 17:37:52.669  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.670  3797  3846 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 17:37:52.670  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:52.673  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:52.673  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 17:37:52.673  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:52.675  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:52.676  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:52.676  3797  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 17:37:52.676  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:52.678  4182  4192 D BtGatt.GattService: registerClient() - UUID=81c557dd-2daf-4c51-b673-f54aa105ca9e
,08-26 17:37:52.678  4182  4198 D BtGatt.GattService: onClientRegistered() - UUID=81c557dd-2daf-4c51-b673-f54aa105ca9e, clientIf=5
08-26 17:37:52.678  3797  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 17:37:52.679  4182  4226 D BtGatt.GattService: start scan with filters
,08-26 17:37:52.680  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 17:37:52.681  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:52.681  4182  4201 D BtGatt.ScanManager: handling starting scan
08-26 17:37:52.681  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:52.681  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:52.683  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:52.683  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:52.684  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 17:37:52.685  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:52.686  4182  4198 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 17:37:52.687  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.687  4182  4201 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 17:37:52.689  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:52.689  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:52.690  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:52.690  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.690  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:52.690  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 17:37:52.690  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:52.690  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92fee72 removed from the list
08-26 17:37:52.690  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.690  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b72c3 removed from the list
,08-26 17:37:52.690  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:52.690  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.691  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.691  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 17:37:52.691  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.691  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.692  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 17:37:52.692  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.692  4182  4201 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:52.692  4182  4201 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.693  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b72c3 not in the list
08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 17:37:52.693  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:52.693  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:52.693  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:52.694  3797  3846 D BluetoothAdapter: STATE_ON
08-26 17:37:52.694  4182  4228 D BtGatt.GattService: stopScan() - queue size =1
08-26 17:37:52.695  4182  4222 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 17:37:52.695  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 17:37:52.695  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:52.695  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:52.696  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 17:37:52.696  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 17:37:52.697  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:52.697  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 17:37:52.697  3797  3846 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:52.697  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:52.698  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:52.699  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:52.699  3797  3797 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:52.699  3797  3797 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:52.699  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.699  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.699  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.699  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a7fbe removed from the list
08-26 17:37:52.699  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:52.699  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.699  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.700  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.700  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ad7679 removed from the list
08-26 17:37:52.700  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:52.700  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ad9ca added. We now have 2 listener(s)
,08-26 17:37:52.702  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 17:37:52.702  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:52.702  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.703  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:52.703  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16773b added. We now have 9 listener(s)
08-26 17:37:52.703  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.704  4182  4198 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 17:37:52.704  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.706  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:52.710  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:52.712  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 17:37:52.712  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:52.714  3797  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:52.716  3797  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:52.716  3797  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:52.716  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:52.717  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1227bb1 added. We now have 3 listener(s)
08-26 17:37:52.719  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.719  4182  4198 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 17:37:52.720  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.720  4182  4201 D BtGatt.ScanManager: stopping BLe Batch
,08-26 17:37:52.721  3797  3797 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:52.724  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 17:37:52.724  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:52.724  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:52.724  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:52.724  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@944c896 added. We now have 10 listener(s)
,08-26 17:37:52.724  3797  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:52.724  3797  3846 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:52.725  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:52.725  3797  3846 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:52.725  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.725  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.725  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:52.725  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.725  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ad9ca removed from the list
08-26 17:37:52.725  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:52.725  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16773b removed from the list
08-26 17:37:52.725  3797  3846 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:52.725  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.726  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.726  4182  4198 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 17:37:52.726  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 17:37:52.726  4182  4201 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 17:37:52.727  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.727  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.727  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.727  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.728  3797  3846 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f16773b not in the list
,08-26 17:37:52.728  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.728  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.729  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:52.729  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:52.729  3797  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:52.729  3797  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@944c896 removed from the list
08-26 17:37:52.729  3797  3846 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:52.729  3797  3846 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:52.729  3797  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:52.729  3797  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:52.729  3797  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1227bb1 removed from the list
08-26 17:37:52.730  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 17:37:52.730  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 17:37:52.730  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 17:37:52.731  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:52.731  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 17:37:52.731  3797  3846 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:52.732  4182  4198 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 17:37:52.732  4182  4198 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 17:37:52.737  3797  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
,08-26 17:37:52.738  3797  4268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: My test thread name)
08-26 17:37:52.738  3797  4268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 17:37:52.739  3797  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: My test thread name)
,08-26 17:37:52.739  3797  4269 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: My test thread name)
08-26 17:37:52.739  3797  4269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 17:37:52.741  3797  3846 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 17:37:52.741  3797  3846 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 17:37:52.741  3797  3846 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-26 17:37:52.741  3797  3846 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 17:37:52.741  3797  3846 D com.test.thalitest.ThaliTestRunner: Total duration: 22852 ms
,08-26 17:37:52.742  3797  3846 I jxcore-log: *Native tests were executed*
08-26 17:37:52.742  3797  3846 I jxcore-log: 
,08-26 17:37:52.743  3797  3846 I jxcore-log: Total number of executed tests:  80
08-26 17:37:52.743  3797  3846 I jxcore-log: 
08-26 17:37:52.743  3797  3846 I jxcore-log: Number of passed tests:  80
08-26 17:37:52.743  3797  3846 I jxcore-log: 
08-26 17:37:52.743  3797  3846 I jxcore-log: Number of failed tests:  0
08-26 17:37:52.743  3797  3846 I jxcore-log: 
08-26 17:37:52.743  3797  3846 I jxcore-log: Number of ignored tests:  0
08-26 17:37:52.743  3797  3846 I jxcore-log: 
,08-26 17:37:52.744  3797  3846 I jxcore-log: Total duration:  22852
08-26 17:37:52.744  3797  3846 I jxcore-log: 
08-26 17:37:52.744  3797  3846 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 17:37:52.744  3797  3846 I jxcore-log: 
,08-26 17:37:52.749  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.749  3797  3846 I jxcore-log: 
08-26 17:37:52.750  3797  3797 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 17:37:52.753  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.753  3797  3846 I jxcore-log: 
,08-26 17:37:52.755  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.755  3797  3846 I jxcore-log: 
08-26 17:37:52.757  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.757  3797  3846 I jxcore-log: 
08-26 17:37:52.758  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.758  3797  3846 I jxcore-log: 
,08-26 17:37:52.760  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.760  3797  3846 I jxcore-log: 
,08-26 17:37:52.763  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.763  3797  3846 I jxcore-log: 
,08-26 17:37:52.765  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.765  3797  3846 I jxcore-log: 
,08-26 17:37:52.766  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.766  3797  3846 I jxcore-log: 
08-26 17:37:52.767  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.767  3797  3846 I jxcore-log: 
08-26 17:37:52.768  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.768  3797  3846 I jxcore-log: 
08-26 17:37:52.768  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:52.768  3797  3846 I jxcore-log: 
08-26 17:37:52.769  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.769  3797  3846 I jxcore-log: 
08-26 17:37:52.770  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.770  3797  3846 I jxcore-log: 
08-26 17:37:52.770  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.770  3797  3846 I jxcore-log: 
08-26 17:37:52.771  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.771  3797  3846 I jxcore-log: 
08-26 17:37:52.772  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.772  3797  3846 I jxcore-log: 
,08-26 17:37:52.772  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.772  3797  3846 I jxcore-log: 
08-26 17:37:52.773  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.773  3797  3846 I jxcore-log: 
,08-26 17:37:52.774  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.774  3797  3846 I jxcore-log: 
,08-26 17:37:52.774  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.774  3797  3846 I jxcore-log: 
,08-26 17:37:52.775  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.775  3797  3846 I jxcore-log: 
08-26 17:37:52.776  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.776  3797  3846 I jxcore-log: 
,08-26 17:37:52.776  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:52.776  3797  3846 I jxcore-log: 
08-26 17:37:52.777  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.777  3797  3846 I jxcore-log: 
08-26 17:37:52.777  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:52.777  3797  3846 I jxcore-log: 
08-26 17:37:52.778  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.778  3797  3846 I jxcore-log: 
08-26 17:37:52.779  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.779  3797  3846 I jxcore-log: 
08-26 17:37:52.779  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.779  3797  3846 I jxcore-log: 
08-26 17:37:52.780  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.780  3797  3846 I jxcore-log: 
,08-26 17:37:52.781  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.781  3797  3846 I jxcore-log: 
,08-26 17:37:52.781  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:52.781  3797  3846 I jxcore-log: 
,08-26 17:37:53.048  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 17:37:53.051  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:53.051  3797  3846 I jxcore-log: 
,08-26 17:37:53.147  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 17:37:53.150  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:53.150  3797  3846 I jxcore-log: 
,08-26 17:37:53.199  3797  3797 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 17:37:53.202  3797  3846 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:53.202  3797  3846 I jxcore-log: 
,08-26 17:37:53.325  2148  2650 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 17:37:53.371  4270  4270 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 17:37:53.376  4270  4270 D AndroidRuntime: CheckJNI is OFF
,08-26 17:37:53.419  4270  4270 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 17:37:53.467  4270  4270 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 17:37:53.490  4270  4270 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 17:37:53.502   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 17:37:53.503   874   887 I ActivityManager: Killing 3797:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 17:37:53.615   874   897 W PackageSettings: Skipping PackageSetting{83d5158 com.example.hello/10273} due to missing metadata
,08-26 17:37:53.618   874  1914 I WindowState: WIN DEATH: Window{7c543f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 17:37:53.619   874  1316 D WifiService: Client connection lost with reason: 4
08-26 17:37:53.621   874  1969 D GraphicsStats: Buffer count: 2
,08-26 17:37:53.649   874   897 I art     : Starting a blocking GC Explicit
,08-26 17:37:53.662   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 17:37:53.662   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 17:37:53.663   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-26 17:37:53.663   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 17:37:53.663   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:53.663   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.663   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:53.663   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 17:37:53.664   874   887 I ActivityManager:   Force finishing activity ActivityRecord{9da9e51 u0 com.test.thalitest/.MainActivity t2}
08-26 17:37:53.670   874  1918 W ActivityManager: Spurious death for ProcessRecord{2b5e53 0:com.test.thalitest/u0a0}, curProc for 3797: null
,08-26 17:37:53.695   874   897 I art     : Explicit concurrent mark sweep GC freed 13707(957KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 787us total 45.248ms
,08-26 17:37:53.724   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 17:37:53.727  4270  4270 I art     : System.exit called, status: 0
08-26 17:37:53.727  4270  4270 I AndroidRuntime: VM exiting with result code 0.
,08-26 17:37:53.731   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 17:37:53.745   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-26 17:37:53.748  4182  4182 D BluetoothMapAppObserver: onReceive
08-26 17:37:53.748  4182  4182 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 17:37:53.749  2148  2289 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 17:37:53.751  3664  3664 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-26 17:37:53.751  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
08-26 17:37:53.752   874  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 17:37:53.768   874   884 I ActivityManager: Start proc 4284:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 17:37:53.790  1954  1954 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 17:37:53.792  1864  4282 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 17:37:53.794  1864  4282 I Decoder : createOrResetDecoder
,08-26 17:37:53.827  1543  1543 I ConfigService: onCreate
,08-26 17:37:53.828   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 17:37:53.837  4284  4284 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 17:37:53.846  1864  4282 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 17:37:53.863   874  1998 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3797 uid 10000
,08-26 17:37:53.864  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-26 17:37:53.886  1864  4282 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 17:37:53.889  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 17:37:53.889  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 17:37:53.890   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 17:37:53.891   874   886 E PackageManager: Failed to write settings, restoring backup
08-26 17:37:53.891   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 17:37:53.891   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 17:37:53.891   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 17:37:53.891   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 17:37:53.891   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 17:37:53.891   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:53.891   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.891   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 17:37:53.892  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 17:37:53.892  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 17:37:53.893  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-26 17:37:53.893  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 17:37:53.895  1864  4282 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 17:37:53.895  1864  4282 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-26 17:37:53.895  1864  4282 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 17:37:53.895  1864  4282 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 17:37:53.895  1864  4282 I StatsUtilsManager: startPeriodStatsRecorder() : Success,
08-26 17:37:53.895  1864  4282 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 17:37:53.895   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-26 17:37:53.895   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 17:37:53.895   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:53.895   874   887 E DropBoxManagerService: 	... 13 more
,08-26 17:37:53.900  1975  2070 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-26 17:37:53.912   874   885 I ActivityManager: Start proc 4302:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-26 17:37:53.913  1975  2070 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 17:37:53.913  1975  2070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1975
08-26 17:37:53.913  1975  2070 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.913  1975  2070 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:53.915   874  1377 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 17:37:53.915   874  4307 E DropBoxManagerService: Can't write: system_app_crash
08-26 17:37:53.915   874  4307 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:53.915   874  4307 E DropBoxManagerService: 	... 5 more
08-26 17:37:53.917  4284  4284 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-26 17:37:53.920  1975  2070 I Process : Sending signal. PID: 1975 SIG: 9
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.938  4284  4300 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:53.938   874  3101 I ActivityManager: Start proc 4317:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.938  4284  4300 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:53.940  4284  4316 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 17:37:53.971  4317  4317 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 17:37:53.987  1543  1543 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 17:37:53.988  1543  1543 D AndroidRuntime: Shutting down VM
08-26 17:37:53.989  1543  1543 E AndroidRuntime: FATAL EXCEPTION: main
08-26 17:37:53.989  1543  1543 E AndroidRuntime: Process: com.google.process.gapps, PID: 1543
08-26 17:37:53.989  1543  1543 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 17:37:53.989  1543  1543 E AndroidRuntime: 	... 8 more
,08-26 17:37:53.993   874  4331 E DropBoxManagerService: Can't write: system_app_crash
08-26 17:37:53.993   874  4331 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:53.993   874  4331 E DropBoxManagerService: 	... 5 more
,08-26 17:37:53.994  1543  1543 I Process : Sending signal. PID: 1543 SIG: 9
,08-26 17:37:53.995   874  1462 D GraphicsStats: Buffer count: 1
,08-26 17:37:53.996   874  1377 I WindowState: WIN DEATH: Window{8935168 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 17:37:54.001   874  1998 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1975) has died
,08-26 17:37:54.002   874  1998 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-26 17:37:54.003   874  1998 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 17:37:54.021   874   887 I ActivityManager: Start proc 4334:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 17:37:54.043   874   892 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,08-26 17:37:54.044   874   892 W DisplayManagerService: Failed to notify process 1543 that displays changed, assuming it died.
08-26 17:37:54.044   874   892 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 17:37:54.044   874   892 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 17:37:54.052   874  1316 D WifiService: Client connection lost with reason: 4
,08-26 17:37:54.056   874  1973 I ActivityManager: Process com.google.process.gapps (pid 1543) has died
,08-26 17:37:54.057   874  1973 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,08-26 17:37:54.057   874  1973 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
08-26 17:37:54.057   874  1973 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-26 17:37:54.057   874  1973 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,08-26 17:37:54.064  1740  1740 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 17:37:54.075  4334  4334 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:54.075  4334  4334 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 17:37:54.076  4334  4334 D AndroidRuntime: Shutting down VM
,08-26 17:37:54.077   874  1918 I ActivityManager: Start proc 4347:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-26 17:37:54.086  4334  4334 E AndroidRuntime: FATAL EXCEPTION: main
08-26 17:37:54.086  4334  4334 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4334
08-26 17:37:54.086  4334  4334 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 17:37:54.086  4334  4334 E AndroidRuntime: 	... 10 more
08-26 17:37:54.088   874  1998 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 17:37:54.088  4334  4334 I Process : Sending signal. PID: 4334 SIG: 9
,08-26 17:37:54.095   874  4359 E DropBoxManagerService: Can't write: system_app_crash
08-26 17:37:54.095   874  4359 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:54.095   874  4359 E DropBoxManagerService: 	... 5 more
,08-26 17:37:54.109  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 17:37:54.109  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 17:37:54.110   874  1918 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4334) has died
08-26 17:37:54.112   874  1918 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 17:37:54.117  4347  4347 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-26 17:37:54.124  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 17:37:54.124  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-26 17:37:54.127  4347  4347 I MultiDex: VM with version 2.1.0 has multidex support
08-26 17:37:54.127  4347  4347 I MultiDex: install
08-26 17:37:54.127   874   887 I ActivityManager: Start proc 4363:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 17:37:54.127  4347  4347 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 17:37:54.133  4347  4347 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-26 17:37:54.136  4347  4347 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 17:37:54.138  4347  4347 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:54.138  4347  4347 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 17:37:54.139  4347  4347 D AndroidRuntime: Shutting down VM
08-26 17:37:54.139  4347  4347 E AndroidRuntime: FATAL EXCEPTION: main
08-26 17:37:54.139  4347  4347 E AndroidRuntime: Process: com.google.process.gapps, PID: 4347
08-26 17:37:54.139  4347  4347 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvid,er: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 17:37:54.139  4347  4347 E AndroidRuntime: 	... 10 more
08-26 17:37:54.141  4347  4347 I Process : Sending signal. PID: 4347 SIG: 9
,08-26 17:37:54.144   874  4377 E DropBoxManagerService: Can't write: system_app_crash
08-26 17:37:54.144   874  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:54.144   874  4377 E DropBoxManagerService: 	... 5 more
,08-26 17:37:54.156  1740  4369 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 17:37:54.157  2043  4375 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-26 17:37:54.167   874  1914 I ActivityManager: Process com.google.process.gapps (pid 4347) has died
,08-26 17:37:54.168   874  1914 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{e9e1987 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-26 17:37:54.168   874  1914 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{92faa73 u0 com.google.android.gms/.auth.GetToken}
08-26 17:37:54.168   874  1914 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{3e89195 u0 com.google.android.gms/.config.ConfigService}
08-26 17:37:54.168   874  1914 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{223e8e5 u0 com.google.android.gms/.gcm.GcmService}
,08-26 17:37:54.184  1740  4369 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-26 17:37:54.184  1740  4369 E AndroidRuntime: Process: com.google.android.gms, PID: 1740
08-26 17:37:54.184  1740  4369 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 17:37:54.184  1740  4369 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-26 17:37:54.184   874  1914 I ActivityManager: Start proc 4379:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-26 17:37:54.186  4363  4363 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 17:37:54.186  4363  4363 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 17:37:54.187  4363  4363 D AndroidRuntime: Shutting down VM
08-26 17:37:54.187   874  1900 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-26 17:37:54.187   874  1900 I ActivityManager: Killing 1740:com.google.android.gms/u0,a11 (adj 5): crash
08-26 17:37:54.190   874  4389 E DropBoxManagerService: Can't write: system_app_crash
08-26 17:37:54.190   874  4389 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 17:37:54.190   874  4389 E DropBoxManagerService: 	... 5 more
,08-26 17:37:54.208  2043  4375 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 17:37:54.224   874  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-26 17:37:54.229  4284  4300 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 17:37:54.234  4284  4316 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.234  4284  4316 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 17:37:54.234  4284  4316 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 17:37:54.234  4284  4316 E AndroidRuntime: Process: android.process.acore, PID: 4284
08-26 17:37:54.234  4284  4316 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 17:37:54.234  4284  4316 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 17:37:54.235  4284  4300 I Process : Sending signal. PID: 4284 SIG: 9
08-26 17:37:54.236   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
