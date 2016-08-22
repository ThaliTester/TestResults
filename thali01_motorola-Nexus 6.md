#### Test 82147046d1155fd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-22 11:15:05.117   875  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-22 11:15:05.838  3894  3894 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-22 11:15:05.843  3894  3894 D AndroidRuntime: CheckJNI is OFF
08-22 11:15:05.879  3894  3894 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-22 11:15:05.922  3894  3894 I Radio-JNI: register_android_hardware_Radio DONE
08-22 11:15:05.944  3894  3894 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 11:15:05.948   875  1706 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 11:15:05.995  2021  2035 W SearchService: Abort, client detached.
08-22 11:15:06.006  2021  2332 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3f6ce3b
08-22 11:15:06.007  2021  2340 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-22 11:15:06.007  2021  2021 I HotwordDetector: Closing mic
08-22 11:15:06.022  3894  3894 D AndroidRuntime: Shutting down VM
08-22 11:15:06.055   875  1956 I ActivityManager: Start proc 3903:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-22 11:15:06.083   377  2342 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-22 11:15:06.084   377  2342 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-22 11:15:06.088   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-22 11:15:06.089  2021  2339 I MicroRecognitionRnrImpl: Detection finished
08-22 11:15:06.090  2021  2335 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-22 11:15:06.132  3903  3903 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-22 11:15:06.170  3903  3903 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-22 11:15:06.187  3903  3903 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3743-3748)
08-22 11:15:06.187  3903  3903 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 11:15:06.210  3903  3903 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b876e1a}
08-22 11:15:06.211  3903  3903 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 11:15:06.211  3903  3903 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 11:15:06.219  3903  3903 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-22 11:15:06.221  3903  3903 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 11:15:06.253  3903  3903 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 11:15:06.280  3903  3903 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 11:15:06.280  3903  3903 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 11:15:06.280  3903  3903 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 11:15:06.280  3903  3903 I Adreno  : Build Date                       : 10/20/15
08-22 11:15:06.280  3903  3903 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 11:15:06.280  3903  3903 I Adreno  : Local Branch                     : M14
08-22 11:15:06.280  3903  3903 I Adreno  : Remote Branch                    : 
08-22 11:15:06.280  3903  3903 I Adreno  : Remote Branch                    : 
08-22 11:15:06.280  3903  3903 I Adreno  : Reconstruct Branch               : 
,08-22 11:15:06.374   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b28d1c5:true
,08-22 11:15:06.468  3903  3903 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 11:15:06.489  3903  3903 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-22 11:15:06.561  3903  3942 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 11:15:06.573  3903  3928 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-22 11:15:06.593  3903  3942 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 11:15:06.661   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +621ms
08-22 11:15:06.667  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-22 11:15:06.794  3903  3903 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3903
,08-22 11:15:06.865   875  1385 I ActivityManager: Killing 3484:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-22 11:15:06.949   875  1385 I ActivityManager: Killing 3085:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-22 11:15:07.004  3903  3903 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 11:15:07.149  3903  3944 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1679492816
,08-22 11:15:07.155  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 11:15:07.155  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 11:15:07.155  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 11:15:07.155  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 11:15:07.155  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 11:15:07.156  3903  3944 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfe527e added. We now have 1 listener(s)
,08-22 11:15:07.161  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-22 11:15:07.162  3903  3944 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 11:15:07.163  3903  3944 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:07.164  3903  3944 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 11:15:07.169  3903  3944 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ef02f5 added. We now have 1 listener(s)
08-22 11:15:07.170  3903  3944 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:07.172   875  1308 D WifiService: New client listening to asynchronous messages
,08-22 11:15:07.173  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:07.173  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
,08-22 11:15:07.173  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-22 11:15:07.174  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 11:15:07.174  3903  3944 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 11:15:07.178  3903  3944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:07.178  3903  3944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-22 11:15:07.185  3903  3944 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:07.186  3903  3944 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:07.186  3903  3944 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 11:15:07.186  3903  3944 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:07.186  3903  3944 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:15:07.320  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:07.327  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:07.334  3903  3903 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 11:15:07.972  3903  3951 W jxcore-log: Initializing JXcore engine
,08-22 11:15:07.973  3903  3951 W jxcore-log: JXcore engine is ready
,08-22 11:15:08.019  3951  3951 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-22 11:15:08.019  3951  3951 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11738]" dev="sockfs" ino=11738 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-22 11:15:08.019  3951  3951 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 11:15:08.019  3951  3951 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27249]" dev="sockfs" ino=27249 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-22 11:15:08.035  3903  3951 W jxcore-log: Starting JXcore engine
,08-22 11:15:08.120  3903  3951 W jxcore-log: Platform android
08-22 11:15:08.120  3903  3951 W jxcore-log: 
,08-22 11:15:08.120  3903  3951 W jxcore-log: Process ARCH arm
08-22 11:15:08.120  3903  3951 W jxcore-log: 
,08-22 11:15:08.375  3903  3951 I jxcore-log: JXcore Cordova bridge is ready!
08-22 11:15:08.375  3903  3951 I jxcore-log: 
,08-22 11:15:08.376  3903  3951 W jxcore-log: JXcore engine is started
,08-22 11:15:08.386  3903  3944 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 11:15:08.392  3903  3903 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 11:15:09.081  3143  3954 V KeepSync: Connecting to GoogleApiClient
,08-22 11:15:09.083   875  1979 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-22 11:15:09.141  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:09.142  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:09.166  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-22 11:15:09.166  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-22 11:15:09.166  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 11:15:09.166  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:09.188  1716  3955 V BaseAuthAsyncOperation: access token request failed
,08-22 11:15:09.189  3143  3954 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-22 11:15:09.269  1499  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-22 11:15:09.269  1499  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-22 11:15:09.269  1499  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 11:15:09.269  1499  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:09.306  3143  3954 E KeepSync: IOException
08-22 11:15:09.306  3143  3954 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-22 11:15:09.306  3143  3954 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 11:15:09.306  3143  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-22 11:15:09.306  3143  3954 E KeepSync: 	... 10 more
,08-22 11:15:09.306  3143  3954 W KeepSync: Sync result 2
,08-22 11:15:09.319   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 125618, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-22 11:15:11.173  1716  3960 I EventLogService: Opted in for usage reporting
,08-22 11:15:11.175  1716  3960 I EventLogService: Aggregate from 1471855502279 (log), 1471855502279 (data)
,08-22 11:15:11.196  3677  3963 V GoogleAuthProtoRequest: [298] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 11:15:11.239  1716  3960 W EventLogAggregator: Unknown tag: snet_gcore
,08-22 11:15:11.239  1716  3960 W EventLogAggregator: Unknown tag: snet_launch_service
,08-22 11:15:11.279  1716  3960 I ServiceDumpSys: dumping service [account]
,08-22 11:15:11.284  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-22 11:15:11.284  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-22 11:15:11.284  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 11:15:11.284  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:11.302  3677  3963 W ExperimentUpdateService: [298] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: [298] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-22 11:15:11.305  3677  3963 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-22 11:15:11.333  1499  3965 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-22 11:15:11.335  1499  3965 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-22 11:15:11.360  1499  3965 W Uploader:  no longer exists, so no auth token.
,08-22 11:15:11.378  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:11.396  1499  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-22 11:15:11.397  1499  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-22 11:15:11.397  1499  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 11:15:11.397  1499  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:11.407  3600  3600 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-22 11:15:11.407  3600  3600 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-22 11:15:11.407  3600  3600 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-22 11:15:13.491  1499  3965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-22 11:15:13.491  1499  3965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-22 11:15:13.491  1499  3965 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 11:15:13.491  1499  3965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:13.532  1499  3965 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-22 11:15:13.532  1499  3965 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-22 11:15:13.532  1499  3965 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-22 11:15:13.713  1499  3965 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-22 11:15:13.714  1499  3965 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-22 11:15:13.714  1499  3965 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 11:15:13.715  1499  3965 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:13.758  1499  3965 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-22 11:15:13.758  1499  3965 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-22 11:15:13.758  1499  3965 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-22 11:15:14.683  1499  1499 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 11:15:14.686  1499  3976 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-22 11:15:15.209   875  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 11:15:18.452  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 11:15:18.452  3903  3951 I jxcore-log: 
08-22 11:15:18.455  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 11:15:18.455  3903  3951 I jxcore-log: 
,08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:18.467  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:18.474  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:18.482  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 11:15:18.482  3903  3951 I jxcore-log: 
,08-22 11:15:18.489  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 11:15:18.489  3903  3951 I jxcore-log: 
,08-22 11:15:19.016  3903  3951 D ExecuteNativeTests: Running unit tests
,08-22 11:15:19.074  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:19.074  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce added. We now have 2 listener(s)
,08-22 11:15:19.075  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:19.075  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:19.075  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:19.076  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:19.076  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef added. We now have 2 listener(s)
08-22 11:15:19.076  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:19.076  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:19.082  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.095  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:19.099  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.099  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:19.113  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 11:15:19.113  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:19.113  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:19.114  3903  3951 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-22 11:15:19.114  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.115  3903  3951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:19.116  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:19.116  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:19.116  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:19.117  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.117  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.117  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:19.118  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.118  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.118  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:19.118  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:19.118  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce removed from the list
08-22 11:15:19.118  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.118  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef removed from the list
,08-22 11:15:19.121  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.122  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.122  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.123  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.123  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.124  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:19.124  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.124  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.125  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.126  3903  3951 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-22 11:15:19.127  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.127  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.127  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.127  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:19.127  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.127  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.127  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.127  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:19.127  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.127  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.128  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.128  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.128  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.128  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.129  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.129  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.129  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:19.129  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:19.134  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:19.135  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:19.138  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:19.138  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.138  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.138  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.139  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:19.139  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.139  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.139  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.139  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.140  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.140  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.140  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.140  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.140  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.140  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.141  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.141  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.141  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.141  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.142  3903  3951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-22 11:15:19.146  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.158  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:19.166  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.167  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:19.168  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:19.168  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:19.169  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 11:15:19.169  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:19.169  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:19.176  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.183  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 11:15:19.183  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 11:15:19.184  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.198  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:19.203  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 11:15:19.204  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:19.210  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-22 11:15:19.218  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-22 11:15:19.218  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:19.218  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:19.219  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:19.220  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.225  2737  2899 D BtGatt.GattService: registerClient() - UUID=7304fd10-b123-4921-8153-83d34d1cc3fe
,08-22 11:15:19.226  2737  2781 D BtGatt.GattService: onClientRegistered() - UUID=7304fd10-b123-4921-8153-83d34d1cc3fe, clientIf=5
,08-22 11:15:19.227  3903  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 11:15:19.230  2737  2749 D BtGatt.GattService: start scan with filters
,08-22 11:15:19.235  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:19.235  2737  2790 D BtGatt.ScanManager: handling starting scan
08-22 11:15:19.236  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 11:15:19.236  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:19.236  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:19.238  2737  2790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:19.241  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.242  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.243  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:19.248  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:19.250  2737  2781 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 11:15:19.250  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.251  2737  2790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 11:15:19.254  3903  3951 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:19.259  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:19.259  3903  3951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 11:15:19.260  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:19.260  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 11:15:19.260  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.260  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 11:15:19.260  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-22 11:15:19.260  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 11:15:19.260  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:19.260  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-22 11:15:19.262  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 11:15:19.262  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:19.263  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.264  2737  2899 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:19.264  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 11:15:19.265  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.265  2737  2900 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 11:15:19.266  2737  2790 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:19.266  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:19.266  2737  2790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 11:15:19.266  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:19.266  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 11:15:19.267  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:19.267  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:19.274  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.275  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:19.275  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:19.276  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:19.277  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:19.280  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:19.280  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:19.280  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.280  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.280  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.280  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:19.281  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.281  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.281  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.281  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.281  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.282  3903  3951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 11:15:19.286  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:19.292  2737  2781 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 11:15:19.292  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.294  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:19.299  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.300  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:19.301  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-22 11:15:19.301  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.301  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:19.301  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 11:15:19.303  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 11:15:19.305  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:19.306  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.308  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:19.311  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.316  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 11:15:19.316  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:19.324  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 11:15:19.324  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.325  2737  2790 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:19.325  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:19.326  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 11:15:19.326  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:19.329  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:19.330  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:19.330  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:19.330  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.333  2737  2899 D BtGatt.GattService: registerClient() - UUID=76a1ce34-6da5-43c1-865f-5c1170e08026
,08-22 11:15:19.334  2737  2781 D BtGatt.GattService: onClientRegistered() - UUID=76a1ce34-6da5-43c1-865f-5c1170e08026, clientIf=5
,08-22 11:15:19.334  3903  3915 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 11:15:19.335  2737  2877 D BtGatt.GattService: start scan with filters
,08-22 11:15:19.337  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
,08-22 11:15:19.337  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.338  2737  2790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 11:15:19.339  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:19.339  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 11:15:19.339  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 11:15:19.340  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:19.344  2737  2781 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 11:15:19.344  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.344  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.344  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:19.345  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.347  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:19.347  2737  2790 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:19.354  3903  3951 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:19.355  2737  2781 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 11:15:19.356  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.356  2737  2790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 11:15:19.359  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:19.359  3903  3951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-22 11:15:19.359  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:19.359  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 11:15:19.359  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.359  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 11:15:19.359  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-22 11:15:19.360  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 11:15:19.360  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 11:15:19.360  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:19.360  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 11:15:19.360  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:19.361  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.363  2737  2877 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:19.365  2737  2877 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 11:15:19.365  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 11:15:19.365  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 11:15:19.365  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:19.365  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 11:15:19.366  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-22 11:15:19.366  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 11:15:19.366  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.367  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.367  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 11:15:19.367  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 11:15:19.367  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:19.368  2737  2790 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:19.368  2737  2790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 11:15:19.368  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:19.370  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.370  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.370  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.371  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.371  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.371  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:19.371  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
,08-22 11:15:19.371  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.371  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.371  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.371  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.372  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.372  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.376  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.376  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:19.376  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.376  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.378  3903  3951 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 11:15:19.381  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:19.388  2737  2781 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 11:15:19.388  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.390  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:19.394  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.394  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:19.395  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 11:15:19.395  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:19.395  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:19.396  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 11:15:19.396  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.395  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:19.397  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:19.398  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.402  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 11:15:19.402  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:19.402  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.405  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 11:15:19.405  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.405  2737  2790 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:19.407  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:19.408  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 11:15:19.408  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:19.412  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:19.412  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:19.412  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:19.413  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 11:15:19.413  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.413  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.413  2737  2790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 11:15:19.416  2737  2747 D BtGatt.GattService: registerClient() - UUID=7ec77f5e-0477-43b8-acd0-054dc1e3efe8
08-22 11:15:19.417  2737  2781 D BtGatt.GattService: onClientRegistered() - UUID=7ec77f5e-0477-43b8-acd0-054dc1e3efe8, clientIf=5
,08-22 11:15:19.417  3903  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 11:15:19.418  2737  2749 D BtGatt.GattService: start scan with filters
,08-22 11:15:19.420  2737  2781 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 11:15:19.420  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.424  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:19.424  2737  2790 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:19.424  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:19.424  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:19.425  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:19.428  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.428  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:19.428  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:19.430  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:19.434  3903  3951 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:19.434  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:19.434  3903  3951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:19.434  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:19.434  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 11:15:19.434  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.434  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:19.434  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-22 11:15:19.434  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:19.434  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 11:15:19.434  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:19.435  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 11:15:19.435  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:19.436  2737  2781 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 11:15:19.436  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:19.436  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.436  2737  2790 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 11:15:19.436  2737  2900 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:19.437  2737  2749 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 11:15:19.437  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 11:15:19.437  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:19.437  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 11:15:19.438  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 11:15:19.438  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:19.440  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.440  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:19.440  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 11:15:19.440  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:19.441  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:19.442  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.443  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:19.443  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:19.443  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:19.443  3903  3951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 11:15:19.444  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.444  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 11:15:19.444  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.444  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.444  2737  2790 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:19.444  2737  2790 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 11:15:19.444  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.444  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.444  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:19.445  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.445  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:19.445  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.445  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.445  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.446  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.446  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.447  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.448  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.448  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.448  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.449  3903  3951 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-22 11:15:19.450  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.450  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.450  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.450  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.451  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.451  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.451  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.451  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.451  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
,08-22 11:15:19.451  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.451  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.451  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.451  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.452  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.453  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.453  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.453  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.453  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.455  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:19.455  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.455  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.455  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.456  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.456  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.456  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.456  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
,08-22 11:15:19.456  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.456  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.456  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.457  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.457  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.457  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.457  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.457  2737  2781 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 11:15:19.457  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.459  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.459  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.459  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.460  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.460  3903  3951 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-22 11:15:19.460  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.461  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.461  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.461  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.461  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.461  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.461  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.461  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.461  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.461  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.461  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.461  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.461  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.461  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.463  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.463  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.463  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:19.463  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.464  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 11:15:19.464  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:19.465  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.465  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:19.465  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:19.466  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.466  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.466  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
,08-22 11:15:19.466  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.466  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 11:15:19.466  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.466  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:19.466  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:19.466  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:19.466  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.466  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.467  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.468  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.468  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.468  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.468  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.469  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 11:15:19.473  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:19.473  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-22 11:15:19.473  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-22 11:15:19.473  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 11:15:19.474  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:19.474  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.474  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.474  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:19.475  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:19.475  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.475  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.475  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
,08-22 11:15:19.475  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.475  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.476  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.476  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.476  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.476  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.476  2737  2781 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 11:15:19.476  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.476  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.477  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.477  2737  2790 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:19.477  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.477  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.477  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.481  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:19.482  3903  3951 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:19.482  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 11:15:19.484  2737  2781 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 11:15:19.484  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.484  2737  2790 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 11:15:19.491  2737  2781 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 11:15:19.491  2737  2781 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:19.494  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:19.494  3903  3951 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 11:15:19.495  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:19.496  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:19.496  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:19.497  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 11:15:19.498  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 11:15:19.498  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:19.499  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:19.499  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:19.500  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 11:15:19.501  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:19.501  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 11:15:19.502  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:19.502  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:19.502  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 11:15:19.503  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 11:15:19.503  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:19.503  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:19.504  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:19.504  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:19.504  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:19.505  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:19.505  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:19.506  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:19.506  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 11:15:19.507  3903  3951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:19.507  3903  3951 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 11:15:19.507  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:19.507  3903  3951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:19.507  3903  3951 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 11:15:19.507  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:19.507  3903  3951 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:19.507  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 11:15:19.511  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 11:15:19.512  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 11:15:19.512  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-22 11:15:19.513  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 11:15:19.513  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 11:15:19.513  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 11:15:19.513  3903  3951 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:19.513  3903  3951 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 11:15:19.514  3903  3982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-22 11:15:19.514  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.514  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.514  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.514  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.514  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.514  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.515  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 11:15:19.516  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.516  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.516  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.516  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.516  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.516  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.516  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.516  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.517  3903  3983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-22 11:15:19.517  3903  3983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-22 11:15:19.517  3903  3983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
08-22 11:15:19.517  3903  3982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:19.517  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.517  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.518  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.518  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.518  3903  3951 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 11:15:19.519  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.519  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.519  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.519  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.519  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.519  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.519  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.520  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.520  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.520  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.520  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.520  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.520  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.520  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:19.520  3903  3982 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-22 11:15:19.521  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.521  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.521  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.521  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.522  3903  3951 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 11:15:19.522  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.522  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.522  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.522  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.522  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.522  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.523  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.523  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.523  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.523  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.523  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.523  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.523  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.523  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.524  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.524  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.524  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.524  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.525  3903  3951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 11:15:19.525  3903  3951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 11:15:19.525  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:19.525  3903  3951 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 11:15:19.525  3903  3951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:19.525  3903  3951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 11:15:19.525  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:19.525  3903  3951 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 11:15:19.525  3903  3951 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:19.525  3903  3951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:19.526  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:19.526  3903  3951 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 11:15:19.526  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.526  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.526  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.526  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.526  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.526  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.526  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.526  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.526  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.526  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.526  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.526  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.527  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.527  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.528  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.528  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.528  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.529  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.529  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.529  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.529  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.529  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.529  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.529  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.530  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.530  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.530  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.530  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.530  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.530  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.530  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.530  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.530  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.530  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.530  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.530  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.530  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.531  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.531  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.531  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.531  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.531  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.531  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.531  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.531  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.531  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.531  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.532  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.532  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.532  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.533  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.534  3903  3951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 11:15:19.534  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:19.535  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-22 11:15:19.536  3903  3951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 11:15:19.536  3903  3951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 11:15:19.536  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 11:15:19.536  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:19.537  3903  3903 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 11:15:19.537  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.537  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 11:15:19.537  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 11:15:19.537  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 11:15:19.537  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.537  3903  3951 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 11:15:19.537  3903  3903 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 11:15:19.537  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.537  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.537  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:19.537  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:19.538  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:19.538  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.538  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.538  3903  3984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:19.539  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:19.539  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.539  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.539  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.539  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:19.539  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.539  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:19.539  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.539  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.539  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.540  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.540  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.540  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.540  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.540  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.540  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.540  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.540  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.540  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.541  3903  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-22 11:15:19.541  3903  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 11:15:19.541  3903  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 11:15:19.541  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.541  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.541  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.541  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.541  3903  3903 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-22 11:15:19.542  3903  3951 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 11:15:19.543  3903  3951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:19.543  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:19.543  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:19.543  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.543  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.543  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.543  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.543  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.543  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.543  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.543  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.543  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.544  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.544  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.544  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.544  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.544  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.545  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.545  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.545  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.545  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.549  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.550  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.550  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.550  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.550  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.550  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.550  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.550  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.550  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.550  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.550  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.551  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.551  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.551  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.552  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.552  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.552  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.552  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.553  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:19.553  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:19.553  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:19.553  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:19.553  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.553  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.553  3903  3951 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5da8dce not in the list
08-22 11:15:19.554  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.554  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.554  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:19.554  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.554  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.554  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:19.554  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:19.555  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:19.555  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:19.555  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:19.555  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9754ef not in the list
08-22 11:15:19.556  3903  3951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 11:15:19.556  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:19.556  3903  3951 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 11:15:19.556  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:19.556  3903  3951 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 11:15:19.556  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:19.558  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:19.558  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 11:15:19.559  3903  3951 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 11:15:19.559  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:19.559  3903  3951 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 11:15:19.559  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:19.559  3903  3951 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 11:15:19.559  3903  3951 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 11:15:19.560  3903  3951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 11:15:19.560  3903  3951 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 11:15:19.560  3903  3951 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 11:15:19.560  3903  3951 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 11:15:19.561  3903  3951 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 11:15:19.561  3903  3951 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 11:15:19.561  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:19.562  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@899e039 added. We now have 2 listener(s)
08-22 11:15:19.562  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:19.564  3903  3951 D BluetoothAdapter: enable(): BT is already enabled..!
08-22 11:15:19.564   875  3214 D WifiService: setWifiEnabled: true pid=3903, uid=10000
08-22 11:15:19.564   875  3214 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 11:15:19.565  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:19.565  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ec067e added. We now have 3 listener(s)
08-22 11:15:19.565  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:19.573  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:19.573  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed57df added. We now have 4 listener(s)
08-22 11:15:19.573  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:19.574  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:19.575  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@84e8c2c added. We now have 5 listener(s)
08-22 11:15:19.575  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:19.578   875  1395 D WifiService: setWifiEnabled: false pid=3903, uid=10000
08-22 11:15:19.578   875  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 11:15:19.583  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:19.584  2737  2775 D BluetoothAdapterState: Current state: ON, message: 23
08-22 11:15:19.584  2737  2775 D BluetoothAdapterProperties: Setting state to 13
08-22 11:15:19.584  2737  2775 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 11:15:19.584  2737  2775 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 11:15:19.587  2737  2775 I BluetoothAdapterState: Entering PendingCommandState
08-22 11:15:19.588  2737  2737 D BluetoothMapService: onReceive
08-22 11:15:19.589  2737  2737 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:19.589  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.589  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:19.589  2737  2737 D BluetoothMapService: STATE_TURNING_OFF
,08-22 11:15:19.590  2737  2737 D BluetoothMapService: MAP Service closeService in
,08-22 11:15:19.590  2737  2737 D BluetoothMapMasInstance0: MAP Service shutdown
,08-22 11:15:19.591  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:19.591  2737  2737 D ObexServerSockets0: shutdown(block = true)
08-22 11:15:19.591  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.591  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:19.591  2737  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-22 11:15:19.594  2737  2737 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-22 11:15:19.595  2737  2902 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 11:15:19.595  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.596  2737  2875 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 11:15:19.597  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 11:15:19.598   875  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-22 11:15:19.598   875  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-22 11:15:19.598   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 11:15:19.598   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 11:15:19.599  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.597  2737  2737 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 11:15:19.602  2737  2737 I BtOppRfcommListener: stopping Accept Thread
08-22 11:15:19.602  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.602  2737  3534 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:19.603  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:19.603  2737  3534 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 11:15:19.604  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.604  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:19.607  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.608   875   888 I ActivityManager: Start proc 3987:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-22 11:15:19.609   875  1877 D DhcpClient: Clearing IP address
08-22 11:15:19.609   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:19.611   373   873 D CommandListener: Setting iface cfg
08-22 11:15:19.611  2737  2781 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:19.611  2737  2775 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-22 11:15:19.612  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.614  1499  2461 V NativeCrypto: Read error: ssl=0x9acffe00: I/O error during system call, Connection timed out
08-22 11:15:19.615  1499  2461 V NativeCrypto: SSL shutdown failed: ssl=0x9acffe00: I/O error during system call, Broken pipe
08-22 11:15:19.616  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.617  2737  2737 D HeadsetService: Received stop request...Stopping profile...
08-22 11:15:19.618   875  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-22 11:15:19.619   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-22 11:15:19.619   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-22 11:15:19.619  1928  2090 D BluetoothHeadset: Proxy object disconnected
,08-22 11:15:19.619   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 11:15:19.619   875   875 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:19.619  1352  2056 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:19.620   875   875 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:19.620   875   875 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:19.622  2737  2737 D A2dpService: Received stop request...Stopping profile...
08-22 11:15:19.622  2737  2892 D A2dpStateMachine: Exit Disconnected: -1
,08-22 11:15:19.624   396   396 E Parcel  : Reading a NULL string not supported here.
08-22 11:15:19.624   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:19.627   875   875 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:19.628  2737  2737 D HidService: Received stop request...Stopping profile...
08-22 11:15:19.628   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-22 11:15:19.628  2737  2737 D HidService: Stopping Bluetooth HidService
08-22 11:15:19.630  2737  2737 D HealthService: Received stop request...Stopping profile...
08-22 11:15:19.632   875  1878 D DhcpClient: Receive thread stopped
,08-22 11:15:19.632  2737  2737 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:19.632  2737  2737 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:19.632  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.632  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.634  2737  2737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 11:15:19.634  2737  2781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 11:15:19.634  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:19.634  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 11:15:19.634  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:19.635  2737  2781 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-22 11:15:19.635  2737  2737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 11:15:19.634  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:19.635  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:19.635  2737  2737 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:19.635  2737  2737 V BluetoothAdapterState: isTurningOn()=false
,08-22 11:15:19.635  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.635  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.635  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:19.635  1352  1352 D HidProfile: Bluetooth service disconnected
08-22 11:15:19.636  2737  2737 D PanService: Received stop request...Stopping profile...
08-22 11:15:19.637  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 11:15:19.637  1352  1352 D PanProfile: Bluetooth service disconnected
,08-22 11:15:19.638  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:19.638  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:19.639  2737  2856 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:19.639  2737  2856 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:19.639  2737  2856 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:19.639  2737  2856 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:19.639  2737  2781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 11:15:19.640  2737  2737 V BluetoothAdapterState: isTurningOff()=true
,08-22 11:15:19.640  2737  2737 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:19.640  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.640  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.641  2737  2737 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 11:15:19.641  2737  2781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 11:15:19.641  2737  2737 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:19.642  2737  2737 D BluetoothMapService: Received stop request...Stopping profile...
08-22 11:15:19.642  2737  2737 D BluetoothMapService: stop()
08-22 11:15:19.643  2737  2737 D BluetoothMapAppObserver: deinitObservers()
,08-22 11:15:19.643  2737  2737 D BluetoothMapAppObserver: removeReceiver()
08-22 11:15:19.645  2737  2737 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:19.645  2737  2737 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:19.645  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.645  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.645  2737  2737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:19.645  2737  2781 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 11:15:19.646  2737  2737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-22 11:15:19.646  2737  2737 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:19.647  2737  2737 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:19.647  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.647  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.648  2737  2737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:19.648  1352  1352 D BluetoothMap: Proxy object disconnected
08-22 11:15:19.648  1352  1352 D MapProfile: Bluetooth service disconnected
08-22 11:15:19.648  2737  2737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 11:15:19.651  2737  2737 D BluetoothMapService: MAP Service closeService in
08-22 11:15:19.652  2737  2737 V BluetoothAdapterState: isTurningOff()=true
,08-22 11:15:19.652  2737  2737 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:19.652  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:19.652  2737  2737 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:19.652  2737  2775 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 11:15:19.652  2737  2775 D BluetoothAdapterProperties: Setting state to 15
08-22 11:15:19.653  2737  2775 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 11:15:19.653  2737  2775 I BluetoothAdapterState: Entering BleOnState
08-22 11:15:19.653  2737  2737 D BluetoothMapService: cleanup()
08-22 11:15:19.653  2737  2737 D BluetoothMapService: MAP Service closeService in
,08-22 11:15:19.653  1352  1366 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:19.653  1928  2090 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:19.654  1352  1365 D BluetoothMap: onBluetoothStateChange: up=false
08-22 11:15:19.654   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:19.655   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:19.655  1352  1709 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 11:15:19.655   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:19.656  1352  2056 D BluetoothPan: onBluetoothStateChange on: false
,08-22 11:15:19.656  1352  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 11:15:19.657  1352  1709 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 11:15:19.657   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 11:15:19.658  2737  2775 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 11:15:19.658  2737  2775 D BluetoothAdapterProperties: Setting state to 16
08-22 11:15:19.658  2737  2775 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 11:15:19.658  2737  2775 D BluetoothAdapterProperties: onBleDisable
08-22 11:15:19.659  2737  2775 I BluetoothAdapterState: Entering PendingCommandState
08-22 11:15:19.659  2737  2776 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-22 11:15:19.660  2737  2781 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:19.660  2737  2856 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 11:15:19.660  2737  2856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:19.662  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:19.662  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:19.663  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.663  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:19.669  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:19.669  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:19.669  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.669  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:19.670  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.671  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:19.674   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:19.695   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:19.696   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-22 11:15:19.696   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:19.700   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:19.700   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:19.702   875  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 11:15:19.702  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:19.702  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:19.702  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:19.703  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:19.704  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:19.704  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:19.705  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:19.705  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:19.706  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.707  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:19.708  2000  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:19.721  3987  3987 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-22 11:15:19.730  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:19.735   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75be1ec:true
,08-22 11:15:19.737  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:19.749   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-22 11:15:19.749   875  1980 I ActivityManager: Start proc 4007:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-22 11:15:19.757  3987  3987 D LocalBluetoothProfileManager: Adding local MAP profile
,08-22 11:15:19.761  3987  3987 D BluetoothMap: Create BluetoothMap proxy object
,08-22 11:15:19.766  3987  3987 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-22 11:15:19.772  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:19.775   875  1690 I ActivityManager: Killing 2274:com.google.android.talk/u0a61 (adj 15): empty #17
,08-22 11:15:19.824  4007  4007 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-22 11:15:19.869  2737  2781 I bt_hci  : shut_down
,08-22 11:15:19.870  2737  2791 D bt_hwcfg: hw_epilog_process
,08-22 11:15:19.871  2737  2791 I bt_vendor: low_power_mode_cb
,08-22 11:15:19.894  2737  2791 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 11:15:19.895  2737  2791 I bt_vendor: epilog_cb
,08-22 11:15:19.895  2737  2791 I bt_hci  : epilog_finished_callback
,08-22 11:15:19.903  2737  2781 I bt_hci_h4: hal_close
,08-22 11:15:19.904  2737  2781 I bt_userial_vendor: device fd = 51 close
,08-22 11:15:19.961  4007  4007 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.961  4007  4007 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.961  4007  4007 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.961  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.962  4007  4007 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.962  4007  4007 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.k.d(PG:583)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.962  4007  4007 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.962  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.964  4007  4007 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.964  4007  4007 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:19.964  4007  4007 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:19.988   875  1948 I ActivityManager: Start proc 4036:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-22 11:15:19.990   875  1948 I ActivityManager: Killing 3554:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-22 11:15:20.040  3903  3903 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:20.044  2737  2776 D bt_stack_manager: event_shut_down_stack finished.
,08-22 11:15:20.044  2737  2775 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 11:15:20.049  2737  2775 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-22 11:15:20.050  2737  2737 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:20.051  2737  2737 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 11:15:20.051  2737  2737 D BtGatt.GattService: stop()
,08-22 11:15:20.051  2737  2737 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 11:15:20.056  2737  2737 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:20.056  2737  2737 V BluetoothAdapterState: isTurningOn()=false
,08-22 11:15:20.056  2737  2737 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:20.056  2737  2737 V BluetoothAdapterState: isBleTurningOff()=true
08-22 11:15:20.056  2737  2775 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 11:15:20.057  2737  2775 D BluetoothAdapterProperties: Setting state to 10
08-22 11:15:20.057  2737  2775 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-22 11:15:20.060  2737  2775 I BluetoothAdapterState: Entering OffState
,08-22 11:15:20.060   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-22 11:15:20.075  2737  2737 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-22 11:15:20.076  2737  2737 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 11:15:20.076  2737  2776 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-22 11:15:20.076  2737  2737 I BluetoothServiceJni: cleanupNative: return from cleanup
08-22 11:15:20.077  2737  2776 D bt_stack_manager: event_clean_up_stack finished.
,08-22 11:15:20.080  2737  2737 I art     : System.exit called, status: 0
08-22 11:15:20.080  2737  2737 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 11:15:20.090  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-22 11:15:20.145   875  1948 I ActivityManager: Process com.android.bluetooth (pid 2737) has died
,08-22 11:15:20.306  4036  4056 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-22 11:15:20.306  4036  4056 I Babel_SMS: MmsConfig.loadMmsSettings
08-22 11:15:20.308  4036  4056 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-22 11:15:20.308  4036  4056 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 11:15:20.354  4036  4056 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-22 11:15:20.354  4036  4056 I Babel_SMS: MmsConfig.loadFromResources
08-22 11:15:20.355  4036  4056 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-22 11:15:20.356  4036  4056 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-22 11:15:20.384  4036  4036 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:20.386  4036  4036 I Babel_Crash: startup - clean
,08-22 11:15:20.458  4036  4036 I Babel_telephony: TeleModule.launchCompleted
,08-22 11:15:20.464   875  1956 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-22 11:15:20.474  4036  4036 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-22 11:15:20.481  4036  4036 W Babel   : BAM#gBA: invalid account id: -1
,08-22 11:15:20.481  4036  4036 W Babel   : BAM#gBA: invalid account id: -1
08-22 11:15:20.481  4036  4036 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-22 11:15:20.494  4036  4062 I Babel   : deleted: false for 0
,08-22 11:15:20.497   875  1395 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-22 11:15:20.511  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:20.538   875  2016 I ActivityManager: Start proc 4065:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-22 11:15:20.548  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:20.576  4036  4036 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:20.674  4036  4036 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 11:15:20.685  4036  4036 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:20.687  4036  4036 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:20.693  4036  4036 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:20.704  4007  4027 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 11:15:20.714  4036  4036 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:20.725  4036  4036 I vclib   : onServiceConnected
,08-22 11:15:20.747  4065  4065 D AdapterServiceConfig: Adding HeadsetService
08-22 11:15:20.747  4065  4065 D AdapterServiceConfig: Adding A2dpService
08-22 11:15:20.747  4065  4065 D AdapterServiceConfig: Adding HidService
08-22 11:15:20.747  4065  4065 D AdapterServiceConfig: Adding HealthService
,08-22 11:15:20.748  4065  4065 D AdapterServiceConfig: Adding PanService
,08-22 11:15:20.759  4065  4065 D AdapterServiceConfig: Adding GattService
,08-22 11:15:20.759  4065  4065 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 11:15:20.763   875  2016 I ActivityManager: Killing 1692:android.process.acore/u0a5 (adj 15): empty #17
,08-22 11:15:20.857   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@455e677:true
,08-22 11:15:20.909  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:20.957  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 11:15:20.958  1716  2437 I iu.UploadsManager: num queued entries: 0
08-22 11:15:20.958  1716  2437 I iu.UploadsManager: num updated entries: 0
08-22 11:15:20.959  1716  2437 I iu.SyncManager: NEXT; no task
,08-22 11:15:20.970  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 11:15:20.979  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 11:15:21.000   875  3214 I ActivityManager: Start proc 4078:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-22 11:15:21.083  4078  4078 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-22 11:15:21.088  4078  4078 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:21.098  4078  4078 D SprintDMHelper: simOperator: 
08-22 11:15:21.099  4078  4078 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 11:15:21.126   875  1395 I ActivityManager: Start proc 4090:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-22 11:15:21.130   875  1395 I ActivityManager: Killing 3756:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-22 11:15:21.299   875  1948 I ActivityManager: Start proc 4105:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-22 11:15:21.304  4036  4104 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 11:15:21.308   875  1385 I ActivityManager: Killing 3773:com.android.musicfx/u0a18 (adj 15): empty #17
,08-22 11:15:21.392  4105  4105 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-22 11:15:21.456  4105  4105 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 11:15:21.456  4105  4105 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 11:15:21.456  4105  4105 I GAv4    :   adb logcat -s GAv4
,08-22 11:15:21.473  4105  4105 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:21.479  4105  4105 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:21.505  4105  4123 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:21.615  4105  4105 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-22 11:15:21.654  4105  4105 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-22 11:15:21.661  4105  4105 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9220-9222)
,08-22 11:15:21.662  4105  4105 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 11:15:21.674  4105  4105 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ba2572e}
,08-22 11:15:21.674  4105  4105 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 11:15:21.675  4105  4105 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 11:15:21.684  4105  4105 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 11:15:21.686  4105  4105 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 11:15:21.705  4105  4105 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 11:15:21.721  4105  4105 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 11:15:21.721  4105  4105 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 11:15:21.721  4105  4105 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 11:15:21.721  4105  4105 I Adreno  : Build Date                       : 10/20/15
08-22 11:15:21.721  4105  4105 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 11:15:21.721  4105  4105 I Adreno  : Local Branch                     : M14
08-22 11:15:21.721  4105  4105 I Adreno  : Remote Branch                    : 
08-22 11:15:21.721  4105  4105 I Adreno  : Remote Branch                    : 
08-22 11:15:21.721  4105  4105 I Adreno  : Reconstruct Branch               : 
,08-22 11:15:21.779  4105  4152 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-22 11:15:21.795  4105  4105 I NSApplication: Starting up...
,08-22 11:15:21.832   875  1706 I ActivityManager: Start proc 4157:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-22 11:15:21.833   875  1706 I ActivityManager: Killing 2203:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-22 11:15:21.904  4157  4157 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-22 11:15:22.077   875  1979 I ActivityManager: Killing 3795:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-22 11:15:22.102  3640  3650 W art     : Suspending all threads took: 12.603ms
,08-22 11:15:22.594   875  1690 D WifiService: setWifiEnabled: true pid=3903, uid=10000
,08-22 11:15:22.594   875  1690 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 11:15:22.609   875  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-22 11:15:22.616  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:22.616  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:22.616  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:22.617  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:22.620  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:22.621  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:22.621  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:22.621  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:22.641   875  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-22 11:15:22.642   875  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 11:15:22.643   875  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-22 11:15:22.644   875  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-22 11:15:22.644   875  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 11:15:22.644   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-22 11:15:22.644   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 11:15:22.661   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 11:15:22.663   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:22.665   875  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-22 11:15:22.665   875  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 11:15:22.668   875  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-22 11:15:22.668   875  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 11:15:22.675   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:22.698   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:24.244   875  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.67 rxSuccessRate=2.00 delta 1000 -> 1000
,08-22 11:15:24.247   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 11:15:24.247   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:24.264   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 11:15:24.321   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 11:15:24.325  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 11:15:24.747  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 11:15:24.806  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 11:15:24.806  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 11:15:24.811   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:24.821   875  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 11:15:24.822   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-22 11:15:24.822   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:24.844   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:24.853   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:24.854   875  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-22 11:15:24.868   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 11:15:24.868   875  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-22 11:15:24.874   875  4183 D DhcpClient: Receive thread started
,08-22 11:15:24.954   875  1307 E native  : do suspend false
,08-22 11:15:24.969   875  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 11:15:24.985   875  4183 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172680, domain null
,08-22 11:15:24.986   875  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172680 seconds
08-22 11:15:24.989   875  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 11:15:25.001   875  4183 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 11:15:25.002   875  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 11:15:25.008   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:25.020   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 11:15:25.020   875  1877 D DhcpClient: Scheduling renewal in 86399s
,08-22 11:15:25.043   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 11:15:25.047   875  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-22 11:15:25.047   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 11:15:25.049   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 11:15:25.053   875  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-22 11:15:25.056   875  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 11:15:25.108   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 11:15:25.108   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-22 11:15:25.109   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-22 11:15:25.111   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-22 11:15:25.112   875  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-22 11:15:25.119   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 11:15:25.120   875  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-22 11:15:25.124   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-22 11:15:25.125   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-22 11:15:25.125   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-22 11:15:25.125   875  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-22 11:15:25.125   875  1309 D ConnectivityService:    accepting network in place of null
08-22 11:15:25.126   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 11:15:25.126   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 11:15:25.132   875  4182 D NetlinkSocketObserver: NeighborEvent{elapsedMs=142693, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 11:15:25.164   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:25.205   875  4181 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-22 11:15:25.209   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:25.212   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-22 11:15:25.212   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:25.213   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-22 11:15:25.214   875   892 D Tethering: MasterInitialState.processMessage what=3
08-22 11:15:25.218  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:25.218  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:25.218  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.219  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:25.222  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:25.222  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:25.222  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.222  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:25.244  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 11:15:25.246  1716  2437 I iu.UploadsManager: num queued entries: 0
,08-22 11:15:25.246  1716  2437 I iu.UploadsManager: num updated entries: 0
,08-22 11:15:25.247  1716  2437 I iu.SyncManager: NEXT; no task
,08-22 11:15:25.252  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 11:15:25.253  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-22 11:15:25.254  1716  4196 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-22 11:15:25.254  1716  4196 W BaseAppContext: Using Auth Proxy for data requests.
08-22 11:15:25.255  1716  4196 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 11:15:25.255  4078  4078 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:25.259  4078  4078 D SprintDMHelper: simOperator: 
,08-22 11:15:25.259  4078  4078 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 11:15:25.262  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:25.264  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:25.269   875  4181 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 09:15:25 GMT], X-Android-Received-Millis=[1471857325268], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471857325245]}
,08-22 11:15:25.270   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 11:15:25.270   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-22 11:15:25.270   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 11:15:25.271   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 11:15:25.298  1499  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 11:15:25.298  1499  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 11:15:25.298  1499  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 11:15:25.300  1499  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:25.317  1716  4196 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-22 11:15:25.370  4036  4198 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 11:15:25.601   875  1980 D WifiService: setWifiEnabled: false pid=3903, uid=10000
,08-22 11:15:25.601   875  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 11:15:25.626  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-22 11:15:25.634   875  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 11:15:25.634   875  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-22 11:15:25.635   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 11:15:25.635   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:25.664   875  1877 D DhcpClient: Clearing IP address
,08-22 11:15:25.666   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:25.671   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:25.672  1499  4205 V NativeCrypto: Read error: ssl=0x9b513400: I/O error during system call, Connection timed out
,08-22 11:15:25.673   875  4183 D DhcpClient: Receive thread stopped
,08-22 11:15:25.678  1499  4205 V NativeCrypto: SSL shutdown failed: ssl=0x9b513400: I/O error during system call, Broken pipe
,08-22 11:15:25.684   875  1395 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-22 11:15:25.685   875  4181 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-22 11:15:25.686   875  4181 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-22 11:15:25.690   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-22 11:15:25.690   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-22 11:15:25.698   396   396 E Parcel  : Reading a NULL string not supported here.
08-22 11:15:25.700   875  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-22 11:15:25.703   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 11:15:25.709   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:25.710   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-22 11:15:25.712   875  4181 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-22 11:15:25.718   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:25.720  2000  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:25.721   875  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 11:15:25.721  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.721  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:25.721  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.721  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:25.722  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.722  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:25.722  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:25.722  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:25.754   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:25.779   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:25.780   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-22 11:15:25.780   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:25.781   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:25.786  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:25.787  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.798  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 11:15:25.800  1716  2437 I iu.UploadsManager: num queued entries: 0
,08-22 11:15:25.801  1716  2437 I iu.UploadsManager: num updated entries: 0
08-22 11:15:25.802  1716  2437 I iu.SyncManager: NEXT; no task
,08-22 11:15:25.802  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-22 11:15:25.803  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-22 11:15:25.805  4078  4078 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:25.809  4078  4078 D SprintDMHelper: simOperator: 
,08-22 11:15:25.809  4078  4078 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 11:15:25.826  4036  4217 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-22 11:15:25.875   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-22 11:15:25.876   875  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-22 11:15:25.876   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 11:15:25.984   875  1948 I ActivityManager: Killing 3717:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-22 11:15:26.212   875  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-22 11:15:28.640   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d509279:true
,08-22 11:15:28.641  4065  4065 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 11:15:28.646  4065  4065 I bt_bluedroid: init
,08-22 11:15:28.647  4065  4220 I BluetoothAdapterState: Entering OffState
,08-22 11:15:28.649  4065  4221 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 11:15:28.649  4065  4221 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-22 11:15:28.649  4065  4221 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 11:15:28.650  4065  4221 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 11:15:28.650  4065  4065 I bt_bluedroid: get_profile_interface socket
,08-22 11:15:28.654  4065  4065 I bt_bluedroid: get_profile_interface sdp
08-22 11:15:28.657  4065  4224 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-22 11:15:28.658  4065  4076 I bt_bluedroid: config_hci_snoop_log
,08-22 11:15:28.659   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-22 11:15:28.660  4065  4224 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 11:15:28.667  4065  4220 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 11:15:28.667  4065  4220 D BluetoothAdapterProperties: Setting state to 14
,08-22 11:15:28.668  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 11:15:28.672  4065  4220 D BluetoothBondStateMachine: make
,08-22 11:15:28.675  4065  4225 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 11:15:28.681  4065  4220 I BluetoothAdapterState: Entering PendingCommandState
,08-22 11:15:28.682  4065  4065 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 11:15:28.685  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:28.686  4065  4065 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:28.687  4065  4065 D BtGatt.GattService: Received start request. Starting profile...
,08-22 11:15:28.688  4065  4065 D BtGatt.GattService: start()
,08-22 11:15:28.688  4065  4065 I bt_bluedroid: get_profile_interface gatt
,08-22 11:15:28.689  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:28.689  4065  4065 D BtGatt.AdvertiseManager: advertise manager created
,08-22 11:15:28.697  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:28.698  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:28.698  4065  4065 V BluetoothAdapterState: isBleTurningOn()=true
08-22 11:15:28.698  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:28.699  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-22 11:15:28.699  4065  4220 I bt_bluedroid: enable
08-22 11:15:28.700  4065  4221 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-22 11:15:28.700  4065  4221 I bt_hci  : start_up
,08-22 11:15:28.718  4065  4221 I bt_vendor: alloc value 0xb3a29189
,08-22 11:15:28.718  4065  4221 I bt_vendor: init
08-22 11:15:28.718  4065  4221 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-22 11:15:28.719  4065  4221 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 11:15:28.828  4065  4221 D bt_hci  : start_up starting async portion
,08-22 11:15:28.828  4065  4228 I bt_hci  : event_finish_startup
,08-22 11:15:28.829  4065  4228 I bt_hci_h4: hal_open
08-22 11:15:28.829  4065  4228 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 11:15:28.842  4065  4228 I bt_userial_vendor: device fd = 51 open
,08-22 11:15:28.869  4065  4228 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 11:15:28.901  4065  4228 D bt_hwcfg: Chipset BCM4354A2
,08-22 11:15:28.902  4065  4228 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 11:15:28.902  4065  4228 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 11:15:29.564  4065  4228 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 11:15:29.565  4065  4228 D bt_hwcfg: Settlement delay -- 100 ms
08-22 11:15:29.566  4065  4228 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 11:15:29.682  4065  4228 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 11:15:29.684  4065  4228 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 11:15:29.713  4065  4228 I bt_hwcfg: vendor lib fwcfg completed
,08-22 11:15:29.713  4065  4228 I bt_vendor: firmware callback
08-22 11:15:29.713  4065  4228 I bt_hci  : firmware_config_callback
,08-22 11:15:29.724  4065  4230 I bt_btu  : btu_task pending for preload complete event
,08-22 11:15:29.724  4065  4230 I bt_btu_task: Bluetooth chip preload is complete
08-22 11:15:29.725  4065  4230 I bt_btu  : btu_task received preload complete event
,08-22 11:15:29.735  4065  4230 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 11:15:29.735  4065  4230 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 11:15:29.735  4065  4230 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 11:15:29.736  4065  4230 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-22 11:15:29.736  4065  4230 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 11:15:29.736  4065  4230 I         : BTE_InitTraceLevels -- TRC_A2D
,08-22 11:15:29.736  4065  4230 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 11:15:29.737  4065  4230 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 11:15:29.737  4065  4230 I         : BTE_InitTraceLevels -- TRC_GAP
,08-22 11:15:29.737  4065  4230 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 11:15:29.737  4065  4230 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 11:15:29.738  4065  4230 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 11:15:29.738  4065  4230 I         : BTE_InitTraceLevels -- TRC_SMP
,08-22 11:15:29.738  4065  4230 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 11:15:29.738  4065  4230 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 11:15:29.873  4065  4230 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,08-22 11:15:29.874  4065  4230 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,08-22 11:15:29.884  4065  4224 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 11:15:29.886  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 11:15:29.887  4065  4224 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 11:15:29.894  4065  4224 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 11:15:29.898  4065  4224 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:29.899  4065  4224 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:29.902  4065  4224 D bt_hci  : do_postload posting postload work item
,08-22 11:15:29.904  4065  4228 I bt_hci  : event_postload
08-22 11:15:29.905  4065  4228 I bt_vendor: sco_config_cb
,08-22 11:15:29.905  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:29.905  4065  4228 I bt_hci  : sco_config_callback postload finished.
08-22 11:15:29.908  4065  4224 D bt_bte_conf: Device ID record 1 : primary
08-22 11:15:29.910  4065  4224 D bt_bte_conf:   vendorId            = 000f
08-22 11:15:29.910  4065  4224 D bt_bte_conf:   vendorIdSource      = 0001,
08-22 11:15:29.910  4065  4224 D bt_bte_conf:   product             = 1200
08-22 11:15:29.910  4065  4224 D bt_bte_conf:   version             = 1436
,08-22 11:15:29.910  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:29.910  4065  4224 D bt_bte_conf:   clientExecutableURL = 
,08-22 11:15:29.910  4065  4224 D bt_bte_conf:   serviceDescription  = 
08-22 11:15:29.911  4065  4224 D bt_bte_conf:   documentationURL    = 
08-22 11:15:29.911  4065  4224 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-22 11:15:29.911  4065  4221 D bt_stack_manager: event_start_up_stack finished
08-22 11:15:29.912  4065  4228 I bt_vendor: low_power_mode_cb
08-22 11:15:29.912  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-22 11:15:29.912  4065  4220 D BluetoothAdapterProperties: Setting state to 15,
08-22 11:15:29.912  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 11:15:29.913  4065  4220 I BluetoothAdapterState: Entering BleOnState
08-22 11:15:29.917  4065  4220 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-22 11:15:29.917  4065  4220 D BluetoothAdapterProperties: Setting state to 11
08-22 11:15:29.917  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 11:15:29.924  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:29.928  4065  4065 D HeadsetService: Received start request. Starting profile...
,08-22 11:15:29.933  4065  4065 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 11:15:29.933  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:29.933  4065  4065 D HeadsetStateMachine: make
08-22 11:15:29.934  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:29.946  4065  4220 I BluetoothAdapterState: Entering PendingCommandState
,08-22 11:15:29.949  4065  4065 D HeadsetStateMachine: max_hf_connections = 1
,08-22 11:15:29.949  4065  4065 I bt_bluedroid: get_profile_interface handsfree
,08-22 11:15:29.950  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-22 11:15:29.950  4065  4224 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 11:15:29.959  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:29.961  4065  4065 D A2dpService: Received start request. Starting profile...
08-22 11:15:29.962  4065  4065 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 11:15:29.962  4065  4065 I bt_bluedroid: get_profile_interface avrcp
,08-22 11:15:29.974  4065  4065 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 11:15:29.975  4065  4065 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-22 11:15:29.975  4065  4065 D A2dpStateMachine: make
,08-22 11:15:29.978  4065  4065 I bt_bluedroid: get_profile_interface a2dp
,08-22 11:15:29.979  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 11:15:29.983  4065  4239 D A2dpStateMachine: Enter Disconnected: -2
,08-22 11:15:29.983  4065  4065 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 11:15:29.985  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:29.987  3987  3987 D BluetoothInputDevice: Proxy object connected
,08-22 11:15:29.987  3987  3987 D HidProfile: Bluetooth service connected
,08-22 11:15:29.987  4065  4065 D HidService: Received start request. Starting profile...
08-22 11:15:29.987  4065  4065 I bt_bluedroid: get_profile_interface hidhost
08-22 11:15:29.988  4065  4065 D HidService: setHidService(): set to: null
08-22 11:15:29.988  4065  4224 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
08-22 11:15:29.988  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-22 11:15:29.989  4065  4065 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 11:15:29.991  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:29.992  4065  4065 D HealthService: Received start request. Starting profile...
,08-22 11:15:29.994  4065  4065 I bt_bluedroid: get_profile_interface health
,08-22 11:15:29.995  4065  4065 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 11:15:29.996  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:29.998  4065  4065 D PanService: Received start request. Starting profile...
,08-22 11:15:29.998  3987  3987 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 11:15:29.998  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 11:15:29.998  4065  4065 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 11:15:29.998  4065  4065 I bt_bluedroid: get_profile_interface pan
08-22 11:15:29.998  3987  3987 D PanProfile: Bluetooth service connected
,08-22 11:15:29.999  4065  4224 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 11:15:30.003  4065  4065 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
08-22 11:15:30.004  4065  4065 D BluetoothMapService: Received start request. Starting profile...
08-22 11:15:30.004  4065  4065 D BluetoothMapService: start()
,08-22 11:15:30.006  3987  3987 D BluetoothMap: Proxy object connected
08-22 11:15:30.006  3987  3987 D MapProfile: Bluetooth service connected
08-22 11:15:30.006  4065  4065 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 11:15:30.006  3987  3987 D BluetoothMap: getConnectedDevices()
08-22 11:15:30.007  4065  4065 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-22 11:15:30.007  4065  4065 D BluetoothMapAppObserver: createReceiver()
,08-22 11:15:30.007  3987  3987 D BluetoothMap: Bluetooth is Not enabled
08-22 11:15:30.008  4065  4065 D BluetoothMapAppObserver: initObservers()
,08-22 11:15:30.008  4065  4065 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 11:15:30.015  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:30.015  4065  4065 V BluetoothAdapterState: isTurningOn()=true
,08-22 11:15:30.015  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:30.015  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:30.017  4065  4237 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isTurningOn()=true,
,08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:30.018  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:30.019  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:30.021  4065  4065 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:30.021  4065  4065 V BluetoothAdapterState: isTurningOn()=true
,08-22 11:15:30.021  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:30.021  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:30.022  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 11:15:30.022  4065  4220 D BluetoothAdapterProperties: ScanMode =  20
08-22 11:15:30.022  4065  4220 D BluetoothAdapterProperties: State =  11
,08-22 11:15:30.022  4065  4220 D BluetoothAdapterProperties: Setting state to 12
08-22 11:15:30.022  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 11:15:30.023  4065  4220 I BluetoothAdapterState: Entering OnState
08-22 11:15:30.023  3987  4000 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 11:15:30.023  1352  2056 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 11:15:30.024  1928  2090 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 11:15:30.025  1352  1366 D BluetoothMap: onBluetoothStateChange: up=true
08-22 11:15:30.026  4065  4224 D BluetoothAdapterProperties: Scan Mode:21
08-22 11:15:30.027  4065  4224 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 11:15:30.028   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 11:15:30.028   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:30.028  1352  1352 D BluetoothMap: Proxy object connected
08-22 11:15:30.028  1352  1352 D MapProfile: Bluetooth service connected
08-22 11:15:30.028  1352  1352 D BluetoothMap: getConnectedDevices()
08-22 11:15:30.029  3987  3998 D BluetoothPan: onBluetoothStateChange on: true
08-22 11:15:30.029  3987  4000 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:30.030  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:30.031  1352  1709 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 11:15:30.033  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:30.034  4065  4065 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 11:15:30.035  4065  4065 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-22 11:15:30.037   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:30.037  1352  2056 D BluetoothPan: onBluetoothStateChange on: true
08-22 11:15:30.037  4065  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:30.039  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:30.039  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:30.039  1352  1352 D PanProfile: Bluetooth service connected
,08-22 11:15:30.040  1352  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:30.041  4065  4065 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:30.041  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:30.042  3987  3998 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:30.042  1352  1709 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 11:15:30.042  4065  4065 D ObexServerSockets: Succeed to create listening sockets 
08-22 11:15:30.043  4065  4065 D ObexServerSockets0: startAccept()
08-22 11:15:30.043  4065  4065 D ObexServerSockets0: prepareForNewConnect()
,08-22 11:15:30.044  1352  1352 D BluetoothInputDevice: Proxy object connected
,08-22 11:15:30.044  1352  1352 D HidProfile: Bluetooth service connected
08-22 11:15:30.044   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:30.047   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 11:15:30.048  4065  4065 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-22 11:15:30.048  4065  4065 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-22 11:15:30.050  1352  1352 D BluetoothA2dp: Proxy object connected
08-22 11:15:30.050  4065  4245 D ObexServerSockets0: Accepting socket connection...
08-22 11:15:30.050  4065  4065 D BluetoothMapService: onReceive
08-22 11:15:30.050   875   875 D BluetoothA2dp: Proxy object connected
08-22 11:15:30.050  4065  4065 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:30.050  4065  4065 D BluetoothMapService: STATE_ON
08-22 11:15:30.050  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:30.051  4065  4246 D ObexServerSockets0: Accepting socket connection...
08-22 11:15:30.052  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:30.055  3987  3987 D LocalBluetoothProfileManager: Adding local A2DP profile
08-22 11:15:30.059  3987  3987 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-22 11:15:30.067  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:30.071  4065  4065 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 11:15:30.071  4065  4065 D ObexServerSockets0: prepareForNewConnect()
08-22 11:15:30.071  3987  3987 D BluetoothA2dp: Proxy object connected
,08-22 11:15:30.076  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:30.079  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:30.084  1352  1352 D BluetoothPbap: Proxy object connected
,08-22 11:15:30.084  1352  1352 D PbapServerProfile: Bluetooth service connected
08-22 11:15:30.084  3987  3987 D BluetoothPbap: Proxy object connected
08-22 11:15:30.084  3987  3987 D PbapServerProfile: Bluetooth service connected
,08-22 11:15:30.092  4065  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:30.107  4065  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:30.109  4065  4255 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:30.125  1928  1945 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.125   875   875 D BluetoothHeadset: Proxy object connected
,08-22 11:15:30.126  1352  1709 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.126  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:30.126   875   875 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.126   875   875 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.128   875   892 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.128   875   892 D BluetoothHeadset: Proxy object connected
,08-22 11:15:30.137   875   892 D BluetoothHeadset: Proxy object connected
,08-22 11:15:30.162  3987  4000 D BluetoothHeadset: Proxy object connected
08-22 11:15:30.163  3987  3987 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:31.619  4065  4220 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 11:15:31.620  4065  4220 D BluetoothAdapterProperties: Setting state to 13
,08-22 11:15:31.620  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 11:15:31.622  4065  4220 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 11:15:31.624  4065  4220 I BluetoothAdapterState: Entering PendingCommandState
08-22 11:15:31.633  4065  4065 D BluetoothMapService: onReceive
08-22 11:15:31.633  4065  4065 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:31.634  4065  4065 D BluetoothMapService: STATE_TURNING_OFF
,08-22 11:15:31.635  4065  4065 D BluetoothMapService: MAP Service closeService in
08-22 11:15:31.635  4065  4065 D BluetoothMapMasInstance0: MAP Service shutdown
,08-22 11:15:31.636  4065  4065 D ObexServerSockets0: shutdown(block = true)
08-22 11:15:31.638  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:31.639  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:31.641  4065  4224 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:31.641  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:31.642  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:31.642  4065  4245 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-22 11:15:31.642  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-22 11:15:31.643  4065  4065 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 11:15:31.644  4065  4246 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 11:15:31.644  4065  4232 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 11:15:31.645  4065  4065 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 11:15:31.645  4065  4065 I BtOppRfcommListener: stopping Accept Thread
,08-22 11:15:31.646  4065  4255 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 11:15:31.647  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:31.647  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:31.648  3903  3903 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:31.648  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:31.649  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:31.651  4065  4255 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 11:15:31.651  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:31.653  4065  4065 D HeadsetService: Received stop request...Stopping profile...
08-22 11:15:31.655  1928  1946 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:31.655   875   875 D BluetoothHeadset: Proxy object disconnected
,08-22 11:15:31.655  4065  4065 D A2dpService: Received stop request...Stopping profile...
08-22 11:15:31.656  4065  4239 D A2dpStateMachine: Exit Disconnected: -1
08-22 11:15:31.656  1352  1709 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:31.656  1352  1352 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:31.657  1352  1352 D BluetoothA2dp: Proxy object disconnected
,08-22 11:15:31.658  3987  3998 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:31.658   875   875 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:31.658   875   875 D BluetoothHeadset: Proxy object disconnected
08-22 11:15:31.658   875   875 D BluetoothA2dp: Proxy object disconnected
,08-22 11:15:31.658  4065  4065 D HidService: Received stop request...Stopping profile...
08-22 11:15:31.658  4065  4065 D HidService: Stopping Bluetooth HidService
08-22 11:15:31.660  4065  4065 D HealthService: Received stop request...Stopping profile...
,08-22 11:15:31.661  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:31.661  1352  1352 D HidProfile: Bluetooth service disconnected
08-22 11:15:31.661  4065  4065 D PanService: Received stop request...Stopping profile...
,08-22 11:15:31.662  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 11:15:31.662  1352  1352 D PanProfile: Bluetooth service disconnected
,08-22 11:15:31.664  4065  4065 D BluetoothMapService: Received stop request...Stopping profile...
08-22 11:15:31.664  4065  4065 D BluetoothMapService: stop()
,08-22 11:15:31.664  4065  4065 D BluetoothMapAppObserver: deinitObservers()
08-22 11:15:31.665  4065  4065 D BluetoothMapAppObserver: removeReceiver()
,08-22 11:15:31.666  1352  1352 D BluetoothMap: Proxy object disconnected
,08-22 11:15:31.666  4065  4065 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:31.666  1352  1352 D MapProfile: Bluetooth service disconnected
08-22 11:15:31.666  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:31.666  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:31.666  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:31.668  4065  4065 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 11:15:31.668  4065  4065 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 11:15:31.668  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 11:15:31.668  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:31.668  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:31.668  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-22 11:15:31.668  4065  4065 V BluetoothAdapterState: isTurningOff()=true
,08-22 11:15:31.669  4065  4065 V BluetoothAdapterState: isTurningOn()=false
,08-22 11:15:31.669  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:31.669  4065  4224 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-22 11:15:31.669  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:31.669  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 11:15:31.670  4065  4065 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:31.670  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:31.670  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:31.671  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:31.671  4065  4065 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 11:15:31.671  4065  4065 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:31.671  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 11:15:31.671  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:31.671  4065  4065 V BluetoothAdapterState: isTurningOff()=true
,08-22 11:15:31.671  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 11:15:31.671  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:31.671  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:31.671  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:31.671  4065  4230 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:31.671  4065  4230 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-22 11:15:31.672  4065  4230 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:31.672  4065  4065 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:31.672  4065  4230 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:31.672  4065  4065 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 11:15:31.672  4065  4224 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 11:15:31.672  4065  4065 V BluetoothAdapterState: isTurningOff()=true
,08-22 11:15:31.672  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:31.672  4065  4224 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 11:15:31.672  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:31.672  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:31.673  4065  4065 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:31.673  4065  4065 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 11:15:31.675  4065  4065 D BluetoothMapService: MAP Service closeService in
,08-22 11:15:31.675  4065  4065 V BluetoothAdapterState: isTurningOff()=true
08-22 11:15:31.675  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:31.675  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:31.675  4065  4065 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:31.676  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 11:15:31.676  4065  4220 D BluetoothAdapterProperties: Setting state to 15
,08-22 11:15:31.676  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 11:15:31.677  4065  4220 I BluetoothAdapterState: Entering BleOnState
08-22 11:15:31.677  3987  4261 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 11:15:31.677  4065  4065 D BluetoothMapService: cleanup()
08-22 11:15:31.677  4065  4065 D BluetoothMapService: MAP Service closeService in
08-22 11:15:31.678  3987  3998 D BluetoothMap: onBluetoothStateChange: up=false
08-22 11:15:31.679  1352  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 11:15:31.679  1928  2311 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:31.680  3987  4000 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:31.681  1352  2056 D BluetoothMap: onBluetoothStateChange: up=false
08-22 11:15:31.681  3987  3987 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:31.682   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:31.682   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 11:15:31.683  3987  4261 D BluetoothPan: onBluetoothStateChange on: false
08-22 11:15:31.684  3987  3987 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:31.684  3987  4000 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 11:15:31.684  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 11:15:31.684  3987  3987 D HidProfile: Bluetooth service disconnected
,08-22 11:15:31.686  1352  1709 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 11:15:31.687   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 11:15:31.687  1352  1365 D BluetoothPan: onBluetoothStateChange on: false
08-22 11:15:31.688  1352  2056 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 11:15:31.688  3987  3998 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:31.692  1352  1366 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:31.693  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:31.694   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:31.695  4065  4220 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-22 11:15:31.695  4065  4220 D BluetoothAdapterProperties: Setting state to 16
08-22 11:15:31.695  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 11:15:31.696  4065  4220 D BluetoothAdapterProperties: onBleDisable
08-22 11:15:31.696  4065  4220 I BluetoothAdapterState: Entering PendingCommandState
,08-22 11:15:31.696  4065  4221 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 11:15:31.696  4065  4230 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 11:15:31.697  4065  4230 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 11:15:31.701  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.702  4065  4224 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:31.703  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.703  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:31.704  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:31.705  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:31.708  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:31.709  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:31.897  4065  4224 I bt_hci  : shut_down
,08-22 11:15:31.898  4065  4228 D bt_hwcfg: hw_epilog_process
,08-22 11:15:31.908  4065  4228 I bt_vendor: low_power_mode_cb
,08-22 11:15:31.931  4065  4228 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 11:15:31.931  4065  4228 I bt_vendor: epilog_cb
08-22 11:15:31.931  4065  4228 I bt_hci  : epilog_finished_callback
,08-22 11:15:31.940  4065  4224 I bt_hci_h4: hal_close
,08-22 11:15:31.942  4065  4224 I bt_userial_vendor: device fd = 51 close
,08-22 11:15:32.070  4065  4221 D bt_stack_manager: event_shut_down_stack finished.
,08-22 11:15:32.071  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 11:15:32.078  4065  4220 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-22 11:15:32.078  4065  4065 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:32.080  4065  4065 D BtGatt.GattService: Received stop request...Stopping profile...
,08-22 11:15:32.080  4065  4065 D BtGatt.GattService: stop()
08-22 11:15:32.080  4065  4065 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 11:15:32.086  4065  4065 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:32.087  4065  4065 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:32.087  4065  4065 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:32.087  4065  4065 V BluetoothAdapterState: isBleTurningOff()=true
08-22 11:15:32.088  4065  4220 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 11:15:32.089  4065  4220 D BluetoothAdapterProperties: Setting state to 10
,08-22 11:15:32.089  4065  4220 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-22 11:15:32.091  4065  4220 I BluetoothAdapterState: Entering OffState
08-22 11:15:32.093   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-22 11:15:32.125  4065  4065 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-22 11:15:32.126  4065  4065 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 11:15:32.126  4065  4221 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 11:15:32.134  4065  4221 D bt_stack_manager: event_clean_up_stack finished.
,08-22 11:15:32.134  4065  4065 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 11:15:32.140  4065  4065 I art     : System.exit called, status: 0
,08-22 11:15:32.140  4065  4065 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 11:15:32.216   875  1690 I ActivityManager: Process com.android.bluetooth (pid 4065) has died
,08-22 11:15:32.740   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-22 11:15:32.748  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-22 11:15:32.767   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 11:15:32.767   875   895 I Adreno  : Build Date                       : 10/20/15
08-22 11:15:32.767   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 11:15:32.767   875   895 I Adreno  : Local Branch                     : M14
08-22 11:15:32.767   875   895 I Adreno  : Remote Branch                    : 
08-22 11:15:32.767   875   895 I Adreno  : Remote Branch                    : 
08-22 11:15:32.767   875   895 I Adreno  : Reconstruct Branch               : 
,08-22 11:15:32.807   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (315 us)
,08-22 11:15:33.132   875  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-22 11:15:33.506  3903  3903 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 11:15:33.506  3903  3903 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 11:15:33.543   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-22 11:15:33.544  3903  3903 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@799ef40 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@83e0c8a, 16908290=android.view.AbsSavedState$1@83e0c8a}, android:focusedViewId=100}]}]
,08-22 11:15:33.544  3903  3903 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-22 11:15:33.545  3903  3903 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 11:15:33.545  3903  3903 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 11:15:33.566   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-22 11:15:33.571   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-22 11:15:33.572   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-22 11:15:33.572   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-22 11:15:33.829   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-22 11:15:33.832   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-22 11:15:33.833   875  1334 D SurfaceControl: Excessive delay in setPowerMode(): 262ms
08-22 11:15:33.838   875   895 I DreamManagerService: Entering dreamland.
08-22 11:15:33.839   875   895 I PowerManagerService: Dozing...
,08-22 11:15:33.840   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-22 11:15:33.886   377  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-22 11:15:33.886   377  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-22 11:15:33.904   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:33.907   875  1307 E native  : do suspend false
,08-22 11:15:33.910  1920  4273 D NfcService: Discovery configuration equal, not updating.
,08-22 11:15:33.941   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:33.944   875  1307 E native  : do suspend true
,08-22 11:15:34.030   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-22 11:15:34.030   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-22 11:15:34.619  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:34.619  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:37.628  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:37.628  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f992fb added. We now have 6 listener(s)
08-22 11:15:37.628  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:37.632  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:37.633  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2e3f18 added. We now have 7 listener(s)
08-22 11:15:37.633  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:37.634  3903  3951 I System.out: IsBluetoothEnabled
,08-22 11:15:37.646  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:37.694   875   892 I ActivityManager: Start proc 4279:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 11:15:37.852  4279  4279 D AdapterServiceConfig: Adding HeadsetService
,08-22 11:15:37.852  4279  4279 D AdapterServiceConfig: Adding A2dpService
08-22 11:15:37.853  4279  4279 D AdapterServiceConfig: Adding HidService
08-22 11:15:37.853  4279  4279 D AdapterServiceConfig: Adding HealthService
,08-22 11:15:37.853  4279  4279 D AdapterServiceConfig: Adding PanService
08-22 11:15:37.853  4279  4279 D AdapterServiceConfig: Adding GattService
08-22 11:15:37.853  4279  4279 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 11:15:37.868   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f86756:true
08-22 11:15:37.869  4279  4279 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 11:15:37.875  4279  4279 I bt_bluedroid: init
,08-22 11:15:37.875  4279  4291 I BluetoothAdapterState: Entering OffState
,08-22 11:15:37.880  4279  4292 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 11:15:37.880  4279  4292 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 11:15:37.881  4279  4292 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 11:15:37.881  4279  4292 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 11:15:37.883  4279  4279 I bt_bluedroid: get_profile_interface socket
,08-22 11:15:37.884  4279  4279 I bt_bluedroid: get_profile_interface sdp
08-22 11:15:37.886  4279  4295 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-22 11:15:37.888  4279  4295 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 11:15:37.890  4279  4290 I bt_bluedroid: config_hci_snoop_log
,08-22 11:15:37.894   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 11:15:37.902  4279  4291 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 11:15:37.902  4279  4291 D BluetoothAdapterProperties: Setting state to 14
,08-22 11:15:37.903  4279  4291 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 11:15:37.909  4279  4291 D BluetoothBondStateMachine: make
,08-22 11:15:37.915  4279  4296 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 11:15:37.922  4279  4291 I BluetoothAdapterState: Entering PendingCommandState
,08-22 11:15:37.923  4279  4279 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 11:15:37.928  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:37.929  4279  4279 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:37.930  4279  4279 D BtGatt.GattService: Received start request. Starting profile...
,08-22 11:15:37.930  4279  4279 D BtGatt.GattService: start()
,08-22 11:15:37.930  4279  4279 I bt_bluedroid: get_profile_interface gatt
08-22 11:15:37.931  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
08-22 11:15:37.931  4279  4279 D BtGatt.AdvertiseManager: advertise manager created
,08-22 11:15:37.941  4279  4279 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:37.941  4279  4279 V BluetoothAdapterState: isTurningOn()=false
08-22 11:15:37.941  4279  4279 V BluetoothAdapterState: isBleTurningOn()=true
08-22 11:15:37.941  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:37.941  4279  4291 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-22 11:15:37.942  4279  4291 I bt_bluedroid: enable
,08-22 11:15:37.942  4279  4292 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-22 11:15:37.943  4279  4292 I bt_hci  : start_up
,08-22 11:15:37.962  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:37.963  4279  4292 I bt_vendor: alloc value 0xb3a86189
08-22 11:15:37.964  4279  4292 I bt_vendor: init
,08-22 11:15:37.964  4279  4292 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 11:15:37.964  4279  4292 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 11:15:37.968  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:37.969  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 11:15:37.989  1499  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-22 11:15:37.989  1499  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-22 11:15:37.990  1499  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 11:15:37.990  1499  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:38.005  3600  3600 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-22 11:15:38.005  3600  3600 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-22 11:15:38.005  3600  3600 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-22 11:15:38.073  4279  4292 D bt_hci  : start_up starting async portion
08-22 11:15:38.073  4279  4299 I bt_hci  : event_finish_startup
,08-22 11:15:38.074  4279  4299 I bt_hci_h4: hal_open
08-22 11:15:38.074  4279  4299 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 11:15:38.079  4279  4299 I bt_userial_vendor: device fd = 51 open
,08-22 11:15:38.115  4279  4299 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 11:15:38.148  4279  4299 D bt_hwcfg: Chipset BCM4354A2
,08-22 11:15:38.148  4279  4299 D bt_hwcfg: Target name = [BCM4354A2]
08-22 11:15:38.149  4279  4299 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 11:15:38.807  4279  4299 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-22 11:15:38.809  4279  4299 D bt_hwcfg: Settlement delay -- 100 ms
08-22 11:15:38.809  4279  4299 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 11:15:38.926  4279  4299 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 11:15:38.927  4279  4299 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 11:15:38.956  4279  4299 I bt_hwcfg: vendor lib fwcfg completed
,08-22 11:15:38.956  4279  4299 I bt_vendor: firmware callback
,08-22 11:15:38.956  4279  4299 I bt_hci  : firmware_config_callback
,08-22 11:15:38.968  4279  4302 I bt_btu  : btu_task pending for preload complete event
,08-22 11:15:38.969  4279  4302 I bt_btu_task: Bluetooth chip preload is complete
08-22 11:15:38.969  4279  4302 I bt_btu  : btu_task received preload complete event
,08-22 11:15:38.980  4279  4302 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 11:15:38.980  4279  4302 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 11:15:38.980  4279  4302 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 11:15:38.981  4279  4302 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 11:15:38.981  4279  4302 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 11:15:38.981  4279  4302 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 11:15:38.981  4279  4302 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 11:15:38.982  4279  4302 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 11:15:38.982  4279  4302 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 11:15:38.982  4279  4302 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 11:15:38.982  4279  4302 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 11:15:38.983  4279  4302 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 11:15:38.983  4279  4302 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 11:15:38.983  4279  4302 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 11:15:38.983  4279  4302 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 11:15:39.120  4279  4302 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a03d9d
,08-22 11:15:39.121  4279  4302 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a03d9d 
,08-22 11:15:39.134  4279  4295 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 11:15:39.139  4279  4295 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 11:15:39.141  2000  2678 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-22 11:15:39.141  4279  4295 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 11:15:39.147  4279  4295 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 11:15:39.153  4279  4295 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:39.153  4279  4295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 11:15:39.154  4279  4295 D bt_hci  : do_postload posting postload work item
08-22 11:15:39.154  4279  4299 I bt_hci  : event_postload
,08-22 11:15:39.155  4279  4299 I bt_vendor: sco_config_cb
08-22 11:15:39.155  4279  4299 I bt_hci  : sco_config_callback postload finished.
08-22 11:15:39.155  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:39.158  4279  4295 D bt_bte_conf: Device ID record 1 : primary
08-22 11:15:39.159  4279  4299 I bt_vendor: low_power_mode_cb
08-22 11:15:39.159  4279  4295 D bt_bte_conf:   vendorId            = 000f
08-22 11:15:39.159  4279  4295 D bt_bte_conf:   vendorIdSource      = 0001
08-22 11:15:39.159  4279  4295 D bt_bte_conf:   product             = 1200
08-22 11:15:39.159  4279  4295 D bt_bte_conf:   version             = 1436
,08-22 11:15:39.159  4279  4295 D bt_bte_conf:   clientExecutableURL = 
08-22 11:15:39.160  4279  4295 D bt_bte_conf:   serviceDescription  = 
08-22 11:15:39.160  4279  4295 D bt_bte_conf:   documentationURL    = 
08-22 11:15:39.160  4279  4295 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-22 11:15:39.160  4279  4292 D bt_stack_manager: event_start_up_stack finished
08-22 11:15:39.161  4279  4291 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 11:15:39.162  4279  4291 D BluetoothAdapterProperties: Setting state to 15
08-22 11:15:39.162  4279  4291 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 11:15:39.164  4279  4291 I BluetoothAdapterState: Entering BleOnState
,08-22 11:15:39.167  4279  4291 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-22 11:15:39.167  4279  4291 D BluetoothAdapterProperties: Setting state to 11
08-22 11:15:39.168  4279  4291 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 11:15:39.174  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:39.178  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:39.178  4279  4279 D HeadsetService: Received start request. Starting profile...
,08-22 11:15:39.181  4279  4279 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 11:15:39.181  4279  4279 D HeadsetStateMachine: make
,08-22 11:15:39.189  4279  4291 I BluetoothAdapterState: Entering PendingCommandState
,08-22 11:15:39.190  4279  4279 D HeadsetStateMachine: max_hf_connections = 1
,08-22 11:15:39.191  4279  4279 I bt_bluedroid: get_profile_interface handsfree
,08-22 11:15:39.191  4279  4295 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 11:15:39.191  4279  4295 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 11:15:39.196  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:39.197  4279  4279 D A2dpService: Received start request. Starting profile...
,08-22 11:15:39.198  4279  4279 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 11:15:39.198  4279  4279 I bt_bluedroid: get_profile_interface avrcp
,08-22 11:15:39.204  4279  4279 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 11:15:39.204  4279  4279 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 11:15:39.205  4279  4279 D A2dpStateMachine: make
,08-22 11:15:39.206  4279  4279 I bt_bluedroid: get_profile_interface a2dp
,08-22 11:15:39.207  4279  4295 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 11:15:39.209  4279  4311 D A2dpStateMachine: Enter Disconnected: -2
,08-22 11:15:39.210  4279  4279 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 11:15:39.211  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:39.212  4279  4279 D HidService: Received start request. Starting profile...
,08-22 11:15:39.213  4279  4279 I bt_bluedroid: get_profile_interface hidhost
08-22 11:15:39.213  4279  4279 D HidService: setHidService(): set to: null
08-22 11:15:39.213  4279  4279 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 11:15:39.214  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
08-22 11:15:39.214  4279  4295 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e53e5
08-22 11:15:39.215  4279  4295 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-22 11:15:39.215  4279  4279 D HealthService: Received start request. Starting profile...
,08-22 11:15:39.217  4279  4279 I bt_bluedroid: get_profile_interface health
,08-22 11:15:39.218  4279  4279 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 11:15:39.219  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
08-22 11:15:39.219  4279  4279 D PanService: Received start request. Starting profile...
,08-22 11:15:39.220  4279  4279 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-22 11:15:39.220  4279  4279 I bt_bluedroid: get_profile_interface pan
08-22 11:15:39.220  4279  4295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 11:15:39.226  4279  4279 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
08-22 11:15:39.227  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:39.229  4279  4279 D BluetoothMapService: Received start request. Starting profile...
08-22 11:15:39.229  4279  4279 D BluetoothMapService: start()
,08-22 11:15:39.233  4279  4279 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 11:15:39.235  4279  4279 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-22 11:15:39.235  4279  4279 D BluetoothMapAppObserver: createReceiver()
,08-22 11:15:39.237  4279  4279 D BluetoothMapAppObserver: initObservers()
,08-22 11:15:39.237  4279  4279 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 11:15:39.245  4279  4279 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:39.245  4279  4279 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:39.245  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:39.245  4279  4309 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 11:15:39.245  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:39.247  4279  4279 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:39.248  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isTurningOff()=false
08-22 11:15:39.249  4279  4279 V BluetoothAdapterState: isTurningOn()=true
08-22 11:15:39.250  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:39.250  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 11:15:39.251  4279  4279 V BluetoothAdapterState: isTurningOff()=false
,08-22 11:15:39.252  4279  4279 V BluetoothAdapterState: isTurningOn()=true
,08-22 11:15:39.252  4279  4279 V BluetoothAdapterState: isBleTurningOn()=false
08-22 11:15:39.252  4279  4279 V BluetoothAdapterState: isBleTurningOff()=false
08-22 11:15:39.253  4279  4291 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 11:15:39.253  4279  4291 D BluetoothAdapterProperties: ScanMode =  20
,08-22 11:15:39.253  4279  4291 D BluetoothAdapterProperties: State =  11
,08-22 11:15:39.258  4279  4295 D BluetoothAdapterProperties: Scan Mode:21
,08-22 11:15:39.258  4279  4291 D BluetoothAdapterProperties: Setting state to 12
08-22 11:15:39.259  4279  4291 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 11:15:39.259  4279  4295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:39.259  4279  4291 I BluetoothAdapterState: Entering OnState
08-22 11:15:39.259  3987  4261 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:39.261  3987  4000 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 11:15:39.264  1352  1709 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:39.265  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:39.265  1928  1946 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:39.265  3987  3987 D BluetoothA2dp: Proxy object connected
08-22 11:15:39.266  3987  4261 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:39.266  1352  2056 D BluetoothMap: onBluetoothStateChange: up=true
08-22 11:15:39.267  4279  4279 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 11:15:39.267  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:39.268   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 11:15:39.268   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 11:15:39.268  1352  1352 D BluetoothMap: Proxy object connected
,08-22 11:15:39.269  3987  3998 D BluetoothPan: onBluetoothStateChange on: true
,08-22 11:15:39.269  1352  1352 D MapProfile: Bluetooth service connected
08-22 11:15:39.269  1352  1352 D BluetoothMap: getConnectedDevices()
08-22 11:15:39.269  4279  4279 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-22 11:15:39.271  3987  4000 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 11:15:39.272  1352  1365 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 11:15:39.273  4279  4279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:39.274   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 11:15:39.275  1352  4268 D BluetoothPan: onBluetoothStateChange on: true
,08-22 11:15:39.276  1352  1709 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:39.278  1352  1352 D BluetoothA2dp: Proxy object connected
,08-22 11:15:39.278  3987  4269 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:39.279  4279  4279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:39.280  4279  4279 D ObexServerSockets: Succeed to create listening sockets 
08-22 11:15:39.280  4279  4279 D ObexServerSockets0: startAccept()
,08-22 11:15:39.281  3987  3987 D BluetoothMap: Proxy object connected
,08-22 11:15:39.280  4279  4279 D ObexServerSockets0: prepareForNewConnect()
08-22 11:15:39.281  3987  3987 D MapProfile: Bluetooth service connected
08-22 11:15:39.281  3987  3987 D BluetoothMap: getConnectedDevices()
08-22 11:15:39.282  1352  1366 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:39.285  4279  4279 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-22 11:15:39.285  4279  4279 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 11:15:39.286  4279  4316 D ObexServerSockets0: Accepting socket connection...
08-22 11:15:39.286   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:39.287  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:39.287  1352  1352 D PanProfile: Bluetooth service connected
,08-22 11:15:39.288   875   875 D BluetoothA2dp: Proxy object connected
08-22 11:15:39.288  4279  4317 D ObexServerSockets0: Accepting socket connection...
,08-22 11:15:39.288  3987  3987 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 11:15:39.289  3987  3987 D PanProfile: Bluetooth service connected
08-22 11:15:39.290  1352  1352 D BluetoothInputDevice: Proxy object connected
08-22 11:15:39.290  1352  1352 D HidProfile: Bluetooth service connected
08-22 11:15:39.290  3987  3987 D BluetoothInputDevice: Proxy object connected
08-22 11:15:39.290  3987  3987 D HidProfile: Bluetooth service connected
,08-22 11:15:39.295   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 11:15:39.296  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:39.296  4279  4279 D BluetoothMapService: onReceive
08-22 11:15:39.296  4279  4279 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:39.296  4279  4279 D BluetoothMapService: STATE_ON
,08-22 11:15:39.302  3987  3987 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:39.307  3987  3987 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:39.308  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:39.316  3987  3987 D BluetoothPbap: Proxy object connected
,08-22 11:15:39.316  3987  3987 D PbapServerProfile: Bluetooth service connected
,08-22 11:15:39.320  1352  1352 D BluetoothPbap: Proxy object connected
,08-22 11:15:39.320  1352  1352 D PbapServerProfile: Bluetooth service connected
,08-22 11:15:39.323  4279  4279 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 11:15:39.323  4279  4279 D ObexServerSockets0: prepareForNewConnect()
,08-22 11:15:39.325  4279  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:39.348  4279  4326 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:39.349  4279  4326 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:39.367  1928  2311 D BluetoothHeadset: Proxy object connected
,08-22 11:15:39.368   875   875 D BluetoothHeadset: Proxy object connected
,08-22 11:15:39.368  1352  4268 D BluetoothHeadset: Proxy object connected
08-22 11:15:39.368   875   892 D BluetoothHeadset: Proxy object connected
08-22 11:15:39.368   875   892 D BluetoothHeadset: Proxy object connected
,08-22 11:15:39.368  1352  1352 D HeadsetProfile: Bluetooth service connected
08-22 11:15:39.368  3987  3998 D BluetoothHeadset: Proxy object connected
08-22 11:15:39.369   875   875 D BluetoothHeadset: Proxy object connected
08-22 11:15:39.369   875   875 D BluetoothHeadset: Proxy object connected
08-22 11:15:39.369  3987  3987 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:39.375   875   892 D BluetoothHeadset: Proxy object connected
,08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:39.671  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:39.678  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:39.682  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:39.684  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7a5d71 added. We now have 8 listener(s)
08-22 11:15:39.684  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:39.689   875  1689 D WifiService: setWifiEnabled: false pid=3903, uid=10000
08-22 11:15:39.690   875  1689 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 11:15:39.703  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:39.704   875  1690 D WifiService: setWifiEnabled: true pid=3903, uid=10000
,08-22 11:15:39.704   875  1690 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 11:15:39.727   875  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:39.737  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:39.743  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:39.754   875  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-22 11:15:39.755   875  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 11:15:39.756   875  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 11:15:39.756   875  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 11:15:39.757   875  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 11:15:39.757   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-22 11:15:39.757   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 11:15:39.770   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-22 11:15:39.771   875  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.05 rxSuccessRate=1.19 delta 1000 -> 1000
08-22 11:15:39.771   373   873 D CommandListener: Setting iface cfg
08-22 11:15:39.771   875  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-22 11:15:39.772   875  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-22 11:15:39.772   875  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 11:15:39.775   875  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 11:15:39.776   875  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 11:15:39.833   875  1307 E native  : do suspend true
,08-22 11:15:39.880   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 11:15:39.881   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:39.890   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 11:15:39.945   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 11:15:39.950  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 11:15:40.392  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 11:15:40.442  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 11:15:40.443  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 11:15:40.448   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 11:15:40.469   875  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-22 11:15:40.469   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:40.470   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-22 11:15:40.502   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:40.527   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:40.529   875  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-22 11:15:40.544   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 11:15:40.560   875  4335 D DhcpClient: Receive thread started
,08-22 11:15:40.647   875  1307 E native  : do suspend false
,08-22 11:15:40.666   875  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 11:15:40.679   875  4335 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172784, domain null
,08-22 11:15:40.680   875  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172784 seconds
,08-22 11:15:40.684   875  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 11:15:40.704   875  4335 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 11:15:40.705   875  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 11:15:40.710   373   873 D CommandListener: Setting iface cfg
,08-22 11:15:40.721   875  1877 D DhcpClient: Scheduling renewal in 86399s
,08-22 11:15:40.727   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 11:15:40.731   875  1307 E native  : do suspend true
,08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:40.731  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:40.738  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:40.750  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 11:15:40.752  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 11:15:40.753   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 11:15:40.758   875  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 11:15:40.759  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@799ef40 Bundle[{}]
,08-22 11:15:40.760   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 11:15:40.761  3903  3951 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:15:40.761  3903  3951 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-22 11:15:40.763  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-22 11:15:40.765  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 11:15:40.766   875  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-22 11:15:40.767  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-22 11:15:40.770  3903  3951 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 11:15:40.775  3903  3951 I System.out: Running OutgoingSocketThread
08-22 11:15:40.776   875  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 11:15:40.777  3903  4337 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 431)
08-22 11:15:40.778  3903  4337 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47467
,08-22 11:15:40.778  3903  4337 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 11:15:40.819   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 11:15:40.820   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-22 11:15:40.821   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-22 11:15:40.823   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-22 11:15:40.824   875  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-22 11:15:40.836   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-22 11:15:40.842   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-22 11:15:40.843   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-22 11:15:40.843   875  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-22 11:15:40.844   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 11:15:40.844   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-22 11:15:40.845   875  1309 D ConnectivityService:    accepting network in place of null
,08-22 11:15:40.847   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 11:15:40.878   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:40.878   875  4334 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158439, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 11:15:40.912   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 11:15:40.917   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-22 11:15:40.917   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:40.921   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-22 11:15:40.924   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:40.951   875  4333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:40.953  3903  3903 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:40.955  3903  3903 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:40.983  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 11:15:40.988  1716  2437 I iu.UploadsManager: num queued entries: 0
,08-22 11:15:40.989  1716  2437 I iu.UploadsManager: num updated entries: 0
,08-22 11:15:40.991  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 11:15:40.993  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 11:15:40.995  4078  4078 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:40.998  1716  4347 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-22 11:15:40.998  1716  4347 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 11:15:41.000  1716  4347 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 11:15:41.000  4078  4078 D SprintDMHelper: simOperator: 
08-22 11:15:41.000  4078  4078 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 11:15:41.009  1716  2437 I iu.SyncManager: NEXT; no task
,08-22 11:15:41.019   875  4333 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 09:15:41 GMT], X-Android-Received-Millis=[1471857341016], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471857340993]}
,08-22 11:15:41.025   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-22 11:15:41.025   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-22 11:15:41.025   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-22 11:15:41.027   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 11:15:41.059  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 11:15:41.059  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 11:15:41.059  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 11:15:41.059  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 11:15:41.077  1716  4347 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-22 11:15:41.108  4036  4349 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 11:15:41.778  3903  3951 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 432)
,08-22 11:15:41.779  3903  3951 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 432)
,08-22 11:15:41.789  3903  3951 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,08-22 11:15:41.791  3903  3951 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-22 11:15:41.791  3903  3951 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-22 11:15:41.797  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:41.798  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f86756 added. We now have 2 listener(s)
,08-22 11:15:41.799  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:41.800  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:41.800  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:41.800  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:41.800  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c463d7 added. We now have 9 listener(s)
,08-22 11:15:41.800  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:41.801  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:41.804  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:41.810  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:41.813  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:41.813  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:41.813  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:41.813  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c865fad added. We now have 3 listener(s)
,08-22 11:15:41.815  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 11:15:41.815  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.815  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:41.816  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:41.816  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ba2e2 added. We now have 10 listener(s)
08-22 11:15:41.816  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:41.816  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:41.816  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:41.816  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:41.817  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:41.817  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:41.817  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:41.817  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:41.817  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f86756 removed from the list
08-22 11:15:41.817  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:41.817  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c463d7 removed from the list
08-22 11:15:41.818  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.822  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.822  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:41.822  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:41.823  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:41.824  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:41.825  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:41.825  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:41.826  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:41.826  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c463d7 not in the list
08-22 11:15:41.826  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:41.826  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:41.828  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:41.828  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:41.828  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:41.828  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ba2e2 removed from the list
08-22 11:15:41.828  3903  39,51 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:41.828  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:41.828  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.828  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-22 11:15:41.828  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c865fad removed from the list
08-22 11:15:41.829  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:41.829  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2016673 added. We now have 2 listener(s)
08-22 11:15:41.831  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:41.831  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.831  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:41.831  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:41.832  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c1d930 added. We now have 9 listener(s)
08-22 11:15:41.832  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:41.832  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 11:15:41.835  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:41.841  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:41.843  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-22 11:15:41.844  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:41.844  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:41.844  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f650b2e added. We now have 3 listener(s)
08-22 11:15:41.847  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.847  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:41.847  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.847  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:41.847  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:41.847  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b01f6cf added. We now have 10 listener(s)
08-22 11:15:41.847  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:41.848  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:41.848  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:41.848  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:41.848  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:41.848  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:41.850  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.853  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 11:15:41.853  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:41.857  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:41.858  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 11:15:41.858  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:41.861  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:41.862  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:41.862  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:41.862  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:41.865  4279  4318 D BtGatt.GattService: registerClient() - UUID=448aa2c4-6282-42ef-9445-b943e15273a1
,08-22 11:15:41.866  4279  4295 D BtGatt.GattService: onClientRegistered() - UUID=448aa2c4-6282-42ef-9445-b943e15273a1, clientIf=5
,08-22 11:15:41.867  3903  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 11:15:41.869  4279  4289 D BtGatt.GattService: start scan with filters
,08-22 11:15:41.873  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:41.873  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:41.873  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-22 11:15:41.873  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:41.873  4279  4298 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:41.876  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:41.876  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:41.877  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:41.878  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:41.879  4279  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b9c09d4
,08-22 11:15:41.882  3903  3951 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 11:15:41.882  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:41.882  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 11:15:41.882  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.882  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 11:15:41.882  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:41.882  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 11:15:41.882  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:41.882  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:41.883  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:41.883  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:41.883  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:41.889  4279  4318 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:41.890  4279  4290 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 11:15:41.891  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 11:15:41.891  4279  4295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 11:15:41.891  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.891  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 11:15:41.891  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 11:15:41.892  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:41.892  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:41.892  4279  4298 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 11:15:41.893  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:41.893  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 11:15:41.893  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:41.893  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:41.896  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:41.898  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:41.898  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:41.899  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:41.905  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:41.906  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:41.906  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:41.907  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:41.907  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.907  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:41.908  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:41.908  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2016673 removed from the list,
,08-22 11:15:41.908  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:41.908  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c1d930 removed from the list
,08-22 11:15:41.909  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 11:15:41.909  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:41.910  4279  4298 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:41.910  4279  4298 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 11:15:41.909  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:41.911  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.916  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.916  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.917  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:41.917  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:41.917  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:41.917  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c1d930 not in the list
08-22 11:15:41.918  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.918  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.919  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:41.919  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:41.919  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:41.919  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b01f6cf removed from the list
08-22 11:15:41.919  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:41.920  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.920  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.920  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:41.920  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f650b2e removed from the list
,08-22 11:15:41.920  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:41.921  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d130eb added. We now have 2 listener(s)
08-22 11:15:41.922  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 11:15:41.922  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.922  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:41.923  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:41.923  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bb9e48 added. We now have 9 listener(s)
08-22 11:15:41.923  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:41.923  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 11:15:41.925  4279  4295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 11:15:41.925  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.926  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:41.931  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:41.932  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.933  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:41.933  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 11:15:41.933  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:41.935  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:41.936  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:41.936  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6975206 added. We now have 3 listener(s)
08-22 11:15:41.937  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.938  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:41.938  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.938  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:41.938  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:41.938  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff0c7 added. We now have 10 listener(s)
,08-22 11:15:41.939  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:41.939  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:41.940  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:41.940  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:41.940  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:41.940  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:41.940  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:41.941  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 11:15:41.941  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.941  4279  4298 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:41.943  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 11:15:41.943  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:41.946  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:41.947  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 11:15:41.947  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 11:15:41.947  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 11:15:41.947  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:41.948  4279  4298 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 11:15:41.950  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:41.950  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:41.950  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:41.951  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:41.952  4279  4308 D BtGatt.GattService: registerClient() - UUID=eebf4f37-74c3-4338-ad6d-004d5a91ef8b
,08-22 11:15:41.953  4279  4295 D BtGatt.GattService: onClientRegistered() - UUID=eebf4f37-74c3-4338-ad6d-004d5a91ef8b, clientIf=5
,08-22 11:15:41.953  3903  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 11:15:41.953  4279  4289 D BtGatt.GattService: start scan with filters
,08-22 11:15:41.954  4279  4295 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 11:15:41.954  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:41.955  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:41.955  4279  4298 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:41.955  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:41.956  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 11:15:41.956  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:41.958  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:41.959  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-22 11:15:41.959  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:41.960  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-22 11:15:41.961  4279  4295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 11:15:41.961  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:41.961  4279  4298 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 11:15:41.962  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 11:15:41.963  3903  3951 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-22 11:15:41.963  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:41.963  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:41.963  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-22 11:15:41.963  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-22 11:15:41.963  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 11:15:41.963  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-22 11:15:41.963  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:41.964  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d130eb removed from the list
,08-22 11:15:41.964  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:41.964  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bb9e48 removed from the list
,08-22 11:15:41.964  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:41.964  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:41.964  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-22 11:15:41.964  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
,08-22 11:15:41.964  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:41.964  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:41.965  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:41.965  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:41.965  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:41.965  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bb9e48 not in the list
,08-22 11:15:41.965  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:41.966  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:41.966  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:41.966  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:41.966  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 11:15:41.966  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:41.967  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 11:15:41.967  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.967  4279  4289 D BtGatt.GattService: stopScan() - queue size =1
08-22 11:15:41.967  4279  4298 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:41.967  4279  4298 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 11:15:41.967  4279  4318 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 11:15:41.968  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:41.968  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 11:15:41.968  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:41.968  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:41.968  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 11:15:41.969  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:41.969  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:41.969  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:41.969  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:41.969  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:41.970  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:41.970  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:41.970  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:41.971  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:41.971  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:41.971  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:41.971  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff0c7 removed from the list
08-22 11:15:41.971  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:41.971  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:41.971  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:41.971  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:41.971  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6975206 removed from the list
08-22 11:15:41.972  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:41.972  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690d263 added. We now have 2 listener(s)
08-22 11:15:41.973  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 11:15:41.974  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:41.974  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:41.974  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:41.974  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755ee60 added. We now have 9 listener(s)
08-22 11:15:41.974  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:41.974  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 11:15:41.977  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:41.977  4279  4295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 11:15:41.977  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:41.982  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:41.982  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-22 11:15:41.982  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.984  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:41.984  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:41.985  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:41.985  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409bde added. We now have 3 listener(s)
08-22 11:15:41.987  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.987  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 11:15:41.987  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:41.987  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:41.987  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:41.988  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b431bf added. We now have 10 listener(s)
08-22 11:15:41.988  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:41.988  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:41.988  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:41.988  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 11:15:41.988  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:41.988  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:41.989  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 11:15:41.989  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:41.989  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:41.989  4279  4298 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:41.995  3903  3951 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 11:15:41.998  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:42.000  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 11:15:42.000  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:42.000  4279  4298 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 11:15:42.003  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:42.004  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 11:15:42.004  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:42.006  4279  4295 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 11:15:42.006  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:42.009  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:42.009  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:42.009  3903  3951 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:42.009  3903  3951 D BluetoothAdapter: STATE_ON
,08-22 11:15:42.012  4279  4327 D BtGatt.GattService: registerClient() - UUID=0aa1c04d-6275-4034-82a9-be5a559cb142
,08-22 11:15:42.013  4279  4295 D BtGatt.GattService: onClientRegistered() - UUID=0aa1c04d-6275-4034-82a9-be5a559cb142, clientIf=5
,08-22 11:15:42.013  3903  3915 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 11:15:42.013  4279  4289 D BtGatt.GattService: start scan with filters
,08-22 11:15:42.016  4279  4298 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:42.016  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:42.017  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-22 11:15:42.017  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 11:15:42.017  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:42.020  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:42.021  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:42.021  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 11:15:42.022  4279  4295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 11:15:42.023  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:42.023  4279  4298 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 11:15:42.023  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:42.028  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 11:15:42.029  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:42.028  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-22 11:15:42.029  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:42.029  4279  4298 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:42.029  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:42.029  4279  4298 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 11:15:42.029  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:42.029  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:42.029  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 11:15:42.029  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:42.030  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@690d263 removed from the list
08-22 11:15:42.030  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:42.030  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755ee60 removed from the list
08-22 11:15:42.030  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:42.030  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:42.030  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:42.031  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 11:15:42.031  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:42.031  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:42.032  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:42.032  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:42.032  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:42.032  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755ee60 not in the list
08-22 11:15:42.032  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:42.032  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:42.032  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:42.033  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:42.033  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 11:15:42.034  3903  3951 D BluetoothAdapter: STATE_ON
08-22 11:15:42.036  4279  4308 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:42.039  4279  4327 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 11:15:42.039  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:42.039  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:42.039  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 11:15:42.039  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 11:15:42.039  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:42.041  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:42.041  4279  4295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 11:15:42.041  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:42.041  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 11:15:42.041  3903  3951 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:42.041  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:42.042  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:42.043  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:42.043  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:42.043  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:42.043  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:42.043  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b431bf removed from the list
,08-22 11:15:42.043  3903  3903 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:42.043  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 11:15:42.043  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:42.043  3903  3903 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:42.043  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:42.044  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:42.044  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@409bde removed from the list
,08-22 11:15:42.044  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:42.044  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9842adb added. We now have 2 listener(s)
08-22 11:15:42.046  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:42.046  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 11:15:42.046  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:42.046  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:42.046  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:42.047  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:42.047  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b72978 added. We now have 9 listener(s)
08-22 11:15:42.047  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:42.048  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 11:15:42.049  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:42.053  4279  4295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 11:15:42.053  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:42.053  3903  3951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:42.053  4279  4298 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:42.056  3903  3951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:42.056  3903  3951 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:42.057  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:42.057  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dde48b6 added. We now have 3 listener(s)
08-22 11:15:42.058  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 11:15:42.058  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:42.058  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:42.058  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:42.058  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:42.059  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49099b7 added. We now have 10 listener(s)
08-22 11:15:42.059  3903  3951 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:42.059  3903  3951 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:42.059  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:42.059  3903  3951 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:42.060  3903  3903 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:42.060  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:42.060  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:42.060  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:42.060  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:42.060  4279  4295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 11:15:42.060  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 11:15:42.060  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9842adb removed from the list
,08-22 11:15:42.060  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:42.060  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b72978 removed from the list
08-22 11:15:42.060  3903  3951 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:42.060  4279  4298 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 11:15:42.060  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:42.060  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:42.060  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:42.061  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:42.061  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:42.061  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:42.061  3903  3951 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b72978 not in the list
08-22 11:15:42.061  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:42.061  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:42.062  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:42.062  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:42.062  3903  3951 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:42.062  3903  3951 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@49099b7 removed from the list
08-22 11:15:42.062  3903  3951 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:42.062  3903  3951 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:42.062  3903  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:42.062  3903  3951 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:42.063  3903  3951 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dde48b6 removed from the list
08-22 11:15:42.063  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 11:15:42.063  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 11:15:42.063  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 11:15:42.063  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:42.064  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 11:15:42.064  3903  3951 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 11:15:42.065  4279  4295 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 11:15:42.065  4279  4295 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 11:15:42.069  3903  4356 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
,08-22 11:15:42.069  3903  4356 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
08-22 11:15:42.069  3903  4356 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 11:15:42.071  3903  4357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,08-22 11:15:42.071  3903  4357 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
08-22 11:15:42.071  3903  4357 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 11:15:42.072  3903  3951 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-22 11:15:42.072  3903  3951 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 11:15:42.072  3903  3951 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 11:15:42.072  3903  3951 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 11:15:42.072  3903  3951 D com.test.thalitest.ThaliTestRunner: Total duration: 23000 ms
,08-22 11:15:42.073  3903  3951 I jxcore-log: Total number of executed tests:  80
08-22 11:15:42.073  3903  3951 I jxcore-log: 
,08-22 11:15:42.074  3903  3951 I jxcore-log: Number of passed tests:  80
08-22 11:15:42.074  3903  3951 I jxcore-log: 
08-22 11:15:42.074  3903  3951 I jxcore-log: Number of failed tests:  0
08-22 11:15:42.074  3903  3951 I jxcore-log: 
08-22 11:15:42.074  3903  3951 I jxcore-log: Number of ignored tests:  0
08-22 11:15:42.074  3903  3951 I jxcore-log: 
08-22 11:15:42.074  3903  3951 I jxcore-log: Total duration:  23000
08-22 11:15:42.074  3903  3951 I jxcore-log: 
,08-22 11:15:42.075  3903  3951 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 11:15:42.075  3903  3951 I jxcore-log: 
,08-22 11:15:42.077  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.077  3903  3951 I jxcore-log: 
08-22 11:15:42.079  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.079  3903  3951 I jxcore-log: 
08-22 11:15:42.080  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.080  3903  3951 I jxcore-log: 
08-22 11:15:42.081  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.081  3903  3951 I jxcore-log: 
08-22 11:15:42.081  3903  3903 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 11:15:42.081  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.081  3903  3951 I jxcore-log: 
08-22 11:15:42.083  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.083  3903  3951 I jxcore-log: 
08-22 11:15:42.085  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.085  3903  3951 I jxcore-log: 
08-22 11:15:42.086  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.086  3903  3951 I jxcore-log: 
08-22 11:15:42.086  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.086  3903  3951 I jxcore-log: 
08-22 11:15:42.087  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.087  3903  3951 I jxcore-log: 
08-22 11:15:42.088  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.088  3903  3951 I jxcore-log: 
08-22 11:15:42.089  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:42.089  3903  3951 I jxcore-log: 
08-22 11:15:42.090  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.090  3903  3951 I jxcore-log: 
08-22 11:15:42.090  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.090  3903  3951 I jxcore-log: 
08-22 11:15:42.091  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.091  3903  3951 I jxcore-log: 
08-22 11:15:42.091  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.091  3903  3951 I jxcore-log: 
08-22 11:15:42.092  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.092  3903  3951 I jxcore-log: 
08-22 11:15:42.092  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.092  3903  3951 I jxcore-log: 
08-22 11:15:42.093  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.093  3903  3951 I jxcore-log: 
08-22 11:15:42.094  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.094  3903  3951 I jxcore-log: 
,08-22 11:15:42.094  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.094  3903  3951 I jxcore-log: 
08-22 11:15:42.095  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.095  3903  3951 I jxcore-log: 
,08-22 11:15:42.095  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.095  3903  3951 I jxcore-log: 
,08-22 11:15:42.096  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:42.096  3903  3951 I jxcore-log: 
,08-22 11:15:42.097  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.097  3903  3951 I jxcore-log: 
08-22 11:15:42.097  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:42.097  3903  3951 I jxcore-log: 
,08-22 11:15:42.098  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.098  3903  3951 I jxcore-log: 
,08-22 11:15:42.098  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.098  3903  3951 I jxcore-log: 
,08-22 11:15:42.099  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.099  3903  3951 I jxcore-log: 
,08-22 11:15:42.100  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.100  3903  3951 I jxcore-log: 
,08-22 11:15:42.100  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.100  3903  3951 I jxcore-log: 
,08-22 11:15:42.101  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:42.101  3903  3951 I jxcore-log: 
,08-22 11:15:42.400  3903  3903 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:42.403  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:42.403  3903  3951 I jxcore-log: 
,08-22 11:15:42.470  3903  3903 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:42.473  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:42.473  3903  3951 I jxcore-log: 
,08-22 11:15:42.544  3903  3903 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:42.547  3903  3951 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:42.547  3903  3951 I jxcore-log: 
,08-22 11:15:42.717  4358  4358 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-22 11:15:42.722  4358  4358 D AndroidRuntime: CheckJNI is OFF
,08-22 11:15:42.765  4358  4358 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-22 11:15:42.813  4358  4358 I Radio-JNI: register_android_hardware_Radio DONE
,08-22 11:15:42.837  4358  4358 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 11:15:42.850   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-22 11:15:42.851   875   888 I ActivityManager: Killing 3903:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-22 11:15:42.944   875  1690 D GraphicsStats: Buffer count: 2
,08-22 11:15:42.944   875  1956 I WindowState: WIN DEATH: Window{d3ab635 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 11:15:42.945   875  1308 D WifiService: Client connection lost with reason: 4
,08-22 11:15:42.985   875   898 W PackageSettings: Skipping PackageSetting{fd00f51 com.example.hello/10273} due to missing metadata
,08-22 11:15:43.011   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-22 11:15:43.012   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-22 11:15:43.012   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-22 11:15:43.012   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-22 11:15:43.012   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.012   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.012   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:15:43.012   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-22 11:15:43.013   875   888 I ActivityManager:   Force finishing activity ActivityRecord{d78f012 u0 com.test.thalitest/.MainActivity t2}
08-22 11:15:43.015   875   898 I art     : Starting a blocking GC Explicit
,08-22 11:15:43.024   875   885 W ActivityManager: Spurious death for ProcessRecord{77c927b 0:com.test.thalitest/u0a0}, curProc for 3903: null
,08-22 11:15:43.095   875   898 I art     : Explicit concurrent mark sweep GC freed 14187(977KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.155ms total 80.043ms
,08-22 11:15:43.127   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-22 11:15:43.132  4358  4358 I art     : System.exit called, status: 0
08-22 11:15:43.132  4358  4358 I AndroidRuntime: VM exiting with result code 0.
,08-22 11:15:43.186   875   898 I ActivityManager: Start proc 4368:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-22 11:15:43.187   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-22 11:15:43.221   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-22 11:15:43.226  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-22 11:15:43.227  4279  4279 D BluetoothMapAppObserver: onReceive
08-22 11:15:43.227  4279  4279 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-22 11:15:43.230  2000  2288 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 11:15:43.234   875  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 11:15:43.254  3742  3742 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-22 11:15:43.262  1863  4382 I Keyboard.Facilitator.DecoderInitializer: run()
,08-22 11:15:43.267  1863  4382 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-22 11:15:43.268  1863  4382 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-22 11:15:43.268  1863  4382 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-22 11:15:43.268  1863  4382 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-22 11:15:43.268  1863  4382 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-22 11:15:43.268  1863  4382 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-22 11:15:43.268   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-22 11:15:43.272   875   887 E PackageManager: Failed to write settings, restoring backup
08-22 11:15:43.272   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-22 11:15:43.272   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-22 11:15:43.272   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-22 11:15:43.272   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-22 11:15:43.272   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-22 11:15:43.272   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.272   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.272   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 11:15:43.274  1863  4382 I Decoder : createOrResetDecoder
,08-22 11:15:43.279   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-22 11:15:43.279   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 11:15:43.279   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 11:15:43.279   875   888 E DropBoxManagerService: 	... 13 more
,08-22 11:15:43.282  1928  1928 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-22 11:15:43.291   875  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-22 11:15:43.301   875  3214 I ActivityManager: Start proc 4384:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-22 11:15:43.306  1499  1499 I ConfigService: onCreate
,08-22 11:15:43.309  1499  4391 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-22 11:15:43.309  1499  4391 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-22 11:15:43.309  1499  4391 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-22 11:15:43.311  1499  4391 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-22 11:15:43.339   875  1689 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3903 uid 10000
,08-22 11:15:43.346   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 11:15:43.351  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-22 11:15:43.359  1863  4382 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-22 11:15:43.376  4384  4384 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-22 11:15:43.393  1949  2038 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-22 11:15:43.394  1863  4382 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-22 11:15:43.404  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-22 11:15:43.405  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-22 11:15:43.406   875  1956 I ActivityManager: Start proc 4398:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-22 11:15:43.407  1949  2038 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-22 11:15:43.407  1949  2038 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1949
08-22 11:15:43.407  1949  2038 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.407  1949  2038 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:15:43.409   875  1948 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-22 11:15:43.409   875  4403 E DropBoxManagerService: Can't write: system_app_crash
08-22 11:15:43.409   875  4403 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 11:15:43.409   875  4403 E DropBoxManagerService: 	... 5 more
,08-22 11:15:43.414  1949  2038 I Process : Sending signal. PID: 1949 SIG: 9
,08-22 11:15:43.417  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-22 11:15:43.417  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-22 11:15:43.418  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-22 11:15:43.418  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-22 11:15:43.421  1863  4382 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-22 11:15:43.421  1863  4382 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-22 11:15:43.421  1863  4382 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-22 11:15:43.421  1863  4382 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-22 11:15:43.421  1863  4382 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-22 11:15:43.421  1863  4382 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-22 11:15:43.455  4384  4384 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-22 11:15:43.466  4384  4415 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-22 11:15:43.471  4384  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.471  4384  4413 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.472  4384  4413 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 11:15:43.476   875  3214 I ActivityManager: Start proc 4416:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-22 11:15:43.480   875  1689 I WindowState: WIN DEATH: Window{1e08f04 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-22 11:15:43.480   875   885 D GraphicsStats: Buffer count: 1
,08-22 11:15:43.491   875  1979 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1949) has died
,08-22 11:15:43.492   875  1979 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-22 11:15:43.493   875  1979 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-22 11:15:43.520   875   888 I ActivityManager: Start proc 4429:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 11:15:43.541  4416  4416 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-22 11:15:43.572  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-22 11:15:43.573  1499  1499 D AndroidRuntime: Shutting down VM
08-22 11:15:43.574  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
08-22 11:15:43.574  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
,08-22 11:15:43.574  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-22 11:15:43.574  1499  1499 E AndroidRuntime: 	... 8 more
08-22 11:15:43.578   875  4445 E DropBoxManagerService: Can't write: system_app_crash
08-22 11:15:43.578   875  4445 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186),
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 11:15:43.578   875  4445 E DropBoxManagerService: 	... 5 more
08-22 11:15:43.578  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:43.585  4429  4429 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 11:15:43.585  4429  4429 D AndroidRuntime: Shutting down VM
,08-22 11:15:43.592  4429  4429 E AndroidRuntime: FATAL EXCEPTION: main
08-22 11:15:43.592  4429  4429 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4429
08-22 11:15:43.592  4429  4429 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 11:15:43.592  4429  4429 E AndroidRuntime: 	... 10 more
08-22 11:15:43.594   875  1395 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-22 11:15:43.594  4429  4429 I Process : Sending signal. PID: 4429 SIG: 9
08-22 11:15:43.595   875  4447 E DropBoxManagerService: Can't write: system_app_crash
08-22 11:15:43.595   875  4447 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 11:15:43.595   875  4447 E DropBoxManagerService: 	... 5 more
,08-22 11:15:43.604   875  1395 I ActivityManager: Killing 3853:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-22 11:15:43.620  4384  4413 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-22 11:15:43.625  4384  4415 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.625  4384  4415 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 11:15:43.626  4384  4415 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-22 11:15:43.626  4384  4415 E AndroidRuntime: Process: android.process.acore, PID: 4384
08-22 11:15:43.626  4384  4415 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 11:15:43.626  4384  4415 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 11:15:43.627  4384  4413 I Process : Sending signal. PID: 4384 SIG: 9

```
