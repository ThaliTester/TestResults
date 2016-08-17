#### Test 808075738e7a0be_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 19:16:23.861   875  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 19:16:24.537  3813  3813 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 19:16:24.542  3813  3813 D AndroidRuntime: CheckJNI is OFF
08-17 19:16:24.587  3813  3813 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 19:16:24.639  3813  3813 I Radio-JNI: register_android_hardware_Radio DONE
08-17 19:16:24.661  3813  3813 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 19:16:24.667   875  1984 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 19:16:24.708  2008  3772 W SearchService: Abort, client detached.
08-17 19:16:24.708  3813  3813 D AndroidRuntime: Shutting down VM
08-17 19:16:24.713  2008  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b664ae9
08-17 19:16:24.713  2008  2008 I HotwordDetector: Closing mic
08-17 19:16:24.713  2008  2338 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 19:16:24.754   875  2239 I ActivityManager: Start proc 3822:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 19:16:24.761   378  2340 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 19:16:24.765   378  2340 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 19:16:24.771   378  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 19:16:24.775  2008  2335 I MicroRecognitionRnrImpl: Detection finished
08-17 19:16:24.775  2008  2333 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 19:16:24.831  3822  3822 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 19:16:24.862  3822  3822 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 19:16:24.870  3822  3822 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4029-4032)
08-17 19:16:24.870  3822  3822 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:16:24.888  3822  3822 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {121037d}
08-17 19:16:24.888  3822  3822 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:16:24.889  3822  3822 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:16:24.906  3822  3822 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 19:16:24.908  3822  3822 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:16:24.931  3822  3822 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 19:16:24.946  3822  3822 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:16:24.946  3822  3822 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:16:24.946  3822  3822 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:16:24.946  3822  3822 I Adreno  : Build Date                       : 10/20/15
08-17 19:16:24.946  3822  3822 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:16:24.946  3822  3822 I Adreno  : Local Branch                     : M14
08-17 19:16:24.946  3822  3822 I Adreno  : Remote Branch                    : 
08-17 19:16:24.946  3822  3822 I Adreno  : Remote Branch                    : 
08-17 19:16:24.946  3822  3822 I Adreno  : Reconstruct Branch               : 
,08-17 19:16:25.027   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae52028:true
,08-17 19:16:25.062  3822  3822 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 19:16:25.074  3822  3822 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 19:16:25.117  3822  3860 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 19:16:25.124  3822  3847 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 19:16:25.157  3822  3860 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 19:16:25.223   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +503ms
,08-17 19:16:25.230  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 19:16:25.291  3822  3822 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3822
,08-17 19:16:25.370  3822  3822 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:16:25.520  3822  3862 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1679820496
,08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 19:16:25.536  3822  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed82718 added. We now have 1 listener(s)
,08-17 19:16:25.542  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 19:16:25.545  3822  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:16:25.545  3822  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:25.546  3822  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 19:16:25.550  3822  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9456bd7 added. We now have 1 listener(s)
08-17 19:16:25.551  3822  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:25.554   875  1308 D WifiService: New client listening to asynchronous messages
,08-17 19:16:25.555  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:16:25.555  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 19:16:25.556  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 19:16:25.556  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-17 19:16:25.556  3822  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 19:16:25.562  3822  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:25.562  3822  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 19:16:25.571   875  2234 I ActivityManager: Killing 2975:com.google.android.calendar/u0a37 (adj 15): empty #17
08-17 19:16:25.571  3822  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:25.571  3822  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:25.572  3822  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:16:25.572  3822  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:25.573  3822  3862 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 19:16:25.573  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:25.575  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:25.602  3822  3822 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:16:25.649   875  2234 I ActivityManager: Killing 3094:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 19:16:26.695  3822  3871 W jxcore-log: Initializing JXcore engine
,08-17 19:16:26.695  3822  3871 W jxcore-log: JXcore engine is ready
,08-17 19:16:26.733  3871  3871 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8786 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 19:16:26.733  3871  3871 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10652]" dev="sockfs" ino=10652 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 19:16:26.733  3871  3871 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 19:16:26.733  3871  3871 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25927]" dev="sockfs" ino=25927 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 19:16:26.750  3822  3871 W jxcore-log: Starting JXcore engine
,08-17 19:16:26.861  3822  3871 W jxcore-log: Platform android
08-17 19:16:26.861  3822  3871 W jxcore-log: 
,08-17 19:16:26.862  3822  3871 W jxcore-log: Process ARCH arm
08-17 19:16:26.862  3822  3871 W jxcore-log: 
,08-17 19:16:27.234  3822  3871 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:16:27.234  3822  3871 I jxcore-log: 
08-17 19:16:27.235  3822  3871 W jxcore-log: JXcore engine is started
,08-17 19:16:27.240  3822  3862 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 19:16:27.244  3822  3822 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:16:27.263  3591  3874 V KeepSync: Connecting to GoogleApiClient
,08-17 19:16:27.263   875  1382 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 19:16:27.323  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:27.325  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:27.356  1503  2993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 19:16:27.356  1503  2993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 19:16:27.356  1503  2993 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 19:16:27.357  1503  2993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:27.378  1715  3875 V BaseAuthAsyncOperation: access token request failed
,08-17 19:16:27.379  3591  3874 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 19:16:27.447  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 19:16:27.447  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 19:16:27.448  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:27.448  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:27.478  3591  3874 E KeepSync: IOException
08-17 19:16:27.478  3591  3874 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 19:16:27.478  3591  3874 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 19:16:27.478  3591  3874 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 19:16:27.478  3591  3874 E KeepSync: 	... 10 more
,08-17 19:16:27.478  3591  3874 W KeepSync: Sync result 2
,08-17 19:16:27.486   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126286, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:16:29.946  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:29.986  1503  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 19:16:29.987  1503  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 19:16:29.987  1503  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:29.987  1503  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:30.033  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 19:16:30.034  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 19:16:30.034  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 19:16:37.633  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 19:16:37.633  3822  3871 I jxcore-log: 
,08-17 19:16:37.636  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 19:16:37.636  3822  3871 I jxcore-log: 
,08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.646  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:37.650  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.653  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:16:37.653  3822  3871 I jxcore-log: 
,08-17 19:16:37.655  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:16:37.655  3822  3871 I jxcore-log: 
,08-17 19:16:38.005  3822  3871 D ExecuteNativeTests: Running unit tests
,08-17 19:16:38.063  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:16:38.063  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 added. We now have 2 listener(s)
08-17 19:16:38.065  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:16:38.065  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:38.065  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:38.065  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.065  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 added. We now have 2 listener(s)
08-17 19:16:38.065  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:38.065  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:38.067  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.082  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.085  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.085  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:38.092  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 19:16:38.093  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:16:38.093  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:16:38.096  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 19:16:38.097  3822  3871 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 19:16:38.099  3822  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:38.099  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.100  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:38.100  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:16:38.100  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:38.102  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.103  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.103  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.104  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.104  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.104  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.104  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:38.104  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 removed from the list
08-17 19:16:38.104  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.104  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 removed from the list
08-17 19:16:38.104  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.104  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.105  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.105  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.106  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.106  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.106  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.106  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.108  3822  3871 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 19:16:38.108  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.108  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.108  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.108  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.108  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.108  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.108  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.109  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.109  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.109  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.109  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.109  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.109  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.109  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.110  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.110  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.110  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.110  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.114  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:38.114  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:38.114  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:38.115  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:38.116  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:38.116  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.116  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.116  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.116  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.116  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.116  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.116  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.116  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.117  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.117  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.117  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.117  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.117  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.117  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.118  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.118  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.118  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.118  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.119  3822  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:38.120  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.124  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.125  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.125  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.125  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.125  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.126  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.126  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.126  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:16:38.128  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.129  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:16:38.129  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:38.130  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.135  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:16:38.136  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:16:38.137  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:16:38.140  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:38.142  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:38.142  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:38.142  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:38.144  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:38.145  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:16:38.151  2699  2713 D BtGatt.GattService: registerClient() - UUID=c7374a15-411a-4a8b-a8dc-e47aa7540aae
08-17 19:16:38.152  2699  2752 D BtGatt.GattService: onClientRegistered() - UUID=c7374a15-411a-4a8b-a8dc-e47aa7540aae, clientIf=5
08-17 19:16:38.152  3822  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:16:38.153  2699  2883 D BtGatt.GattService: start scan with filters
08-17 19:16:38.157  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:38.157  2699  2767 D BtGatt.ScanManager: handling starting scan
08-17 19:16:38.157  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:38.157  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:38.157  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.158  2699  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
08-17 19:16:38.160  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:38.160  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:38.161  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:38.162  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 19:16:38.165  3822  3871 I io.jxcore.node.ConnectionHelper: start: OK
08-17 19:16:38.166  2699  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:16:38.166  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.166  2699  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 19:16:38.168  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.168  3822  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:38.168  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.169  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:38.169  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.169  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.169  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.169  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.169  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.169  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:38.170  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:38.170  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:38.172  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:16:38.172  2699  2718 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:38.172  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:16:38.173  2699  2883 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:16:38.172  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.173  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:38.173  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.173  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:38.173  2699  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:38.173  2699  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 19:16:38.173  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:38.173  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:38.175  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.175  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:38.175  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.175  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.175  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.176  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.176  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.176  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.176  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.176  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.176  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.176  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.176  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.176  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.176  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.176  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.177  3822  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:38.178  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.181  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.183  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.183  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.183  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.183  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.183  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.183  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.183  2699  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:16:38.183  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:16:38.183  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.185  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.187  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.188  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:16:38.188  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:38.189  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:16:38.189  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.192  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:16:38.192  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:16:38.192  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:16:38.195  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:16:38.196  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.196  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:38.196  2699  2767 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:38.196  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:38.196  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:38.197  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:16:38.199  2699  2718 D BtGatt.GattService: registerClient() - UUID=05ba476e-e173-4714-b6b9-dd49ef702904
08-17 19:16:38.199  2699  2752 D BtGatt.GattService: onClientRegistered() - UUID=05ba476e-e173-4714-b6b9-dd49ef702904, clientIf=5
,08-17 19:16:38.200  3822  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:16:38.200  2699  2883 D BtGatt.GattService: start scan with filters
,08-17 19:16:38.201  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 19:16:38.202  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.202  2699  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 19:16:38.203  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:38.203  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:16:38.203  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:38.203  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.205  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:38.205  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:38.205  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:38.207  2699  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 19:16:38.207  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:38.207  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.209  2699  2767 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:38.209  3822  3871 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:38.212  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.212  3822  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:38.212  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:38.212  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:38.212  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.212  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.212  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.213  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.213  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.213  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:38.213  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:16:38.213  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:38.214  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:16:38.214  2699  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:16:38.214  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.214  2699  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 19:16:38.215  2699  2713 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:38.215  2699  2883 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:16:38.216  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:16:38.216  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.216  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:38.216  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:16:38.216  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:38.217  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.217  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:38.217  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.217  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.217  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.219  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.219  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.219  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.219  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:16:38.219  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.219  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.219  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.219  2699  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:38.219  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.219  2699  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:16:38.220  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.220  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.220  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.220  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.220  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.220  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.220  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.221  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.221  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.221  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.221  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.222  3822  3871 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:16:38.223  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.227  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.229  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:38.229  2699  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:16:38.229  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.230  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.230  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.230  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.230  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.230  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.230  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:38.232  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.234  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.234  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 19:16:38.234  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:38.236  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 19:16:38.236  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:16:38.238  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:38.239  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
,08-17 19:16:38.239  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:38.242  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:38.242  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:38.242  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:38.243  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:16:38.243  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:16:38.244  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:16:38.244  2699  2767 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:38.244  2699  2883 D BtGatt.GattService: registerClient() - UUID=67726f19-7dbe-4df7-9076-3e02aa9037f2
,08-17 19:16:38.245  2699  2752 D BtGatt.GattService: onClientRegistered() - UUID=67726f19-7dbe-4df7-9076-3e02aa9037f2, clientIf=5
,08-17 19:16:38.245  3822  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:16:38.245  2699  2718 D BtGatt.GattService: start scan with filters
,08-17 19:16:38.248  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:38.248  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:38.248  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:16:38.248  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.250  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.250  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 19:16:38.250  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:16:38.250  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.251  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:38.251  2699  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:16:38.252  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:38.254  3822  3871 I io.jxcore.node.ConnectionHelper: start: OK
08-17 19:16:38.254  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.254  3822  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:38.254  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.254  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:38.254  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.254  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.254  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.254  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.254  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:16:38.254  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:38.255  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:38.255  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:38.256  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:16:38.256  2699  2883 D BtGatt.GattService: stopScan() - queue size =0
08-17 19:16:38.256  2699  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:16:38.256  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:16:38.257  2699  2713 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:16:38.257  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:38.257  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.257  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:16:38.257  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:38.257  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:38.258  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.258  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:38.258  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.258  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.259  2699  2767 D BtGatt.ScanManager: handling starting scan
08-17 19:16:38.259  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.261  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.261  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.261  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.261  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.261  3822  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:38.261  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.261  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.261  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.261  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.261  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.262  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.262  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.262  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.262  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.262  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.262  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.262  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.263  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.263  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.263  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.263  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.264  3822  3871 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 19:16:38.264  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.264  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.267  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.267  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.267  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.267  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.267  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.267  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.267  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.267  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.267  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.267  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.267  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.267  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.268  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.269  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.269  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.269  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.269  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:38.269  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.270  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.270  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.270  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.270  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.270  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.270  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.270  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.270  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.270  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.270  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.270  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.270  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.270  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.271  2699  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:16:38.271  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.271  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.273  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.271  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.274  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.274  2699  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 19:16:38.274  3822  3871 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 19:16:38.274  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.274  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:38.274  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.275  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.275  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.275  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.275  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.275  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.275  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.275  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.275  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.275  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.275  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.275  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.278  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.278  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.279  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.279  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.280  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 19:16:38.280  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.281  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:16:38.281  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.281  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.281  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.281  2699  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:38.282  2699  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 19:16:38.282  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.282  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.282  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.283  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
,08-17 19:16:38.283  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.283  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.283  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.283  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.283  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.283  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.284  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.286  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.287  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.287  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.287  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.288  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 19:16:38.289  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:38.289  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:38.289  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:38.289  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 19:16:38.291  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:38.291  2699  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 19:16:38.291  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.291  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.293  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:38.293  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.294  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.294  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.294  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.294  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
,08-17 19:16:38.294  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.295  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.295  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.295  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.295  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.295  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.295  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.298  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:16:38.298  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.297  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.299  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.299  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.299  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.301  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:38.301  3822  3871 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.301  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:38.308  2699  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:16:38.308  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.309  2699  2767 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:38.311  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:38.311  3822  3871 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-17 19:16:38.311  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-17 19:16:38.311  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:38.311  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:16:38.311  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:38.311  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-17 19:16:38.312  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-17 19:16:38.313  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:38.313  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:16:38.314  3822  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 19:16:38.314  3822  3871 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:16:38.314  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:38.314  3822  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 19:16:38.314  3822  3871 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 19:16:38.314  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:38.314  3822  3871 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:38.314  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:38.316  2699  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:16:38.316  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.316  2699  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:16:38.318  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 19:16:38.319  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 19:16:38.319  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 19:16:38.319  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 19:16:38.320  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:16:38.320  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:16:38.320  3822  3871 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:38.320  3822  3871 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-17 19:16:38.320  3822  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-17 19:16:38.321  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.321  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.321  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.322  3822  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:38.322  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.322  2699  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:16:38.322  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.322  2699  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:16:38.322  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.322  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:16:38.323  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.323  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.323  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.323  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.323  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.323  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.323  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.323  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.324  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.324  3822  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-17 19:16:38.324  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.324  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.324  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.324  3822  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 390)
08-17 19:16:38.324  2699  2879 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-17 19:16:38.325  3822  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-17 19:16:38.325  3822  3871 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:16:38.325  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.325  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.325  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.325  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.326  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.326  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.326  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.326  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.326  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.326  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.326  3822  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 390)
08-17 19:16:38.326  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.326  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.326  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.326  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.327  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:38.327  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.327  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.327  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.327  3822  3871 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:16:38.327  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.328  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.328  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.328  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.328  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.328  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.328  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.328  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.328  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.328  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.328  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.328  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.328  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.328  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.329  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.329  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.329  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.329  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.329  3822  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:16:38.329  3822  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 19:16:38.329  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.330  3822  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:16:38.330  3822  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-17 19:16:38.330  3822  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:16:38.330  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:38.330  3822  3871 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:16:38.330  3822  3871 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.330  3822  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.330  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:38.330  3822  3871 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:16:38.330  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.330  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.330  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.330  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.330  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.330  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.330  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.330  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.330  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.331  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.331  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.331  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.331  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.331  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.331  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.331  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.331  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.331  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.332  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.332  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.332  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.332  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.332  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.332  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.332  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.332  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.332  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.332  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.332  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.332  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.332  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.332  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.333  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.333  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.333  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.333  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.333  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.333  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.333  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.333  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.333  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.333  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.333  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.333  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.333  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.333  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.333  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.334  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.334  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.334  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.334  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.335  3822  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 19:16:38.335  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.336  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 19:16:38.336  3822  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 19:16:38.336  3822  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.337  3822  3822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-17 19:16:38.337  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 19:16:38.337  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.337  3822  3871 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 19:16:38.337  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.337  3822  3822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.337  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:16:38.337  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.337  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:38.337  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.338  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.338  3822  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:38.338  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.338  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.339  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.339  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.339  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.339  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.339  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.339  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.339  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.339  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.339  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.339  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.339  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.339  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.339  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.339  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.339  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.339  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.339  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.340  3822  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 19:16:38.340  3822  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:16:38.340  3822  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 19:16:38.340  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:38.340  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.340  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.340  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.340  3822  3822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 19:16:38.341  3822  3871 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:16:38.341  3822  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:38.341  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:38.341  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:16:38.341  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.341  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.341  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.342  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.342  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.342  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.342  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.342  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.342  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.342  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.342  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.342  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.342  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.342  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.343  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.343  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.343  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.343  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.346  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.346  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.346  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.346  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.346  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.346  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.346  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.347  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.347  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
,08-17 19:16:38.347  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.347  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.347  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.347  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.347  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.348  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.348  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.348  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.348  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.349  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.349  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.349  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.349  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.349  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.349  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.349  3822  3871 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c14d297 not in the list
08-17 19:16:38.349  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.349  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.349  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.349  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.349  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.349  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.349  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.350  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.351  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.351  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.351  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1dc84 not in the list
08-17 19:16:38.351  3822  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:16:38.351  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.351  3822  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 19:16:38.351  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.352  3822  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 19:16:38.352  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:38.353  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:38.353  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-17 19:16:38.353  3822  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 19:16:38.353  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:38.354  3822  3871 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:38.354  3822  3871 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:16:38.354  3822  3871 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-17 19:16:38.355  3822  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 19:16:38.355  3822  3871 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:16:38.355  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.355  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfd33c6 added. We now have 2 listener(s)
08-17 19:16:38.355  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:38.357  3822  3871 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 19:16:38.357   875  2239 D WifiService: setWifiEnabled: true pid=3822, uid=10000
08-17 19:16:38.357   875  2239 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 19:16:38.358  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:38.358  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb98f87 added. We now have 3 listener(s)
08-17 19:16:38.358  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:38.362  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.362  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8276eb4 added. We now have 4 listener(s)
08-17 19:16:38.362  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:38.363  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.363  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbd2add added. We now have 5 listener(s)
08-17 19:16:38.363  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:38.365   875  1968 D WifiService: setWifiEnabled: false pid=3822, uid=10000
08-17 19:16:38.365   875  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:16:38.370  2699  2748 D BluetoothAdapterState: Current state: ON, message: 23
08-17 19:16:38.370  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.370  2699  2748 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:38.370  2699  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:38.371  2699  2748 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 19:16:38.373  2699  2748 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:38.373  2699  2699 D BluetoothMapService: onReceive
,08-17 19:16:38.373  2699  2699 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:38.374  2699  2699 D BluetoothMapService: STATE_TURNING_OFF
,08-17 19:16:38.374  2699  2699 D BluetoothMapService: MAP Service closeService in
,08-17 19:16:38.374  2699  2699 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 19:16:38.374  2699  2699 D ObexServerSockets0: shutdown(block = true)
,08-17 19:16:38.374  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.374  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.374  2699  2699 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 19:16:38.375  2699  2699 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:16:38.375  2699  2879 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 19:16:38.375  2699  2892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 19:16:38.375  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.375  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.375  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.375  2699  2891 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 19:16:38.378  2699  2699 I BtOppRfcommListener: stopping Accept Thread
,08-17 19:16:38.378  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.378  2699  3459 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:16:38.379  2699  3459 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 19:16:38.380  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.383  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.383  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.384  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:38.384  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.384  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 19:16:38.386  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.386   875  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 19:16:38.386   875  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 19:16:38.386   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 19:16:38.387   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:38.390   875   888 I ActivityManager: Start proc 3889:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-17 19:16:38.391  2699  2752 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:38.392  2699  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 19:16:38.395  2699  2699 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:16:38.395  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.395   875  2091 D DhcpClient: Clearing IP address
08-17 19:16:38.396   374   873 D CommandListener: Clearing all IP addresses on wlan0
08-17 19:16:38.396   875   875 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:38.396   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 19:16:38.396   875   875 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:38.396  1365  1376 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:38.397  1938  2194 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:38.398  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.398  2699  2699 V BluetoothAdapterState: isTurningOff()=true
,08-17 19:16:38.398  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.399  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.399  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:38.399   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:38.401   875  2131 D DhcpClient: Receive thread stopped
,08-17 19:16:38.402  1365  1365 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:38.403  2699  2699 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 19:16:38.403  2699  2699 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:16:38.403  2699  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 19:16:38.403  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:38.404  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:16:38.404  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:38.404  2699  2752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-17 19:16:38.406  2699  2699 D A2dpService: Received stop request...Stopping profile...
08-17 19:16:38.406  2699  2886 D A2dpStateMachine: Exit Disconnected: -1
08-17 19:16:38.407   875   875 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.408  1365  1365 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.408  2699  2699 D HidService: Received stop request...Stopping profile...
08-17 19:16:38.408  2699  2699 D HidService: Stopping Bluetooth HidService
08-17 19:16:38.410  2699  2699 D HealthService: Received stop request...Stopping profile...
08-17 19:16:38.410  1365  1365 D BluetoothInputDevice: Proxy object disconnected
08-17 19:16:38.410  1365  1365 D HidProfile: Bluetooth service disconnected
,08-17 19:16:38.412  2699  2699 D PanService: Received stop request...Stopping profile...
,08-17 19:16:38.412  1503  3493 V NativeCrypto: Read error: ssl=0x9b6f5a00: I/O error during system call, Connection timed out
08-17 19:16:38.413  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:38.413  1365  1365 D PanProfile: Bluetooth service disconnected
08-17 19:16:38.413  1503  3493 V NativeCrypto: SSL shutdown failed: ssl=0x9b6f5a00: I/O error during system call, Broken pipe
08-17 19:16:38.415   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 19:16:38.415   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 19:16:38.418  2699  2699 D BluetoothMapService: Received stop request...Stopping profile...
08-17 19:16:38.418  2699  2699 D BluetoothMapService: stop()
,08-17 19:16:38.418   407   407 E Parcel  : Reading a NULL string not supported here.
08-17 19:16:38.419  2699  2699 D BluetoothMapAppObserver: deinitObservers()
08-17 19:16:38.419  2699  2699 D BluetoothMapAppObserver: removeReceiver()
08-17 19:16:38.420  1365  1365 D BluetoothMap: Proxy object disconnected
08-17 19:16:38.420  1365  1365 D MapProfile: Bluetooth service disconnected
08-17 19:16:38.420  2699  2699 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:38.420  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.421  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.421  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:38.422  2699  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 19:16:38.422  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:38.422  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:38.422  2699  2874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:38.422  2699  2874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 19:16:38.422  2699  2874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:38.422  2699  2874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:38.424   875  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 19:16:38.424  2699  2699 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:38.424  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.424  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.424  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:38.424   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:16:38.424  2699  2699 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:38.425  2699  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 19:16:38.425   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-17 19:16:38.426  2699  2699 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:38.428   374   873 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:38.432  2699  2699 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:38.432  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.432  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.432  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:38.433  2699  2699 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:38.433   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 19:16:38.433  2699  2752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 19:16:38.433  2699  2699 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:38.433  2699  2699 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:38.433  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.433  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:38.433  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:38.434  2699  2699 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:38.435  2699  2699 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 19:16:38.435  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:38.435  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:38.435  2699  2699 D BluetoothMapService: MAP Service closeService in
08-17 19:16:38.436  2699  2699 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:38.436  2699  2699 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:16:38.436  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.436  2699  2699 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:38.436  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.436  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:38.436  2699  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 19:16:38.436  2699  2748 D BluetoothAdapterProperties: Setting state to 15
,08-17 19:16:38.436  2699  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 19:16:38.437  2699  2748 I BluetoothAdapterState: Entering BleOnState
08-17 19:16:38.437  2699  2699 D BluetoothMapService: cleanup()
08-17 19:16:38.437  1365  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:38.437  2699  2699 D BluetoothMapService: MAP Service closeService in
,08-17 19:16:38.438  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:38.438  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:38.438  1365  2040 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 19:16:38.438   875  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:16:38.439  1365  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:38.439  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:38.439  1365  2013 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:38.439  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:38.440   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:38.440   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:38.440   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:38.440  1365  1381 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:38.441  1938  1950 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:38.441   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:38.441  1365  2040 D BluetoothPan: onBluetoothStateChange on: false
,08-17 19:16:38.450  2699  2748 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 19:16:38.450  2699  2748 D BluetoothAdapterProperties: Setting state to 16
08-17 19:16:38.450  2699  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 19:16:38.451  2699  2748 D BluetoothAdapterProperties: onBleDisable
08-17 19:16:38.451  2699  2748 I BluetoothAdapterState: Entering PendingCommandState
08-17 19:16:38.451  2699  2749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 19:16:38.452  2699  2874 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:16:38.452  2699  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:38.452  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.453  2699  2752 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:38.453  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.457  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.458  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.465  1882  2296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:16:38.475   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 19:16:38.476  3889  3889 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-17 19:16:38.485  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:16:38.492   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 19:16:38.493  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:38.494   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 19:16:38.494   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 19:16:38.496   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d628419:true
08-17 19:16:38.498   875   892 D Tethering: MasterInitialState.processMessage what=3
08-17 19:16:38.499  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.500  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.513   875  2238 I ActivityManager: Start proc 3908:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-17 19:16:38.517  3392  3392 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2822571 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 19:16:38.518  2008  2008 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-17 19:16:38.533  3889  3889 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 19:16:38.536  3889  3889 D BluetoothMap: Create BluetoothMap proxy object
,08-17 19:16:38.544  3889  3889 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 19:16:38.548   374   873 E Netd    : netlink response contains error (No such file or directory)
,08-17 19:16:38.551  3908  3908 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 19:16:38.559  3889  3889 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:38.569   875  2234 I ActivityManager: Killing 3209:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 19:16:38.653  2699  2752 I bt_hci  : shut_down
,08-17 19:16:38.653  2699  2770 D bt_hwcfg: hw_epilog_process
,08-17 19:16:38.665  2699  2770 I bt_vendor: low_power_mode_cb
,08-17 19:16:38.689  2699  2770 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 19:16:38.690  2699  2770 I bt_vendor: epilog_cb
08-17 19:16:38.690  2699  2770 I bt_hci  : epilog_finished_callback
,08-17 19:16:38.694  2699  2752 I bt_hci_h4: hal_close
,08-17 19:16:38.695  2699  2752 I bt_userial_vendor: device fd = 51 close
,08-17 19:16:38.730  3908  3908 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:16:38.730  3908  3908 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:16:38.730  3908  3908 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.730  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:16:38.731  3908  3908 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:16:38.731  3908  3908 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:16:38.731  3908  3908 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:16:38.731  3908  3908 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.731  3908  3908 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:16:38.731  3908  3908 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:16:38.731  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:16:38.770   875  1964 I ActivityManager: Start proc 3941:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-17 19:16:38.771   875  1964 I ActivityManager: Killing 3392:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 19:16:38.840  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:16:38.907  2699  2749 D bt_stack_manager: event_shut_down_stack finished.
,08-17 19:16:38.907  2699  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-17 19:16:38.910  2699  2699 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:16:38.910  2699  2748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-17 19:16:38.910  2699  2699 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:16:38.910  2699  2699 D BtGatt.GattService: stop()
08-17 19:16:38.910  2699  2699 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 19:16:38.912  2699  2699 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:38.912  2699  2699 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:38.912  2699  2699 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:38.912  2699  2699 V BluetoothAdapterState: isBleTurningOff()=true
08-17 19:16:38.912  2699  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 19:16:38.913  2699  2748 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:38.913  2699  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 19:16:38.913  2699  2748 I BluetoothAdapterState: Entering OffState
08-17 19:16:38.914   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 19:16:38.922  2699  2699 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 19:16:38.922  2699  2699 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 19:16:38.922  2699  2699 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 19:16:38.922  2699  2749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 19:16:38.925  2699  2749 D bt_stack_manager: event_clean_up_stack finished.
,08-17 19:16:38.929  3941  3941 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 19:16:38.935  2699  2699 I art     : System.exit called, status: 0
,08-17 19:16:38.936  2699  2699 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 19:16:38.963  3908  3929 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:16:38.985   875  1968 I ActivityManager: Process com.android.bluetooth (pid 2699) has died
,08-17 19:16:39.046   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69b0b43:true
,08-17 19:16:39.070  3941  3941 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 19:16:39.113  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:39.141   875  1680 I ActivityManager: Start proc 3969:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-17 19:16:39.142  3889  3889 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:39.237  3969  3969 D AdapterServiceConfig: Adding HeadsetService
,08-17 19:16:39.237  3969  3969 D AdapterServiceConfig: Adding A2dpService
08-17 19:16:39.237  3969  3969 D AdapterServiceConfig: Adding HidService
,08-17 19:16:39.237  3969  3969 D AdapterServiceConfig: Adding HealthService
08-17 19:16:39.237  3969  3969 D AdapterServiceConfig: Adding PanService
,08-17 19:16:39.238  3969  3969 D AdapterServiceConfig: Adding GattService
08-17 19:16:39.238  3969  3969 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 19:16:39.239   875  1681 I ActivityManager: Killing 2772:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 19:16:39.275  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:39.304  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:16:39.308  1715  1715 D SystemUpdateService: onCreate
,08-17 19:16:39.312  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:16:39.319  1715  3982 I SystemUpdateService: active receiver: enabled
,08-17 19:16:39.322  1715  3982 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:16:39.323  1715  3982 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 19:16:39.323  1715  3982 I SystemUpdateService: now status is 0 (complete)
08-17 19:16:39.323  1715  3982 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 19:16:39.323  1715  3982 I SystemUpdateService: file has been verified
08-17 19:16:39.324  1715  3982 I SystemUpdateService: OTA package size = 12249756
,08-17 19:16:39.328  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-17 19:16:39.328  1715  3982 I SystemUpdateService: showing system update notification
,08-17 19:16:39.330  1715  2512 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:39.331  1715  2512 I iu.UploadsManager: num updated entries: 0
,08-17 19:16:39.332  1715  2512 I iu.SyncManager: NEXT; no task
,08-17 19:16:39.347  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:16:39.352  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 19:16:39.370   875  1965 I ActivityManager: Start proc 3984:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 19:16:39.374  1715  1715 D SystemUpdateService: onDestroy
,08-17 19:16:39.419  3984  3984 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 19:16:39.421  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:39.428  3984  3984 D SprintDMHelper: simOperator: 
08-17 19:16:39.428  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:16:39.447   875  1382 I ActivityManager: Start proc 3996:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 19:16:39.448   875  1382 I ActivityManager: Killing 3639:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-17 19:16:39.566  2252  4010 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 19:16:39.585   875   886 I ActivityManager: Start proc 4011:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 19:16:39.588   875  1964 I ActivityManager: Killing 1689:android.process.acore/u0a5 (adj 15): empty #17
,08-17 19:16:39.659  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 19:16:39.718  4011  4011 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 19:16:39.718  4011  4011 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:16:39.718  4011  4011 I GAv4    :   adb logcat -s GAv4
,08-17 19:16:39.733  4011  4011 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:39.740  4011  4011 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:39.776  4011  4028 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:39.896  4011  4011 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 19:16:39.955  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 19:16:39.964  4011  4011 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9122-9125)
08-17 19:16:39.964  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 19:16:39.977  4011  4011 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5564ce1}
,08-17 19:16:39.978  4011  4011 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:16:39.978  4011  4011 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:16:39.987  4011  4011 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 19:16:39.989  4011  4011 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 19:16:40.007  4011  4011 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 19:16:40.020  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:16:40.020  4011  4011 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:16:40.020  4011  4011 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:16:40.020  4011  4011 I Adreno  : Build Date                       : 10/20/15
08-17 19:16:40.020  4011  4011 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:16:40.020  4011  4011 I Adreno  : Local Branch                     : M14
08-17 19:16:40.020  4011  4011 I Adreno  : Remote Branch                    : 
08-17 19:16:40.020  4011  4011 I Adreno  : Remote Branch                    : 
08-17 19:16:40.020  4011  4011 I Adreno  : Reconstruct Branch               : 
,08-17 19:16:40.090  4011  4011 I NSApplication: Starting up...
,08-17 19:16:40.099  4011  4057 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 19:16:40.134   875  1964 I ActivityManager: Start proc 4062:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 19:16:40.136   875  1964 I ActivityManager: Killing 3673:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 19:16:40.206  4062  4062 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 19:16:40.393   875  2234 I ActivityManager: Killing 3688:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 19:16:41.378   875  2234 D WifiService: setWifiEnabled: true pid=3822, uid=10000
,08-17 19:16:41.378   875  2234 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:16:41.394   875  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:41.400  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:41.401  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:41.401  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:41.401  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:41.404  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:41.404  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:41.405  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:41.405  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:41.417   875  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 19:16:41.418   875  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 19:16:41.419   875  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 19:16:41.420   875  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:41.421   875  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 19:16:41.421   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 19:16:41.421   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 19:16:41.443   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 19:16:41.446   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:41.446   875  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.12 rxSuccessRate=12.62 delta 1000 -> 994
08-17 19:16:41.448   875  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-17 19:16:41.448   875  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:16:41.458   875  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 19:16:41.467   875  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-17 19:16:41.467   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 19:16:41.467   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:41.485   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 19:16:41.600   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 19:16:41.603  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 19:16:42.018  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 19:16:42.055  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 19:16:42.055  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-17 19:16:42.059   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:16:42.066   875  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:16:42.066   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 19:16:42.066   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:42.083   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:42.094   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:42.095   875  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:16:42.106   875  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 19:16:42.108   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 19:16:42.146   875  4085 D DhcpClient: Receive thread started
,08-17 19:16:42.227   875  1307 E native  : do suspend false
,08-17 19:16:42.248   875  2091 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 19:16:42.261   875  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-17 19:16:42.262   875  2091 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-17 19:16:42.266   875  2091 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 19:16:42.278   875  4085 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 19:16:42.279   875  2091 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 19:16:42.284   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:42.295   875  2091 D DhcpClient: Scheduling renewal in 86399s
,08-17 19:16:42.296   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 19:16:42.320   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 19:16:42.323   875  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 19:16:42.323   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:16:42.325   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 19:16:42.336   875  1309 D ConnectivityService: Adding iface wlan0 to network 101
08-17 19:16:42.344   875  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:16:42.416   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 19:16:42.417   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 19:16:42.419   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 19:16:42.421   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 19:16:42.422   875  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 19:16:42.438   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:16:42.450   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 19:16:42.451   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 19:16:42.451   875  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 19:16:42.451   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 19:16:42.452   875  1309 D ConnectivityService:    accepting network in place of null
08-17 19:16:42.452   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 19:16:42.453   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:16:42.463   875  4084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 19:16:42.490   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:42.563   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:42.568   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 19:16:42.568   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:42.572   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 19:16:42.575   875   892 D Tethering: MasterInitialState.processMessage what=3
08-17 19:16:42.591  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:42.591  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:42.593  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:42.593  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:42.596  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:42.597  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:42.597  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:42.597  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:42.608  2008  2008 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-17 19:16:42.610  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:16:42.613  1715  1715 D SystemUpdateService: onCreate
,08-17 19:16:42.618  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:16:42.621  1715  4096 I SystemUpdateService: active receiver: enabled
,08-17 19:16:42.623  1715  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:16:42.629  1715  4096 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 19:16:42.629  1715  4096 I SystemUpdateService: now status is 0 (complete)
08-17 19:16:42.629  1715  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 19:16:42.629  1715  4096 I SystemUpdateService: file has been verified
08-17 19:16:42.629  1715  4096 I SystemUpdateService: OTA package size = 12249756
,08-17 19:16:42.631  1715  4096 I SystemUpdateService: showing system update notification
,08-17 19:16:42.645  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-17 19:16:42.645  1715  1715 D SystemUpdateService: onDestroy
,08-17 19:16:42.646  1715  2512 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:42.647  1715  2512 I iu.UploadsManager: num updated entries: 0
08-17 19:16:42.647  1715  2512 I iu.SyncManager: NEXT; no task
,08-17 19:16:42.650  1715  4100 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 19:16:42.650  1715  4100 W BaseAppContext: Using Auth Proxy for data requests.
08-17 19:16:42.651  1715  4100 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 19:16:42.651  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 19:16:42.652  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 19:16:42.658  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:42.658  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:42.659  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:42.665  3984  3984 D SprintDMHelper: simOperator: 
,08-17 19:16:42.665  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:16:42.687  1503  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 19:16:42.687  1503  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-17 19:16:42.687  1503  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:42.687  1503  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:42.690   875  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:816::200e
,08-17 19:16:42.700  1715  4100 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-17 19:16:42.769   875  4083 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:16:42 GMT], X-Android-Received-Millis=[1471454202768], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471454202737]}
,08-17 19:16:42.770   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 19:16:42.771   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-17 19:16:42.771   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:16:42.778   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:16:42.780  2252  4104 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 19:16:42.790  1503  2993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 19:16:42.790  1503  2993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 19:16:42.791  1503  2993 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:42.791  1503  2993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:42.805  3560  4103 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 19:16:42.805  3560  4103 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jdm.a(PG:82)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jcs.o(PG:406)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jcn.a(PG:1379)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jcs.i(PG:143)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at blb.a(PG:3937)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at czp.a(PG:18188)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at czp.a(PG:9081)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at czq.run(PG:1686)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:16:42.805  3560  4103 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jdj.a(PG:4091)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jdj.a(PG:1125)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jdm.a(PG:77)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	... 12 more
08-17 19:16:42.805  3560  4103 E HttpOperation: Caused by: faj: BadAuthentication
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at fal.a(PG:38)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	at jdj.a(PG:4089)
08-17 19:16:42.805  3560  4103 E HttpOperation: 	... 14 more
,08-17 19:16:42.843  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 19:16:42.843  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 19:16:42.843  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:42.843  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:42.868  3560  4103 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 19:16:42.868  3560  4103 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jdm.a(PG:82)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jcs.o(PG:406)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jcn.a(PG:1379)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jcs.i(PG:143)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at hec.a(PG:42)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at hee.a(PG:102)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at czr.a(PG:65)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at kka.a(PG:108)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at czp.a(PG:19176)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at czp.a(PG:9081)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at czq.run(PG:1686)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:16:42.868  3560  4103 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jdj.a(PG:4091)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jdj.a(PG:1125)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jdm.a(PG:77)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	... 15 more
08-17 19:16:42.868  3560  4103 E HttpOperation: Caused by: faj: BadAuthentication
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at fal.a(PG:38)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	at jdj.a(PG:4089)
08-17 19:16:42.868  3560  4103 E HttpOperation: 	... 17 more
,08-17 19:16:42.869  3560  4103 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 19:16:42.869  3560  4103 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at hec.a(PG:42)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at hee.a(PG:102)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at czr.a(PG:65)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at kka.a(PG:108)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	... 15 more
08-17 19:16:42.869  3560  4103 E ExperimentLoader: Caused by: faj: BadAuthentication
,08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at fal.a(PG:38)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 19:16:42.869  3560  4103 E ExperimentLoader: 	... 17 more
,08-17 19:16:43.099   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 128068, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:16:43.569   875  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 19:16:43.863   875  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-17 19:16:44.138   875  1680 I ActivityManager: Killing 3418:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 19:16:44.386   875  2238 D WifiService: setWifiEnabled: false pid=3822, uid=10000
,08-17 19:16:44.386   875  2238 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:16:44.424  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 19:16:44.432   875  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 19:16:44.433   875  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 19:16:44.433   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:16:44.433   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:44.454   374   873 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:44.454   875  2091 D DhcpClient: Clearing IP address
08-17 19:16:44.457   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:44.461  1503  4108 V NativeCrypto: Read error: ssl=0x9b6f5000: I/O error during system call, Connection timed out
,08-17 19:16:44.463  1503  4108 V NativeCrypto: SSL shutdown failed: ssl=0x9b6f5000: I/O error during system call, Broken pipe
,08-17 19:16:44.466   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 19:16:44.466   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 19:16:44.469   875  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 19:16:44.470   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:16:44.473   407   407 E Parcel  : Reading a NULL string not supported here.
,08-17 19:16:44.475   374   873 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:44.482   875  4085 D DhcpClient: Receive thread stopped
,08-17 19:16:44.488  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.488  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:44.488  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:44.488  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.489   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 19:16:44.489  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:44.490   875  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.490  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:44.490  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:44.490  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.493  1882  2296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:44.494   875  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:16:44.523   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:44.558   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:44.559   875  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 19:16:44.559   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:44.561   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:16:44.563  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.563  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:44.564  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.564  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:44.571  2008  2008 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-17 19:16:44.575  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:16:44.578  1715  1715 D SystemUpdateService: onCreate
,08-17 19:16:44.581  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:16:44.587  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 19:16:44.593  1715  4120 I SystemUpdateService: active receiver: enabled
,08-17 19:16:44.594  1715  2512 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:44.595  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:16:44.596  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 19:16:44.598  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:44.602  3984  3984 D SprintDMHelper: simOperator: 
,08-17 19:16:44.602  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:16:44.608  1715  2512 I iu.UploadsManager: num updated entries: 0
,08-17 19:16:44.616   374   873 E Netd    : netlink response contains error (No such file or directory)
,08-17 19:16:44.617   875  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 19:16:44.629  1715  4120 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:16:44.629  2252  4124 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 19:16:44.633  1715  2512 I iu.SyncManager: NEXT; no task
,08-17 19:16:44.638  1715  4120 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 19:16:44.638  1715  4120 I SystemUpdateService: now status is 0 (complete)
08-17 19:16:44.638  1715  4120 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 19:16:44.638  1715  4120 I SystemUpdateService: file has been verified
,08-17 19:16:44.638  1715  4120 I SystemUpdateService: OTA package size = 12249756
,08-17 19:16:44.643  1715  4120 I SystemUpdateService: showing system update notification
,08-17 19:16:44.651  1715  1715 D SystemUpdateService: onDestroy
,08-17 19:16:47.430   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a39c4c5:true
,08-17 19:16:47.430  3969  3969 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 19:16:47.435  3969  3969 I bt_bluedroid: init
,08-17 19:16:47.435  3969  4127 I BluetoothAdapterState: Entering OffState
,08-17 19:16:47.439  3969  4128 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:16:47.439  3969  4128 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:16:47.440  3969  4128 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:47.440  3969  4128 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:16:47.440  3969  3969 I bt_bluedroid: get_profile_interface socket
,08-17 19:16:47.442  3969  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 19:16:47.443  3969  3969 I bt_bluedroid: get_profile_interface sdp
,08-17 19:16:47.443  3969  4131 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:16:47.447  3969  3980 I bt_bluedroid: config_hci_snoop_log
,08-17 19:16:47.455   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:16:47.460  3969  4127 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 19:16:47.460  3969  4127 D BluetoothAdapterProperties: Setting state to 14
,08-17 19:16:47.460  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 19:16:47.461  3969  4127 D BluetoothBondStateMachine: make
,08-17 19:16:47.463  3969  4132 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:16:47.466  3969  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:47.467  3969  3969 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 19:16:47.469  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
08-17 19:16:47.470  3969  3969 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:47.470  3969  3969 D BtGatt.GattService: Received start request. Starting profile...
,08-17 19:16:47.471  3969  3969 D BtGatt.GattService: start()
,08-17 19:16:47.471  3969  3969 I bt_bluedroid: get_profile_interface gatt
08-17 19:16:47.472  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:47.472  3969  3969 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:16:47.477  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:47.477  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:47.477  3969  3969 V BluetoothAdapterState: isBleTurningOn()=true
08-17 19:16:47.478  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:47.478  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 19:16:47.478  3969  4127 I bt_bluedroid: enable
08-17 19:16:47.479  3969  4128 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
08-17 19:16:47.479  3969  4128 I bt_hci  : start_up
,08-17 19:16:47.485  3969  4128 I bt_vendor: alloc value 0xb39e9189
,08-17 19:16:47.486  3969  4128 I bt_vendor: init
08-17 19:16:47.486  3969  4128 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 19:16:47.486  3969  4128 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 19:16:47.592  3969  4128 D bt_hci  : start_up starting async portion
08-17 19:16:47.592  3969  4135 I bt_hci  : event_finish_startup
,08-17 19:16:47.593  3969  4135 I bt_hci_h4: hal_open
08-17 19:16:47.593  3969  4135 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 19:16:47.597  3969  4135 I bt_userial_vendor: device fd = 51 open
,08-17 19:16:47.635  3969  4135 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:16:47.667  3969  4135 D bt_hwcfg: Chipset BCM4354A2
,08-17 19:16:47.668  3969  4135 D bt_hwcfg: Target name = [BCM4354A2]
08-17 19:16:47.668  3969  4135 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 19:16:48.331  3969  4135 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 19:16:48.332  3969  4135 D bt_hwcfg: Settlement delay -- 100 ms
08-17 19:16:48.333  3969  4135 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 19:16:48.449  3969  4135 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:16:48.451  3969  4135 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 19:16:48.480  3969  4135 I bt_hwcfg: vendor lib fwcfg completed
,08-17 19:16:48.480  3969  4135 I bt_vendor: firmware callback
,08-17 19:16:48.480  3969  4135 I bt_hci  : firmware_config_callback
,08-17 19:16:48.492  3969  4137 I bt_btu  : btu_task pending for preload complete event
,08-17 19:16:48.492  3969  4137 I bt_btu_task: Bluetooth chip preload is complete
08-17 19:16:48.492  3969  4137 I bt_btu  : btu_task received preload complete event
,08-17 19:16:48.502  3969  4137 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:16:48.503  3969  4137 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:16:48.503  3969  4137 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 19:16:48.503  3969  4137 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 19:16:48.504  3969  4137 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 19:16:48.504  3969  4137 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:16:48.504  3969  4137 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:16:48.505  3969  4137 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:16:48.505  3969  4137 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:16:48.505  3969  4137 I         : BTE_InitTraceLevels -- TRC_PAN
,08-17 19:16:48.505  3969  4137 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 19:16:48.506  3969  4137 I         : BTE_InitTraceLevels -- TRC_GATT
,08-17 19:16:48.506  3969  4137 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 19:16:48.506  3969  4137 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:16:48.506  3969  4137 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 19:16:48.642  3969  4137 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
08-17 19:16:48.642  3969  4137 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-17 19:16:48.654  3969  4131 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 19:16:48.655  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 19:16:48.656  3969  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 19:16:48.659  3969  4131 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:16:48.663  3969  4131 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:48.663  3969  4131 D BluetoothAdapterProperties: Discoverable Timeout:120,
,08-17 19:16:48.664  3969  4131 D bt_hci  : do_postload posting postload work item
,08-17 19:16:48.664  3969  4135 I bt_hci  : event_postload
,08-17 19:16:48.664  3969  4135 I bt_vendor: sco_config_cb
,08-17 19:16:48.664  3969  4135 I bt_hci  : sco_config_callback postload finished.
,08-17 19:16:48.667  3969  4131 D bt_bte_conf: Device ID record 1 : primary
,08-17 19:16:48.667  3969  4131 D bt_bte_conf:   vendorId            = 000f
,08-17 19:16:48.667  3969  4131 D bt_bte_conf:   vendorIdSource      = 0001
08-17 19:16:48.667  3969  4131 D bt_bte_conf:   product             = 1200
,08-17 19:16:48.668  3969  4131 D bt_bte_conf:   version             = 1436
,08-17 19:16:48.668  3969  4131 D bt_bte_conf:   clientExecutableURL = 
,08-17 19:16:48.668  3969  4131 D bt_bte_conf:   serviceDescription  = 
08-17 19:16:48.668  3969  4131 D bt_bte_conf:   documentationURL    = 
,08-17 19:16:48.669  3969  4131 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:16:48.669  3969  4128 D bt_stack_manager: event_start_up_stack finished
08-17 19:16:48.669  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:48.670  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 19:16:48.671  3969  4127 D BluetoothAdapterProperties: Setting state to 15
,08-17 19:16:48.671  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
08-17 19:16:48.673  3969  4135 I bt_vendor: low_power_mode_cb
08-17 19:16:48.675  3969  4127 I BluetoothAdapterState: Entering BleOnState
,08-17 19:16:48.678  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:48.681  3969  4127 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 19:16:48.681  3969  4127 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:16:48.681  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 19:16:48.689  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
08-17 19:16:48.694  3969  3969 D HeadsetService: Received start request. Starting profile...
,08-17 19:16:48.697  3969  3969 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:16:48.698  3969  3969 D HeadsetStateMachine: make
,08-17 19:16:48.704  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:48.706  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:48.706  3969  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:48.710  3969  3969 D HeadsetStateMachine: max_hf_connections = 1
,08-17 19:16:48.710  3969  3969 I bt_bluedroid: get_profile_interface handsfree
08-17 19:16:48.711  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 19:16:48.711  3969  4131 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 19:16:48.716  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:48.717  3969  3969 D A2dpService: Received start request. Starting profile...
,08-17 19:16:48.717  3969  3969 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:48.718  3969  3969 I bt_bluedroid: get_profile_interface avrcp
,08-17 19:16:48.724  3969  3969 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:48.725  3969  3969 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:16:48.725  3969  3969 D A2dpStateMachine: make
,08-17 19:16:48.726  3969  3969 I bt_bluedroid: get_profile_interface a2dp
,08-17 19:16:48.727  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 19:16:48.728  3969  3969 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:48.729  3969  4146 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:16:48.729  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:48.731  3969  3969 D HidService: Received start request. Starting profile...
08-17 19:16:48.731  3969  3969 I bt_bluedroid: get_profile_interface hidhost
,08-17 19:16:48.731  3889  3889 D BluetoothInputDevice: Proxy object connected
08-17 19:16:48.731  3969  4131 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-17 19:16:48.731  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 19:16:48.731  3969  3969 D HidService: setHidService(): set to: null
08-17 19:16:48.732  3969  3969 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 19:16:48.732  3889  3889 D HidProfile: Bluetooth service connected
08-17 19:16:48.732  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
08-17 19:16:48.733  3969  3969 D HealthService: Received start request. Starting profile...
,08-17 19:16:48.736  3969  3969 I bt_bluedroid: get_profile_interface health
,08-17 19:16:48.737  3969  3969 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:48.737  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:48.738  3969  3969 D PanService: Received start request. Starting profile...
,08-17 19:16:48.738  3889  3889 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:48.739  3969  3969 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:48.739  3969  3969 I bt_bluedroid: get_profile_interface pan
08-17 19:16:48.739  3969  4131 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:48.740  3889  3889 D PanProfile: Bluetooth service connected
,08-17 19:16:48.741  3969  3969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:48.742  3969  3969 D BluetoothMapService: Received start request. Starting profile...
08-17 19:16:48.743  3969  3969 D BluetoothMapService: start()
,08-17 19:16:48.743  3889  3889 D BluetoothMap: Proxy object connected
,08-17 19:16:48.744  3889  3889 D MapProfile: Bluetooth service connected
08-17 19:16:48.744  3889  3889 D BluetoothMap: getConnectedDevices()
,08-17 19:16:48.745  3889  3889 D BluetoothMap: Bluetooth is Not enabled
08-17 19:16:48.745  3969  3969 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-17 19:16:48.745  3969  3969 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 19:16:48.746  3969  3969 D BluetoothMapAppObserver: createReceiver()
,08-17 19:16:48.746  3969  3969 D BluetoothMapAppObserver: initObservers()
08-17 19:16:48.746  3969  3969 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 19:16:48.755  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:48.755  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:48.755  3969  3969 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:48.756  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:48.756  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:48.757  3969  4143 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:48.758  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:48.759  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:48.759  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 19:16:48.759  3969  4127 D BluetoothAdapterProperties: ScanMode =  20
,08-17 19:16:48.759  3969  4127 D BluetoothAdapterProperties: State =  11
,08-17 19:16:48.761  3969  4127 D BluetoothAdapterProperties: Setting state to 12
,08-17 19:16:48.761  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 19:16:48.762  3969  4127 I BluetoothAdapterState: Entering OnState
,08-17 19:16:48.763  3889  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:16:48.763  3969  4131 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:48.763  3969  4131 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:48.764  1365  2040 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:48.767  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:48.767  1365  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:16:48.767  1365  1365 D BluetoothA2dp: Proxy object connected
08-17 19:16:48.769  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:48.770  1365  1365 D BluetoothInputDevice: Proxy object connected
08-17 19:16:48.770  1365  1365 D HidProfile: Bluetooth service connected
,08-17 19:16:48.771  1365  2040 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:48.772  1365  2013 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:48.772  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:48.773   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:48.774  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:48.774   875   875 D BluetoothA2dp: Proxy object connected
08-17 19:16:48.774  3969  3969 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 19:16:48.774   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:48.775  3889  3901 D BluetoothPan: onBluetoothStateChange on: true
,08-17 19:16:48.775  3969  3969 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 19:16:48.776  3889  3900 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:48.777  3969  3969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:48.778   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:48.778  3889  3901 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:16:48.778  3969  3969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:48.779  1365  1381 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:16:48.779  3969  3969 D ObexServerSockets: Succeed to create listening sockets 
,08-17 19:16:48.780  3969  3969 D ObexServerSockets0: startAccept()
08-17 19:16:48.780  3969  3969 D ObexServerSockets0: prepareForNewConnect()
08-17 19:16:48.780  1938  2194 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:16:48.780  1365  1365 D BluetoothMap: Proxy object connected
,08-17 19:16:48.781  1365  1365 D MapProfile: Bluetooth service connected
,08-17 19:16:48.781  1365  1365 D BluetoothMap: getConnectedDevices()
08-17 19:16:48.781   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:48.781  1365  2040 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:16:48.781  3969  3969 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 19:16:48.782  3969  3969 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 19:16:48.783  3969  4154 D ObexServerSockets0: Accepting socket connection...
08-17 19:16:48.783  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:48.783  1365  1365 D PanProfile: Bluetooth service connected
,08-17 19:16:48.784  3969  4153 D ObexServerSockets0: Accepting socket connection...
,08-17 19:16:48.785   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 19:16:48.785  3969  3969 D BluetoothMapService: onReceive
08-17 19:16:48.785  3969  3969 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:48.785  3969  3969 D BluetoothMapService: STATE_ON
,08-17 19:16:48.787  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:48.788  3889  3889 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 19:16:48.788  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:48.791  3889  3889 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 19:16:48.797  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:48.799  3889  3889 D BluetoothA2dp: Proxy object connected
,08-17 19:16:48.802  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:48.809  3889  3889 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:48.810  1365  1365 D BluetoothPbap: Proxy object connected
,08-17 19:16:48.810  1365  1365 D PbapServerProfile: Bluetooth service connected
08-17 19:16:48.810  3969  3969 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 19:16:48.810  3969  3969 D ObexServerSockets0: prepareForNewConnect()
,08-17 19:16:48.813  3889  3889 D BluetoothPbap: Proxy object connected
,08-17 19:16:48.814  3889  3889 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:48.825  3969  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:48.837  3969  4163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:48.838  3969  4163 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:48.874   875   875 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.874   875   875 D BluetoothHeadset: Proxy object connected
08-17 19:16:48.874   875   875 D BluetoothHeadset: Proxy object connected
08-17 19:16:48.875  1365  1381 D BluetoothHeadset: Proxy object connected
08-17 19:16:48.875  1365  1365 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:48.875   875   892 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.875  1938  1950 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.878   875   892 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.881  1938  1951 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.882   875   892 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.893  3889  3900 D BluetoothHeadset: Proxy object connected
,08-17 19:16:48.896  3889  3889 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:50.405  3969  4127 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 19:16:50.406  3969  4127 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:50.406  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:50.408  3969  4127 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 19:16:50.417  3969  3969 D BluetoothMapService: onReceive
,08-17 19:16:50.417  3969  3969 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:50.417  3969  3969 D BluetoothMapService: STATE_TURNING_OFF
,08-17 19:16:50.418  3969  3969 D BluetoothMapService: MAP Service closeService in
08-17 19:16:50.418  3969  3969 D BluetoothMapMasInstance0: MAP Service shutdown,
08-17 19:16:50.419  3969  3969 D ObexServerSockets0: shutdown(block = true)
,08-17 19:16:50.421  3969  4153 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 19:16:50.422  3969  3969 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:16:50.423  3969  4154 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-17 19:16:50.423  3969  4131 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:50.424  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.424  3969  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:50.424  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:50.425  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 19:16:50.425  3969  4139 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-17 19:16:50.426  3969  3969 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:16:50.427  3969  3969 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:50.427  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.427  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:50.427  3969  4163 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 19:16:50.428  3969  4163 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 19:16:50.431  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:16:50.436  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:50.436  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:50.436  3969  3969 D HeadsetService: Received stop request...Stopping profile...
08-17 19:16:50.439  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.439  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:50.442  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:50.442   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 19:16:50.442   875   875 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:50.442   875   875 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:50.443  3889  3901 D BluetoothHeadset: Proxy object disconnected
,08-17 19:16:50.443  1365  1376 D BluetoothHeadset: Proxy object disconnected
08-17 19:16:50.444  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:50.444  1938  2122 D BluetoothHeadset: Proxy object disconnected
08-17 19:16:50.445  3969  3969 D A2dpService: Received stop request...Stopping profile...
08-17 19:16:50.446  3969  4146 D A2dpStateMachine: Exit Disconnected: -1
08-17 19:16:50.447   875   875 D BluetoothA2dp: Proxy object disconnected
,08-17 19:16:50.448  3969  3969 D HidService: Received stop request...Stopping profile...
,08-17 19:16:50.448  3969  3969 D HidService: Stopping Bluetooth HidService
,08-17 19:16:50.450  3969  3969 D HealthService: Received stop request...Stopping profile...
08-17 19:16:50.451  3969  3969 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:50.451  3969  3969 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:16:50.451  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.451  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.454  3969  3969 D PanService: Received stop request...Stopping profile...
08-17 19:16:50.454  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:50.455   875  1309 D ConnectivityService: handlePromptUnvalidated 101
08-17 19:16:50.457  3969  3969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 19:16:50.458  3969  3969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:16:50.458  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:16:50.458  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:50.458  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:50.458  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-17 19:16:50.458  3969  4131 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-17 19:16:50.458  3969  3969 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:50.459  3969  3969 D BluetoothMapService: stop()
08-17 19:16:50.459  3969  3969 D BluetoothMapAppObserver: deinitObservers()
08-17 19:16:50.459  3969  3969 D BluetoothMapAppObserver: removeReceiver()
08-17 19:16:50.461  3969  3969 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:50.461  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:50.461  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:50.461  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.462  1365  1365 D HeadsetProfile: Bluetooth service disconnected
08-17 19:16:50.462  1365  1365 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:50.463  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 19:16:50.463  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:50.463  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:16:50.463  1365  1365 D BluetoothInputDevice: Proxy object disconnected
08-17 19:16:50.463  1365  1365 D HidProfile: Bluetooth service disconnected
08-17 19:16:50.463  3969  4137 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:50.463  3969  4137 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:50.463  3969  4137 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:50.463  3969  4137 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:50.464  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:50.464  1365  1365 D PanProfile: Bluetooth service disconnected
,08-17 19:16:50.464  3969  3969 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:50.464  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:50.464  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.464  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.465  1365  1365 D BluetoothMap: Proxy object disconnected
08-17 19:16:50.465  1365  1365 D MapProfile: Bluetooth service disconnected
08-17 19:16:50.465  3969  3969 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-17 19:16:50.465  3969  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 19:16:50.465  3969  3969 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:50.466  3969  3969 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:50.466  3969  3969 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:16:50.466  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.466  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.466  3969  3969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:50.466  3969  4131 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 19:16:50.466  3969  3969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 19:16:50.469  1365  1365 D BluetoothPbap: Proxy object disconnected
08-17 19:16:50.469  1365  1365 D PbapServerProfile: Bluetooth service disconnected
08-17 19:16:50.470  3969  3969 V BluetoothAdapterState: isTurningOff()=true
08-17 19:16:50.470  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:50.470  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.470  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.470  3969  3969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 19:16:50.471  3969  3969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:16:50.474  3969  3969 D BluetoothMapService: MAP Service closeService in
08-17 19:16:50.474  3969  3969 V BluetoothAdapterState: isTurningOff()=true
,08-17 19:16:50.474  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:50.474  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.475  3969  3969 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:50.475  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 19:16:50.475  3969  4127 D BluetoothAdapterProperties: Setting state to 15
08-17 19:16:50.475  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 19:16:50.475  3969  3969 D BluetoothMapService: cleanup()
08-17 19:16:50.476  3969  3969 D BluetoothMapService: MAP Service closeService in
08-17 19:16:50.476  3969  4127 I BluetoothAdapterState: Entering BleOnState
08-17 19:16:50.476  3889  3901 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 19:16:50.477  1365  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:50.478  1365  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 19:16:50.479  1365  2013 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.479  3889  3889 D DockEventReceiver: finishStartingService: stopping service
08-17 19:16:50.480  1365  2040 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 19:16:50.480   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.480  3889  3901 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.481   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.481  3889  3900 D BluetoothPan: onBluetoothStateChange on: false
,08-17 19:16:50.481  3889  3889 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:50.482  3889  3900 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 19:16:50.482   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.482  3889  3901 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.482  3889  3889 D BluetoothMap: Proxy object disconnected
,08-17 19:16:50.482  3889  3900 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:50.482  3889  3889 D MapProfile: Bluetooth service disconnected
,08-17 19:16:50.484  1365  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-17 19:16:50.484  1938  2194 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.484   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:16:50.484  1365  2013 D BluetoothPan: onBluetoothStateChange on: false
,08-17 19:16:50.486  3969  4127 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 19:16:50.486  3969  4127 D BluetoothAdapterProperties: Setting state to 16
08-17 19:16:50.486  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 19:16:50.487  3969  4127 D BluetoothAdapterProperties: onBleDisable
08-17 19:16:50.487  3969  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:50.487  3969  4128 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 19:16:50.488  3969  4137 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:16:50.488  3969  4137 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:16:50.489  3969  4131 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:50.489  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:50.491  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:50.492  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:50.493  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:50.494  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:16:50.498  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:50.503  3889  3889 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:50.689  3969  4131 I bt_hci  : shut_down
,08-17 19:16:50.689  3969  4135 D bt_hwcfg: hw_epilog_process
,08-17 19:16:50.701  3969  4135 I bt_vendor: low_power_mode_cb
,08-17 19:16:50.723  3969  4135 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 19:16:50.723  3969  4135 I bt_vendor: epilog_cb
08-17 19:16:50.724  3969  4135 I bt_hci  : epilog_finished_callback
,08-17 19:16:50.731  3969  4131 I bt_hci_h4: hal_close
,08-17 19:16:50.732  3969  4131 I bt_userial_vendor: device fd = 51 close
,08-17 19:16:50.859  3969  4128 D bt_stack_manager: event_shut_down_stack finished.
,08-17 19:16:50.860  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 19:16:50.866  3969  3969 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:50.867  3969  4127 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 19:16:50.868  3969  3969 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:16:50.868  3969  3969 D BtGatt.GattService: stop()
08-17 19:16:50.868  3969  3969 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:16:50.873  3969  3969 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:50.873  3969  3969 V BluetoothAdapterState: isTurningOn()=false
08-17 19:16:50.874  3969  3969 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:50.874  3969  3969 V BluetoothAdapterState: isBleTurningOff()=true
08-17 19:16:50.875  3969  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 19:16:50.875  3969  4127 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:50.876  3969  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 19:16:50.878  3969  4127 I BluetoothAdapterState: Entering OffState
08-17 19:16:50.880   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 19:16:50.931   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 19:16:50.942   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:16:50.942   875   895 I Adreno  : Build Date                       : 10/20/15
08-17 19:16:50.942   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:16:50.942   875   895 I Adreno  : Local Branch                     : M14
08-17 19:16:50.942   875   895 I Adreno  : Remote Branch                    : 
08-17 19:16:50.942   875   895 I Adreno  : Remote Branch                    : 
08-17 19:16:50.942   875   895 I Adreno  : Reconstruct Branch               : 
,08-17 19:16:50.973  3969  3969 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 19:16:50.975  3969  3969 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-17 19:16:50.975  3969  3969 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 19:16:50.976   281   358 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
,08-17 19:16:50.977  3969  4128 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 19:16:50.970  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 19:16:50.988  3969  4128 D bt_stack_manager: event_clean_up_stack finished.
,08-17 19:16:50.992  3969  3969 I art     : System.exit called, status: 0
,08-17 19:16:50.992  3969  3969 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 19:16:51.052   875  1965 I ActivityManager: Process com.android.bluetooth (pid 3969) has died
,08-17 19:16:51.184  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:51.193  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:51.196  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:51.228  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 19:16:51.229  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-17 19:16:51.229  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:51.229  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:51.264  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 19:16:51.265  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 19:16:51.266  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-17 19:16:51.558  3822  3822 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:16:51.558  3822  3822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 19:16:51.626   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 19:16:51.626  3822  3822 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f793b3b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e159d23, 16908290=android.view.AbsSavedState$1@e159d23}, android:focusedViewId=100}]}]
08-17 19:16:51.626  3822  3822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 19:16:51.627  3822  3822 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 19:16:51.627  3822  3822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 19:16:51.629   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 19:16:51.634   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 19:16:51.635   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-17 19:16:51.640   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 19:16:51.867   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 19:16:51.872   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 19:16:51.878   875  1332 D SurfaceControl: Excessive delay in setPowerMode(): 245ms
,08-17 19:16:51.881   875   895 I DreamManagerService: Entering dreamland.
,08-17 19:16:51.883   875   895 I PowerManagerService: Dozing...
08-17 19:16:51.884   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 19:16:51.939   378  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-17 19:16:51.939   378  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 19:16:51.955  1925  4176 D NfcService: Discovery configuration equal, not updating.
,08-17 19:16:51.957   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:16:51.965   875  1307 E native  : do suspend false
,08-17 19:16:52.000   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:16:52.006   875  1307 E native  : do suspend true
,08-17 19:16:52.079   378  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 19:16:52.080   378  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 19:16:53.401  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:53.402  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:56.230  1882  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 19:16:56.409  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:56.410  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@126c220 added. We now have 6 listener(s)
,08-17 19:16:56.410  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:56.414  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:56.414  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16697d9 added. We now have 7 listener(s)
,08-17 19:16:56.414  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:56.417  3822  3871 I System.out: IsBluetoothEnabled
,08-17 19:16:56.428  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.459   875   892 I ActivityManager: Start proc 4183:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 19:16:56.585  4183  4183 D AdapterServiceConfig: Adding HeadsetService
,08-17 19:16:56.585  4183  4183 D AdapterServiceConfig: Adding A2dpService
,08-17 19:16:56.585  4183  4183 D AdapterServiceConfig: Adding HidService
,08-17 19:16:56.586  4183  4183 D AdapterServiceConfig: Adding HealthService
,08-17 19:16:56.586  4183  4183 D AdapterServiceConfig: Adding PanService
,08-17 19:16:56.586  4183  4183 D AdapterServiceConfig: Adding GattService
,08-17 19:16:56.586  4183  4183 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 19:16:56.604  4183  4183 D BluetoothAdapterState: make() - Creating AdapterState
08-17 19:16:56.603   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a238fd7:true
,08-17 19:16:56.609  4183  4183 I bt_bluedroid: init
,08-17 19:16:56.610  4183  4195 I BluetoothAdapterState: Entering OffState
,08-17 19:16:56.616  4183  4196 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:16:56.616  4183  4196 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:16:56.616  4183  4196 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:56.617  4183  4196 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:16:56.619  4183  4183 I bt_bluedroid: get_profile_interface socket
,08-17 19:16:56.621  4183  4183 I bt_bluedroid: get_profile_interface sdp
,08-17 19:16:56.625  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 19:16:56.628  4183  4194 I bt_bluedroid: config_hci_snoop_log
,08-17 19:16:56.628  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:16:56.632   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:16:56.643  4183  4195 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 19:16:56.644  4183  4195 D BluetoothAdapterProperties: Setting state to 14
,08-17 19:16:56.644  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 19:16:56.647  4183  4195 D BluetoothBondStateMachine: make
,08-17 19:16:56.652  4183  4200 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:16:56.659  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:16:56.661  4183  4183 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 19:16:56.669  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:56.671  4183  4183 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:56.673  4183  4183 D BtGatt.GattService: Received start request. Starting profile...,
,08-17 19:16:56.673  4183  4183 D BtGatt.GattService: start(),
08-17 19:16:56.674  4183  4183 I bt_bluedroid: get_profile_interface gatt
,08-17 19:16:56.676  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
08-17 19:16:56.676  4183  4183 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:16:56.689  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:56.689  4183  4183 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:16:56.689  4183  4183 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 19:16:56.689  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:56.690  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 19:16:56.690  4183  4195 I bt_bluedroid: enable
,08-17 19:16:56.691  4183  4196 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 19:16:56.691  4183  4196 I bt_hci  : start_up
,08-17 19:16:56.699  4183  4196 I bt_vendor: alloc value 0xb3a46189
,08-17 19:16:56.699  4183  4196 I bt_vendor: init
,08-17 19:16:56.699  4183  4196 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 19:16:56.699  4183  4196 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 19:16:56.807  4183  4196 D bt_hci  : start_up starting async portion
,08-17 19:16:56.808  4183  4203 I bt_hci  : event_finish_startup
,08-17 19:16:56.808  4183  4203 I bt_hci_h4: hal_open
08-17 19:16:56.808  4183  4203 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 19:16:56.817  4183  4203 I bt_userial_vendor: device fd = 51 open
,08-17 19:16:56.849  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:16:56.881  4183  4203 D bt_hwcfg: Chipset BCM4354A2
,08-17 19:16:56.882  4183  4203 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 19:16:56.883  4183  4203 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 19:16:57.543  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 19:16:57.545  4183  4203 D bt_hwcfg: Settlement delay -- 100 ms
08-17 19:16:57.545  4183  4203 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 19:16:57.662  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:16:57.663  4183  4203 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 19:16:57.692  4183  4203 I bt_hwcfg: vendor lib fwcfg completed
,08-17 19:16:57.693  4183  4203 I bt_vendor: firmware callback
,08-17 19:16:57.693  4183  4203 I bt_hci  : firmware_config_callback
,08-17 19:16:57.704  4183  4205 I bt_btu  : btu_task pending for preload complete event
,08-17 19:16:57.704  4183  4205 I bt_btu_task: Bluetooth chip preload is complete
08-17 19:16:57.704  4183  4205 I bt_btu  : btu_task received preload complete event
,08-17 19:16:57.717  4183  4205 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:16:57.717  4183  4205 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:16:57.717  4183  4205 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 19:16:57.717  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:16:57.718  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:16:57.718  4183  4205 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 19:16:57.718  4183  4205 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:16:57.719  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:16:57.719  4183  4205 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 19:16:57.719  4183  4205 I         : BTE_InitTraceLevels -- TRC_PAN
,08-17 19:16:57.719  4183  4205 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:16:57.720  4183  4205 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:16:57.720  4183  4205 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 19:16:57.720  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:16:57.720  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 19:16:57.854  4183  4205 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c3d9d
,08-17 19:16:57.854  4183  4205 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c3d9d 
,08-17 19:16:57.865  4183  4199 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 19:16:57.866  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 19:16:57.867  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 19:16:57.870  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:16:57.873  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:57.874  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:57.874  4183  4199 D bt_hci  : do_postload posting postload work item
,08-17 19:16:57.875  4183  4203 I bt_hci  : event_postload
,08-17 19:16:57.875  4183  4203 I bt_vendor: sco_config_cb
,08-17 19:16:57.876  4183  4203 I bt_hci  : sco_config_callback postload finished.
,08-17 19:16:57.880  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.877  4183  4199 D bt_bte_conf: Device ID record 1 : primary
08-17 19:16:57.880  4183  4199 D bt_bte_conf:   vendorId            = 000f
08-17 19:16:57.880  4183  4199 D bt_bte_conf:   vendorIdSource      = 0001
08-17 19:16:57.880  4183  4199 D bt_bte_conf:   product             = 1200
08-17 19:16:57.880  4183  4199 D bt_bte_conf:   version             = 1436
08-17 19:16:57.881  4183  4199 D bt_bte_conf:   clientExecutableURL = 
08-17 19:16:57.881  4183  4199 D bt_bte_conf:   serviceDescription  = 
08-17 19:16:57.881  4183  4199 D bt_bte_conf:   documentationURL    = 
08-17 19:16:57.882  4183  4199 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 19:16:57.882  4183  4196 D bt_stack_manager: event_start_up_stack finished
08-17 19:16:57.884  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 19:16:57.885  4183  4195 D BluetoothAdapterProperties: Setting state to 15
08-17 19:16:57.885  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 19:16:57.885  4183  4203 I bt_vendor: low_power_mode_cb
08-17 19:16:57.886  4183  4195 I BluetoothAdapterState: Entering BleOnState
08-17 19:16:57.896  4183  4195 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 19:16:57.896  4183  4195 D BluetoothAdapterProperties: Setting state to 11
08-17 19:16:57.897  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 19:16:57.912  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:57.913  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.915  4183  4183 D HeadsetService: Received start request. Starting profile...
,08-17 19:16:57.918  4183  4183 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:16:57.918  4183  4183 D HeadsetStateMachine: make
,08-17 19:16:57.926  4183  4183 D HeadsetStateMachine: max_hf_connections = 1
08-17 19:16:57.926  4183  4183 I bt_bluedroid: get_profile_interface handsfree
08-17 19:16:57.927  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
08-17 19:16:57.928  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 19:16:57.928  4183  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-17 19:16:57.932  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.934  4183  4183 D A2dpService: Received start request. Starting profile...
,08-17 19:16:57.935  4183  4183 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:57.936  4183  4183 I bt_bluedroid: get_profile_interface avrcp
,08-17 19:16:57.947  4183  4183 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:57.948  4183  4183 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:16:57.948  4183  4183 D A2dpStateMachine: make
,08-17 19:16:57.950  4183  4183 I bt_bluedroid: get_profile_interface a2dp
,08-17 19:16:57.951  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 19:16:57.954  4183  4214 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:16:57.957  4183  4183 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:57.958  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:57.961  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.962  4183  4183 D HidService: Received start request. Starting profile...
08-17 19:16:57.963  4183  4183 I bt_bluedroid: get_profile_interface hidhost
08-17 19:16:57.963  4183  4183 D HidService: setHidService(): set to: null
08-17 19:16:57.963  4183  4199 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a53e5
,08-17 19:16:57.963  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 19:16:57.964  4183  4183 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 19:16:57.965  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.967  4183  4183 D HealthService: Received start request. Starting profile...
,08-17 19:16:57.970  4183  4183 I bt_bluedroid: get_profile_interface health
,08-17 19:16:57.972  4183  4183 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:57.974  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.975  4183  4183 D PanService: Received start request. Starting profile...
,08-17 19:16:57.976  4183  4183 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 19:16:57.976  4183  4183 I bt_bluedroid: get_profile_interface pan
,08-17 19:16:57.977  4183  4199 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:57.983  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:16:57.984  4183  4183 D BluetoothMapService: Received start request. Starting profile...
,08-17 19:16:57.985  4183  4183 D BluetoothMapService: start()
,08-17 19:16:57.990  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 19:16:57.993  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 19:16:57.993  4183  4183 D BluetoothMapAppObserver: createReceiver()
,08-17 19:16:57.996  4183  4183 D BluetoothMapAppObserver: initObservers()
,08-17 19:16:57.996  4183  4183 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 19:16:58.013  4183  4212 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 19:16:58.014  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:58.014  4183  4183 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:16:58.014  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:58.015  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:58.017  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:58.017  4183  4183 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:16:58.018  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:58.018  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:58.021  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:58.021  4183  4183 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-17 19:16:58.022  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:16:58.023  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:16:58.023  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-17 19:16:58.023  4183  4183 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:16:58.023  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:16:58.023  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:16:58.023  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 19:16:58.023  4183  4195 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:16:58.024  4183  4195 D BluetoothAdapterProperties: State =  11
08-17 19:16:58.024  4183  4195 D BluetoothAdapterProperties: Setting state to 12
08-17 19:16:58.024  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 19:16:58.026  4183  4195 I BluetoothAdapterState: Entering OnState
08-17 19:16:58.026  4183  4199 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:58.026  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:58.026  3889  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:16:58.030  1365  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:58.032  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 19:16:58.033  1365  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:16:58.033  4183  4183 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.033  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:58.035  1365  1365 D BluetoothInputDevice: Proxy object connected
08-17 19:16:58.036  1365  1365 D HidProfile: Bluetooth service connected
08-17 19:16:58.036  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:58.036  3889  3889 D BluetoothInputDevice: Proxy object connected
08-17 19:16:58.036  3889  3889 D HidProfile: Bluetooth service connected
,08-17 19:16:58.038  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:58.039  1365  2040 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:58.040  1365  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:58.041  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:58.042   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:58.043  3889  3901 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:58.043  4183  4183 D ObexServerSockets: Succeed to create listening sockets 
08-17 19:16:58.043  4183  4183 D ObexServerSockets0: startAccept()
08-17 19:16:58.043  4183  4183 D ObexServerSockets0: prepareForNewConnect()
08-17 19:16:58.044   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:58.045  3889  3900 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:16:58.047  4183  4183 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 19:16:58.048  4183  4183 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 19:16:58.048  3889  4168 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:58.049   875   875 D BluetoothA2dp: Proxy object connected
08-17 19:16:58.050  1365  1365 D BluetoothA2dp: Proxy object connected
08-17 19:16:58.052  4183  4222 D ObexServerSockets0: Accepting socket connection...
08-17 19:16:58.052   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:16:58.052  4183  4221 D ObexServerSockets0: Accepting socket connection...
08-17 19:16:58.052  3889  3901 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:58.053  3889  3900 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:58.057  1365  1381 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:16:58.058  1365  1365 D BluetoothMap: Proxy object connected
,08-17 19:16:58.058  1365  1365 D MapProfile: Bluetooth service connected
08-17 19:16:58.058  1365  1365 D BluetoothMap: getConnectedDevices()
08-17 19:16:58.058  1938  2194 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:58.059   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:16:58.059  1365  1376 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:16:58.059  3889  3889 D BluetoothA2dp: Proxy object connected
,08-17 19:16:58.060  3889  3889 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:58.060  3889  3889 D PanProfile: Bluetooth service connected
08-17 19:16:58.060  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:58.060  3889  3889 D BluetoothMap: Proxy object connected
08-17 19:16:58.060  1365  1365 D PanProfile: Bluetooth service connected
,08-17 19:16:58.060  3889  3889 D MapProfile: Bluetooth service connected
08-17 19:16:58.061  3889  3889 D BluetoothMap: getConnectedDevices()
08-17 19:16:58.061   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 19:16:58.062  4183  4183 D BluetoothMapService: onReceive
08-17 19:16:58.062  4183  4183 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:58.062  4183  4183 D BluetoothMapService: STATE_ON
08-17 19:16:58.063  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:58.067  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:58.073  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:58.080  3889  3889 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:58.082  3889  3889 D BluetoothPbap: Proxy object connected
,08-17 19:16:58.082  3889  3889 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:58.086  1365  1365 D BluetoothPbap: Proxy object connected
,08-17 19:16:58.086  1365  1365 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:58.087  4183  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:58.097  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 19:16:58.097  4183  4183 D ObexServerSockets0: prepareForNewConnect()
,08-17 19:16:58.101  4183  4230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:58.102  4183  4230 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:58.142   875   875 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.142   875   875 D BluetoothHeadset: Proxy object connected
08-17 19:16:58.142   875   875 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.143  3889  3900 D BluetoothHeadset: Proxy object connected
08-17 19:16:58.143  3889  3889 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:58.144  1365  1381 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.144   875   892 D BluetoothHeadset: Proxy object connected
08-17 19:16:58.145  1365  1365 D HeadsetProfile: Bluetooth service connected
08-17 19:16:58.146  1938  1950 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.153   875   892 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.153  3889  4168 D BluetoothHeadset: Proxy object connected
08-17 19:16:58.153  3889  3889 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:58.159  1938  1951 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.159   875   892 D BluetoothHeadset: Proxy object connected
,08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.450  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:58.457  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:58.460  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:58.461  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c8f59e added. We now have 8 listener(s)
,08-17 19:16:58.461  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:58.468   875  2239 D WifiService: setWifiEnabled: false pid=3822, uid=10000
,08-17 19:16:58.468   875  2239 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:16:58.481  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:58.482   875  1382 D WifiService: setWifiEnabled: true pid=3822, uid=10000
,08-17 19:16:58.482   875  1382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:16:58.501   875  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.513  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:58.520  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:58.540   875  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 19:16:58.541   875  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 19:16:58.541   875  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 19:16:58.542   875  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:58.542   875  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 19:16:58.543   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 19:16:58.543   875  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 19:16:58.556   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 19:16:58.557   875  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.25 delta 1000 -> 1000
,08-17 19:16:58.557   875  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 19:16:58.557   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:58.558   875  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-17 19:16:58.558   875  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:16:58.570   875  1307 E native  : do suspend true
,08-17 19:16:58.571   875  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 19:16:58.580   875  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 19:16:58.587   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 19:16:58.587   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:58.597   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 19:16:58.663   875  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 19:16:58.665  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 19:16:59.109  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 19:16:59.156  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 19:16:59.156  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 19:16:59.168   875  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:16:59.179   875  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 19:16:59.180   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:59.180   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 19:16:59.200   875  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:59.209   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:59.210   875  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:16:59.220   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 19:16:59.241   875  4238 D DhcpClient: Receive thread started
,08-17 19:16:59.326   875  1307 E native  : do suspend false
,08-17 19:16:59.346   875  2091 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 19:16:59.371   875  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-17 19:16:59.372   875  2091 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-17 19:16:59.375   875  2091 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 19:16:59.396   875  4238 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 19:16:59.397   875  2091 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 19:16:59.402   374   873 D CommandListener: Setting iface cfg
,08-17 19:16:59.414   875  2091 D DhcpClient: Scheduling renewal in 86399s
,08-17 19:16:59.415   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 19:16:59.421   875  1307 E native  : do suspend true
,08-17 19:16:59.446   875  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 19:16:59.449   875  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-17 19:16:59.450   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 19:16:59.454   875  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 19:16:59.467   875  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:59.498  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:59.502  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:59.506  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:16:59.506  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:16:59.508  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f793b3b Bundle[{}]
,08-17 19:16:59.509  3822  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 19:16:59.509  3822  3871 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 19:16:59.510  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 19:16:59.510  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 19:16:59.511  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 19:16:59.511  3822  3871 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:16:59.515  3822  3871 I System.out: Running OutgoingSocketThread
,08-17 19:16:59.517  3822  4241 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-17 19:16:59.517  3822  4241 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47338
,08-17 19:16:59.518  3822  4241 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:16:59.530   875  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 19:16:59.531   875  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 19:16:59.532   875  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 19:16:59.533   875  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-17 19:16:59.534   875  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 19:16:59.546   875  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 19:16:59.552   875  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 19:16:59.553   875  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 19:16:59.553   875  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-17 19:16:59.553   875  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 19:16:59.553   875  1309 D ConnectivityService:    accepting network in place of null
08-17 19:16:59.554   875  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:16:59.554   875  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:16:59.566   875  4237 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158728, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 19:16:59.614   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:59.636   875  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
,08-17 19:16:59.657   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:16:59.665   875  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 19:16:59.665   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:59.671   875  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 19:16:59.673   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:59.688  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:59.692  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:59.697  2008  2008 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-17 19:16:59.706  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:16:59.712   875  4236 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:16:59 GMT], X-Android-Received-Millis=[1471454219711], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471454219683]}
,08-17 19:16:59.714   875  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 19:16:59.714   875  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-17 19:16:59.714   875  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 19:16:59.717   875  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:16:59.719  1715  1715 D SystemUpdateService: onCreate
,08-17 19:16:59.722  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:16:59.728  3774  4249 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 19:16:59.738  1715  4250 I SystemUpdateService: active receiver: enabled
,08-17 19:16:59.743  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 19:16:59.749  1715  2512 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:59.750  1715  2512 I iu.UploadsManager: num updated entries: 0
,08-17 19:16:59.752  1715  4250 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:16:59.755  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:16:59.756  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 19:16:59.760  3984  3984 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:59.762  1715  4253 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 19:16:59.762  1715  4253 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 19:16:59.765  1715  4253 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 19:16:59.767  3984  3984 D SprintDMHelper: simOperator: 
,08-17 19:16:59.767  3984  3984 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:16:59.778  1715  2512 I iu.SyncManager: NEXT; no task
,08-17 19:16:59.778  1715  4250 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 19:16:59.778  1715  4250 I SystemUpdateService: now status is 0 (complete)
08-17 19:16:59.778  1715  4250 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 19:16:59.778  1715  4250 I SystemUpdateService: file has been verified
08-17 19:16:59.779  1715  4250 I SystemUpdateService: OTA package size = 12249756
,08-17 19:16:59.787  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:59.792  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:16:59.799  1715  4250 I SystemUpdateService: showing system update notification
,08-17 19:16:59.819  3774  4258 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 19:16:59.864  1715  1715 D SystemUpdateService: onDestroy
,08-17 19:16:59.869  1503  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 19:16:59.869  1503  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 19:16:59.869  1503  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:59.869  1503  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:59.876  1503  2019 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-17 19:16:59.876  1503  2019 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 19:16:59.876  1503  2019 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:59.877  1503  2019 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:59.883  2252  4255 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 19:16:59.891  1715  4253 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-17 19:16:59.909  1503  3804 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 19:16:59.909  1503  3804 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 19:16:59.909  1503  3804 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:16:59.909  1503  3804 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:16:59.923  3774  4258 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 19:16:59.924  3774  4249 E BooksSync: Soft error
08-17 19:16:59.924  3774  4249 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 19:16:59.924  3774  4249 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 19:16:59.924  3774  4249 E BooksSync: Sync error
08-17 19:16:59.924  3774  4249 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 19:16:59.924  3774  4249 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 19:16:59.924  3774  4249 I BooksSync: Finished books sync
,08-17 19:16:59.933   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158762, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:17:00.519  3822  3871 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-17 19:17:00.519  3822  3871 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-17 19:17:00.528  3822  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-17 19:17:00.531  3822  3871 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 19:17:00.531  3822  3871 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-17 19:17:00.537  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:00.537  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79ae87f added. We now have 2 listener(s)
,08-17 19:17:00.539  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:17:00.539  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:00.539  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:17:00.539  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:17:00.539  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105e04c added. We now have 9 listener(s)
08-17 19:17:00.539  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.540  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:00.543  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:00.551  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:00.553  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:17:00.554  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:17:00.554  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:00.554  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4acdaa added. We now have 3 listener(s)
,08-17 19:17:00.556  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:17:00.561  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:00.561  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.562  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:17:00.562  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ff8d9b added. We now have 10 listener(s)
08-17 19:17:00.562  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.562  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.562  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.562  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.562  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.562  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.562  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.562  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.563  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79ae87f removed from the list
,08-17 19:17:00.563  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.563  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105e04c removed from the list
08-17 19:17:00.563  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.567  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.568  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:17:00.568  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.569  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.569  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.571  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.571  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:00.571  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.572  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105e04c not in the list
08-17 19:17:00.572  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.572  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.573  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.574  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.574  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.574  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ff8d9b removed from the list
,08-17 19:17:00.574  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.574  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.574  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.574  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.574  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4acdaa removed from the list
08-17 19:17:00.575  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.575  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd6b538 added. We now have 2 listener(s)
,08-17 19:17:00.577  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.577  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.577  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.577  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:17:00.577  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f26911 added. We now have 9 listener(s)
08-17 19:17:00.577  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.578  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:17:00.581  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:00.586  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:00.588  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:17:00.589  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.589  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.589  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3f6877 added. We now have 3 listener(s)
,08-17 19:17:00.591  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:17:00.591  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:00.592  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.592  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.592  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddece4 added. We now have 10 listener(s)
08-17 19:17:00.592  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.592  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.593  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.593  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:00.593  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.593  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.593  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:17:00.596  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.598  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:17:00.598  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:00.612  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:17:00.612  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:17:00.612  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:17:00.616  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:17:00.616  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.616  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:17:00.617  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:17:00.620  4183  4220 D BtGatt.GattService: registerClient() - UUID=bef654fa-896d-4200-8670-5fb004642c3f
,08-17 19:17:00.622  4183  4199 D BtGatt.GattService: onClientRegistered() - UUID=bef654fa-896d-4200-8670-5fb004642c3f, clientIf=5
,08-17 19:17:00.622  3822  3834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:17:00.623  4183  4193 D BtGatt.GattService: start scan with filters
,08-17 19:17:00.627  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:17:00.627  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:00.628  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:00.628  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:17:00.628  4183  4202 D BtGatt.ScanManager: handling starting scan
,08-17 19:17:00.631  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.631  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:17:00.631  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.632  4183  4202 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d6fc1f
,08-17 19:17:00.633  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:00.637  3822  3871 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:17:00.637  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.637  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:17:00.637  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.637  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:17:00.638  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:17:00.638  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:17:00.638  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:17:00.638  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:17:00.638  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,08-17 19:17:00.638  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:17:00.639  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:17:00.640  4183  4220 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:17:00.641  4183  4193 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:17:00.641  4183  4199 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:17:00.641  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:17:00.641  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.641  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:17:00.641  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:17:00.642  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:00.642  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-17 19:17:00.643  4183  4202 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:17:00.643  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:00.643  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:17:00.643  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:17:00.644  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:17:00.644  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.647  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:00.647  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.647  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:00.649  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.649  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.650  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:17:00.650  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.650  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-17 19:17:00.650  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.651  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-17 19:17:00.651  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd6b538 removed from the list
,08-17 19:17:00.651  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.651  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f26911 removed from the list
,08-17 19:17:00.651  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.652  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.653  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 19:17:00.653  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.655  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 19:17:00.655  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.655  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.655  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:00.656  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:00.656  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f26911 not in the list
,08-17 19:17:00.656  4183  4202 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:00.656  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.656  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.657  4183  4202 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 19:17:00.659  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.660  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.660  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.660  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddece4 removed from the list
08-17 19:17:00.660  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.661  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.661  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.662  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.662  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3f6877 removed from the list
08-17 19:17:00.664   875  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-17 19:17:00.665  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.665  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fef350 added. We now have 2 listener(s)
08-17 19:17:00.670  4183  4199 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:17:00.670  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.670  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.671  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.671  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.672  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.672  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e902949 added. We now have 9 listener(s)
08-17 19:17:00.672  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.673  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:17:00.677  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:17:00.677  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.677  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:00.682  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:17:00.685  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.685  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:17:00.685  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.685  4183  4202 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:17:00.686  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.686  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.686  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804ef6f added. We now have 3 listener(s)
08-17 19:17:00.688  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.688  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.688  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.688  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.688  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.688  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7f47c added. We now have 10 listener(s)
08-17 19:17:00.688  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.688  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.689  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.689  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:00.689  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.690  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.690  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:17:00.690  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.691  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:17:00.692  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.692  4183  4202 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 19:17:00.693  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:17:00.693  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:17:00.698  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:17:00.702  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:17:00.702  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:17:00.702  4183  4199 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:17:00.702  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.706  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:17:00.706  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.706  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:17:00.707  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:17:00.709  4183  4193 D BtGatt.GattService: registerClient() - UUID=be8d08b8-955c-4bbd-b00c-0a6fb0ee188c
08-17 19:17:00.709  4183  4199 D BtGatt.GattService: onClientRegistered() - UUID=be8d08b8-955c-4bbd-b00c-0a6fb0ee188c, clientIf=5
08-17 19:17:00.710  3822  3834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:17:00.710  4183  4194 D BtGatt.GattService: start scan with filters
08-17 19:17:00.713  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:17:00.713  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:00.713  4183  4202 D BtGatt.ScanManager: handling starting scan
08-17 19:17:00.713  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:00.713  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:17:00.716  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.716  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:17:00.716  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.718  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 19:17:00.720  4183  4199 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:17:00.720  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.720  4183  4202 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 19:17:00.721  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:17:00.721  3822  3871 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 19:17:00.722  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:17:00.722  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.722  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:17:00.722  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:00.722  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.722  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:17:00.722  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:00.722  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fef350 removed from the list
,08-17 19:17:00.722  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:00.722  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e902949 removed from the list,
08-17 19:17:00.722  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop,
,08-17 19:17:00.722  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:00.723  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.723  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:17:00.723  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.723  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:00.726  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:00.726  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:17:00.727  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:00.727  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.727  4183  4202 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:00.727  4183  4202 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:17:00.727  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:00.728  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e902949 not in the list
,08-17 19:17:00.728  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:17:00.728  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:17:00.728  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:17:00.728  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:17:00.728  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-17 19:17:00.729  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:17:00.730  4183  4194 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:17:00.730  4183  4219 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:17:00.731  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:17:00.731  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:00.731  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:17:00.731  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:00.731  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:17:00.733  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:00.733  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:17:00.733  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:17:00.733  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:17:00.733  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.734  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:00.734  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:00.735  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 19:17:00.735  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:00.735  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e7f47c removed from the list
,08-17 19:17:00.735  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:00.735  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.735  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.735  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.735  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:00.735  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.735  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804ef6f removed from the list
,08-17 19:17:00.736  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:00.737  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fddc68 added. We now have 2 listener(s)
08-17 19:17:00.738  4183  4199 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:17:00.738  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.739  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:00.738  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.739  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.739  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:17:00.739  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caeb881 added. We now have 9 listener(s)
,08-17 19:17:00.739  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.739  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:00.742  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.745  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
,08-17 19:17:00.745  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:00.750  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:00.752  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.752  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.752  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.752  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6255d67 added. We now have 3 listener(s)
08-17 19:17:00.753  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:17:00.753  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.753  4183  4202 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:17:00.755  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.757  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.757  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.757  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.757  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.757  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5085714 added. We now have 10 listener(s)
08-17 19:17:00.757  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.758  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.758  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 19:17:00.758  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.759  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.759  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:17:00.759  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:17:00.759  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.759  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.759  4183  4202 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 19:17:00.762  3822  3871 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:17:00.762  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:00.764  4183  4199 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:17:00.764  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.765  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:17:00.765  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:17:00.765  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:17:00.768  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:17:00.768  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.768  3822  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:17:00.769  3822  3871 D BluetoothAdapter: STATE_ON
08-17 19:17:00.770  4183  4211 D BtGatt.GattService: registerClient() - UUID=47573b17-52b0-4cc7-b474-6a66a0d30477
08-17 19:17:00.771  4183  4199 D BtGatt.GattService: onClientRegistered() - UUID=47573b17-52b0-4cc7-b474-6a66a0d30477, clientIf=5
08-17 19:17:00.771  3822  3867 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:17:00.771  4183  4220 D BtGatt.GattService: start scan with filters
,08-17 19:17:00.773  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:17:00.773  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:00.773  4183  4202 D BtGatt.ScanManager: handling starting scan
08-17 19:17:00.773  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:00.773  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:17:00.775  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:00.776  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.776  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:17:00.777  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:00.778  4183  4199 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:17:00.778  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.778  4183  4202 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:17:00.781  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:17:00.781  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:00.781  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.781  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.781  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.781  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:17:00.781  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:00.781  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fddc68 removed from the list
08-17 19:17:00.781  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.782  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caeb881 removed from the list
08-17 19:17:00.782  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.782  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.782  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.782  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:17:00.782  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.782  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.782  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:17:00.783  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.783  4183  4202 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:00.783  4183  4202 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 19:17:00.783  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.783  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.783  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.783  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@caeb881 not in the list
,08-17 19:17:00.783  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:17:00.783  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:17:00.783  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:17:00.784  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:17:00.784  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:17:00.784  3822  3871 D BluetoothAdapter: STATE_ON
,08-17 19:17:00.784  4183  4194 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:17:00.785  4183  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:17:00.785  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:17:00.785  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:17:00.785  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:17:00.785  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:00.785  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:17:00.786  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:00.786  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:17:00.786  3822  3871 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:17:00.786  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:17:00.787  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.788  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.788  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.788  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:00.788  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.788  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.788  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.788  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5085714 removed from the list
08-17 19:17:00.788  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.788  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.788  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.788  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.788  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6255d67 removed from the list
08-17 19:17:00.789  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.789  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19dd080 added. We now have 2 listener(s)
,08-17 19:17:00.790  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:17:00.790  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.791  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.791  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.791  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8f6b9 added. We now have 9 listener(s)
08-17 19:17:00.791  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:17:00.791  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:17:00.791  4183  4199 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:17:00.791  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.793  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.796  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:17:00.796  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:00.797  3822  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:00.798  3822  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:17:00.798  3822  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:17:00.800  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.801  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.802  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:00.802  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f36925f added. We now have 3 listener(s)
08-17 19:17:00.802  4183  4199 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:17:00.802  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.802  4183  4202 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:17:00.803  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:17:00.803  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:00.803  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.803  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.803  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4f74ac added. We now have 10 listener(s)
08-17 19:17:00.803  3822  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:17:00.804  3822  3871 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.804  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:00.804  3822  3871 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.804  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:00.804  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.804  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.804  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.804  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19dd080 removed from the list
,08-17 19:17:00.804  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.804  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8f6b9 removed from the list
08-17 19:17:00.804  3822  3871 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.804  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.805  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.805  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.806  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:00.806  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.806  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.806  3822  3871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b8f6b9 not in the list
08-17 19:17:00.806  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.806  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.807  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.807  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:00.807  3822  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.807  3822  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4f74ac removed from the list
,08-17 19:17:00.807  3822  3871 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.807  3822  3871 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.807  3822  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.807  3822  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.807  3822  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f36925f removed from the list
08-17 19:17:00.807  4183  4199 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:17:00.807  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.808  4183  4202 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:17:00.808  3822  3871 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.813  4183  4199 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 19:17:00.813  3822  4263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
08-17 19:17:00.813  4183  4199 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:17:00.813  3822  4263 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
08-17 19:17:00.813  3822  4263 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:17:00.814  3822  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,08-17 19:17:00.814  3822  4264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
08-17 19:17:00.815  3822  4264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:17:00.816  3822  3871 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 19:17:00.816  3822  3871 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 19:17:00.816  3822  3871 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:17:00.816  3822  3871 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 19:17:00.816  3822  3871 D com.test.thalitest.ThaliTestRunner: Total duration: 22755 ms
,08-17 19:17:00.817  3822  3871 I jxcore-log: Total number of executed tests:  80
08-17 19:17:00.817  3822  3871 I jxcore-log: 
,08-17 19:17:00.818  3822  3871 I jxcore-log: Number of passed tests:  80
08-17 19:17:00.818  3822  3871 I jxcore-log: 
08-17 19:17:00.818  3822  3871 I jxcore-log: Number of failed tests:  0
08-17 19:17:00.818  3822  3871 I jxcore-log: 
08-17 19:17:00.818  3822  3871 I jxcore-log: Number of ignored tests:  0
08-17 19:17:00.818  3822  3871 I jxcore-log: 
08-17 19:17:00.818  3822  3871 I jxcore-log: Total duration:  22755
08-17 19:17:00.818  3822  3871 I jxcore-log: 
08-17 19:17:00.818  3822  3871 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:17:00.818  3822  3871 I jxcore-log: 
,08-17 19:17:00.821  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.821  3822  3871 I jxcore-log: 
08-17 19:17:00.823  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.823  3822  3871 I jxcore-log: 
08-17 19:17:00.824  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.824  3822  3871 I jxcore-log: 
08-17 19:17:00.824  3822  3822 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 19:17:00.825  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.825  3822  3871 I jxcore-log: 
08-17 19:17:00.826  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.826  3822  3871 I jxcore-log: 
08-17 19:17:00.827  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.827  3822  3871 I jxcore-log: 
08-17 19:17:00.829  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.829  3822  3871 I jxcore-log: 
08-17 19:17:00.830  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.830  3822  3871 I jxcore-log: 
08-17 19:17:00.831  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.831  3822  3871 I jxcore-log: 
08-17 19:17:00.832  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:00.832  3822  3871 I jxcore-log: 
08-17 19:17:00.833  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.833  3822  3871 I jxcore-log: 
08-17 19:17:00.833  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.833  3822  3871 I jxcore-log: 
08-17 19:17:00.834  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.834  3822  3871 I jxcore-log: 
08-17 19:17:00.835  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.835  3822  3871 I jxcore-log: 
08-17 19:17:00.835  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.835  3822  3871 I jxcore-log: 
08-17 19:17:00.836  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.836  3822  3871 I jxcore-log: 
08-17 19:17:00.836  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.836  3822  3871 I jxcore-log: 
08-17 19:17:00.837  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.837  3822  3871 I jxcore-log: 
08-17 19:17:00.837  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.837  3822  3871 I jxcore-log: 
08-17 19:17:00.838  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.838  3822  3871 I jxcore-log: 
,08-17 19:17:00.838  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.838  3822  3871 I jxcore-log: 
08-17 19:17:00.839  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.839  3822  3871 I jxcore-log: 
,08-17 19:17:00.839  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.839  3822  3871 I jxcore-log: 
08-17 19:17:00.840  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.840  3822  3871 I jxcore-log: 
,08-17 19:17:00.840  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.840  3822  3871 I jxcore-log: 
08-17 19:17:00.841  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.841  3822  3871 I jxcore-log: 
,08-17 19:17:00.841  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.841  3822  3871 I jxcore-log: 
08-17 19:17:00.841  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.841  3822  3871 I jxcore-log: 
,08-17 19:17:00.842  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.842  3822  3871 I jxcore-log: 
,08-17 19:17:00.842  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.842  3822  3871 I jxcore-log: 
,08-17 19:17:01.149  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:17:01.154  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:01.154  3822  3871 I jxcore-log: 
,08-17 19:17:01.236  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:17:01.240  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:01.240  3822  3871 I jxcore-log: 
,08-17 19:17:01.289  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:17:01.292  3822  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:01.292  3822  3871 I jxcore-log: 
,08-17 19:17:01.557  4265  4265 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 19:17:01.562  4265  4265 D AndroidRuntime: CheckJNI is OFF
,08-17 19:17:01.605  4265  4265 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 19:17:01.653  4265  4265 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 19:17:01.675  4265  4265 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 19:17:01.689   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 19:17:01.690   875   888 I ActivityManager: Killing 3822:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 19:17:01.815   875   898 W PackageSettings: Skipping PackageSetting{2656e90 com.example.hello/10273} due to missing metadata
,08-17 19:17:01.820   875  2240 D GraphicsStats: Buffer count: 2
,08-17 19:17:01.820   875  1680 I WindowState: WIN DEATH: Window{db4e358 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 19:17:01.821   875  1308 D WifiService: Client connection lost with reason: 4
,08-17 19:17:01.860   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 19:17:01.860   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen,
,08-17 19:17:01.861   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-17 19:17:01.861   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 19:17:01.861   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:01.861   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:01.861   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:17:01.861   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 19:17:01.861   875   888 I ActivityManager:   Force finishing activity ActivityRecord{d25e899 u0 com.test.thalitest/.MainActivity t2}
,08-17 19:17:01.865   875   898 I art     : Starting a blocking GC Explicit
08-17 19:17:01.873   875  2240 W ActivityManager: Spurious death for ProcessRecord{57cbcae 0:com.test.thalitest/u0a0}, curProc for 3822: null
,08-17 19:17:01.913   875   898 I art     : Explicit concurrent mark sweep GC freed 15171(1026KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 677us total 45.736ms
,08-17 19:17:01.942   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 19:17:01.946  4265  4265 I art     : System.exit called, status: 0
,08-17 19:17:01.946  4265  4265 I AndroidRuntime: VM exiting with result code 0.
,08-17 19:17:01.985   875   898 I ActivityManager: Start proc 4276:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-17 19:17:01.986   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 19:17:02.002   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 19:17:02.010   875  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 19:17:02.014  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-17 19:17:02.016  1882  2250 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:17:02.017  4183  4183 D BluetoothMapAppObserver: onReceive
08-17 19:17:02.017  4183  4183 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-17 19:17:02.029  3659  3659 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 19:17:02.035  1863  4289 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 19:17:02.038  1863  4289 I Decoder : createOrResetDecoder
,08-17 19:17:02.069  1938  1938 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 19:17:02.099   875  1680 I ActivityManager: Start proc 4292:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 19:17:02.108   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 19:17:02.105  1503  1503 I ConfigService: onCreate
,08-17 19:17:02.119   875  1968 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3822 uid 10000
,08-17 19:17:02.120  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 19:17:02.122  1503  4304 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 19:17:02.122  1503  4304 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 19:17:02.122  1503  4304 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:17:02.124  1503  4304 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-17 19:17:02.137  1863  4289 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 19:17:02.148  4292  4292 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 19:17:02.161  1952  2050 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 19:17:02.162   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-17 19:17:02.162   875   887 E PackageManager: Failed to write settings, restoring backup
08-17 19:17:02.162   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 19:17:02.162   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 19:17:02.162   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 19:17:02.162   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 19:17:02.162   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 19:17:02.162   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.162   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.162   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:17:02.165   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-17 19:17:02.165   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 19:17:02.165   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:17:02.165   875   888 E DropBoxManagerService: 	... 13 more
,08-17 19:17:02.174   875   886 I ActivityManager: Start proc 4305:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-17 19:17:02.175  1952  2050 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 19:17:02.175  1952  2050 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1952
08-17 19:17:02.175  1952  2050 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.175  1952  2050 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:17:02.177   875  1382 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 19:17:02.180   875  4315 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:17:02.180   875  4315 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:17:02.180   875  4315 E DropBoxManagerService: 	... 5 more
08-17 19:17:02.181  1952  2050 I Process : Sending signal. PID: 1952 SIG: 9
,08-17 19:17:02.202  1863  4289 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 19:17:02.203  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-17 19:17:02.203  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 19:17:02.206  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 19:17:02.206  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 19:17:02.207  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 19:17:02.207  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-17 19:17:02.207  1863  4289 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-17 19:17:02.207  1863  4289 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 19:17:02.207  1863  4289 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-17 19:17:02.208  1863  4289 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 19:17:02.208  1863  4289 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-17 19:17:02.210  1863  4289 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 19:17:02.243  4292  4292 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 19:17:02.252   875  2238 D GraphicsStats: Buffer count: 1
08-17 19:17:02.252   875  1964 I WindowState: WIN DEATH: Window{8e206d7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 19:17:02.271  4292  4325 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 19:17:02.280   875  1681 I ActivityManager: Start proc 4327:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 19:17:02.281   875  2238 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1952) has died
,08-17 19:17:02.281   875  2238 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-17 19:17:02.283   875  2238 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 19:17:02.291  4292  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.291  4292  4321 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.295  4292  4321 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:17:02.299   875   888 I ActivityManager: Start proc 4339:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 19:17:02.336  1715  4338 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-17 19:17:02.338  1715  4338 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 19:17:02.341  4327  4327 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 19:17:02.346  4339  4339 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:17:02.346  4339  4339 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:17:02.347  4339  4339 D AndroidRuntime: Shutting down VM
,08-17 19:17:02.355  4339  4339 E AndroidRuntime: FATAL EXCEPTION: main
08-17 19:17:02.355  4339  4339 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4339
08-17 19:17:02.355  4339  4339 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 19:17:02.355  4339  4339 E AndroidRuntime: 	... 10 more
08-17 19:17:02.361   875  1379 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 19:17:02.362  4339  4339 I Process : Sending signal. PID: 4339 SIG: 9
08-17 19:17:02.362   875  4353 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:17:02.362   875  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:17:02.362   875  4353 E DropBoxManagerService: 	... 5 more
08-17 19:17:02.374  1715  4338 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-17 19:17:02.374  1715  4338 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-17 19:17:02.378  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-17 19:17:02.381  1503  1503 D AndroidRuntime: Shutting down VM
08-17 19:17:02.382  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
08-17 19:17:02.382  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
08-17 19:17:02.382  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 19:17:02.382  1503  1503 E AndroidRuntime: 	... 8 more
08-17 19:17:02.386  1503  1503 I Process : Sending signal. PID: 1503 SIG: 9
08-17 19:17:02.386   875  4356 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:17:02.386   875  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:17:02.386   875  4356 E DropBoxManagerService: 	... 5 more
,08-17 19:17:02.389   875   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4339) has died
08-17 19:17:02.390   875   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-17 19:17:02.405   875   888 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 19:17:02.407   875   886 I ActivityManager: Killing 3721:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-17 19:17:02.418   875  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-17 19:17:02.443   875  1308 D WifiService: Client connection lost with reason: 4
,08-17 19:17:02.450  4292  4321 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-17 19:17:02.455  4292  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.455  4292  4325 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:17:02.455  4292  4325 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 19:17:02.455  4292  4325 E AndroidRuntime: Process: android.process.acore, PID: 4292
08-17 19:17:02.455  4292  4325 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:17:02.455  4292  4325 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:17:02.456  4292  4321 I Process : Sending signal. PID: 4292 SIG: 9
,08-17 19:17:02.470   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
