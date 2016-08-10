#### Test 797510154a934e8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 10:41:28.255  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:41:28.268  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:41:28.271  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:41:28.313  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 10:41:28.313  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 10:41:28.313  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:41:28.313  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 10:41:28.345  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 10:41:28.346  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 10:41:28.346  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-10 10:41:28.561   873  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-10 10:41:28.908  3659  3659 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 10:41:28.913  3659  3659 D AndroidRuntime: CheckJNI is OFF
08-10 10:41:28.955  3659  3659 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 10:41:29.008  3659  3659 I Radio-JNI: register_android_hardware_Radio DONE
08-10 10:41:29.030  3659  3659 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 10:41:29.036   873  1740 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 10:41:29.078  3659  3659 D AndroidRuntime: Shutting down VM
08-10 10:41:29.080  1798  1811 W SearchService: Abort, client detached.
08-10 10:41:29.093  1798  2132 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@498b2e0
08-10 10:41:29.094  1798  2141 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 10:41:29.095   873  1791 I ActivityManager: Start proc 3668:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 10:41:29.096  1798  1798 I HotwordDetector: Closing mic
08-10 10:41:29.147   375  2143 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 10:41:29.149   375  2143 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 10:41:29.164   375  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 10:41:29.166  1798  2138 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 10:41:29.169  1798  2140 I MicroRecognitionRnrImpl: Detection finished
08-10 10:41:29.178  3668  3668 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 10:41:29.198  3668  3668 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 10:41:29.216  3668  3668 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 2572-2587)
08-10 10:41:29.217  3668  3668 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 10:41:29.252  3668  3668 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {229d1ba}
08-10 10:41:29.253  3668  3668 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 10:41:29.253  3668  3668 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 10:41:29.259  3668  3668 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 10:41:29.260  3668  3668 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 10:41:29.274  3668  3668 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 10:41:29.283  3668  3668 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 10:41:29.283  3668  3668 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 10:41:29.283  3668  3668 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 10:41:29.283  3668  3668 I Adreno  : Build Date                       : 10/20/15
08-10 10:41:29.283  3668  3668 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 10:41:29.283  3668  3668 I Adreno  : Local Branch                     : M14
08-10 10:41:29.283  3668  3668 I Adreno  : Remote Branch                    : 
08-10 10:41:29.283  3668  3668 I Adreno  : Remote Branch                    : 
08-10 10:41:29.283  3668  3668 I Adreno  : Reconstruct Branch               : 
,08-10 10:41:29.365   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89c6a02:true
,08-10 10:41:29.390  3668  3668 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 10:41:29.402  3668  3668 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 10:41:29.466  3668  3706 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 10:41:29.478  3668  3693 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 10:41:29.527  3668  3706 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 10:41:29.635   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +554ms
,08-10 10:41:29.642  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-10 10:41:29.743  3668  3668 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3668
,08-10 10:41:29.928   873  1740 I ActivityManager: Killing 3275:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 10:41:29.935  3668  3668 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 10:41:29.981   873  1740 I ActivityManager: Killing 2852:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-10 10:41:30.215  3668  3709 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1698694864
,08-10 10:41:30.222  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 10:41:30.222  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 10:41:30.222  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 10:41:30.222  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 10:41:30.222  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 10:41:30.223  3668  3709 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc041e added. We now have 1 listener(s)
,08-10 10:41:30.225  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 10:41:30.227  3668  3709 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-10 10:41:30.229  3668  3709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:41:30.229  3668  3709 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 10:41:30.243  3668  3709 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f1915 added. We now have 1 listener(s)
08-10 10:41:30.244  3668  3709 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 10:41:30.253   873  1310 D WifiService: New client listening to asynchronous messages
,08-10 10:41:30.256  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 10:41:30.257  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 10:41:30.257  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 10:41:30.257  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-10 10:41:30.258  3668  3709 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 10:41:30.266  3668  3709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:30.267  3668  3709 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 10:41:30.284  3668  3709 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:30.284  3668  3709 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:41:30.284  3668  3709 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 10:41:30.284  3668  3709 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:41:30.285  3668  3709 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 10:41:30.366  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:30.369  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:30.370  3668  3668 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 10:41:31.735  3668  3719 W jxcore-log: Initializing JXcore engine
,08-10 10:41:31.735  3668  3719 W jxcore-log: JXcore engine is ready
,08-10 10:41:31.808  3719  3719 W Thread-334: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 10:41:31.808  3719  3719 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10709]" dev="sockfs" ino=10709 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 10:41:31.808  3719  3719 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 10:41:31.808  3719  3719 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22348]" dev="sockfs" ino=22348 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 10:41:31.829  3668  3719 W jxcore-log: Starting JXcore engine
,08-10 10:41:31.906  3668  3719 W jxcore-log: Platform android
08-10 10:41:31.906  3668  3719 W jxcore-log: 
,08-10 10:41:31.906  3668  3719 W jxcore-log: Process ARCH arm
08-10 10:41:31.906  3668  3719 W jxcore-log: 
,08-10 10:41:32.120  3668  3719 I jxcore-log: JXcore Cordova bridge is ready!
08-10 10:41:32.120  3668  3719 I jxcore-log: 
,08-10 10:41:32.120  3668  3719 W jxcore-log: JXcore engine is started
,08-10 10:41:32.132  3668  3709 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 10:41:32.137  3668  3668 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 10:41:33.969  2914  3721 V KeepSync: Connecting to GoogleApiClient
,08-10 10:41:33.969   873  1690 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:41:34.006  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:41:34.008  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:41:34.043  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 10:41:34.043  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 10:41:34.043  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:41:34.044  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:41:34.068  1958  3722 V BaseAuthAsyncOperation: access token request failed
,08-10 10:41:34.069  2914  3721 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:41:34.161  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 10:41:34.162  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 10:41:34.162  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:41:34.162  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:41:34.177  2914  3721 E KeepSync: IOException
08-10 10:41:34.177  2914  3721 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:41:34.177  2914  3721 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:41:34.177  2914  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:41:34.177  2914  3721 E KeepSync: 	... 10 more
,08-10 10:41:34.178  2914  3721 W KeepSync: Sync result 2
,08-10 10:41:34.183   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:41:47.965  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 10:41:47.965  3668  3719 I jxcore-log: 
,08-10 10:41:47.968  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 10:41:47.968  3668  3719 I jxcore-log: 
,08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:47.980  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:41:47.985  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:41:47.987  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 10:41:47.987  3668  3719 I jxcore-log: 
,08-10 10:41:47.989  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 10:41:47.989  3668  3719 I jxcore-log: 
,08-10 10:41:48.327  3668  3719 D ExecuteNativeTests: Running unit tests
,08-10 10:41:48.390  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:41:48.390  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de added. We now have 2 listener(s)
,08-10 10:41:48.391  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 10:41:48.391  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 10:41:48.391  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 10:41:48.391  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 10:41:48.391  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf added. We now have 2 listener(s)
,08-10 10:41:48.391  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 10:41:48.414  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 10:41:48.417  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.425  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:41:48.427  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:41:48.427  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:41:48.430  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 10:41:48.431  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.431  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 10:41:48.431  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 10:41:48.433  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.433  3668  3719 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 10:41:48.434  3668  3719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-10 10:41:48.434  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 10:41:48.434  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 10:41:48.434  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 10:41:48.434  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:41:48.435  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.435  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.435  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:41:48.435  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.435  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:41:48.435  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-10 10:41:48.435  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de removed from the list
,08-10 10:41:48.435  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:41:48.435  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf removed from the list
08-10 10:41:48.435  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.435  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.436  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.436  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.437  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 10:41:48.437  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.437  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:41:48.437  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.438  3668  3719 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-10 10:41:48.439  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.439  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 10:41:48.439  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.439  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.439  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:41:48.439  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.439  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
,08-10 10:41:48.439  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.439  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
,08-10 10:41:48.439  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.439  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.440  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.440  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.440  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.440  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.440  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 10:41:48.440  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.440  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 10:41:48.445  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 10:41:48.446  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-10 10:41:48.447  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-10 10:41:48.447  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-10 10:41:48.447  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-10 10:41:48.447  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:41:48.447  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.447  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.447  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:41:48.447  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:41:48.447  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.447  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
,08-10 10:41:48.447  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.447  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
,08-10 10:41:48.447  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.447  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.447  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 10:41:48.447  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.447  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.448  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 10:41:48.448  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.448  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:41:48.448  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.449  3668  3719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 10:41:48.450  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.453  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:41:48.455  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.455  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 10:41:48.455  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 10:41:48.455  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 10:41:48.455  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 10:41:48.455  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:41:48.455  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 10:41:48.456  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.458  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.459  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 10:41:48.459  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 10:41:48.463  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-10 10:41:48.464  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 10:41:48.464  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 10:41:48.466  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 10:41:48.469  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-10 10:41:48.469  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 10:41:48.469  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 10:41:48.470  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 10:41:48.470  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:41:48.474  2561  2769 D BtGatt.GattService: registerClient() - UUID=92a6966e-e017-4a17-8b18-116993f65c1d
08-10 10:41:48.475  2561  2616 D BtGatt.GattService: onClientRegistered() - UUID=92a6966e-e017-4a17-8b18-116993f65c1d, clientIf=5
08-10 10:41:48.475  3668  3680 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 10:41:48.476  2561  2760 D BtGatt.GattService: start scan with filters
,08-10 10:41:48.478  2561  2620 D BtGatt.ScanManager: handling starting scan
08-10 10:41:48.478  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 10:41:48.478  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 10:41:48.478  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 10:41:48.478  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 10:41:48.479  2561  2620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
08-10 10:41:48.480  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:41:48.481  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 10:41:48.481  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:41:48.482  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 10:41:48.485  3668  3719 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 10:41:48.485  2561  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 10:41:48.485  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:41:48.486  2561  2620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 10:41:48.488  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:41:48.488  3668  3719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 10:41:48.488  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.489  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 10:41:48.489  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.489  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 10:41:48.490  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 10:41:48.490  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 10:41:48.490  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 10:41:48.490  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 10:41:48.490  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.490  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:41:48.491  2561  2620 D BtGatt.ScanManager: Starting BLE batch scan
08-10 10:41:48.491  2561  2620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 10:41:48.491  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:41:48.491  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-10 10:41:48.492  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:41:48.493  2561  2576 D BtGatt.GattService: stopScan() - queue size =1
,08-10 10:41:48.493  2561  2768 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 10:41:48.493  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 10:41:48.493  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 10:41:48.494  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 10:41:48.494  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:41:48.494  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 10:41:48.494  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 10:41:48.495  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:41:48.495  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 10:41:48.495  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 10:41:48.496  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:41:48.497  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.497  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:41:48.497  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:41:48.497  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.497  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 10:41:48.497  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:41:48.497  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 10:41:48.497  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.497  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.497  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.497  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.498  3668  3719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 10:41:48.499  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.499  2561  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 10:41:48.499  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.503  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:41:48.504  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 10:41:48.504  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.505  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:41:48.505  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:41:48.505  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 10:41:48.505  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 10:41:48.505  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 10:41:48.506  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.506  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 10:41:48.507  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.509  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 10:41:48.510  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.510  2561  2620 D BtGatt.ScanManager: stopping BLe Batch
08-10 10:41:48.510  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.511  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 10:41:48.511  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 10:41:48.514  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 10:41:48.515  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 10:41:48.515  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 10:41:48.515  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 10:41:48.515  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.515  2561  2620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 10:41:48.518  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 10:41:48.518  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 10:41:48.518  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 10:41:48.519  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:41:48.520  2561  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 10:41:48.520  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:41:48.520  2561  2760 D BtGatt.GattService: registerClient() - UUID=b2b34223-eca9-4f55-a89a-f0b03b48bc98
,08-10 10:41:48.521  2561  2616 D BtGatt.GattService: onClientRegistered() - UUID=b2b34223-eca9-4f55-a89a-f0b03b48bc98, clientIf=5
08-10 10:41:48.521  3668  3679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 10:41:48.521  2561  2575 D BtGatt.GattService: start scan with filters
,08-10 10:41:48.523  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 10:41:48.523  2561  2620 D BtGatt.ScanManager: handling starting scan
08-10 10:41:48.523  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 10:41:48.523  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 10:41:48.523  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 10:41:48.525  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:41:48.525  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 10:41:48.525  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 10:41:48.526  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 10:41:48.528  3668  3719 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 10:41:48.528  2561  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 10:41:48.528  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.528  2561  2620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 10:41:48.530  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:41:48.530  3668  3719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 10:41:48.530  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.530  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 10:41:48.530  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.530  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 10:41:48.530  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 10:41:48.530  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 10:41:48.530  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 10:41:48.530  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:41:48.530  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:41:48.530  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 10:41:48.531  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:41:48.531  2561  2768 D BtGatt.GattService: stopScan() - queue size =1
,08-10 10:41:48.531  2561  2769 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 10:41:48.532  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 10:41:48.532  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 10:41:48.532  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-10 10:41:48.532  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:41:48.532  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 10:41:48.533  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 10:41:48.533  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:41:48.533  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 10:41:48.533  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 10:41:48.533  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 10:41:48.533  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.533  2561  2620 D BtGatt.ScanManager: Starting BLE batch scan
08-10 10:41:48.533  2561  2620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 10:41:48.534  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:41:48.534  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.534  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 10:41:48.534  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.534  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:41:48.534  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:41:48.534  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.534  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:41:48.534  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 10:41:48.535  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
,08-10 10:41:48.535  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.535  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.535  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.535  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.536  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.536  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 10:41:48.536  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.536  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.537  3668  3719 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 10:41:48.539  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:41:48.542  2561  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 10:41:48.542  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.542  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:41:48.544  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:41:48.544  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 10:41:48.544  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:41:48.544  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 10:41:48.544  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 10:41:48.544  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.544  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 10:41:48.546  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.546  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 10:41:48.546  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:41:48.547  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 10:41:48.547  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 10:41:48.548  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.550  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 10:41:48.550  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 10:41:48.551  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 10:41:48.553  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 10:41:48.553  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.553  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 10:41:48.553  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 10:41:48.553  2561  2620 D BtGatt.ScanManager: stopping BLe Batch
08-10 10:41:48.553  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 10:41:48.554  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:41:48.556  2561  2769 D BtGatt.GattService: registerClient() - UUID=3259ecad-e891-4e37-ab5f-ce69a940a8f9
,08-10 10:41:48.556  2561  2616 D BtGatt.GattService: onClientRegistered() - UUID=3259ecad-e891-4e37-ab5f-ce69a940a8f9, clientIf=5
08-10 10:41:48.556  3668  3679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 10:41:48.556  2561  2760 D BtGatt.GattService: start scan with filters
,08-10 10:41:48.558  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 10:41:48.558  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.558  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 10:41:48.558  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 10:41:48.558  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 10:41:48.558  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 10:41:48.558  2561  2620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 10:41:48.560  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:41:48.560  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 10:41:48.560  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 10:41:48.561  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 10:41:48.565  2561  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 10:41:48.565  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.565  3668  3719 I io.jxcore.node.ConnectionHelper: start: OK
08-10 10:41:48.565  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:41:48.565  3668  3719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 10:41:48.566  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.566  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 10:41:48.566  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.566  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 10:41:48.566  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 10:41:48.566  2561  2620 D BtGatt.ScanManager: handling starting scan
08-10 10:41:48.566  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 10:41:48.566  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 10:41:48.566  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:41:48.566  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:41:48.566  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 10:41:48.567  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:41:48.567  2561  2768 D BtGatt.GattService: stopScan() - queue size =1
08-10 10:41:48.568  2561  2760 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 10:41:48.568  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 10:41:48.568  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 10:41:48.568  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 10:41:48.568  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:41:48.568  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 10:41:48.569  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:41:48.569  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:41:48.569  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 10:41:48.569  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 10:41:48.569  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:41:48.570  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.570  3668  3719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 10:41:48.570  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.570  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.570  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.570  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.570  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:41:48.571  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.571  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.571  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.571  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.571  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.571  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:41:48.571  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 10:41:48.571  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:41:48.571  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.571  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.572  2561  2616 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 10:41:48.572  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.572  2561  2620 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 10:41:48.572  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.572  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.572  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.573  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.573  3668  3719 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-10 10:41:48.573  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.573  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.573  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.574  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:41:48.574  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.574  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.574  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
,08-10 10:41:48.574  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.574  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.574  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.574  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.574  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.574  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.574  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.575  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.575  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.575  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.575  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.576  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 10:41:48.576  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.576  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.576  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.576  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:41:48.576  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.576  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.577  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.577  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.577  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
,08-10 10:41:48.577  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 10:41:48.577  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.577  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:41:48.577  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.577  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.577  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.577  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.578  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.578  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.578  3668  3719 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 10:41:48.579  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.579  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.579  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 10:41:48.579  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.579  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 10:41:48.580  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.580  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.580  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.580  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.580  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.580  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.580  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 10:41:48.580  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.580  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.580  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.580  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.581  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.581  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.581  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.581  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.581  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 10:41:48.582  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.582  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.582  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.582  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.582  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.582  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.582  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.582  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:41:48.582  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.582  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.582  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.582  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.582  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.582  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.583  2561  2620 D BtGatt.ScanManager: Starting BLE batch scan
08-10 10:41:48.583  2561  2620 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 10:41:48.584  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.584  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.584  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.584  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.584  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 10:41:48.585  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 10:41:48.585  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 10:41:48.585  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 10:41:48.585  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 10:41:48.585  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 10:41:48.585  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.585  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.586  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.586  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.586  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.586  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.586  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.586  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.586  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.586  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.586  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.586  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.586  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.586  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.587  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.587  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.587  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.587  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.588  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 10:41:48.588  3668  3719 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 10:41:48.588  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 10:41:48.591  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 10:41:48.591  3668  3719 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 10:41:48.591  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 10:41:48.592  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 10:41:48.592  2561  2616 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 10:41:48.593  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 10:41:48.593  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 10:41:48.593  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 10:41:48.593  3668  3719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 10:41:48.594  3668  3719 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 10:41:48.594  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 10:41:48.594  3668  3719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 10:41:48.594  3668  3719 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 10:41:48.594  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 10:41:48.594  3668  3719 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 10:41:48.594  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 10:41:48.597  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 10:41:48.598  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.598  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 10:41:48.598  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 10:41:48.598  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 10:41:48.599  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 10:41:48.599  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 10:41:48.599  3668  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-10 10:41:48.600  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 10:41:48.600  3668  3719 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 10:41:48.600  3668  3719 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 10:41:48.601  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.601  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.601  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.601  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.601  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.601  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.601  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 10:41:48.602  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.602  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.602  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.602  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.602  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.602  3668  3733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:41:48.602  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.602  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.602  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.603  2561  2616 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 10:41:48.603  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.603  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.603  2561  2620 D BtGatt.ScanManager: stopping BLe Batch
08-10 10:41:48.603  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.604  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.604  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.604  3668  3719 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 10:41:48.604  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.604  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.604  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.605  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.605  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.605  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.605  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.605  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.605  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.605  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.605  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.605  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.605  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.605  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.606  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.606  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.606  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.606  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.607  3668  3719 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 10:41:48.607  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.607  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.607  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.607  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.607  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.607  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.607  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.607  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.607  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.607  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.608  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.608  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.608  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.608  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.608  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.608  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.608  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.608  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.609  3668  3719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 10:41:48.609  3668  3719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 10:41:48.609  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 10:41:48.609  3668  3719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 10:41:48.609  3668  3719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 10:41:48.609  3668  3719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 10:41:48.609  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 10:41:48.609  3668  3719 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 10:41:48.609  3668  3719 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 10:41:48.609  3668  3719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 10:41:48.610  3668  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-10 10:41:48.610  3668  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 398)
08-10 10:41:48.610  3668  3733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-10 10:41:48.610  2561  2616 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 10:41:48.610  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.610  2561  2620 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 10:41:48.610  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 10:41:48.611  3668  3719 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 10:41:48.611  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.611  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.611  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.611  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.611  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.611  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.611  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.611  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.611  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.611  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.611  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.611  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.611  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.612  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.612  2561  2757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-10 10:41:48.612  3668  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 398)
08-10 10:41:48.613  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.613  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.613  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.613  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.614  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.614  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.614  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.614  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.614  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.614  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.614  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.614  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.614  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.614  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.614  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.614  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.614  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.614  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.614  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.614  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.614  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.614  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.615  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.615  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.615  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.615  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.615  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.615  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.615  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.615  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.615  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.615  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.615  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.616  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.616  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.616  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.616  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.617  3668  3719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 10:41:48.617  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.617  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 10:41:48.618  2561  2616 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 10:41:48.618  2561  2616 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:41:48.618  3668  3719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 10:41:48.618  3668  3719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 10:41:48.618  3668  3668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 10:41:48.618  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 10:41:48.618  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 10:41:48.619  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.619  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 10:41:48.619  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 10:41:48.619  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-10 10:41:48.619  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.619  3668  3719 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 10:41:48.619  3668  3668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 10:41:48.619  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.619  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.619  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 10:41:48.619  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 10:41:48.619  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:41:48.620  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.620  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.620  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:41:48.621  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:41:48.621  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:41:48.621  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:41:48.621  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.621  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.621  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.621  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.621  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.621  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.621  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.621  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.621  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.621  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.621  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.622  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.622  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.622  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.622  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.622  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.622  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.623  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.623  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.623  3668  3735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 10:41:48.623  3668  3735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 10:41:48.623  3668  3668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 10:41:48.624  3668  3719 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 10:41:48.624  3668  3719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 10:41:48.624  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 10:41:48.625  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 10:41:48.625  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.625  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.625  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.625  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.625  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.625  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.625  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.626  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.626  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.626  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.626  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.626  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.626  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.626  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.626  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.627  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.627  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.627  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.630  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.630  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.630  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.630  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.630  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.630  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.631  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.631  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.631  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.631  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.631  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.631  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.631  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.631  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.632  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.632  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.632  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.632  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.632  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:41:48.632  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:41:48.632  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:41:48.633  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:41:48.633  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.633  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.633  3668  3719 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fec9de not in the list
08-10 10:41:48.633  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.633  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.633  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:41:48.633  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.633  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.633  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:41:48.633  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:41:48.634  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:41:48.634  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:41:48.634  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:41:48.634  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b1c7bf not in the list
08-10 10:41:48.636  3668  3719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 10:41:48.636  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 10:41:48.636  3668  3719 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 10:41:48.636  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 10:41:48.636  3668  3719 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 10:41:48.636  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 10:41:48.637  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 10:41:48.637  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 10:41:48.638  3668  3719 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 10:41:48.638  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 10:41:48.638  3668  3719 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 10:41:48.638  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 10:41:48.638  3668  3719 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 10:41:48.638  3668  3719 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 10:41:48.639  3668  3719 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 10:41:48.640  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:41:48.640  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15d7689 added. We now have 2 listener(s)
08-10 10:41:48.640  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:41:48.641  3668  3719 D BluetoothAdapter: enable(): BT is already enabled..!
08-10 10:41:48.641   873  1675 D WifiService: setWifiEnabled: true pid=3668, uid=10000
08-10 10:41:48.641   873  1675 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 10:41:48.642  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:41:48.642  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5df668e added. We now have 3 listener(s)
08-10 10:41:48.642  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:41:48.647  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:41:48.647  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1321eaf added. We now have 4 listener(s)
08-10 10:41:48.647  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:41:48.648  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:41:48.648  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20a92bc added. We now have 5 listener(s)
08-10 10:41:48.648  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:41:48.649   873  1740 D WifiService: setWifiEnabled: false pid=3668, uid=10000
08-10 10:41:48.649   873  1740 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 10:41:48.654  2561  2611 D BluetoothAdapterState: Current state: ON, message: 23
08-10 10:41:48.654  2561  2611 D BluetoothAdapterProperties: Setting state to 13
,08-10 10:41:48.654  2561  2611 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 10:41:48.654  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:41:48.654  2561  2611 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 10:41:48.654  2561  2611 I BluetoothAdapterState: Entering PendingCommandState
08-10 10:41:48.656  2561  2561 D BluetoothMapService: onReceive
08-10 10:41:48.656  2561  2561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 10:41:48.656  2561  2561 D BluetoothMapService: STATE_TURNING_OFF
08-10 10:41:48.656  2561  2561 D BluetoothMapService: MAP Service closeService in
08-10 10:41:48.656  2561  2561 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 10:41:48.656  2561  2561 D ObexServerSockets0: shutdown(block = true)
08-10 10:41:48.657  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 10:41:48.657  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 10:41:48.657  2561  2757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 10:41:48.657  2561  2770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 10:41:48.658  2561  2771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 10:41:48.658  2561  2561 I BtOppRfcommListener: stopping Accept Thread
08-10 10:41:48.658  2561  3287 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 10:41:48.658  2561  3287 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-10 10:41:48.665  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.665  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:41:48.666  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 10:41:48.667  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:48.667  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.667  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:41:48.669   873  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 10:41:48.669   873  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 10:41:48.669   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 10:41:48.669   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:41:48.669  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.671  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.674   873   886 I ActivityManager: Start proc 3739:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-10 10:41:48.674  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:48.674  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:41:48.675  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.675  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:48.675  2561  2616 D BluetoothAdapterProperties: Scan Mode:20
08-10 10:41:48.675  2561  2611 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 10:41:48.677  2561  2561 D HeadsetService: Received stop request...Stopping profile...
08-10 10:41:48.677   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-10 10:41:48.677   873  1987 D DhcpClient: Clearing IP address
08-10 10:41:48.678   873   873 D BluetoothHeadset: Proxy object disconnected
08-10 10:41:48.678  1351  1824 D BluetoothHeadset: Proxy object disconnected
08-10 10:41:48.678   873   873 D BluetoothHeadset: Proxy object disconnected
08-10 10:41:48.679  1717  1729 D BluetoothHeadset: Proxy object disconnected
,08-10 10:41:48.679   873   873 D BluetoothHeadset: Proxy object disconnected
08-10 10:41:48.679  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.681  2561  2561 D A2dpService: Received stop request...Stopping profile...
08-10 10:41:48.681  2561  2763 D A2dpStateMachine: Exit Disconnected: -1
08-10 10:41:48.681  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.682   873   873 D BluetoothA2dp: Proxy object disconnected
08-10 10:41:48.682  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 10:41:48.682  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:48.682  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.682  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:41:48.684  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.684  1547  2296 V NativeCrypto: Read error: ssl=0xaed94a00: I/O error during system call, Connection timed out
08-10 10:41:48.684  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-10 10:41:48.684  2561  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 10:41:48.684  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:41:48.684  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 10:41:48.684  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:41:48.684  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:41:48.684  2561  2616 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 10:41:48.684  2561  2561 D HidService: Received stop request...Stopping profile...
08-10 10:41:48.684  2561  2561 D HidService: Stopping Bluetooth HidService
08-10 10:41:48.685  1547  2296 V NativeCrypto: SSL shutdown failed: ssl=0xaed94a00: I/O error during system call, Broken pipe
08-10 10:41:48.686   371   871 D CommandListener: Setting iface cfg
08-10 10:41:48.687   873  1675 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-10 10:41:48.687   873  1985 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-10 10:41:48.687   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 10:41:48.688   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-10 10:41:48.688   873  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
08-10 10:41:48.688   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 10:41:48.693  2561  2561 D HealthService: Received stop request...Stopping profile...
08-10 10:41:48.693   394   394 E Parcel  : Reading a NULL string not supported here.
08-10 10:41:48.695  2561  2561 D PanService: Received stop request...Stopping profile...
08-10 10:41:48.695  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 10:41:48.696  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:48.696  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.696  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:48.696   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-10 10:41:48.698   873  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 10:41:48.698  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-10 10:41:48.698  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-10 10:41:48.698  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-10 10:41:48.698  1351  1351 D HidProfile: Bluetooth service disconnected
08-10 10:41:48.698  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 10:41:48.699  1351  1351 D PanProfile: Bluetooth service disconnected
08-10 10:41:48.699  2561  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 10:41:48.699  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:41:48.699  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:41:48.699  2561  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 10:41:48.699  2561  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 10:41:48.699  2561  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 10:41:48.699  2561  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 10:41:48.699  2561  2561 D BluetoothMapService: Received stop request...Stopping profile...
08-10 10:41:48.700  2561  2561 D BluetoothMapService: stop()
08-10 10:41:48.700  2561  2561 D BluetoothMapAppObserver: deinitObservers()
08-10 10:41:48.700  2561  2561 D BluetoothMapAppObserver: removeReceiver()
08-10 10:41:48.703   873  1994 D DhcpClient: Receive thread stopped
08-10 10:41:48.704  1351  1351 D BluetoothMap: Proxy object disconnected
,08-10 10:41:48.705  1351  1351 D MapProfile: Bluetooth service disconnected
,08-10 10:41:48.705  2561  2561 V BluetoothAdapterState: isTurningOff()=true
,08-10 10:41:48.705  2561  2561 V BluetoothAdapterState: isTurningOn()=false
,08-10 10:41:48.705  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.705  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:48.705  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 10:41:48.705  2561  2616 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 10:41:48.705  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 10:41:48.706  2561  2561 V BluetoothAdapterState: isTurningOff()=true
,08-10 10:41:48.706  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:48.706  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.706  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:48.706  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 10:41:48.706  2561  2616 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 10:41:48.707  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 10:41:48.708  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 10:41:48.708  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:48.708  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.708  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:48.708  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 10:41:48.708  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 10:41:48.709  2561  2561 D BluetoothMapService: MAP Service closeService in
08-10 10:41:48.709  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 10:41:48.709  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:48.709  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:48.709  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:48.709   873  1985 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-10 10:41:48.710  2561  2611 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 10:41:48.710  2561  2611 D BluetoothAdapterProperties: Setting state to 15
08-10 10:41:48.710  2561  2611 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 10:41:48.710  1351  1824 D BluetoothMap: onBluetoothStateChange: up=false
08-10 10:41:48.711  2561  2611 I BluetoothAdapterState: Entering BleOnState
08-10 10:41:48.711  1351  1363 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 10:41:48.711   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:41:48.711   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 10:41:48.711  1351  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 10:41:48.712   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:41:48.712  1351  1824 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 10:41:48.714  1717  1857 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 10:41:48.714  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:41:48.714  1351  1367 D BluetoothPan: onBluetoothStateChange on: false
08-10 10:41:48.715   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:41:48.715  2561  2611 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 10:41:48.715  2561  2561 D BluetoothMapService: cleanup()
08-10 10:41:48.715  2561  2561 D BluetoothMapService: MAP Service closeService in
,08-10 10:41:48.715  2561  2611 D BluetoothAdapterProperties: Setting state to 16
08-10 10:41:48.715  2561  2611 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 10:41:48.715  2561  2611 D BluetoothAdapterProperties: onBleDisable
08-10 10:41:48.716  2561  2611 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:41:48.716  2561  2612 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 10:41:48.717  2561  2616 D BluetoothAdapterProperties: Scan Mode:20
08-10 10:41:48.717  2561  2750 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 10:41:48.717  2561  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 10:41:48.720  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:48.720  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:48.721  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.721  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:41:48.727  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:48.727  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:48.728  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.728  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:48.729  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:48.730  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.755   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:48.757  3739  3739 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-10 10:41:48.768  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 10:41:48.773  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-10 10:41:48.775   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:48.776   873  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 10:41:48.776   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:48.787   873  1690 I ActivityManager: Start proc 3756:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 10:41:48.788   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d77f004:true
,08-10 10:41:48.793  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.794  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:48.795  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:41:48.794   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 10:41:48.796   873   890 D Tethering: MasterInitialState.processMessage what=3
08-10 10:41:48.800  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:48.800  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:48.801  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.801  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:48.803  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:48.803  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:48.803  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:41:48.804  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:48.804  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:48.806  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:41:48.810  1964  2094 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 10:41:48.812   873  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-10 10:41:48.827  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 10:41:48.827  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 10:41:48.827  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:41:48.827  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:41:48.847   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-10 10:41:48.848  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 10:41:48.848  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 10:41:48.848  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-10 10:41:48.848   873  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 10:41:48.848   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 10:41:48.855  3739  3739 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 10:41:48.859  3756  3756 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 10:41:48.861  3739  3739 D BluetoothMap: Create BluetoothMap proxy object
,08-10 10:41:48.869  3739  3739 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 10:41:48.881  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:41:48.886   873  1747 I ActivityManager: Killing 2362:com.google.android.talk/u0a61 (adj 15): empty #17
,08-10 10:41:48.919  2561  2616 I bt_hci  : shut_down
,08-10 10:41:48.985  2561  2621 I bt_vendor: low_power_mode_cb
,08-10 10:41:48.990  2561  2621 D bt_hwcfg: hw_epilog_process
,08-10 10:41:49.005  2561  2621 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 10:41:49.006  2561  2621 I bt_vendor: epilog_cb
,08-10 10:41:49.006  2561  2621 I bt_hci  : epilog_finished_callback
,08-10 10:41:49.013  2561  2616 I bt_hci_h4: hal_close
08-10 10:41:49.013  2561  2616 I bt_userial_vendor: device fd = 51 close
,08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-,10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 10:41:49.071  3756  3756 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 10:41:49.071  3756  3756 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 10:41:49.100   873   884 I ActivityManager: Start proc 3789:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-10 10:41:49.105   873   884 I ActivityManager: Killing 3111:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-10 10:41:49.122  3668  3668 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-10 10:41:49.144  2561  2612 D bt_stack_manager: event_shut_down_stack finished.
08-10 10:41:49.145  2561  2611 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-10 10:41:49.149  2561  2611 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-10 10:41:49.149  2561  2561 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 10:41:49.150  2561  2561 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 10:41:49.150  2561  2561 D BtGatt.GattService: stop()
08-10 10:41:49.150  2561  2561 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 10:41:49.154  2561  2561 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:49.154  2561  2561 V BluetoothAdapterState: isTurningOn()=false
,08-10 10:41:49.154  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:49.155  2561  2561 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 10:41:49.155  2561  2611 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 10:41:49.155  2561  2611 D BluetoothAdapterProperties: Setting state to 10
08-10 10:41:49.156  2561  2611 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 10:41:49.157  2561  2611 I BluetoothAdapterState: Entering OffState
08-10 10:41:49.158   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-10 10:41:49.188  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 10:41:49.189  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 10:41:49.189  2561  2612 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 10:41:49.191  2561  2612 D bt_stack_manager: event_clean_up_stack finished.
,08-10 10:41:49.191  2561  2561 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 10:41:49.194  2561  2561 I art     : System.exit called, status: 0
,08-10 10:41:49.194  2561  2561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 10:41:49.204  3789  3789 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-10 10:41:49.268   873  1388 I ActivityManager: Process com.android.bluetooth (pid 2561) has died
,08-10 10:41:49.416  3756  3779 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 10:41:49.439  3789  3810 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-10 10:41:49.439  3789  3810 I Babel_SMS: MmsConfig.loadMmsSettings
,08-10 10:41:49.444  3789  3810 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-10 10:41:49.444  3789  3810 I Babel_SMS: MmsConfig.loadFromDatabase
,08-10 10:41:49.484  3789  3810 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-10 10:41:49.484  3789  3810 I Babel_SMS: MmsConfig.loadFromResources
,08-10 10:41:49.486  3789  3810 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-10 10:41:49.487  3789  3810 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-10 10:41:49.536  3789  3789 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 10:41:49.551  3789  3789 I Babel_Crash: startup - clean
,08-10 10:41:49.580  3789  3789 I Babel_telephony: TeleModule.launchCompleted
,08-10 10:41:49.586   873  1793 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-10 10:41:49.594  3789  3789 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-10 10:41:49.607  3789  3789 W Babel   : BAM#gBA: invalid account id: -1
,08-10 10:41:49.607  3789  3789 W Babel   : BAM#gBA: invalid account id: -1
,08-10 10:41:49.607  3789  3789 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-10 10:41:49.611  3789  3815 I Babel   : deleted: false for 0
,08-10 10:41:49.613   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed73c00:true
,08-10 10:41:49.618   873  1388 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-10 10:41:49.631  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 10:41:49.673   873  1625 I ActivityManager: Start proc 3818:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-10 10:41:49.675  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:41:49.678  3789  3789 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 10:41:49.745  3789  3789 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 10:41:49.762  3789  3789 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 10:41:49.773  3789  3789 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 10:41:49.781  3789  3789 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 10:41:49.791  3789  3789 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 10:41:49.809  3789  3789 I vclib   : onServiceConnected
,08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding HeadsetService
,08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding A2dpService
08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding HidService
,08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding HealthService
,08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding PanService
,08-10 10:41:49.829  3818  3818 D AdapterServiceConfig: Adding GattService
08-10 10:41:49.830  3818  3818 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 10:41:49.843   873  1793 I ActivityManager: Killing 3442:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-10 10:41:49.907  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:41:49.941  1958  1958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 10:41:49.944  1958  1958 D SystemUpdateService: onCreate
,08-10 10:41:49.954  1958  1958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 10:41:49.961  1958  3830 I SystemUpdateService: active receiver: enabled
,08-10 10:41:49.965  1958  3830 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 10:41:49.969  1958  1958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 10:41:49.973  1958  3830 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 10:41:49.973  1958  3830 I SystemUpdateService: now status is 0 (complete)
,08-10 10:41:49.973  1958  3830 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 10:41:49.974  1958  3830 I SystemUpdateService: file has been verified
,08-10 10:41:49.974  1958  3830 I SystemUpdateService: OTA package size = 12249756
,08-10 10:41:49.977  1958  3830 I SystemUpdateService: showing system update notification
,08-10 10:41:49.977  1958  2337 I iu.UploadsManager: num queued entries: 0
,08-10 10:41:49.978  1958  2337 I iu.UploadsManager: num updated entries: 0
,08-10 10:41:49.980  1958  2337 I iu.SyncManager: NEXT; no task
,08-10 10:41:50.004  1958  1958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 10:41:50.005  1958  1958 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 10:41:50.022   873  1385 I ActivityManager: Start proc 3832:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 10:41:50.026  1958  1958 D SystemUpdateService: onDestroy
,08-10 10:41:50.054  3832  3832 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 10:41:50.056  3832  3832 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:50.062  3832  3832 D SprintDMHelper: simOperator: 
08-10 10:41:50.062  3832  3832 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 10:41:50.084   873  1625 I ActivityManager: Start proc 3844:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-10 10:41:50.085   873  1625 I ActivityManager: Killing 3319:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 10:41:50.215   873  1740 I ActivityManager: Start proc 3859:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 10:41:50.219  3789  3858 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-10 10:41:50.224   873  1747 I ActivityManager: Killing 3364:android.process.acore/u0a5 (adj 15): empty #17
,08-10 10:41:50.281  3859  3859 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 10:41:50.341  3859  3859 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 10:41:50.341  3859  3859 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 10:41:50.341  3859  3859 I GAv4    :   adb logcat -s GAv4
,08-10 10:41:50.357  3859  3859 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 10:41:50.363  3859  3859 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 10:41:50.399  3859  3876 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 10:41:50.515  3859  3859 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 10:41:50.556  3859  3859 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 10:41:50.564  3859  3859 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3932-3934)
,08-10 10:41:50.564  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 10:41:50.578  3859  3859 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {69fb0ce}
,08-10 10:41:50.578  3859  3859 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 10:41:50.578  3859  3859 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 10:41:50.587  3859  3859 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 10:41:50.589  3859  3859 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 10:41:50.603  3859  3859 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 10:41:50.620  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 10:41:50.620  3859  3859 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 10:41:50.620  3859  3859 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 10:41:50.620  3859  3859 I Adreno  : Build Date                       : 10/20/15
08-10 10:41:50.620  3859  3859 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 10:41:50.620  3859  3859 I Adreno  : Local Branch                     : M14
08-10 10:41:50.620  3859  3859 I Adreno  : Remote Branch                    : 
08-10 10:41:50.620  3859  3859 I Adreno  : Remote Branch                    : 
08-10 10:41:50.620  3859  3859 I Adreno  : Reconstruct Branch               : 
,08-10 10:41:50.680  3859  3859 I NSApplication: Starting up...
,08-10 10:41:50.692  3859  3905 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 10:41:50.721   873  1690 I ActivityManager: Start proc 3910:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-10 10:41:50.723   873  1690 I ActivityManager: Killing 3518:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 10:41:50.799  3910  3910 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 10:41:50.977   873  1740 I ActivityManager: Killing 3535:com.android.musicfx/u0a18 (adj 15): empty #17
,08-10 10:41:51.119   873  1675 I ActivityManager: Start proc 3924:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-10 10:41:51.198  3924  3924 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 10:41:51.252  3924  3924 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 10:41:51.324   873   884 I ActivityManager: Killing 2060:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 10:41:51.670   873  1388 D WifiService: setWifiEnabled: true pid=3668, uid=10000
08-10 10:41:51.670   873  1388 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 10:41:51.681   873  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-10 10:41:51.692  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:51.692  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:51.693  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:51.693  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:51.695  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:51.696  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:51.696  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:51.697  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:41:51.703   873  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-10 10:41:51.704   873  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-10 10:41:51.705   873  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 10:41:51.706   873  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 10:41:51.706   873  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 10:41:51.706   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 10:41:51.706   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 10:41:51.724   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-10 10:41:51.726   371   871 D CommandListener: Setting iface cfg
,08-10 10:41:51.726   873  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.50 rxSuccessRate=7.88 delta 1000 -> 1000
08-10 10:41:51.727   873  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
08-10 10:41:51.728   873  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 10:41:51.734   873  1308 D WifiNative-HAL: p2pGetDeviceAddress
08-10 10:41:51.735   873  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 10:41:51.759   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-10 10:41:51.759   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:41:51.765   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 10:41:51.832   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 10:41:51.835  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 10:41:52.251  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 10:41:52.293  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 10:41:52.294  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 10:41:52.301   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 10:41:52.318   873  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 10:41:52.319   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 10:41:52.319   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 10:41:52.354   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:41:52.375   371   871 D CommandListener: Setting iface cfg
,08-10 10:41:52.376   873  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,08-10 10:41:52.393   873  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-10 10:41:52.400   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 10:41:52.444   873  3959 D DhcpClient: Receive thread started
,08-10 10:41:52.527   873  1309 E native  : do suspend false
,08-10 10:41:52.548   873  1987 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 10:41:52.563   873  3959 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172676, domain null
,08-10 10:41:52.564   873  1987 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172676 seconds
,08-10 10:41:52.567   873  1987 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 10:41:52.580   873  3959 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 10:41:52.581   873  1987 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 10:41:52.586   371   871 D CommandListener: Setting iface cfg
,08-10 10:41:52.597   873  1987 D DhcpClient: Scheduling renewal in 86399s
,08-10 10:41:52.599   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 10:41:52.617   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 10:41:52.620   873  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 10:41:52.621   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 10:41:52.622   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 10:41:52.624   873  1311 D ConnectivityService: Adding iface wlan0 to network 101
08-10 10:41:52.631   873  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 10:41:52.679   873  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 10:41:52.680   873  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-10 10:41:52.681   873  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-10 10:41:52.681   873  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-10 10:41:52.683   873  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-10 10:41:52.691   873  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 10:41:52.696   873  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-10 10:41:52.696   873  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-10 10:41:52.696   873  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-10 10:41:52.696   873  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-10 10:41:52.696   873  1311 D ConnectivityService:    accepting network in place of null
08-10 10:41:52.697   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 10:41:52.697   873  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 10:41:52.709   873  3958 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146079, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:41:52.732   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:52.775   873  3957 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:815::200e
,08-10 10:41:52.794   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:52.801   873  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-10 10:41:52.802   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:52.809   873  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-10 10:41:52.810   873   890 D Tethering: MasterInitialState.processMessage what=3
08-10 10:41:52.816  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:52.816  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:41:52.816  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:52.816  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:52.821  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:41:52.822  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:41:52.822  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:52.822  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:41:52.833  1958  1958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 10:41:52.835  1958  1958 D SystemUpdateService: onCreate
,08-10 10:41:52.839  1958  1958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 10:41:52.841  1958  3970 I SystemUpdateService: active receiver: enabled
,08-10 10:41:52.844  1958  3970 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 10:41:52.851   873  3957 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 08:41:52 GMT], X-Android-Received-Millis=[1470818512850], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470818512819]}
,08-10 10:41:52.854   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 10:41:52.854   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-10 10:41:52.854   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 10:41:52.856   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 10:41:52.860  1958  3970 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 10:41:52.860  1958  3970 I SystemUpdateService: now status is 0 (complete)
08-10 10:41:52.860  1958  3970 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 10:41:52.861  1958  3970 I SystemUpdateService: file has been verified
08-10 10:41:52.862  1958  3970 I SystemUpdateService: OTA package size = 12249756
,08-10 10:41:52.864  1958  1958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 10:41:52.868  1958  2337 I iu.UploadsManager: num queued entries: 0
08-10 10:41:52.869  1958  2337 I iu.UploadsManager: num updated entries: 0
,08-10 10:41:52.871  1958  3970 I SystemUpdateService: showing system update notification
,08-10 10:41:52.872  1958  3976 I MDM     : [214] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 10:41:52.872  1958  3976 W BaseAppContext: Using Auth Proxy for data requests.
08-10 10:41:52.874  1958  2337 I iu.SyncManager: NEXT; no task
,08-10 10:41:52.877  1958  3976 V GoogleAuthProtoRequest: [214] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 10:41:52.879  1958  1958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-10 10:41:52.881  1958  1958 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 10:41:52.885  3832  3832 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:52.892  3832  3832 D SprintDMHelper: simOperator: 
,08-10 10:41:52.892  3832  3832 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 10:41:52.905  1958  1958 D SystemUpdateService: onDestroy
,08-10 10:41:52.925  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 10:41:52.925  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-10 10:41:52.925  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:41:52.926  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:41:52.945  1958  3976 E MDM     : [214] SitrepService.a: Error sending sitrep.
,08-10 10:41:53.027  3789  3978 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 10:41:53.801   873  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-10 10:41:54.580   873  1747 I ActivityManager: Killing 3484:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 10:41:54.678   873   883 D WifiService: setWifiEnabled: false pid=3668, uid=10000
08-10 10:41:54.678   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 10:41:54.710  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 10:41:54.720   873  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 10:41:54.721   873  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-10 10:41:54.721   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 10:41:54.722   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:41:54.739   873  1987 D DhcpClient: Clearing IP address
,08-10 10:41:54.739   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-10 10:41:54.745  1547  3982 V NativeCrypto: Read error: ssl=0x9ae7f000: I/O error during system call, Connection timed out
,08-10 10:41:54.748   371   871 D CommandListener: Setting iface cfg
,08-10 10:41:54.752  1547  3982 V NativeCrypto: SSL shutdown failed: ssl=0x9ae7f000: I/O error during system call, Broken pipe
08-10 10:41:54.755   873  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
08-10 10:41:54.755   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 10:41:54.755   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-10 10:41:54.756   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 10:41:54.762   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-10 10:41:54.767   394   394 E Parcel  : Reading a NULL string not supported here.
08-10 10:41:54.769   873  3959 D DhcpClient: Receive thread stopped
,08-10 10:41:54.777   873  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-10 10:41:54.787   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 10:41:54.793  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:54.793  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:54.793  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:54.793  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:54.794   873  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 10:41:54.795  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:54.795  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:54.795  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 10:41:54.795  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:41:54.797  1964  2094 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 10:41:54.814   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:54.843   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:41:54.843   873  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-10 10:41:54.843   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:54.847  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:54.848   873   890 D Tethering: MasterInitialState.processMessage what=3
08-10 10:41:54.848  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:54.853  1958  1958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-10 10:41:54.857  1958  1958 D SystemUpdateService: onCreate
08-10 10:41:54.859  1958  1958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 10:41:54.864  1958  3993 I SystemUpdateService: active receiver: enabled
,08-10 10:41:54.867  1958  3993 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 10:41:54.871  1958  1958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 10:41:54.870  1958  3993 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-10 10:41:54.875  1958  3993 I SystemUpdateService: now status is 0 (complete)
08-10 10:41:54.875  1958  3993 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 10:41:54.875  1958  3993 I SystemUpdateService: file has been verified
08-10 10:41:54.876  1958  3993 I SystemUpdateService: OTA package size = 12249756
,08-10 10:41:54.879  1958  2337 I iu.UploadsManager: num queued entries: 0
08-10 10:41:54.879  1958  2337 I iu.UploadsManager: num updated entries: 0
,08-10 10:41:54.883  1958  2337 I iu.SyncManager: NEXT; no task
,08-10 10:41:54.883  1958  3993 I SystemUpdateService: showing system update notification
,08-10 10:41:54.885  1958  1958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 10:41:54.886  1958  1958 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 10:41:54.888  3832  3832 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:41:54.892  3832  3832 D SprintDMHelper: simOperator: 
08-10 10:41:54.892  3832  3832 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 10:41:54.912  3789  3998 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 10:41:54.935  1958  1958 D SystemUpdateService: onDestroy
,08-10 10:41:54.936   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-10 10:41:56.989   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-10 10:41:57.002  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-10 10:41:57.014   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 10:41:57.014   873   893 I Adreno  : Build Date                       : 10/20/15
08-10 10:41:57.014   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 10:41:57.014   873   893 I Adreno  : Local Branch                     : M14
08-10 10:41:57.014   873   893 I Adreno  : Remote Branch                    : 
08-10 10:41:57.014   873   893 I Adreno  : Remote Branch                    : 
08-10 10:41:57.014   873   893 I Adreno  : Reconstruct Branch               : 
,08-10 10:41:57.043   280  1300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (183 us)
,08-10 10:41:57.720  3668  3668 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-10 10:41:57.720  3668  3668 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 10:41:57.763  3668  3668 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ffc99d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@96f5d9a, 16908290=android.view.AbsSavedState$1@96f5d9a}, android:focusedViewId=100}]}]
,08-10 10:41:57.764  3668  3668 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-10 10:41:57.764  3668  3668 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 10:41:57.764  3668  3668 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-10 10:41:57.764   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 10:41:57.777   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 10:41:57.781   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-10 10:41:57.784   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-10 10:41:57.784   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-10 10:41:57.794   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30f717f:true
,08-10 10:41:57.795  3818  3818 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 10:41:57.797  3818  3818 I bt_bluedroid: init
08-10 10:41:57.797  3818  4004 I BluetoothAdapterState: Entering OffState
,08-10 10:41:57.799  3818  4005 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 10:41:57.800  3818  4005 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 10:41:57.800  3818  4005 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 10:41:57.800  3818  4005 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 10:41:57.801  3818  3818 I bt_bluedroid: get_profile_interface socket
,08-10 10:41:57.802  3818  3818 I bt_bluedroid: get_profile_interface sdp
,08-10 10:41:57.803  3818  4008 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 10:41:57.804  3818  3828 I bt_bluedroid: config_hci_snoop_log
,08-10 10:41:57.804  3818  4008 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 10:41:57.805   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 10:41:57.808  3818  4004 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 10:41:57.808  3818  4004 D BluetoothAdapterProperties: Setting state to 14
08-10 10:41:57.808  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 10:41:57.809  3818  4004 D BluetoothBondStateMachine: make
,08-10 10:41:57.810  3818  4009 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 10:41:57.812  3818  4004 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:41:57.813  3818  3818 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 10:41:57.815  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:57.815  3818  3818 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 10:41:57.816  3818  3818 D BtGatt.GattService: Received start request. Starting profile...,
08-10 10:41:57.816  3818  3818 D BtGatt.GattService: start()
08-10 10:41:57.816  3818  3818 I bt_bluedroid: get_profile_interface gatt
,08-10 10:41:57.817  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
08-10 10:41:57.817  3818  3818 D BtGatt.AdvertiseManager: advertise manager created
,08-10 10:41:57.820  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:57.821  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:41:57.821  3818  3818 V BluetoothAdapterState: isBleTurningOn()=true
08-10 10:41:57.821  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:57.821  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4,
,08-10 10:41:57.821  3818  4004 I bt_bluedroid: enable
08-10 10:41:57.821  3818  4005 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 10:41:57.821  3818  4005 I bt_hci  : start_up
,08-10 10:41:57.827  3818  4005 I bt_vendor: alloc value 0xb3939189
,08-10 10:41:57.827  3818  4005 I bt_vendor: init
08-10 10:41:57.827  3818  4005 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 10:41:57.827  3818  4005 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 10:41:57.935  3818  4005 D bt_hci  : start_up starting async portion
08-10 10:41:57.935  3818  4012 I bt_hci  : event_finish_startup
,08-10 10:41:57.936  3818  4012 I bt_hci_h4: hal_open
08-10 10:41:57.936  3818  4012 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 10:41:57.944  3818  4012 I bt_userial_vendor: device fd = 51 open
,08-10 10:41:57.977  3818  4012 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 10:41:58.009  3818  4012 D bt_hwcfg: Chipset BCM4354A2
,08-10 10:41:58.009  3818  4012 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 10:41:58.010  3818  4012 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 10:41:58.028   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 10:41:58.031   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-10 10:41:58.037   873  1333 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
,08-10 10:41:58.040   873   893 I DreamManagerService: Entering dreamland.
,08-10 10:41:58.041   873   893 I PowerManagerService: Dozing...
,08-10 10:41:58.041   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 10:41:58.092   375  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-10 10:41:58.092   375  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 10:41:58.095   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 10:41:58.098   873  1309 E native  : do suspend false
,08-10 10:41:58.119  1700  4015 D NfcService: Discovery configuration equal, not updating.
,08-10 10:41:58.137   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 10:41:58.141   873  1309 E native  : do suspend true
,08-10 10:41:58.231   375  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 10:41:58.232   375  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 10:41:58.666  3818  4012 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 10:41:58.668  3818  4012 D bt_hwcfg: Settlement delay -- 100 ms
,08-10 10:41:58.668  3818  4012 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 10:41:58.785  3818  4012 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 10:41:58.786  3818  4012 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 10:41:58.815  3818  4012 I bt_hwcfg: vendor lib fwcfg completed
,08-10 10:41:58.815  3818  4012 I bt_vendor: firmware callback
08-10 10:41:58.815  3818  4012 I bt_hci  : firmware_config_callback
,08-10 10:41:58.828  3818  4019 I bt_btu  : btu_task pending for preload complete event
,08-10 10:41:58.828  3818  4019 I bt_btu_task: Bluetooth chip preload is complete
08-10 10:41:58.828  3818  4019 I bt_btu  : btu_task received preload complete event
,08-10 10:41:58.840  3818  4019 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 10:41:58.840  3818  4019 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 10:41:58.841  3818  4019 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 10:41:58.841  3818  4019 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 10:41:58.841  3818  4019 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 10:41:58.842  3818  4019 I         : BTE_InitTraceLevels -- TRC_A2D
,08-10 10:41:58.842  3818  4019 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 10:41:58.842  3818  4019 I         : BTE_InitTraceLevels -- TRC_BTM
,08-10 10:41:58.842  3818  4019 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 10:41:58.843  3818  4019 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 10:41:58.843  3818  4019 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 10:41:58.843  3818  4019 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 10:41:58.843  3818  4019 I         : BTE_InitTraceLevels -- TRC_SMP
,08-10 10:41:58.844  3818  4019 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 10:41:58.844  3818  4019 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 10:41:58.977  3818  4019 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-10 10:41:58.978  3818  4019 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-10 10:41:58.999  3818  4008 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 10:41:59.000  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 10:41:59.001  3818  4008 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 10:41:59.008  3818  4008 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 10:41:59.014  3818  4008 D BluetoothAdapterProperties: Scan Mode:20
08-10 10:41:59.015  3818  4008 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 10:41:59.016  3818  4008 D bt_hci  : do_postload posting postload work item
,08-10 10:41:59.017  3818  4012 I bt_hci  : event_postload
08-10 10:41:59.017  3818  4012 I bt_vendor: sco_config_cb
08-10 10:41:59.017  3818  4012 I bt_hci  : sco_config_callback postload finished.
08-10 10:41:59.018  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:59.020  3818  4008 D bt_bte_conf: Device ID record 1 : primary
08-10 10:41:59.021  3818  4008 D bt_bte_conf:   vendorId            = 000f
08-10 10:41:59.021  3818  4008 D bt_bte_conf:   vendorIdSource      = 0001
08-10 10:41:59.021  3818  4008 D bt_bte_conf:   product             = 1200
08-10 10:41:59.021  3818  4008 D bt_bte_conf:   version             = 1436
08-10 10:41:59.021  3818  4008 D bt_bte_conf:   clientExecutableURL = 
08-10 10:41:59.022  3818  4008 D bt_bte_conf:   serviceDescription  = 
08-10 10:41:59.022  3818  4008 D bt_bte_conf:   documentationURL    = 
,08-10 10:41:59.022  3818  4008 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 10:41:59.022  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:59.023  3818  4005 D bt_stack_manager: event_start_up_stack finished
08-10 10:41:59.024  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 10:41:59.025  3818  4004 D BluetoothAdapterProperties: Setting state to 15
08-10 10:41:59.025  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
,08-10 10:41:59.027  3818  4004 I BluetoothAdapterState: Entering BleOnState
,08-10 10:41:59.032  3818  4004 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 10:41:59.032  3818  4004 D BluetoothAdapterProperties: Setting state to 11
08-10 10:41:59.032  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 10:41:59.036  3818  4012 I bt_vendor: low_power_mode_cb
,08-10 10:41:59.037  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.037  3818  3818 D HeadsetService: Received start request. Starting profile...
,08-10 10:41:59.041  3818  3818 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 10:41:59.042  3818  3818 D HeadsetStateMachine: make
,08-10 10:41:59.047  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:59.049  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:59.053  3818  4004 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:41:59.060  3818  3818 D HeadsetStateMachine: max_hf_connections = 1
,08-10 10:41:59.060  3818  3818 I bt_bluedroid: get_profile_interface handsfree
08-10 10:41:59.060  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 10:41:59.060  3818  4008 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 10:41:59.065  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.066  3818  3818 D A2dpService: Received start request. Starting profile...
08-10 10:41:59.067  3818  3818 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 10:41:59.068  3818  3818 I bt_bluedroid: get_profile_interface avrcp
,08-10 10:41:59.075  3818  3818 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 10:41:59.075  3818  3818 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 10:41:59.075  3818  3818 D A2dpStateMachine: make
08-10 10:41:59.077  3818  3818 I bt_bluedroid: get_profile_interface a2dp
,08-10 10:41:59.077  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 10:41:59.081  3818  4028 D A2dpStateMachine: Enter Disconnected: -2
,08-10 10:41:59.082  3818  3818 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 10:41:59.084  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.086  3739  3739 D BluetoothInputDevice: Proxy object connected
,08-10 10:41:59.087  3818  3818 D HidService: Received start request. Starting profile...
08-10 10:41:59.087  3739  3739 D HidProfile: Bluetooth service connected
,08-10 10:41:59.087  3818  3818 I bt_bluedroid: get_profile_interface hidhost
08-10 10:41:59.087  3818  4008 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-10 10:41:59.088  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-10 10:41:59.088  3818  3818 D HidService: setHidService(): set to: null
,08-10 10:41:59.090  3818  3818 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 10:41:59.091  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.093  3818  3818 D HealthService: Received start request. Starting profile...
,08-10 10:41:59.095  3818  3818 I bt_bluedroid: get_profile_interface health
,08-10 10:41:59.096  3818  3818 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 10:41:59.098  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.100  3739  3739 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 10:41:59.100  3739  3739 D PanProfile: Bluetooth service connected
08-10 10:41:59.101  3818  3818 D PanService: Received start request. Starting profile...
,08-10 10:41:59.101  3818  3818 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 10:41:59.101  3818  3818 I bt_bluedroid: get_profile_interface pan
,08-10 10:41:59.103  3818  4008 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 10:41:59.109  3818  3818 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:41:59.111  3739  3739 D BluetoothMap: Proxy object connected
,08-10 10:41:59.111  3739  3739 D MapProfile: Bluetooth service connected
,08-10 10:41:59.111  3739  3739 D BluetoothMap: getConnectedDevices()
,08-10 10:41:59.111  3818  3818 D BluetoothMapService: Received start request. Starting profile...
08-10 10:41:59.112  3818  3818 D BluetoothMapService: start()
,08-10 10:41:59.113  3739  3739 D BluetoothMap: Bluetooth is Not enabled
,08-10 10:41:59.115  3818  3818 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 10:41:59.116  3818  3818 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 10:41:59.116  3818  3818 D BluetoothMapAppObserver: createReceiver()
,08-10 10:41:59.117  3818  3818 D BluetoothMapAppObserver: initObservers()
,08-10 10:41:59.117  3818  3818 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 10:41:59.126  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:41:59.128  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:59.128  3818  3818 V BluetoothAdapterState: isTurningOn()=true
08-10 10:41:59.128  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:41:59.128  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:59.128  3818  4025 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isTurningOn()=true
08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isTurningOn()=true
08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:59.130  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isTurningOn()=true
08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isTurningOff()=false
08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isTurningOn()=true
08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:41:59.131  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:41:59.132  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:41:59.132  3818  3818 V BluetoothAdapterState: isTurningOn()=true
,08-10 10:41:59.132  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:41:59.132  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:41:59.132  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 10:41:59.132  3818  4004 D BluetoothAdapterProperties: ScanMode =  20
08-10 10:41:59.132  3818  4004 D BluetoothAdapterProperties: State =  11
,08-10 10:41:59.133  3818  4004 D BluetoothAdapterProperties: Setting state to 12
08-10 10:41:59.133  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-10 10:41:59.135  3818  4008 D BluetoothAdapterProperties: Scan Mode:21
08-10 10:41:59.136  3818  4008 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 10:41:59.136  3818  4004 I BluetoothAdapterState: Entering OnState
08-10 10:41:59.137  3739  3751 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:59.138  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:59.140  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:41:59.141  1351  1824 D BluetoothMap: onBluetoothStateChange: up=true
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:41:59.144  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 10:41:59.145  3818  3818 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 10:41:59.145  3818  3818 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 10:41:59.147  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:41:59.150  1351  1351 D BluetoothMap: Proxy object connected
08-10 10:41:59.150  1351  1351 D MapProfile: Bluetooth service connected
08-10 10:41:59.150  1351  1351 D BluetoothMap: getConnectedDevices()
08-10 10:41:59.150  1351  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 10:41:59.150  3818  3818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:41:59.153   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:41:59.153   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 10:41:59.154  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 10:41:59.154  3818  3818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:41:59.155  3818  3818 D ObexServerSockets: Succeed to create listening sockets 
,08-10 10:41:59.155  3818  3818 D ObexServerSockets0: startAccept()
08-10 10:41:59.155  3818  3818 D ObexServerSockets0: prepareForNewConnect()
,08-10 10:41:59.157  1351  1351 D BluetoothInputDevice: Proxy object connected
,08-10 10:41:59.157  1351  1351 D HidProfile: Bluetooth service connected
08-10 10:41:59.157  3739  3752 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 10:41:59.157  3818  3818 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 10:41:59.158  3818  3818 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 10:41:59.158   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 10:41:59.158  3818  4033 D ObexServerSockets0: Accepting socket connection...
,08-10 10:41:59.158  1351  1824 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 10:41:59.159   873   873 D BluetoothA2dp: Proxy object connected
,08-10 10:41:59.160  3818  4034 D ObexServerSockets0: Accepting socket connection...
,08-10 10:41:59.160  1351  1351 D BluetoothA2dp: Proxy object connected
08-10 10:41:59.161  1717  1731 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 10:41:59.162  3739  3751 D BluetoothMap: onBluetoothStateChange: up=true
08-10 10:41:59.162  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:41:59.163  1351  1367 D BluetoothPan: onBluetoothStateChange on: true
,08-10 10:41:59.166  3739  3752 D BluetoothPan: onBluetoothStateChange on: true
,08-10 10:41:59.166  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 10:41:59.166  1351  1351 D PanProfile: Bluetooth service connected
,08-10 10:41:59.166   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 10:41:59.167   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 10:41:59.169  3818  3818 D BluetoothMapService: onReceive
,08-10 10:41:59.169  3818  3818 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 10:41:59.169  3818  3818 D BluetoothMapService: STATE_ON
,08-10 10:41:59.170  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:41:59.172  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:41:59.172  3739  3739 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-10 10:41:59.177  3739  3739 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 10:41:59.182  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 10:41:59.186  3739  3739 D BluetoothA2dp: Proxy object connected
,08-10 10:41:59.189  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:41:59.198  1351  1351 D BluetoothPbap: Proxy object connected
,08-10 10:41:59.198  1351  1351 D PbapServerProfile: Bluetooth service connected
08-10 10:41:59.198  3818  3818 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 10:41:59.198  3818  3818 D ObexServerSockets0: prepareForNewConnect()
,08-10 10:41:59.202  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:41:59.203  3739  3739 D BluetoothPbap: Proxy object connected
,08-10 10:41:59.203  3739  3739 D PbapServerProfile: Bluetooth service connected
,08-10 10:41:59.212  3818  4040 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:41:59.237  3818  4044 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:41:59.239  3818  4044 I BtOppRfcommListener: Accept thread started.
,08-10 10:41:59.255   873   873 D BluetoothHeadset: Proxy object connected
08-10 10:41:59.256  1351  1363 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.256  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-10 10:41:59.256   873   873 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.256  1717  1857 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.257   873   873 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.259   873   890 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.262  1717  1729 D BluetoothHeadset: Proxy object connected
08-10 10:41:59.264  1351  1824 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.264  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-10 10:41:59.266   873   890 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.280  3739  3751 D BluetoothHeadset: Proxy object connected
,08-10 10:41:59.283  3739  3739 D HeadsetProfile: Bluetooth service connected
,08-10 10:42:00.703   873  1311 D ConnectivityService: handlePromptUnvalidated 101
,08-10 10:42:00.773  3818  4004 D BluetoothAdapterState: Current state: ON, message: 23
08-10 10:42:00.773  3818  4004 D BluetoothAdapterProperties: Setting state to 13
,08-10 10:42:00.774  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 10:42:00.777  3818  4004 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 10:42:00.780  3818  4004 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:42:00.786  3818  3818 D BluetoothMapService: onReceive
,08-10 10:42:00.786  3818  3818 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 10:42:00.787  3818  3818 D BluetoothMapService: STATE_TURNING_OFF
08-10 10:42:00.787  3818  3818 D BluetoothMapService: MAP Service closeService in
08-10 10:42:00.787  3818  3818 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 10:42:00.787  3818  3818 D ObexServerSockets0: shutdown(block = true)
08-10 10:42:00.788  3818  4033 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-10 10:42:00.790  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:00.790  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:00.793  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-10 10:42:00.793  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:42:00.794  3818  3818 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 10:42:00.795  3818  4008 D BluetoothAdapterProperties: Scan Mode:20
,08-10 10:42:00.795  3818  4034 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-10 10:42:00.795  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 10:42:00.796  3818  4021 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-10 10:42:00.797  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:00.797  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:00.797  3818  3818 D ObexServerSockets0: shutdown called from another thread - interrupt().,
,08-10 10:42:00.799  3668  3668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 10:42:00.799  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:42:00.800  3818  3818 D HeadsetService: Received stop request...Stopping profile...
,08-10 10:42:00.801  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:00.802  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:00.803  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 10:42:00.812   873   873 D BluetoothHeadset: Proxy object disconnected
,08-10 10:42:00.812  1351  1367 D BluetoothHeadset: Proxy object disconnected
08-10 10:42:00.813  3818  3818 I BtOppRfcommListener: stopping Accept Thread
,08-10 10:42:00.813  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-10 10:42:00.813  3818  4044 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-10 10:42:00.813  3739  3751 D BluetoothHeadset: Proxy object disconnected
08-10 10:42:00.813   873   873 D BluetoothHeadset: Proxy object disconnected
08-10 10:42:00.813  1717  1731 D BluetoothHeadset: Proxy object disconnected
,08-10 10:42:00.814   873   873 D BluetoothHeadset: Proxy object disconnected
08-10 10:42:00.814  3818  4044 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 10:42:00.815  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:42:00.816  3818  3818 D A2dpService: Received stop request...Stopping profile...
,08-10 10:42:00.816  3818  4028 D A2dpStateMachine: Exit Disconnected: -1
08-10 10:42:00.818  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-10 10:42:00.818   873   873 D BluetoothA2dp: Proxy object disconnected
,08-10 10:42:00.818  3739  3739 D HeadsetProfile: Bluetooth service disconnected
08-10 10:42:00.818  3739  3739 D BluetoothA2dp: Proxy object disconnected
,08-10 10:42:00.820  3818  3818 D HidService: Received stop request...Stopping profile...
,08-10 10:42:00.820  3818  3818 D HidService: Stopping Bluetooth HidService
08-10 10:42:00.820  1351  1351 D BluetoothInputDevice: Proxy object disconnected
,08-10 10:42:00.821  1351  1351 D HidProfile: Bluetooth service disconnected
,08-10 10:42:00.822  3818  3818 D HealthService: Received stop request...Stopping profile...
08-10 10:42:00.822  3739  3739 D BluetoothInputDevice: Proxy object disconnected
,08-10 10:42:00.822  3739  3739 D HidProfile: Bluetooth service disconnected
,08-10 10:42:00.823  3818  3818 D PanService: Received stop request...Stopping profile...
08-10 10:42:00.823  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 10:42:00.823  1351  1351 D PanProfile: Bluetooth service disconnected
08-10 10:42:00.823  3739  3739 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 10:42:00.823  3739  3739 D PanProfile: Bluetooth service disconnected
08-10 10:42:00.824  3818  3818 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 10:42:00.824  3818  3818 D BluetoothMapService: stop()
08-10 10:42:00.824  3818  3818 D BluetoothMapAppObserver: deinitObservers()
08-10 10:42:00.824  3818  3818 D BluetoothMapAppObserver: removeReceiver()
,08-10 10:42:00.825  1351  1351 D BluetoothMap: Proxy object disconnected
,08-10 10:42:00.825  1351  1351 D MapProfile: Bluetooth service disconnected
08-10 10:42:00.825  3739  3739 D BluetoothMap: Proxy object disconnected
08-10 10:42:00.825  3739  3739 D MapProfile: Bluetooth service disconnected
,08-10 10:42:00.828  3818  3818 V BluetoothAdapterState: isTurningOff()=true
,08-10 10:42:00.828  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:42:00.828  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 10:42:00.828  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:00.828  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:00.831  3818  3818 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-10 10:42:00.831  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 10:42:00.831  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:42:00.831  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:42:00.831  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 10:42:00.832  3818  4008 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-10 10:42:00.832  3818  3818 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 10:42:00.836  3818  3818 V BluetoothAdapterState: isTurningOff()=true
,08-10 10:42:00.836  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:42:00.836  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:42:00.836  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:00.838  3818  3818 V BluetoothAdapterState: isTurningOff()=true
,08-10 10:42:00.838  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:42:00.838  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:00.838  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:00.838  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 10:42:00.838  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:42:00.838  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 10:42:00.839  3818  4019 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 10:42:00.839  3818  3818 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 10:42:00.839  3818  4019 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 10:42:00.839  3818  3818 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 10:42:00.839  3818  4019 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 10:42:00.839  3818  4019 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 10:42:00.839  3818  3818 V BluetoothAdapterState: isTurningOff()=true
08-10 10:42:00.839  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:42:00.839  3818  4008 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 10:42:00.839  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:00.839  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:00.840  3818  3818 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 10:42:00.840  3818  4008 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 10:42:00.840  3818  3818 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 10:42:00.840  3818  3818 V BluetoothAdapterState: isTurningOff()=true
08-10 10:42:00.840  3818  3818 V BluetoothAdapterState: isTurningOn()=false
08-10 10:42:00.840  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:00.840  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:00.841  3818  3818 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 10:42:00.841  3818  3818 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 10:42:00.841  3818  3818 D BluetoothMapService: MAP Service closeService in
08-10 10:42:00.841  3818  3818 V BluetoothAdapterState: isTurningOff()=true
08-10 10:42:00.842  3818  3818 V BluetoothAdapterState: isTurningOn()=false
,08-10 10:42:00.842  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:42:00.842  3818  3818 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:00.842  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 10:42:00.842  3818  4004 D BluetoothAdapterProperties: Setting state to 15
,08-10 10:42:00.842  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-10 10:42:00.843  3818  4004 I BluetoothAdapterState: Entering BleOnState
08-10 10:42:00.843  3818  3818 D BluetoothMapService: cleanup()
08-10 10:42:00.843  3818  3818 D BluetoothMapService: MAP Service closeService in
08-10 10:42:00.843  3739  3752 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:42:00.843  3739  3751 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 10:42:00.844  1351  1367 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 10:42:00.844  1351  1351 D BluetoothPbap: Proxy object disconnected
08-10 10:42:00.844  1351  1351 D PbapServerProfile: Bluetooth service disconnected
08-10 10:42:00.844  1351  1824 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 10:42:00.845   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:42:00.845   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 10:42:00.846  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 10:42:00.848  3739  3752 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 10:42:00.851   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:42:00.851  1351  1367 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 10:42:00.851  1717  1857 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 10:42:00.852  3739  3751 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 10:42:00.852  3739  3752 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 10:42:00.853  1351  1824 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 10:42:00.853  1351  1363 D BluetoothPan: onBluetoothStateChange on: false
08-10 10:42:00.853  3739  3751 D BluetoothPan: onBluetoothStateChange on: false
08-10 10:42:00.854   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 10:42:00.854  3818  4004 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 10:42:00.854  3818  4004 D BluetoothAdapterProperties: Setting state to 16
08-10 10:42:00.854  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 10:42:00.855  3818  4004 D BluetoothAdapterProperties: onBleDisable
08-10 10:42:00.858  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:00.859  3818  4004 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:42:00.859  3818  4005 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 10:42:00.860  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 10:42:00.860  3818  4019 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 10:42:00.860  3818  4019 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 10:42:00.860  3818  4008 D BluetoothAdapterProperties: Scan Mode:20
08-10 10:42:00.860  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:00.862  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:00.863  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:00.865  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:42:00.871  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:42:01.067  3818  4008 I bt_hci  : shut_down
,08-10 10:42:01.079  3818  4012 I bt_vendor: low_power_mode_cb
,08-10 10:42:01.079  3818  4012 D bt_hwcfg: hw_epilog_process
,08-10 10:42:01.096  3818  4012 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 10:42:01.096  3818  4012 I bt_vendor: epilog_cb
,08-10 10:42:01.096  3818  4012 I bt_hci  : epilog_finished_callback
,08-10 10:42:01.104  3818  4008 I bt_hci_h4: hal_close
,08-10 10:42:01.105  3818  4008 I bt_userial_vendor: device fd = 51 close
,08-10 10:42:01.226  3818  4005 D bt_stack_manager: event_shut_down_stack finished.
,08-10 10:42:01.227  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 10:42:01.233  3818  3818 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 10:42:01.232  3818  4004 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 10:42:01.235  3818  3818 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 10:42:01.235  3818  3818 D BtGatt.GattService: stop()
,08-10 10:42:01.236  3818  3818 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 10:42:01.243  3818  3818 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:42:01.243  3818  3818 V BluetoothAdapterState: isTurningOn()=false
,08-10 10:42:01.244  3818  3818 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:01.244  3818  3818 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 10:42:01.245  3818  4004 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 10:42:01.245  3818  4004 D BluetoothAdapterProperties: Setting state to 10
08-10 10:42:01.246  3818  4004 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 10:42:01.247  3818  4004 I BluetoothAdapterState: Entering OffState
,08-10 10:42:01.249   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 10:42:01.273  3818  3818 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 10:42:01.273  3818  3818 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 10:42:01.274  3818  4005 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-10 10:42:01.277  3818  4005 D bt_stack_manager: event_clean_up_stack finished.
,08-10 10:42:01.280  3818  3818 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 10:42:01.284  3818  3818 I art     : System.exit called, status: 0
,08-10 10:42:01.284  3818  3818 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 10:42:01.353   873  1740 I ActivityManager: Process com.android.bluetooth (pid 3818) has died
,08-10 10:42:02.494  1964  2491 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 10:42:03.770  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 10:42:03.770  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:06.777  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 10:42:06.778  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20bf6cb added. We now have 6 listener(s)
08-10 10:42:06.778  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 10:42:06.782  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:06.783  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c1ea8 added. We now have 7 listener(s)
,08-10 10:42:06.783  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:06.784  3668  3719 I System.out: IsBluetoothEnabled
,08-10 10:42:06.793  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:06.843   873   890 I ActivityManager: Start proc 4056:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 10:42:06.970  4056  4056 D AdapterServiceConfig: Adding HeadsetService
,08-10 10:42:06.971  4056  4056 D AdapterServiceConfig: Adding A2dpService
,08-10 10:42:06.971  4056  4056 D AdapterServiceConfig: Adding HidService
,08-10 10:42:06.971  4056  4056 D AdapterServiceConfig: Adding HealthService
,08-10 10:42:06.971  4056  4056 D AdapterServiceConfig: Adding PanService
,08-10 10:42:06.971  4056  4056 D AdapterServiceConfig: Adding GattService
,08-10 10:42:06.972  4056  4056 D AdapterServiceConfig: Adding BluetoothMapService
08-10 10:42:06.990   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7fb8d37:true
,08-10 10:42:06.991  4056  4056 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 10:42:06.997  4056  4056 I bt_bluedroid: init
,08-10 10:42:06.998  4056  4068 I BluetoothAdapterState: Entering OffState
,08-10 10:42:07.003  4056  4069 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 10:42:07.003  4056  4069 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 10:42:07.004  4056  4069 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 10:42:07.004  4056  4069 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 10:42:07.006  4056  4056 I bt_bluedroid: get_profile_interface socket
,08-10 10:42:07.008  4056  4056 I bt_bluedroid: get_profile_interface sdp,
,08-10 10:42:07.013  4056  4066 I bt_bluedroid: config_hci_snoop_log
,08-10 10:42:07.016   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 10:42:07.018  4056  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 10:42:07.022  4056  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 10:42:07.023  4056  4068 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 10:42:07.024  4056  4068 D BluetoothAdapterProperties: Setting state to 14
,08-10 10:42:07.024  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 10:42:07.028  4056  4068 D BluetoothBondStateMachine: make
,08-10 10:42:07.033  4056  4073 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 10:42:07.043  4056  4068 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:42:07.043  4056  4056 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 10:42:07.051  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:07.053  4056  4056 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 10:42:07.055  4056  4056 D BtGatt.GattService: Received start request. Starting profile...
,08-10 10:42:07.055  4056  4056 D BtGatt.GattService: start()
08-10 10:42:07.056  4056  4056 I bt_bluedroid: get_profile_interface gatt
,08-10 10:42:07.058  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:07.059  4056  4056 D BtGatt.AdvertiseManager: advertise manager created
,08-10 10:42:07.075  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-10 10:42:07.075  4056  4056 V BluetoothAdapterState: isTurningOn()=false
,08-10 10:42:07.076  4056  4056 V BluetoothAdapterState: isBleTurningOn()=true
,08-10 10:42:07.076  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:07.077  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 10:42:07.078  4056  4068 I bt_bluedroid: enable
,08-10 10:42:07.078  4056  4069 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 10:42:07.079  4056  4069 I bt_hci  : start_up
,08-10 10:42:07.098  4056  4069 I bt_vendor: alloc value 0xb39b0189
,08-10 10:42:07.099  4056  4069 I bt_vendor: init
08-10 10:42:07.099  4056  4069 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 10:42:07.099  4056  4069 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 10:42:07.208  4056  4069 D bt_hci  : start_up starting async portion
,08-10 10:42:07.209  4056  4076 I bt_hci  : event_finish_startup
08-10 10:42:07.209  4056  4076 I bt_hci_h4: hal_open
,08-10 10:42:07.209  4056  4076 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 10:42:07.218  4056  4076 I bt_userial_vendor: device fd = 51 open
,08-10 10:42:07.250  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 10:42:07.282  4056  4076 D bt_hwcfg: Chipset BCM4354A2
,08-10 10:42:07.282  4056  4076 D bt_hwcfg: Target name = [BCM4354A2]
08-10 10:42:07.284  4056  4076 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 10:42:07.936  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 10:42:07.937  4056  4076 D bt_hwcfg: Settlement delay -- 100 ms
08-10 10:42:07.938  4056  4076 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 10:42:08.054  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 10:42:08.055  4056  4076 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 10:42:08.085  4056  4076 I bt_hwcfg: vendor lib fwcfg completed
,08-10 10:42:08.085  4056  4076 I bt_vendor: firmware callback
,08-10 10:42:08.085  4056  4076 I bt_hci  : firmware_config_callback
,08-10 10:42:08.097  4056  4078 I bt_btu  : btu_task pending for preload complete event
,08-10 10:42:08.097  4056  4078 I bt_btu_task: Bluetooth chip preload is complete
08-10 10:42:08.097  4056  4078 I bt_btu  : btu_task received preload complete event
,08-10 10:42:08.110  4056  4078 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 10:42:08.110  4056  4078 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 10:42:08.110  4056  4078 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 10:42:08.111  4056  4078 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 10:42:08.111  4056  4078 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 10:42:08.111  4056  4078 I         : BTE_InitTraceLevels -- TRC_A2D
,08-10 10:42:08.111  4056  4078 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 10:42:08.113  4056  4078 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 10:42:08.114  4056  4078 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 10:42:08.115  4056  4078 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 10:42:08.116  4056  4078 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 10:42:08.118  4056  4078 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 10:42:08.119  4056  4078 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 10:42:08.119  4056  4078 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 10:42:08.119  4056  4078 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 10:42:08.253  4056  4078 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-10 10:42:08.254  4056  4078 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-10 10:42:08.271  4056  4072 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 10:42:08.276  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 10:42:08.277  4056  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 10:42:08.280  4056  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 10:42:08.282  4056  4072 D BluetoothAdapterProperties: Scan Mode:20
,08-10 10:42:08.282  4056  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 10:42:08.283  4056  4072 D bt_hci  : do_postload posting postload work item
,08-10 10:42:08.283  4056  4076 I bt_hci  : event_postload
08-10 10:42:08.283  4056  4076 I bt_vendor: sco_config_cb
,08-10 10:42:08.283  4056  4076 I bt_hci  : sco_config_callback postload finished.
,08-10 10:42:08.287  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:08.288  4056  4072 D bt_bte_conf: Device ID record 1 : primary
08-10 10:42:08.289  4056  4072 D bt_bte_conf:   vendorId            = 000f
08-10 10:42:08.290  4056  4072 D bt_bte_conf:   vendorIdSource      = 0001
08-10 10:42:08.292  4056  4076 I bt_vendor: low_power_mode_cb
,08-10 10:42:08.290  4056  4072 D bt_bte_conf:   product             = 1200
08-10 10:42:08.293  4056  4072 D bt_bte_conf:   version             = 1436
08-10 10:42:08.293  4056  4072 D bt_bte_conf:   clientExecutableURL = 
08-10 10:42:08.293  4056  4072 D bt_bte_conf:   serviceDescription  = 
08-10 10:42:08.293  4056  4072 D bt_bte_conf:   documentationURL    = 
08-10 10:42:08.293  4056  4072 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 10:42:08.294  4056  4069 D bt_stack_manager: event_start_up_stack finished
,08-10 10:42:08.294  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-10 10:42:08.295  4056  4068 D BluetoothAdapterProperties: Setting state to 15
08-10 10:42:08.295  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 10:42:08.296  4056  4068 I BluetoothAdapterState: Entering BleOnState
,08-10 10:42:08.299  4056  4068 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-10 10:42:08.300  4056  4068 D BluetoothAdapterProperties: Setting state to 11
,08-10 10:42:08.300  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 10:42:08.306  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:08.314  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:08.315  4056  4056 D HeadsetService: Received start request. Starting profile...
,08-10 10:42:08.318  4056  4056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 10:42:08.318  4056  4056 D HeadsetStateMachine: make
,08-10 10:42:08.322  4056  4068 I BluetoothAdapterState: Entering PendingCommandState
,08-10 10:42:08.324  4056  4056 D HeadsetStateMachine: max_hf_connections = 1
,08-10 10:42:08.324  4056  4056 I bt_bluedroid: get_profile_interface handsfree
,08-10 10:42:08.325  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 10:42:08.326  4056  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 10:42:08.330  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:42:08.331  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
08-10 10:42:08.331  4056  4056 D A2dpService: Received start request. Starting profile...
,08-10 10:42:08.332  4056  4056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 10:42:08.332  4056  4056 I bt_bluedroid: get_profile_interface avrcp
,08-10 10:42:08.337  4056  4056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 10:42:08.338  4056  4056 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 10:42:08.338  4056  4056 D A2dpStateMachine: make
,08-10 10:42:08.339  4056  4056 I bt_bluedroid: get_profile_interface a2dp
,08-10 10:42:08.340  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048,
,08-10 10:42:08.340  4056  4086 D A2dpStateMachine: Enter Disconnected: -2
08-10 10:42:08.341  4056  4056 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 10:42:08.342  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
08-10 10:42:08.343  4056  4056 D HidService: Received start request. Starting profile...
08-10 10:42:08.343  4056  4056 I bt_bluedroid: get_profile_interface hidhost
,08-10 10:42:08.343  4056  4056 D HidService: setHidService(): set to: null
08-10 10:42:08.343  4056  4072 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-10 10:42:08.343  4056  4056 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 10:42:08.343  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 10:42:08.344  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:08.344  4056  4056 D HealthService: Received start request. Starting profile...
,08-10 10:42:08.346  4056  4056 I bt_bluedroid: get_profile_interface health
,08-10 10:42:08.347  4056  4056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 10:42:08.348  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
08-10 10:42:08.348  4056  4056 D PanService: Received start request. Starting profile...
08-10 10:42:08.348  4056  4056 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 10:42:08.348  4056  4056 I bt_bluedroid: get_profile_interface pan
08-10 10:42:08.349  4056  4072 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 10:42:08.351  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:08.351  4056  4056 D BluetoothMapService: Received start request. Starting profile...
,08-10 10:42:08.352  4056  4056 D BluetoothMapService: start()
,08-10 10:42:08.353  4056  4056 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 10:42:08.354  4056  4056 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 10:42:08.354  4056  4056 D BluetoothMapAppObserver: createReceiver()
,08-10 10:42:08.356  4056  4056 D BluetoothMapAppObserver: initObservers()
,08-10 10:42:08.356  4056  4056 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 10:42:08.363  4056  4056 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:42:08.364  4056  4056 V BluetoothAdapterState: isTurningOn()=true,
,08-10 10:42:08.364  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:08.364  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:08.366  4056  4084 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-10 10:42:08.369  4056  4056 V BluetoothAdapterState: isTurningOn()=true
,08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-10 10:42:08.370  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:08.371  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:08.371  4056  4056 V BluetoothAdapterState: isTurningOff()=false
,08-10 10:42:08.371  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-10 10:42:08.371  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-10 10:42:08.371  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-10 10:42:08.372  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-10 10:42:08.372  4056  4068 D BluetoothAdapterProperties: ScanMode =  20
08-10 10:42:08.372  4056  4068 D BluetoothAdapterProperties: State =  11
08-10 10:42:08.373  4056  4072 D BluetoothAdapterProperties: Scan Mode:21
08-10 10:42:08.374  4056  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 10:42:08.374  4056  4068 D BluetoothAdapterProperties: Setting state to 12
08-10 10:42:08.374  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 10:42:08.375  3739  3752 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:42:08.375  4056  4068 I BluetoothAdapterState: Entering OnState
08-10 10:42:08.375  3739  3751 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:08.376  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:08.377  1351  1367 D BluetoothMap: onBluetoothStateChange: up=true
08-10 10:42:08.379  1351  1824 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 10:42:08.379  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 10:42:08.380   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:42:08.380   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 10:42:08.380  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 10:42:08.380  1351  1351 D BluetoothMap: Proxy object connected
,08-10 10:42:08.381  1351  1351 D MapProfile: Bluetooth service connected
08-10 10:42:08.381  1351  1351 D BluetoothMap: getConnectedDevices()
08-10 10:42:08.381   873   873 D BluetoothA2dp: Proxy object connected
08-10 10:42:08.382  3739  3752 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 10:42:08.382  1351  1351 D BluetoothA2dp: Proxy object connected
,08-10 10:42:08.383  4056  4056 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 10:42:08.384  4056  4056 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 10:42:08.385   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:42:08.385  1351  1824 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 10:42:08.386  1717  1729 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 10:42:08.386  4056  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 10:42:08.387  3739  3751 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 10:42:08.389  3739  3752 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 10:42:08.389  3739  3739 D BluetoothMap: Proxy object connected
,08-10 10:42:08.389  3739  3739 D MapProfile: Bluetooth service connected
,08-10 10:42:08.389  4056  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 10:42:08.390  4056  4056 D ObexServerSockets: Succeed to create listening sockets 
08-10 10:42:08.391  4056  4056 D ObexServerSockets0: startAccept()
08-10 10:42:08.391  1351  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 10:42:08.391  4056  4056 D ObexServerSockets0: prepareForNewConnect()
08-10 10:42:08.391  1351  1363 D BluetoothPan: onBluetoothStateChange on: true
08-10 10:42:08.391  3739  3739 D BluetoothMap: getConnectedDevices()
,08-10 10:42:08.393  4056  4056 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 10:42:08.393  3739  3751 D BluetoothPan: onBluetoothStateChange on: true
08-10 10:42:08.393  4056  4056 D BluetoothSdpJni: SDP Create record success - handle: 0
08-10 10:42:08.394  1351  1351 D BluetoothInputDevice: Proxy object connected
08-10 10:42:08.394  1351  1351 D HidProfile: Bluetooth service connected
08-10 10:42:08.395  4056  4094 D ObexServerSockets0: Accepting socket connection...
08-10 10:42:08.395  4056  4093 D ObexServerSockets0: Accepting socket connection...
08-10 10:42:08.396   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 10:42:08.396  3739  3739 D BluetoothA2dp: Proxy object connected
08-10 10:42:08.397   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 10:42:08.398  4056  4056 D BluetoothMapService: onReceive
08-10 10:42:08.398  4056  4056 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 10:42:08.398  4056  4056 D BluetoothMapService: STATE_ON
08-10 10:42:08.398  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 10:42:08.398  1351  1351 D PanProfile: Bluetooth service connected
08-10 10:42:08.399  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:08.400  3739  3739 D BluetoothInputDevice: Proxy object connected
08-10 10:42:08.400  3739  3739 D HidProfile: Bluetooth service connected
08-10 10:42:08.402  3739  3739 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 10:42:08.402  3739  3739 D PanProfile: Bluetooth service connected
,08-10 10:42:08.408  3739  3739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 10:42:08.414  1547  1547 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 10:42:08.414  3739  3739 D DockEventReceiver: finishStartingService: stopping service
,08-10 10:42:08.423  3739  3739 D BluetoothPbap: Proxy object connected
,08-10 10:42:08.423  4056  4056 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 10:42:08.423  4056  4056 D ObexServerSockets0: prepareForNewConnect()
08-10 10:42:08.423  3739  3739 D PbapServerProfile: Bluetooth service connected
,08-10 10:42:08.423  1351  1351 D BluetoothPbap: Proxy object connected
,08-10 10:42:08.423  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-10 10:42:08.433  4056  4100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:42:08.450  4056  4104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 10:42:08.452  4056  4104 I BtOppRfcommListener: Accept thread started.
,08-10 10:42:08.477   873   873 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.477  1351  1363 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.478  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-10 10:42:08.478  3739  4092 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.479   873   873 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.479  3739  3739 D HeadsetProfile: Bluetooth service connected
08-10 10:42:08.479  1717  1731 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.480   873   873 D BluetoothHeadset: Proxy object connected
08-10 10:42:08.480   873   890 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.485   873   890 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.487  1717  1857 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.491  1351  1824 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.492  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-10 10:42:08.496   873   890 D BluetoothHeadset: Proxy object connected
,08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:08.813  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:08.820  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:42:08.823  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 10:42:08.824  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb06dc1 added. We now have 8 listener(s)
08-10 10:42:08.824  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 10:42:08.832   873  1791 D WifiService: setWifiEnabled: false pid=3668, uid=10000
,08-10 10:42:08.833   873  1791 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 10:42:08.843  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:08.844   873   883 D WifiService: setWifiEnabled: true pid=3668, uid=10000
08-10 10:42:08.844   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 10:42:08.859   873  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:08.873  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:08.880  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:42:08.910   873  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-10 10:42:08.911   873  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 10:42:08.912   873  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 10:42:08.913   873  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 10:42:08.913   873  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 10:42:08.913   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK,
08-10 10:42:08.913   873  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 10:42:08.927   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 10:42:08.929   371   871 D CommandListener: Setting iface cfg
,08-10 10:42:08.929   873  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.10 rxSuccessRate=0.15 delta 1000 -> 1000
,08-10 10:42:08.930   873  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)',
,08-10 10:42:08.930   873  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 10:42:08.933   873  1308 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 10:42:08.933   873  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 10:42:08.936   873  1309 E native  : do suspend true
,08-10 10:42:08.966   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-10 10:42:08.967   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:42:08.977   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 10:42:09.051   873  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 10:42:09.865  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 10:42:09.873  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 10:42:09.886  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-10 10:42:09.889  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-10 10:42:09.895  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ffc99d Bundle[{}]
,08-10 10:42:09.895  3668  3719 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 10:42:09.896  3668  3719 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-10 10:42:09.897  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-10 10:42:09.898  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 10:42:09.899  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-10 10:42:09.900  3668  3719 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 10:42:09.904  3668  3719 I System.out: Running OutgoingSocketThread
,08-10 10:42:09.908  3668  4110 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
08-10 10:42:09.910  3668  4110 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42978
,08-10 10:42:09.910  3668  4110 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-10 10:42:09.911  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 10:42:09.944   873  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 10:42:09.947  1467  1467 E wpa_supplicant: PNO: In assoc process
,08-10 10:42:09.948   873  1309 E WifiStateMachine:  Fail to set up pno, want true now false
,08-10 10:42:10.382  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 10:42:10.421  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 10:42:10.422  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 10:42:10.426   873  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 10:42:10.436   873  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 10:42:10.436   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 10:42:10.437   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:42:10.455   873  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 10:42:10.466   371   871 D CommandListener: Setting iface cfg
,08-10 10:42:10.467   873  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,08-10 10:42:10.474   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 10:42:10.512   873  4113 D DhcpClient: Receive thread started
,08-10 10:42:10.599   873  1309 E native  : do suspend false
,08-10 10:42:10.622   873  1987 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 10:42:10.644   873  4113 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-10 10:42:10.646   873  1987 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-10 10:42:10.649   873  1987 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 10:42:10.664   873  4113 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 10:42:10.665   873  1987 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 10:42:10.671   371   871 D CommandListener: Setting iface cfg
,08-10 10:42:10.682   873  1987 D DhcpClient: Scheduling renewal in 86399s
,08-10 10:42:10.685   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 10:42:10.689   873  1309 E native  : do suspend true
,08-10 10:42:10.720   873  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 10:42:10.724   873  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 10:42:10.726   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 10:42:10.729   873  1311 D ConnectivityService: Adding iface wlan0 to network 102
,08-10 10:42:10.732   873  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 10:42:10.819   873  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 10:42:10.820   873  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-10 10:42:10.821   873  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-10 10:42:10.822   873  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-10 10:42:10.823   873  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-10 10:42:10.832   873  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 10:42:10.846   873  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-10 10:42:10.846   873  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-10 10:42:10.846   873  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-10 10:42:10.846   873  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-10 10:42:10.846   873  1311 D ConnectivityService:    accepting network in place of null
,08-10 10:42:10.847   873  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 10:42:10.849   873  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 10:42:10.860   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164230, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:42:10.885   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 10:42:10.906  3668  3719 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-10 10:42:10.906  3668  3719 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-10 10:42:10.909  3668  3719 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-10 10:42:10.910  3668  3719 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-10 10:42:10.910  3668  3719 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-10 10:42:10.912  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:42:10.912  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5b966 added. We now have 2 listener(s)
08-10 10:42:10.914  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:10.915  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:10.915  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:10.915  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:10.915  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6134a7 added. We now have 9 listener(s)
08-10 10:42:10.915  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:10.916  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 10:42:10.923  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:10.931  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:42:10.936   873  4111 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:80e::200e
,08-10 10:42:10.936  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:10.937  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 10:42:10.937  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:42:10.937  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81524fd added. We now have 3 listener(s)
08-10 10:42:10.939  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:10.939  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 10:42:10.939  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:10.939  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:10.939  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af405f2 added. We now have 10 listener(s)
08-10 10:42:10.940  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 10:42:10.940  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:42:10.940  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:10.940  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:42:10.940  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:42:10.940  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:10.940  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:42:10.940  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:10.940  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d5b966 removed from the list
08-10 10:42:10.940  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:10.941  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6134a7 removed from the list
,08-10 10:42:10.943  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:10.943  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:42:10.943  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:10.944  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:10.944  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:10.946  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:10.946  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:10.947  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:10.947  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6134a7 not in the list
08-10 10:42:10.947  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:10.947  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:10.949  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:10.950  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:10.950  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:10.950  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af405f2 removed from the list
08-10 10:42:10.950  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:10.950  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:10.950  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:10.950  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:10.950  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81524fd removed from the list
08-10 10:42:10.951  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 10:42:10.951  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee27443 added. We now have 2 listener(s)
08-10 10:42:10.952  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:10.953  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:10.953  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:10.953  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:10.954  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:10.954  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4aa1ac0 added. We now have 9 listener(s)
08-10 10:42:10.954  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:10.955   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-10 10:42:10.955  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 10:42:10.960   873  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-10 10:42:10.960   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 10:42:10.964   873  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-10 10:42:10.965   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:10.984  3668  3668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:42:10.988  3668  3668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:42:10.989  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:10.995  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:42:10.998  1958  1958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-10 10:42:10.999  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:10.999  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:42:11.000  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:42:11.000  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f388f3e added. We now have 3 listener(s)
08-10 10:42:11.001  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.003  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.006  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.006  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.006  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:11.006  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.006  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eae119f added. We now have 10 listener(s)
08-10 10:42:11.006  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.007  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:42:11.007  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 10:42:11.007  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 10:42:11.007  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:42:11.007  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 10:42:11.009   873  4111 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 08:42:10 GMT], X-Android-Received-Millis=[1470818531008], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470818530982]}
08-10 10:42:11.011   873  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 10:42:11.011   873  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-10 10:42:11.011   873  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 10:42:11.012   873  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 10:42:11.013  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 10:42:11.013  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 10:42:11.018  1958  1958 D SystemUpdateService: onCreate
,08-10 10:42:11.021  1958  1958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 10:42:11.021  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 10:42:11.021  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 10:42:11.021  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 10:42:11.026  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 10:42:11.026  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 10:42:11.026  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 10:42:11.028  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:42:11.031  4056  4091 D BtGatt.GattService: registerClient() - UUID=bea13685-ad14-462c-986c-0042fb160a99
,08-10 10:42:11.032  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=bea13685-ad14-462c-986c-0042fb160a99, clientIf=5
,08-10 10:42:11.033  3668  3679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 10:42:11.034  4056  4067 D BtGatt.GattService: start scan with filters
,08-10 10:42:11.040  4056  4075 D BtGatt.ScanManager: handling starting scan
,08-10 10:42:11.040  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 10:42:11.041  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 10:42:11.042  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 10:42:11.042  4056  4075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cea5074
,08-10 10:42:11.042  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 10:42:11.040  1958  4123 I SystemUpdateService: active receiver: enabled
,08-10 10:42:11.047  4056  4072 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 10:42:11.047  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.047  4056  4075 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 10:42:11.047  1958  4123 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 10:42:11.052  1958  4123 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 10:42:11.052  1958  4123 I SystemUpdateService: now status is 0 (complete)
,08-10 10:42:11.052  1958  4123 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 10:42:11.052  1958  4123 I SystemUpdateService: file has been verified
08-10 10:42:11.053  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.053  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 10:42:11.053  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.054  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 10:42:11.057  3668  3719 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 10:42:11.057  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:11.058  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 10:42:11.058  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.058  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 10:42:11.058  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 10:42:11.058  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 10:42:11.058  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 10:42:11.058  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:42:11.058  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:42:11.058  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 10:42:11.058  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:42:11.059  4056  4091 D BtGatt.GattService: stopScan() - queue size =1
08-10 10:42:11.059  4056  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 10:42:11.060  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 10:42:11.060  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-10 10:42:11.060  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 10:42:11.060  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:42:11.060  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 10:42:11.060  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:42:11.061  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:42:11.061  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 10:42:11.061  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 10:42:11.061  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:42:11.062  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:42:11.062  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:42:11.062  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 10:42:11.064  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:42:11.052  1958  4123 I SystemUpdateService: OTA package size = 12249756
,08-10 10:42:11.064  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:11.064  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:42:11.064  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:11.064  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.064  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:42:11.064  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:11.064  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee27443 removed from the list
,08-10 10:42:11.064  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.064  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4aa1ac0 removed from the list
08-10 10:42:11.064  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:42:11.065  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:11.065  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.065  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.066  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 10:42:11.066  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.066  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:11.066  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.066  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.066  4056  4075 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 10:42:11.066  4056  4075 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 10:42:11.066  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4aa1ac0 not in the list
08-10 10:42:11.066  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.067  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.068  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.068  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 10:42:11.068  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.068  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eae119f removed from the list
08-10 10:42:11.068  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:11.068  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.068  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:11.069  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 10:42:11.069  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f388f3e removed from the list
08-10 10:42:11.069  1958  4123 I SystemUpdateService: showing system update notification
08-10 10:42:11.070  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 10:42:11.070  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66c28bb added. We now have 2 listener(s)
08-10 10:42:11.072  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.072  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.072  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 10:42:11.072  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.072  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1881d8 added. We now have 9 listener(s)
,08-10 10:42:11.072  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.073  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 10:42:11.073  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:42:11.076  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:42:11.078  4056  4072 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 10:42:11.078  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:11.080  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:42:11.081  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:11.082  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 10:42:11.082  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 10:42:11.082  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b54816 added. We now have 3 listener(s)
08-10 10:42:11.084  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.084  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.084  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:11.084  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.084  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2a9597 added. We now have 10 listener(s)
08-10 10:42:11.084  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.084  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:42:11.085  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:42:11.085  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 10:42:11.085  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 10:42:11.085  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:42:11.085  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 10:42:11.086  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 10:42:11.086  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.086  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:11.089  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 10:42:11.088  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 10:42:11.089  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 10:42:11.091  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 10:42:11.091  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.091  4056  4075 D BtGatt.ScanManager: stopping BLe Batch
,08-10 10:42:11.093  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 10:42:11.094  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 10:42:11.094  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 10:42:11.097  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 10:42:11.097  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.097  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 10:42:11.097  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 10:42:11.097  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 10:42:11.097  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 10:42:11.098  3668  3719 D BluetoothAdapter: STATE_ON
,08-10 10:42:11.100  4056  4067 D BtGatt.GattService: registerClient() - UUID=340d863a-4c90-49d1-a110-47e670531b01
08-10 10:42:11.101  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=340d863a-4c90-49d1-a110-47e670531b01, clientIf=5
08-10 10:42:11.101  3668  3679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 10:42:11.101  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 10:42:11.101  4056  4096 D BtGatt.GattService: start scan with filters
08-10 10:42:11.101  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.105  4056  4075 D BtGatt.ScanManager: handling starting scan
,08-10 10:42:11.105  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 10:42:11.105  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 10:42:11.105  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 10:42:11.105  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 10:42:11.108  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.108  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.108  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 10:42:11.110  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-10 10:42:11.110  4056  4072 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 10:42:11.110  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-10 10:42:11.110  4056  4075 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 10:42:11.112  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:42:11.112  3668  3719 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-10 10:42:11.112  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:42:11.112  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-10 10:42:11.112  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:42:11.113  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:11.113  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.113  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 10:42:11.113  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 10:42:11.113  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66c28bb removed from the list
08-10 10:42:11.113  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.113  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1881d8 removed from the list
08-10 10:42:11.113  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:42:11.113  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:42:11.114  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.114  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-10 10:42:11.114  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.114  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:42:11.114  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 10:42:11.114  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.114  4056  4075 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 10:42:11.114  4056  4075 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 10:42:11.115  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1881d8 not in the list
,08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 10:42:11.115  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 10:42:11.115  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:42:11.115  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 10:42:11.116  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:42:11.116  4056  4096 D BtGatt.GattService: stopScan() - queue size =1
08-10 10:42:11.117  4056  4091 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 10:42:11.117  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 10:42:11.117  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 10:42:11.117  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 10:42:11.117  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:42:11.117  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 10:42:11.118  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:42:11.118  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:42:11.118  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-10 10:42:11.118  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 10:42:11.118  3617  4126 I BooksSync: Starting books sync for 61035162, extras: ade
08-10 10:42:11.118  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.120  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:42:11.120  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:42:11.120  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:42:11.120  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.120  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 10:42:11.120  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.120  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2a9597 removed from the list
08-10 10:42:11.120  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:42:11.120  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.121  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.121  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:11.121  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b54816 removed from the list
08-10 10:42:11.121  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:42:11.121  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8f433 added. We now have 2 listener(s)
08-10 10:42:11.123  4056  4072 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 10:42:11.123  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.123  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.123  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 10:42:11.123  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:11.123  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.123  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d9b3f0 added. We now have 9 listener(s)
08-10 10:42:11.123  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.124  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 10:42:11.126  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:42:11.127  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 10:42:11.127  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:11.131  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 10:42:11.133  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 10:42:11.133  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.133  4056  4075 D BtGatt.ScanManager: stopping BLe Batch
08-10 10:42:11.134  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:11.134  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 10:42:11.134  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 10:42:11.134  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54543ee added. We now have 3 listener(s)
08-10 10:42:11.136  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.136  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.136  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:11.136  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.136  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144a08f added. We now have 10 listener(s)
08-10 10:42:11.136  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.136  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 10:42:11.136  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 10:42:11.136  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 10:42:11.136  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 10:42:11.136  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 10:42:11.138  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.138  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 10:42:11.138  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.138  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 10:42:11.139  3668  3719 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 10:42:11.139  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 10:42:11.139  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.142  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 10:42:11.142  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 10:42:11.142  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 10:42:11.143  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 10:42:11.143  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.145  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 10:42:11.145  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 10:42:11.145  3668  3719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 10:42:11.145  1958  1958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-10 10:42:11.145  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:42:11.147  4056  4096 D BtGatt.GattService: registerClient() - UUID=880cdf33-cb90-4a5c-95e6-31043c0dd4ec
,08-10 10:42:11.147  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=880cdf33-cb90-4a5c-95e6-31043c0dd4ec, clientIf=5
08-10 10:42:11.147  3668  3679 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 10:42:11.148  4056  4091 D BtGatt.GattService: start scan with filters
08-10 10:42:11.151  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 10:42:11.151  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 10:42:11.151  4056  4075 D BtGatt.ScanManager: handling starting scan
08-10 10:42:11.151  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 10:42:11.151  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 10:42:11.153  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.153  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 10:42:11.153  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 10:42:11.154  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-10 10:42:11.157  4056  4072 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 10:42:11.157  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 10:42:11.158  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.158  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 10:42:11.158  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:42:11.158  4056  4075 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 10:42:11.158  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:42:11.158  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.158  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 10:42:11.159  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:11.159  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8f433 removed from the list
08-10 10:42:11.159  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.159  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d9b3f0 removed from the list
08-10 10:42:11.159  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
08-10 10:42:11.159  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:42:11.162  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.162  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-10 10:42:11.162  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.162  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.163  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d9b3f0 not in the list
08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 10:42:11.163  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 10:42:11.163  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 10:42:11.163  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 10:42:11.164  3668  3719 D BluetoothAdapter: STATE_ON
08-10 10:42:11.164  4056  4066 D BtGatt.GattService: stopScan() - queue size =1
,08-10 10:42:11.165  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 10:42:11.165  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.165  4056  4075 D BtGatt.ScanManager: Starting BLE batch scan
08-10 10:42:11.165  4056  4075 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 10:42:11.165  4056  4091 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 10:42:11.165  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 10:42:11.167  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 10:42:11.167  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 10:42:11.167  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 10:42:11.167  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 10:42:11.168  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:42:11.168  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 10:42:11.168  3668  3719 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 10:42:11.168  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 10:42:11.168  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:11.169  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.170  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:11.170  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.170  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 10:42:11.170  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144a08f removed from the list
08-10 10:42:11.170  3668  3668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 10:42:11.170  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 10:42:11.170  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.170  3668  3668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 10:42:11.170  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.170  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:11.170  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54543ee removed from the list
,08-10 10:42:11.171  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 10:42:11.171  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf4b6ab added. We now have 2 listener(s)
08-10 10:42:11.172  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 10:42:11.172  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.172  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 10:42:11.172  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 10:42:11.172  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71c1108 added. We now have 9 listener(s)
,08-10 10:42:11.173  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.173  4056  4072 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 10:42:11.173  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.173  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 10:42:11.175  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 10:42:11.177  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 10:42:11.177  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 10:42:11.177  1958  2337 I iu.UploadsManager: num queued entries: 0
,08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 10:42:11.178  3668  3719 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 10:42:11.180  1958  1958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-10 10:42:11.180  3668  3719 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 10:42:11.180  3668  3719 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 10:42:11.180  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 10:42:11.180  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ade2c6 added. We now have 3 listener(s)
08-10 10:42:11.181  1958  1958 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-10 10:42:11.182  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 10:42:11.182  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.182  4056  4075 D BtGatt.ScanManager: stopping BLe Batch
08-10 10:42:11.182  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.182  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 10:42:11.183  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 10:42:11.183  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 10:42:11.183  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 10:42:11.183  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b461287 added. We now have 10 listener(s)
,08-10 10:42:11.183  3668  3719 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 10:42:11.184  3832  3832 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-10 10:42:11.184  3668  3668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 10:42:11.184  3668  3719 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 10:42:11.184  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:11.185  3668  3719 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 10:42:11.185  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:11.185  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.185  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 10:42:11.185  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 10:42:11.185  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf4b6ab removed from the list
,08-10 10:42:11.185  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.185  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71c1108 removed from the list
,08-10 10:42:11.185  3668  3719 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 10:42:11.185  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.186  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.186  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.187  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 10:42:11.187  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:11.187  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.187  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 10:42:11.187  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.187  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 10:42:11.187  3668  3719 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71c1108 not in the list
08-10 10:42:11.187  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 10:42:11.187  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 10:42:11.188  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 10:42:11.188  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 10:42:11.188  3668  3719 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 10:42:11.188  3668  3719 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b461287 removed from the list
08-10 10:42:11.188  3668  3719 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 10:42:11.188  3668  3719 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 10:42:11.188  3668  3719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 10:42:11.188  3668  3719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 10:42:11.188  3668  3719 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ade2c6 removed from the list
,08-10 10:42:11.189  3832  3832 D SprintDMHelper: simOperator: 
,08-10 10:42:11.189  3832  3832 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 10:42:11.189  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 10:42:11.190  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 10:42:11.190  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 10:42:11.190  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 10:42:11.190  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 10:42:11.190  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:11.192  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 10:42:11.192  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 10:42:11.196  3668  4132 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
08-10 10:42:11.196  3668  4132 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-10 10:42:11.196  3668  4132 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 10:42:11.197  3668  4133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
08-10 10:42:11.198  3668  4133 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
08-10 10:42:11.198  3668  4133 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 10:42:11.199  3668  3719 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-10 10:42:11.199  3668  3719 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-10 10:42:11.199  3668  3719 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-10 10:42:11.199  3668  3719 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-10 10:42:11.199  3668  3719 D com.test.thalitest.ThaliTestRunner: Total duration: 22811 ms
,08-10 10:42:11.201  3668  3719 I jxcore-log: Total number of executed tests:  80
08-10 10:42:11.201  3668  3719 I jxcore-log: 
08-10 10:42:11.201  3668  3719 I jxcore-log: Number of passed tests:  80
08-10 10:42:11.201  3668  3719 I jxcore-log: 
08-10 10:42:11.201  3668  3719 I jxcore-log: Number of failed tests:  0
08-10 10:42:11.201  3668  3719 I jxcore-log: 
08-10 10:42:11.201  1958  4128 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-10 10:42:11.201  1958  4128 W BaseAppContext: Using Auth Proxy for data requests.
08-10 10:42:11.201  3668  3719 I jxcore-log: Number of ignored tests:  0
08-10 10:42:11.201  3668  3719 I jxcore-log: 
08-10 10:42:11.202  3668  3719 I jxcore-log: Total duration:  22811
08-10 10:42:11.202  3668  3719 I jxcore-log: 
,08-10 10:42:11.204  3668  3719 I jxcore-log: Unit Test app is loaded
08-10 10:42:11.204  3668  3719 I jxcore-log: 
,08-10 10:42:11.206  1958  4128 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
08-10 10:42:11.213  3668  3668 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 10:42:11.216  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.216  3668  3719 I jxcore-log: 
08-10 10:42:11.217  1958  2337 I iu.UploadsManager: num updated entries: 0
08-10 10:42:11.218  1958  2337 I iu.SyncManager: NEXT; no task
08-10 10:42:11.220  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.220  3668  3719 I jxcore-log: 
08-10 10:42:11.221  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.221  3668  3719 I jxcore-log: 
08-10 10:42:11.223  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.223  3668  3719 I jxcore-log: 
08-10 10:42:11.224  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.224  3668  3719 I jxcore-log: 
,08-10 10:42:11.225  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.225  3668  3719 I jxcore-log: 
08-10 10:42:11.227  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.227  3668  3719 I jxcore-log: 
08-10 10:42:11.228  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.228  3668  3719 I jxcore-log: 
08-10 10:42:11.229  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.229  3668  3719 I jxcore-log: 
08-10 10:42:11.230  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.230  3668  3719 I jxcore-log: 
08-10 10:42:11.231  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.231  3668  3719 I jxcore-log: 
08-10 10:42:11.232  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 10:42:11.232  3668  3719 I jxcore-log: 
08-10 10:42:11.232  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.232  3668  3719 I jxcore-log: 
08-10 10:42:11.233  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.233  3668  3719 I jxcore-log: 
08-10 10:42:11.234  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.234  3668  3719 I jxcore-log: 
08-10 10:42:11.234  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.234  3668  3719 I jxcore-log: 
08-10 10:42:11.235  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.235  3668  3719 I jxcore-log: 
08-10 10:42:11.236  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.236  3668  3719 I jxcore-log: 
08-10 10:42:11.237  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.237  3668  3719 I jxcore-log: 
08-10 10:42:11.237  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.237  3668  3719 I jxcore-log: 
,08-10 10:42:11.238  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.238  3668  3719 I jxcore-log: 
08-10 10:42:11.238  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.238  3668  3719 I jxcore-log: 
08-10 10:42:11.239  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.239  3668  3719 I jxcore-log: 
08-10 10:42:11.240  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 10:42:11.240  3668  3719 I jxcore-log: 
08-10 10:42:11.240  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.240  3668  3719 I jxcore-log: 
08-10 10:42:11.241  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 10:42:11.241  3668  3719 I jxcore-log: 
08-10 10:42:11.241  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.241  3668  3719 I jxcore-log: 
08-10 10:42:11.242  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.242  3668  3719 I jxcore-log: 
08-10 10:42:11.243  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.243  3668  3719 I jxcore-log: 
08-10 10:42:11.244  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.244  3668  3719 I jxcore-log: 
08-10 10:42:11.244  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.244  3668  3719 I jxcore-log: 
08-10 10:42:11.245  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 10:42:11.245  3668  3719 I jxcore-log: 
,08-10 10:42:11.248  3668  3719 I jxcore-log: My device name is: motorola-Nexus 6
08-10 10:42:11.248  3668  3719 I jxcore-log: 
,08-10 10:42:11.328  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:11.330  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:11.347  1547  4137 I VacuumService: Vacuum at: now=1470818531347 tag=VacuumService
,08-10 10:42:11.373  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:42:11.373  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 10:42:11.374  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.374  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.384  3424  4130 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:42:11.384  3424  4130 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:11.384  3424  4130 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	... 12 more
08-10 10:42:11.384  3424  4130 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at fal.a(PG:38)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:42:11.384  3424  4130 E HttpOperation: 	... 14 more
,08-10 10:42:11.408  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:42:11.408  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:42:11.409  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.409  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.459  3424  4130 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:42:11.459  3424  4130 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at hec.a(PG:42)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at hee.a(PG:102)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at czr.a(PG:65)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at kka.a(PG:108)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:11.459  3424  4130 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	... 15 more
08-10 10:42:11.459  3424  4130 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at fal.a(PG:38)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:42:11.459  3424  4130 E HttpOperation: 	... 17 more
,08-10 10:42:11.459  3424  4130 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:42:11.459  3424  4130 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	... 15 more
08-10 10:42:11.459  3424  4130 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:42:11.459  3424  4130 E ExperimentLoader: 	... 17 more
,08-10 10:42:11.488  3789  4134 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 10:42:11.538  1958  1958 D SystemUpdateService: onDestroy
,08-10 10:42:11.562  3668  3668 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 10:42:11.567  3617  4145 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:42:11.621  3668  3668 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 10:42:11.632   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 161041, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:42:11.637  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 10:42:11.637  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 10:42:11.637  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.637  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.653  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:42:11.653  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 10:42:11.654  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.654  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.670  3668  3668 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 10:42:11.689  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:42:11.689  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:42:11.689  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.689  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.704  3617  4145 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:42:11.704  3617  4126 E BooksSync: Soft error
08-10 10:42:11.704  3617  4126 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:42:11.704  3617  4126 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 10:42:11.704  3617  4126 E BooksSync: Sync error
08-10 10:42:11.704  3617  4126 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:42:11.704  3617  4126 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 10:42:11.706  3617  4126 I BooksSync: Finished books sync
,08-10 10:42:11.720   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159064, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:42:11.731  1547  4139 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-10 10:42:11.733  1547  4139 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 10:42:11.746  1958  4128 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-10 10:42:11.900  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:42:11.949  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 10:42:11.949  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 10:42:11.949  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:11.949  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:11.961   873  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-10 10:42:11.970  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 10:42:11.970  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 10:42:11.970  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 10:42:12.100  1547  4139 W Uploader:  no longer exists, so no auth token.
,08-10 10:42:12.684   873  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-10 10:42:12.863  1547  4139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-10 10:42:12.863  1547  4139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-10 10:42:12.863  1547  4139 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:12.863  1547  4139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:12.876  1547  4139 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 10:42:12.876  1547  4139 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 10:42:12.876  1547  4139 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 10:42:13.223  1547  4139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 10:42:13.223  1547  4139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 10:42:13.223  1547  4139 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:13.223  1547  4139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:13.235  1547  4139 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 10:42:13.235  1547  4139 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 10:42:13.235  1547  4139 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 10:42:13.654  1547  4139 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-10 10:42:13.654  1547  4139 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-10 10:42:13.654  1547  4139 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:13.655  1547  4139 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:13.672  1547  4139 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 10:42:13.672  1547  4139 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 10:42:13.672  1547  4139 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 10:42:13.721  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 10:42:13.721  3668  3719 I jxcore-log: 
,08-10 10:42:14.372  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 10:42:14.372  3668  3719 I jxcore-log: 
,08-10 10:42:14.397  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 10:42:14.397  3668  3719 I jxcore-log: 
,08-10 10:42:15.751  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 10:42:15.751  3668  3719 I jxcore-log: 
,08-10 10:42:15.979  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 10:42:15.979  3668  3719 I jxcore-log: 
,08-10 10:42:15.984  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 10:42:15.984  3668  3719 I jxcore-log: 
,08-10 10:42:16.002  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 10:42:16.002  3668  3719 I jxcore-log: 
,08-10 10:42:16.006  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 10:42:16.006  3668  3719 I jxcore-log: 
,08-10 10:42:16.684  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 10:42:16.684  3668  3719 I jxcore-log: 
,08-10 10:42:16.696  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 10:42:16.696  3668  3719 I jxcore-log: 
,08-10 10:42:16.706  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 10:42:16.706  3668  3719 I jxcore-log: 
,08-10 10:42:16.714  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 10:42:16.714  3668  3719 I jxcore-log: 
,08-10 10:42:16.763  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 10:42:16.763  3668  3719 I jxcore-log: 
,08-10 10:42:16.820  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 10:42:16.820  3668  3719 I jxcore-log: 
,08-10 10:42:16.828  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 10:42:16.828  3668  3719 I jxcore-log: 
,08-10 10:42:16.994  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 10:42:16.994  3668  3719 I jxcore-log: 
,08-10 10:42:17.022  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 10:42:17.022  3668  3719 I jxcore-log: 
,08-10 10:42:17.030  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 10:42:17.030  3668  3719 I jxcore-log: 
,08-10 10:42:17.039  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 10:42:17.039  3668  3719 I jxcore-log: 
,08-10 10:42:17.063  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 10:42:17.063  3668  3719 I jxcore-log: 
,08-10 10:42:17.149  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 10:42:17.149  3668  3719 I jxcore-log: 
,08-10 10:42:17.161  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 10:42:17.161  3668  3719 I jxcore-log: 
,08-10 10:42:17.188  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 10:42:17.188  3668  3719 I jxcore-log: 
,08-10 10:42:17.199  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 10:42:17.199  3668  3719 I jxcore-log: 
,08-10 10:42:17.218  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 10:42:17.218  3668  3719 I jxcore-log: 
,08-10 10:42:17.255  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 10:42:17.255  3668  3719 I jxcore-log: 
,08-10 10:42:17.261  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 10:42:17.261  3668  3719 I jxcore-log: 
,08-10 10:42:17.486  3668  3719 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 10:42:17.486  3668  3719 I jxcore-log: 
,08-10 10:42:17.496  3668  3719 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-10 10:42:17.497  3668  3719 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-10 10:42:17.497  3668  3719 I jxcore-log: 
,08-10 10:42:17.544  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 10:42:17.544  3668  3719 I jxcore-log: 
,08-10 10:42:17.544  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 10:42:17.544  3668  3719 I jxcore-log: 
08-10 10:42:17.545  3668  3719 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 10:42:17.545  3668  3719 I jxcore-log: 
,08-10 10:42:17.545  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 10:42:17.545  3668  3719 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-10 10:42:17.546  3668  3719 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 10:42:17.546  3668  3719 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-10 10:42:18.853   873  1311 D ConnectivityService: handlePromptUnvalidated 102
,08-10 10:42:32.167  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:32.177  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:32.178  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:32.206  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 10:42:32.206  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 10:42:32.206  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:42:32.207  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:32.234  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 10:42:32.235  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 10:42:32.235  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 10:42:38.467   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:42:43.328  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:43.329  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:42:43.362  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 10:42:43.362  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:42:43.362  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:43.362  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:43.388  3424  4157 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:42:43.388  3424  4157 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:43.388  3424  4157 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	... 12 more
08-10 10:42:43.388  3424  4157 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at fal.a(PG:38)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:42:43.388  3424  4157 E HttpOperation: 	... 14 more
,08-10 10:42:43.435  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:42:43.435  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:42:43.435  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:42:43.436  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:43.452  3424  4157 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:42:43.452  3424  4157 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at hec.a(PG:42)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at hee.a(PG:102)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at czr.a(PG:65)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at kka.a(PG:108)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:43.452  3424  4157 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	... 15 more
08-10 10:42:43.452  3424  4157 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at fal.a(PG:38)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:42:43.452  3424  4157 E HttpOperation: 	... 17 more
,08-10 10:42:43.452  3424  4157 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:42:43.452  3424  4157 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	... 15 more
08-10 10:42:43.452  3424  4157 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:42:43.452  3424  4157 E ExperimentLoader: 	... 17 more
,08-10 10:42:43.651   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 196340, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:42:43.697  3617  4159 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 10:42:43.710  3617  4160 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:42:43.733  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:42:43.734  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:42:43.734  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:42:43.734  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:43.772  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:42:43.772  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:42:43.772  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:42:43.772  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:42:43.786  3617  4160 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:42:43.787  3617  4159 E BooksSync: Soft error
08-10 10:42:43.787  3617  4159 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:42:43.787  3617  4159 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:42:43.787  3617  4159 E BooksSync: Sync error
08-10 10:42:43.787  3617  4159 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:42:43.787  3617  4159 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 10:42:43.787  3617  4159 I BooksSync: Finished books sync
,08-10 10:42:43.800   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 196476, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:42:44.681   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=198051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 10:42:57.043  1643  1759 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-10 10:42:57.043  1643  1759 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 10:42:57.096  1547  1547 I ConfigService: onCreate
,08-10 10:43:02.180  1547  1547 I ConfigService: onDestroy
,08-10 10:43:09.401   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:43:15.041   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 10:43:38.448  2914  4164 V KeepSync: Connecting to GoogleApiClient
,08-10 10:43:38.449   873  1791 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:43:38.530  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:43:38.538  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:43:38.586  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 10:43:38.586  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 10:43:38.586  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:43:38.586  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:43:38.621  1958  4165 V BaseAuthAsyncOperation: access token request failed
,08-10 10:43:38.623  2914  4164 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:43:38.698  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 10:43:38.698  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 10:43:38.698  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:43:38.698  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:43:38.721  2914  4164 E KeepSync: IOException
08-10 10:43:38.721  2914  4164 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:43:38.721  2914  4164 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:43:38.721  2914  4164 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:43:38.721  2914  4164 E KeepSync: 	... 10 more
,08-10 10:43:38.721  2914  4164 W KeepSync: Sync result 2
,08-10 10:43:38.732   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 251477, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:44:00.014   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:44:05.561   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 10:44:08.925  3617  4168 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 10:44:09.035  3617  4170 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:44:09.045  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:44:09.047  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:44:09.067  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:44:09.067  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:44:09.072  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:44:09.072  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.095  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:44:09.097  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:44:09.124  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:44:09.124  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:44:09.124  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:44:09.124  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.150  3617  4170 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:44:09.150  3617  4168 E BooksSync: Soft error
08-10 10:44:09.150  3617  4168 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:44:09.150  3617  4168 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 10:44:09.150  3617  4168 E BooksSync: Sync error
08-10 10:44:09.150  3617  4168 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:44:09.150  3617  4168 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:44:09.150  3617  4168 I BooksSync: Finished books sync
,08-10 10:44:09.160   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 259941, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:44:09.174  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:44:09.174  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:44:09.174  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:44:09.174  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.198  3424  4169 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:44:09.198  3424  4169 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:44:09.198  3424  4169 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	... 12 more
08-10 10:44:09.198  3424  4169 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at fal.a(PG:38)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:44:09.198  3424  4169 E HttpOperation: 	... 14 more
,08-10 10:44:09.250  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:44:09.250  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:44:09.250  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:44:09.250  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.264  3424  4169 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:44:09.264  3424  4169 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at hec.a(PG:42)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at hee.a(PG:102)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at czr.a(PG:65)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at kka.a(PG:108)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:44:09.264  3424  4169 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	... 15 more
08-10 10:44:09.264  3424  4169 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at fal.a(PG:38)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:44:09.264  3424  4169 E HttpOperation: 	... 17 more
,08-10 10:44:09.264  3424  4169 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:44:09.264  3424  4169 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	... 15 more
08-10 10:44:09.264  3424  4169 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:44:09.264  3424  4169 E ExperimentLoader: 	... 17 more
,08-10 10:44:09.393   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 259696, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:44:09.436  2914  4172 V KeepSync: Connecting to GoogleApiClient
08-10 10:44:09.436   873  1740 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:44:09.497  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 10:44:09.497  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 10:44:09.498  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:44:09.498  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.522  1958  4173 V BaseAuthAsyncOperation: access token request failed
08-10 10:44:09.523  2914  4172 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:44:09.583  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 10:44:09.583  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 10:44:09.583  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:44:09.583  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:44:09.599  2914  4172 E KeepSync: IOException
08-10 10:44:09.599  2914  4172 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:44:09.599  2914  4172 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:44:09.599  2914  4172 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:44:09.599  2914  4172 E KeepSync: 	... 10 more
,08-10 10:44:09.599  2914  4172 W KeepSync: Sync result 2
,08-10 10:44:09.607   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 282760, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:44:30.254   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:44:35.894   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=309263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 10:45:08.735  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:45:08.749  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:45:08.756  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:45:08.795  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 10:45:08.795  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 10:45:08.795  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:45:08.795  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:45:08.819  1547  2079 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 10:45:08.819  1547  2079 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 10:45:08.823  3385  3414 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 10:45:08.823  3385  3414 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 10:45:08.823  3385  3414 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 10:45:08.823  3385  3414 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 10:45:08.823  3385  3414 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 10:45:08.823  3385  3414 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 10:45:08.823  3385  3414 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 10:45:11.035  2914  4192 V KeepSync: Connecting to GoogleApiClient
,08-10 10:45:11.036   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:45:11.146  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 10:45:11.147  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 10:45:11.147  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:45:11.147  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:45:11.191  1958  4193 V BaseAuthAsyncOperation: access token request failed
,08-10 10:45:11.192  2914  4192 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:45:11.281  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 10:45:11.282  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 10:45:11.282  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:45:11.282  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:45:11.318  2914  4192 E KeepSync: IOException
08-10 10:45:11.318  2914  4192 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:45:11.318  2914  4192 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:45:11.318  2914  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:45:11.318  2914  4192 E KeepSync: 	... 10 more
08-10 10:45:11.319  2914  4192 W KeepSync: Sync result 2
,08-10 10:45:11.333   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 344292, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:45:50.894   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:45:56.227   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:46:09.556  1547  1956 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 10:46:14.874  3617  4197 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 10:46:14.895  3617  4198 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:46:14.908  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 10:46:14.910  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:46:14.936  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 10:46:14.936  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 10:46:14.936  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:46:14.936  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:46:14.956  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:46:14.957  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:46:14.978  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 10:46:14.978  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:46:14.978  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:46:14.978  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:46:14.991  3617  4198 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:46:14.992  3617  4197 E BooksSync: Soft error
08-10 10:46:14.992  3617  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:46:14.992  3617  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:46:14.992  3617  4197 E BooksSync: Sync error
08-10 10:46:14.992  3617  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:46:14.992  3617  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:46:14.992  3617  4197 I BooksSync: Finished books sync
,08-10 10:46:15.007   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 408071, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:46:15.130  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:46:15.132  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:46:15.158  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:46:15.158  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:46:15.158  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:46:15.158  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:46:15.178  3424  4200 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:46:15.178  3424  4200 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:46:15.178  3424  4200 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	... 12 more
08-10 10:46:15.178  3424  4200 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at fal.a(PG:38)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:46:15.178  3424  4200 E HttpOperation: 	... 14 more
,08-10 10:46:15.247  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:46:15.247  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 10:46:15.247  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:46:15.247  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:46:15.267  3424  4200 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:46:15.267  3424  4200 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at hec.a(PG:42)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at hee.a(PG:102)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at czr.a(PG:65)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at kka.a(PG:108)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:46:15.267  3424  4200 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	... 15 more
08-10 10:46:15.267  3424  4200 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:46:15.267  3424  4200 E HttpOperation: 	at fal.a(PG:38)
08-10 10:46:15.267  3424  4200 E HttpOperation: ,	at jdj.a(PG:4089)
08-10 10:46:15.267  3424  4200 E HttpOperation: 	... 17 more
08-10 10:46:15.267  3424  4200 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:46:15.267  3424  4200 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	... 15 more
08-10 10:46:15.267  3424  4200 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:46:15.267  3424  4200 E ExperimentLoader: 	... 17 more
,08-10 10:46:15.485   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 408111, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:46:15.960   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:46:21.320   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:46:41.027   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=434397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:46:46.387   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:47:06.094   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:47:11.453   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=464823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:47:14.076  2914  4206 V KeepSync: Connecting to GoogleApiClient
,08-10 10:47:14.077   873  1791 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:47:14.136  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:47:14.138  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:47:14.181  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 10:47:14.181  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 10:47:14.181  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:47:14.181  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:47:14.207  1958  4207 V BaseAuthAsyncOperation: access token request failed
,08-10 10:47:14.208  2914  4206 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:47:14.291  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 10:47:14.291  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 10:47:14.291  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:47:14.291  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:47:14.313  2914  4206 E KeepSync: IOException
08-10 10:47:14.313  2914  4206 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:47:14.313  2914  4206 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:47:14.313  2914  4206 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:47:14.313  2914  4206 E KeepSync: 	... 10 more
,08-10 10:47:14.313  2914  4206 W KeepSync: Sync result 2
,08-10 10:47:14.331   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 467332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:47:31.161   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=484531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:47:36.507   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=489877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:47:56.227   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=509597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:48:01.587   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:48:21.348   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=534718, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:48:26.667   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=540037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:48:46.414   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=559784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:48:51.720   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=565090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:49:11.481   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=584850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:49:16.787   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:49:36.547   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=609917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:49:41.853   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=615223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:50:01.561   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=634931, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:50:06.920   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=640290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:50:26.165  3617  4218 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 10:50:26.216  3617  4219 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:50:26.231  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.235  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.268  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 10:50:26.268  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 10:50:26.268  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:50:26.269  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:50:26.303  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.308  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.340  1547  2079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:50:26.340  1547  2079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 10:50:26.340  1547  2079 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:50:26.340  1547  2079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:50:26.360  3617  4219 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:50:26.361  3617  4218 E BooksSync: Soft error
08-10 10:50:26.361  3617  4218 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:50:26.361  3617  4218 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 10:50:26.362  3617  4218 E BooksSync: Sync error
08-10 10:50:26.362  3617  4218 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:50:26.362  3617  4218 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:50:26.363  3617  4218 I BooksSync: Finished books sync
,08-10 10:50:26.379   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 659457, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:50:26.626   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=659997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:50:26.631  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.635  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:50:26.691  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 10:50:26.692  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:50:26.692  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:50:26.692  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:50:26.718  3424  4221 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:50:26.718  3424  4221 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:50:26.718  3424  4221 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	... 12 more
08-10 10:50:26.718  3424  4221 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at fal.a(PG:38)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:50:26.718  3424  4221 E HttpOperation: 	... 14 more
,08-10 10:50:26.793  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:50:26.793  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:50:26.793  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:50:26.793  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:50:26.816  3424  4221 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:50:26.816  3424  4221 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at hec.a(PG:42)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at hee.a(PG:102)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at czr.a(PG:65)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at kka.a(PG:108)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:50:26.816  3424  4221 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	... 15 more
08-10 10:50:26.816  3424  4221 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at fal.a(PG:38)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:50:26.816  3424  4221 E HttpOperation: 	... 17 more
,08-10 10:50:26.816  3424  4221 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:50:26.816  3424  4221 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	... 15 more
08-10 10:50:26.816  3424  4221 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:50:26.816  3424  4221 E ExperimentLoader: 	... 17 more
,08-10 10:50:26.953   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 659551, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:50:31.973   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=665343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:50:51.694   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:50:57.027   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=690397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:51:16.761   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:51:19.844  2914  4227 V KeepSync: Connecting to GoogleApiClient
,08-10 10:51:19.844   873  1793 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:51:19.908  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:51:19.910  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:51:19.959  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 10:51:19.959  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 10:51:19.959  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:51:19.960  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:51:19.980  1958  4228 V BaseAuthAsyncOperation: access token request failed
,08-10 10:51:19.981  2914  4227 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:51:20.044  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 10:51:20.044  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 10:51:20.044  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:51:20.044  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:51:20.069  2914  4227 E KeepSync: IOException
08-10 10:51:20.069  2914  4227 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:51:20.069  2914  4227 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:51:20.069  2914  4227 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:51:20.069  2914  4227 E KeepSync: 	... 10 more
,08-10 10:51:20.069  2914  4227 W KeepSync: Sync result 2
,08-10 10:51:20.084   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 712958, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:51:22.120   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=715490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:51:41.827   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=735197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:51:47.173   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=740543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:52:06.894   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=760264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:52:12.241   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=765610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:52:31.960   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=785330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:52:37.293   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=790663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:52:57.027   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=810397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:53:02.360   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=815730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:53:22.094   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=835464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:53:27.427   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=840797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:53:47.160   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=860530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:53:52.480   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=865850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:54:12.227   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=885597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:54:17.547   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=890917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:54:27.774   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=901144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:54:42.627   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=915997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:54:52.841   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=926210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:55:07.694   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:55:17.880   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=951250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:55:32.760   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=966130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:55:42.947   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=976317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:55:57.814   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:56:08.014   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1001383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:56:22.880   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1016250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:56:33.081   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1026450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:56:47.934   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1041304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:56:58.147   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1051517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:57:08.302  4056  4071 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-10 10:57:13.000   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:57:23.213   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1076583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:57:38.067   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:57:48.280   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:58:03.120   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1116490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:58:13.321   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:58:28.174   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:58:38.360   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1151730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:58:48.583  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:58:48.585  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:58:48.639  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:58:48.639  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:58:48.639  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:58:48.639  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:58:48.660  3424  4250 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 10:58:48.660  3424  4250 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at blb.a(PG:3937)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at czp.a(PG:18188)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:58:48.660  3424  4250 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	... 12 more
08-10 10:58:48.660  3424  4250 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at fal.a(PG:38)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:58:48.660  3424  4250 E HttpOperation: 	... 14 more
,08-10 10:58:48.730  1547  1563 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 10:58:48.730  1547  1563 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 10:58:48.730  1547  1563 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 10:58:48.730  1547  1563 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:58:48.757  3424  4250 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 10:58:48.757  3424  4250 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jdm.a(PG:82)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jcs.o(PG:406)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jcn.a(PG:1379)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jcs.i(PG:143)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at hec.a(PG:42)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at hee.a(PG:102)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at czr.a(PG:65)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at kka.a(PG:108)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at czp.a(PG:19176)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at czp.a(PG:9081)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at czq.run(PG:1686)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818),
08-10 10:58:48.757  3424  4250 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jdj.a(PG:4091)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jdj.a(PG:1125)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jdm.a(PG:77)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	... 15 more
08-10 10:58:48.757  3424  4250 E HttpOperation: Caused by: faj: BadAuthentication
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at fal.a(PG:38)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	at jdj.a(PG:4089)
08-10 10:58:48.757  3424  4250 E HttpOperation: 	... 17 more
08-10 10:58:48.757  3424  4250 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 10:58:48.757  3424  4250 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at hec.a(PG:42)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at hee.a(PG:102)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at czr.a(PG:65)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at kka.a(PG:108)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	... 15 more
08-10 10:58:48.757  3424  4250 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at fal.a(PG:38)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 10:58:48.757  3424  4250 E ExperimentLoader: 	... 17 more
,08-10 10:58:48.901   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1161715, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:58:48.943  3617  4254 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 10:58:48.959  3617  4255 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 10:58:48.986  1547  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:58:48.986  1547  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 10:58:48.986  1547  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:58:48.986  1547  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:58:49.034  1547  1881 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 10:58:49.034  1547  1881 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 10:58:49.034  1547  1881 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:58:49.034  1547  1881 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:58:49.049  3617  4255 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 10:58:49.050  3617  4254 E BooksSync: Soft error
08-10 10:58:49.050  3617  4254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:58:49.050  3617  4254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:58:49.050  3617  4254 E BooksSync: Sync error
08-10 10:58:49.050  3617  4254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 10:58:49.050  3617  4254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 10:58:49.050  3617  4254 I BooksSync: Finished books sync
,08-10 10:58:49.064   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1161910, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:58:53.240   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1166610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:59:10.360   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1183730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:59:18.293   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1191663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 10:59:30.799  2914  4257 V KeepSync: Connecting to GoogleApiClient
08-10 10:59:30.799   873  1793 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 10:59:30.856  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:59:30.858  1547  1547 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 10:59:30.909  1547  1562 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 10:59:30.909  1547  1562 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 10:59:30.910  1547  1562 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:59:30.910  1547  1562 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:59:30.943  1958  4258 V BaseAuthAsyncOperation: access token request failed
,08-10 10:59:30.945  2914  4257 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 10:59:31.048  1547  2080 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 10:59:31.049  1547  2080 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 10:59:31.049  1547  2080 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 10:59:31.049  1547  2080 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 10:59:31.063  2914  4257 E KeepSync: IOException
08-10 10:59:31.063  2914  4257 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 10:59:31.063  2914  4257 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 10:59:31.063  2914  4257 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 10:59:31.063  2914  4257 E KeepSync: 	... 10 more
08-10 10:59:31.063  2914  4257 W KeepSync: Sync result 2
,08-10 10:59:31.074   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1203967, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 10:59:39.160   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1212530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 10:59:44.743   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 10:59:47.040   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1220410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:00:04.174   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:00:12.094   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1245464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:00:29.240   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1262610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:00:37.147   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:00:48.699  1547  1956 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 11:00:54.307   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1287677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:01:02.214   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:01:19.373   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1312743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:01:27.267   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:01:44.387   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1337757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:01:52.333   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:02:09.454   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1362824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:02:17.387   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:02:34.520   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1387890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:02:42.467   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:02:59.587   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1412957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:03:07.521   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:03:24.654   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:03:32.573   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:03:49.720   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:03:57.640   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1471010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:04:14.787   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1488157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:04:22.694   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1496064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:04:28.894   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1502264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:04:47.747   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1521117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:04:53.960   873  4112 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1527330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-10 11:04:59.977  4273  4273 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 11:04:59.982  4273  4273 D AndroidRuntime: CheckJNI is OFF
08-10 11:05:00.017  4273  4273 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 11:05:00.063  4273  4273 I Radio-JNI: register_android_hardware_Radio DONE
08-10 11:05:00.085  4273  4273 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 11:05:00.097   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 11:05:00.098   873   886 I ActivityManager: Killing 3668:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 11:05:00.197   873  1385 D GraphicsStats: Buffer count: 2
08-10 11:05:00.197   873  1690 I WindowState: WIN DEATH: Window{98757b2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 11:05:00.198   873  1310 D WifiService: Client connection lost with reason: 4
08-10 11:05:00.241   873   896 W PackageSettings: Skipping PackageSetting{fb47771 com.example.hello/10273} due to missing metadata
08-10 11:05:00.266   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 11:05:00.266   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 11:05:00.267   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-10 11:05:00.267   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 11:05:00.267   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.267   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.267   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.267   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 11:05:00.267   873   886 I ActivityManager:   Force finishing activity ActivityRecord{1807dab u0 com.test.thalitest/.MainActivity t8}
08-10 11:05:00.271   873   896 I art     : Starting a blocking GC Explicit
08-10 11:05:00.284   873  1791 W ActivityManager: Spurious death for ProcessRecord{77488de 0:com.test.thalitest/u0a0}, curProc for 3668: null
08-10 11:05:00.347   873   896 I art     : Explicit concurrent mark sweep GC freed 27523(2MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 28MB/43MB, paused 1.086ms total 75.228ms
08-10 11:05:00.370   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 11:05:00.378  4273  4273 I art     : System.exit called, status: 0
08-10 11:05:00.378  4273  4273 I AndroidRuntime: VM exiting with result code 0.
08-10 11:05:00.387   873   896 I ActivityManager: Start proc 4284:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 11:05:00.387   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 11:05:00.399   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 11:05:00.416  4056  4056 D BluetoothMapAppObserver: onReceive
08-10 11:05:00.416  4056  4056 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-10 11:05:00.417  1964  2050 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 11:05:00.424   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 11:05:00.433  3504  3504 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 11:05:00.444  1643  1643 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 11:05:00.460   873  1747 I ActivityManager: Start proc 4299:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 11:05:00.469  1643  4298 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 11:05:00.475  1643  4298 I Decoder : createOrResetDecoder
08-10 11:05:00.487  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 11:05:00.513  1547  1547 I ConfigService: onCreate
08-10 11:05:00.515   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 11:05:00.523   873  1388 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3668 uid 10000
08-10 11:05:00.533  1643  1643 I Keyboard.Facilitator: onFinishInput()
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 11:05:00.535  1547  4312 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 11:05:00.535  1547  4312 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:05:00.539  4299  4299 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 11:05:00.544  1547  4312 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 11:05:00.555  1732  1823 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 11:05:00.558   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 11:05:00.560   873   885 E PackageManager: Failed to write settings, restoring backup
08-10 11:05:00.560   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 11:05:00.560   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 11:05:00.560   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 11:05:00.560   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 11:05:00.560   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 11:05:00.560   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.560   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.560   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.560  1643  4298 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 11:05:00.564   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-10 11:05:00.564   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 11:05:00.564   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 11:05:00.564   873   886 E DropBoxManagerService: 	... 13 more
08-10 11:05:00.567   873   884 I ActivityManager: Start proc 4313:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-10 11:05:00.568  1732  1823 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 11:05:00.568  1732  1823 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1732
08-10 11:05:00.568  1732  1823 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.568  1732  1823 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.570   873  1388 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 11:05:00.570   873  4319 E DropBoxManagerService: Can't write: system_app_crash
08-10 11:05:00.570   873  4319 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 11:05:00.570   873  4319 E DropBoxManagerService: 	... 5 more
08-10 11:05:00.573  1732  1823 I Process : Sending signal. PID: 1732 SIG: 9
08-10 11:05:00.608  1643  4298 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-10 11:05:00.609  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-10 11:05:00.609  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-10 11:05:00.612  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-10 11:05:00.612  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-10 11:05:00.613  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 11:05:00.613  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-10 11:05:00.614  1643  4298 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-10 11:05:00.614  1643  4298 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 11:05:00.614  1643  4298 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 11:05:00.614  1643  4298 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 11:05:00.614  1643  4298 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 11:05:00.614  1643  4298 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 11:05:00.637  4299  4299 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 11:05:00.654   873  1690 D GraphicsStats: Buffer count: 1
08-10 11:05:00.654   873  1740 I WindowState: WIN DEATH: Window{8955cf0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-10 11:05:00.655   873  1791 I ActivityManager: Start proc 4333:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 11:05:00.666   873  1690 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1732) has died
08-10 11:05:00.667   873  1690 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-10 11:05:00.668   873  1690 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 11:05:00.668  4299  4332 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 11:05:00.692   873   886 I ActivityManager: Start proc 4346:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 11:05:00.712  4333  4333 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-10 11:05:00.731  1958  4343 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 11:05:00.732  1958  4343 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 11:05:00.738  1547  1547 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-10 11:05:00.740  1547  1547 D AndroidRuntime: Shutting down VM
08-10 11:05:00.740  1547  1547 E AndroidRuntime: FATAL EXCEPTION: main
08-10 11:05:00.740  1547  1547 E AndroidRuntime: Process: com.google.process.gapps, PID: 1547
08-10 11:05:00.740  1547  1547 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-10 11:05:00.740  1547  1547 E AndroidRuntime: 	... 8 more
08-10 11:05:00.743   873  4360 E DropBoxManagerService: Can't write: system_app_crash
08-10 11:05:00.743   873  4360 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 11:05:00.743   873  4360 E DropBoxManagerService: 	... 5 more
08-10 11:05:00.744  1547  1547 I Process : Sending signal. PID: 1547 SIG: 9
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:05:00.744  4346  4346 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:05:00.744  4346  4346 D AndroidRuntime: Shutting down VM
08-10 11:05:00.750  4346  4346 E AndroidRuntime: FATAL EXCEPTION: main
08-10 11:05:00.750  4346  4346 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4346
08-10 11:05:00.750  4346  4346 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 11:05:00.750  4346  4346 E AndroidRuntime: 	... 10 more
08-10 11:05:00.752   873  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 11:05:00.753   873  4361 E DropBoxManagerService: Can't write: system_app_crash
08-10 11:05:00.753   873  4361 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 11:05:00.753   873  4361 E DropBoxManagerService: 	... 5 more
08-10 11:05:00.753  4346  4346 I Process : Sending signal. PID: 4346 SIG: 9
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.767  4299  4328 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.773  1958  4343 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.773  4299  4328 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.773  1958  4343 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 11:05:00.779   873  1388 I ActivityManager: Killing 3556:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-10 11:05:00.794   873  1310 D WifiService: Client connection lost with reason: 4
08-10 11:05:00.811  4299  4328 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.816  4299  4332 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-10 11:05:00.816  4299  4332 E AndroidRuntime: Process: android.process.acore, PID: 4299
08-10 11:05:00.816  4299  4332 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:05:00.816  4299  4332 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 11:05:00.817  4299  4328 I Process : Sending signal. PID: 4299 SIG: 9
08-10 11:05:00.832   873  1747 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4346) has died
08-10 11:05:00.834   873  1747 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 11:05:00.841   873   884 I ActivityManager: Process com.google.process.gapps (pid 1547) has died
08-10 11:05:00.842   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-10 11:05:00.843   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-10 11:05:00.843   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-10 11:05:00.843  1958  1958 W RocketImpressions: ClearcutLogger connection suspended: 1
08-10 11:05:00.878   873   886 I ActivityManager: Start proc 4363:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 11:05:00.886   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
