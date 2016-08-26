#### Test 81444731251ddd8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 19:02:40.124  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:02:40.133  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 19:02:40.134  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 19:02:40.162  1495  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 19:02:40.163  1495  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 19:02:40.163  1495  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:02:40.163  1495  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 19:02:40.182  3477  3477 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 19:02:40.183  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 19:02:40.183  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 19:02:40.809  3757  3757 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 19:02:40.815  3757  3757 D AndroidRuntime: CheckJNI is OFF
08-26 19:02:40.858  3757  3757 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 19:02:40.909  3757  3757 I Radio-JNI: register_android_hardware_Radio DONE
08-26 19:02:40.932  3757  3757 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 19:02:40.938   872  1883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 19:02:40.978  1986  3746 W SearchService: Abort, client detached.
08-26 19:02:40.982  1986  1986 I HotwordDetector: Closing mic
08-26 19:02:40.983  1986  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ce7cf79
08-26 19:02:40.983  1986  2325 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 19:02:40.985  3757  3757 D AndroidRuntime: Shutting down VM
08-26 19:02:41.018   872  1957 I ActivityManager: Start proc 3766:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 19:02:41.061   375  2327 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 19:02:41.063   375  2327 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 19:02:41.073   375  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 19:02:41.075  1986  2307 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 19:02:41.075  1986  2322 I MicroRecognitionRnrImpl: Detection finished
08-26 19:02:41.110  3766  3766 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 19:02:41.143  3766  3766 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 19:02:41.151  3766  3766 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9117-9120)
08-26 19:02:41.151  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:02:41.167  3766  3766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e7e9a86}
08-26 19:02:41.168  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:02:41.168  3766  3766 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 19:02:41.178  3766  3766 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 19:02:41.180  3766  3766 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 19:02:41.199  3766  3766 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 19:02:41.210  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:02:41.210  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:02:41.210  3766  3766 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:02:41.210  3766  3766 I Adreno  : Build Date                       : 10/20/15
08-26 19:02:41.210  3766  3766 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:02:41.210  3766  3766 I Adreno  : Local Branch                     : M14
08-26 19:02:41.210  3766  3766 I Adreno  : Remote Branch                    : 
08-26 19:02:41.210  3766  3766 I Adreno  : Remote Branch                    : 
08-26 19:02:41.210  3766  3766 I Adreno  : Reconstruct Branch               : 
,08-26 19:02:41.258   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db45f08:true
,08-26 19:02:41.312  3766  3766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 19:02:41.326  3766  3766 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 19:02:41.396  3766  3807 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 19:02:41.405  3766  3793 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 19:02:41.453  3766  3807 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 19:02:41.511  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-26 19:02:41.511   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +520ms
,08-26 19:02:41.585  3766  3766 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3766
,08-26 19:02:41.686  3766  3766 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 19:02:41.815   872  2229 I ActivityManager: Killing 2956:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 19:02:41.873   872  2229 I ActivityManager: Killing 3175:com.google.android.gm/u0a78 (adj 15): empty #18
,08-26 19:02:41.996  3766  3809 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1697384144
,08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 19:02:42.004  3766  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72c9f2a added. We now have 1 listener(s)
,08-26 19:02:42.008  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 19:02:42.009  3766  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:02:42.009  3766  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:02:42.010  3766  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 19:02:42.013  3766  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f58891 added. We now have 1 listener(s)
08-26 19:02:42.013  3766  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:42.018   872  1302 D WifiService: New client listening to asynchronous messages
08-26 19:02:42.018  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:02:42.018  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:02:42.018  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 19:02:42.018  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:02:42.019  3766  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 19:02:42.021  3766  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:42.021  3766  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-26 19:02:42.025  3766  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:42.026  3766  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:42.026  3766  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:02:42.026  3766  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:42.026  3766  3809 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 19:02:42.084  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:42.087  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:42.090  3766  3766 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 19:02:42.671  3766  3818 W jxcore-log: Initializing JXcore engine
,08-26 19:02:42.671  3766  3818 W jxcore-log: JXcore engine is ready
,08-26 19:02:42.720  3818  3818 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8933 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 19:02:42.720  3818  3818 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13113]" dev="sockfs" ino=13113 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 19:02:42.720  3818  3818 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 19:02:42.734  3766  3818 W jxcore-log: Starting JXcore engine
,08-26 19:02:42.720  3818  3818 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24967]" dev="sockfs" ino=24967 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 19:02:42.813  3766  3818 W jxcore-log: Platform android
08-26 19:02:42.813  3766  3818 W jxcore-log: 
,08-26 19:02:42.813  3766  3818 W jxcore-log: Process ARCH arm
08-26 19:02:42.813  3766  3818 W jxcore-log: 
,08-26 19:02:43.003  3766  3818 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:02:43.003  3766  3818 I jxcore-log: 
08-26 19:02:43.004  3766  3818 W jxcore-log: JXcore engine is started
,08-26 19:02:43.013  3766  3809 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 19:02:43.019  3766  3766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 19:02:45.727   872  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 19:02:48.797  3016  3825 V KeepSync: Connecting to GoogleApiClient
,08-26 19:02:48.798   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 19:02:48.843  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:02:48.850  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:02:48.869  1495  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 19:02:48.869  1495  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 19:02:48.869  1495  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:02:48.869  1495  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:48.883  1710  3826 V BaseAuthAsyncOperation: access token request failed
,08-26 19:02:48.884  3016  3825 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 19:02:48.949  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 19:02:48.949  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-26 19:02:48.949  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:02:48.950  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:48.984  3016  3825 E KeepSync: IOException
08-26 19:02:48.984  3016  3825 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 19:02:48.984  3016  3825 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 19:02:48.984  3016  3825 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 19:02:48.984  3016  3825 E KeepSync: 	... 10 more
,08-26 19:02:48.984  3016  3825 W KeepSync: Sync result 2
,08-26 19:02:49.001   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 19:02:49.087  3571  3827 I BooksSync: Starting books sync for 61035162, extras: ade
,08-26 19:02:49.118  3571  3828 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-26 19:02:49.175  1495  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 19:02:49.175  1495  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 19:02:49.176  1495  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:02:49.176  1495  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:49.276  1495  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-26 19:02:49.276  1495  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-26 19:02:49.277  1495  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:02:49.277  1495  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:49.318  3571  3828 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 19:02:49.321  3571  3827 E BooksSync: Soft error
08-26 19:02:49.321  3571  3827 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 19:02:49.321  3571  3827 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-26 19:02:49.322  3571  3827 E BooksSync: Sync error
08-26 19:02:49.322  3571  3827 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-26 19:02:49.322  3571  3827 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-26 19:02:49.322  3571  3827 I BooksSync: Finished books sync
,08-26 19:02:49.337   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126810, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 19:02:51.235   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 19:02:52.861  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 19:02:52.861  3766  3818 I jxcore-log: 
,08-26 19:02:52.864  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 19:02:52.864  3766  3818 I jxcore-log: 
,08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:52.871  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:52.874  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:52.877  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:02:52.877  3766  3818 I jxcore-log: 
,08-26 19:02:52.879  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:02:52.879  3766  3818 I jxcore-log: 
,08-26 19:02:53.414  3766  3818 D executeNativeTests: Running unit tests
,08-26 19:02:53.480  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:02:53.481  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a added. We now have 2 listener(s)
,08-26 19:02:53.482  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:02:53.482  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:02:53.482  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:02:53.482  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 19:02:53.482  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b added. We now have 2 listener(s)
08-26 19:02:53.482  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:53.483  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:02:53.487  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.492  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:53.496  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:53.496  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:53.498  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 19:02:53.499  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 19:02:53.499  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:53.500  3766  3818 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 19:02:53.500  3766  3818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:53.500  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:53.500  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:53.500  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:53.502  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.503  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.504  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.504  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.504  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.504  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.504  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:53.504  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:02:53.504  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a removed from the list
08-26 19:02:53.504  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.505  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b removed from the list
,08-26 19:02:53.508  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.509  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.509  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.511  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.511  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.513  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:53.513  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.513  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.513  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.516  3766  3818 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 19:02:53.516  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:53.517  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:53.517  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:02:53.517  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.517  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.517  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.517  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
,08-26 19:02:53.517  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.517  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
,08-26 19:02:53.518  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:53.518  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.518  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 19:02:53.518  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.518  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.521  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.521  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:02:53.521  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:53.521  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
,08-26 19:02:53.528  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:53.529  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:53.530  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 19:02:53.531  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:02:53.531  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:53.531  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:02:53.531  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:02:53.531  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 19:02:53.531  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.531  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.531  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.531  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.531  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.531  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.531  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.532  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.532  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.532  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:53.532  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.532  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.532  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.532  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.533  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.533  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.533  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.533  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.534  3766  3818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:53.536  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.544  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:53.545  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:53.545  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:53.546  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:53.546  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 19:02:53.546  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:53.546  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.546  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:02:53.548  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.550  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:02:53.550  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:02:53.551  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.554  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:53.556  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:02:53.556  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-26 19:02:53.558  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 19:02:53.560  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 19:02:53.560  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:02:53.561  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:02:53.561  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:02:53.562  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.566  2620  2630 D BtGatt.GattService: registerClient() - UUID=b3555d10-a6f2-442e-a3ae-b0d4a2c3852e
,08-26 19:02:53.568  2620  2665 D BtGatt.GattService: onClientRegistered() - UUID=b3555d10-a6f2-442e-a3ae-b0d4a2c3852e, clientIf=5
,08-26 19:02:53.568  3766  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 19:02:53.569  2620  2753 D BtGatt.GattService: start scan with filters
,08-26 19:02:53.572  2620  2668 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:53.573  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:02:53.573  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:02:53.573  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:53.573  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:53.575  2620  2668 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:02:53.576  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:53.576  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:02:53.577  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:53.578  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:02:53.580  3766  3818 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:53.582  2620  2665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:02:53.582  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.583  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:53.583  3766  3818 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:02:53.583  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:53.583  2620  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:02:53.583  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 19:02:53.583  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.583  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 19:02:53.584  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:02:53.584  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 19:02:53.584  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 19:02:53.584  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:02:53.584  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 19:02:53.584  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:02:53.585  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.586  2620  2746 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:02:53.587  2620  2632 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 19:02:53.587  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:02:53.587  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:53.587  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 19:02:53.588  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 19:02:53.588  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:02:53.588  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:02:53.588  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-26 19:02:53.588  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:53.589  2620  2668 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:02:53.589  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:02:53.589  2620  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-26 19:02:53.589  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:02:53.589  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:02:53.590  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:53.591  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:02:53.591  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.591  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:53.591  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 19:02:53.591  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.591  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.591  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
,08-26 19:02:53.591  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:53.591  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:53.591  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.591  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:53.591  3766  3818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:53.593  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.597  2620  2665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:02:53.597  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.598  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:53.601  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:53.602  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:53.602  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:02:53.603  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 19:02:53.603  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:02:53.603  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.603  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:02:53.603  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.603  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:02:53.604  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.607  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.610  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:02:53.610  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.610  2620  2668 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:02:53.610  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 19:02:53.610  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-26 19:02:53.615  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:02:53.615  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.615  2620  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 19:02:53.617  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:53.618  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 19:02:53.618  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:02:53.621  2620  2665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:02:53.621  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:02:53.623  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:02:53.623  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:02:53.623  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:02:53.624  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.626  2620  2632 D BtGatt.GattService: registerClient() - UUID=f27cffcf-eb81-4762-bbe6-2c55fa299764
08-26 19:02:53.626  2620  2665 D BtGatt.GattService: onClientRegistered() - UUID=f27cffcf-eb81-4762-bbe6-2c55fa299764, clientIf=5
08-26 19:02:53.626  3766  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:02:53.627  2620  2744 D BtGatt.GattService: start scan with filters
,08-26 19:02:53.628  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:02:53.628  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:02:53.628  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:53.628  2620  2668 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:53.628  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:53.630  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:53.631  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:53.631  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:02:53.632  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:02:53.634  2620  2665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:02:53.634  3766  3818 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:53.634  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.635  2620  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:02:53.637  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:53.637  3766  3818 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:02:53.637  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.637  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
08-26 19:02:53.637  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.637  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 19:02:53.637  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:02:53.637  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 19:02:53.637  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:53.637  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:53.638  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:02:53.638  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:02:53.638  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.639  2620  2753 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:02:53.639  2620  2632 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:02:53.639  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:02:53.639  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.639  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:53.639  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:53.640  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:02:53.640  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:02:53.640  2620  2668 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:02:53.640  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:02:53.640  2620  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:02:53.641  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:53.641  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:02:53.642  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:02:53.642  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:02:53.642  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:53.643  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:53.643  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:53.644  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:53.644  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.644  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.644  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:53.644  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.644  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.645  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
,08-26 19:02:53.645  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.645  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.646  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.646  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.647  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:53.647  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.647  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.647  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
,08-26 19:02:53.648  3766  3818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:53.650  2620  2665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:02:53.650  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.651  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.655  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:02:53.655  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.655  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:53.658  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:53.658  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:53.659  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:02:53.659  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:53.660  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:53.660  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:53.660  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.661  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:02:53.661  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.661  2620  2668 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:02:53.660  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:02:53.662  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.665  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:02:53.665  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:02:53.666  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 19:02:53.666  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.667  2620  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 19:02:53.668  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:53.669  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:02:53.669  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:02:53.671  2620  2665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 19:02:53.671  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.671  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:02:53.671  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:02:53.672  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:02:53.672  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.674  2620  2630 D BtGatt.GattService: registerClient() - UUID=77a050e1-a4d0-46e7-b726-8c40018c33c9
,08-26 19:02:53.674  2620  2665 D BtGatt.GattService: onClientRegistered() - UUID=77a050e1-a4d0-46e7-b726-8c40018c33c9, clientIf=5
08-26 19:02:53.675  3766  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:02:53.676  2620  2746 D BtGatt.GattService: start scan with filters
,08-26 19:02:53.678  2620  2668 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:53.678  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:02:53.678  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:02:53.678  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:53.678  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:53.680  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:53.680  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:02:53.680  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:02:53.682  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:02:53.683  2620  2665 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:02:53.683  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.683  2620  2668 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:02:53.684  3766  3818 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:53.684  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.684  3766  3818 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:02:53.684  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.684  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:02:53.684  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.684  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:02:53.684  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:02:53.684  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:53.685  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:53.685  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:53.685  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:02:53.685  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:02:53.685  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:02:53.686  2620  2630 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:02:53.686  2620  2746 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:02:53.687  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:02:53.687  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:53.687  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:02:53.687  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:02:53.687  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:02:53.688  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:02:53.688  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.688  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:53.688  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:02:53.688  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:02:53.688  2620  2668 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:02:53.688  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:02:53.688  2620  2668 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:02:53.689  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:53.689  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:53.689  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:53.690  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:53.690  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.690  3766  3818 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:02:53.690  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:53.690  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:02:53.690  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:02:53.690  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.691  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:53.691  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.691  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:53.691  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.691  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:53.691  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.691  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.691  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:53.692  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:53.692  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.692  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:53.692  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.693  3766  3818 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:02:53.693  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.694  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:53.694  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:02:53.694  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:02:53.694  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.694  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.694  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.694  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.694  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.694  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.694  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.694  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.694  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.694  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.695  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.695  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.695  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.695  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.696  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:53.696  2620  2665 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 19:02:53.696  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.696  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.696  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.696  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.697  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.697  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.697  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.697  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.697  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.697  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.697  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.697  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.697  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.697  3766  3818 W org.thaliproject.p2p.bt,connectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.697  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.698  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.698  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.698  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.698  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.699  3766  3818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:02:53.699  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.699  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.699  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.699  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.699  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.699  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.699  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.699  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.700  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.700  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.700  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.700  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.700  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.700  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.700  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 19:02:53.701  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.701  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.701  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.701  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.701  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.702  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:02:53.702  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.703  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.703  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.703  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.703  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.703  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.703  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.703  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.703  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.703  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.703  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.704  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.704  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.704  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.704  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.704  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.704  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.704  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.705  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:53.705  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:53.705  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:53.705  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:53.705  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:53.705  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:53.705  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.705  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.705  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.706  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.706  2620  2665 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:02:53.706  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.706  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.706  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.706  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.706  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.706  2620  2668 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:02:53.706  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.706  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.706  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.707  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.707  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.707  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.707  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.707  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.707  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.707  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.708  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:53.708  3766  3818 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:02:53.708  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:53.710  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:53.711  3766  3818 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:02:53.711  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:02:53.712  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:02:53.712  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:02:53.712  2620  2665 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:02:53.712  3766  3818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:53.712  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.713  3766  3818 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 19:02:53.713  2620  2668 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:02:53.713  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:53.713  3766  3818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:53.713  3766  3818 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-26 19:02:53.713  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:53.713  3766  3818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:53.713  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:53.716  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 19:02:53.717  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:02:53.717  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:02:53.717  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:02:53.717  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:02:53.717  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:02:53.718  2620  2665 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:02:53.718  2620  2665 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:02:53.719  3766  3818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:53.719  3766  3818 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:02:53.719  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.720  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.720  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.720  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.720  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.720  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.720  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:02:53.721  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.721  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.721  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.721  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.721  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.721  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.721  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.721  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.721  3766  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-26 19:02:53.722  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.722  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.722  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.722  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.723  3766  3818 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:02:53.723  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.723  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.723  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.724  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.724  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.724  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.724  3766  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-26 19:02:53.724  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.724  3766  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-26 19:02:53.724  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.724  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.724  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.724  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.724  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.724  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.724  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.725  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.725  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.725  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.725  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.726  3766  3818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:02:53.726  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.726  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.726  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.726  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.726  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.726  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.726  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.726  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.726  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.727  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.727  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.727  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.727  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.727  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.727  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.728  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.728  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.728  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.728  3766  3818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:02:53.728  3766  3818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:02:53.728  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:53.728  3766  3818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:02:53.729  3766  3818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:02:53.729  3766  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:02:53.729  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:53.729  3766  3818 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:02:53.729  3766  3818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:02:53.729  3766  3818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:02:53.729  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:53.729  3766  3818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:02:53.729  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.729  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.729  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.729  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.729  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.730  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.730  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.730  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.730  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.730  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.730  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.730  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.730  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.730  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.731  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.731  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.731  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.731  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.732  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.732  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.732  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.732  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.732  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.732  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.732  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.732  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.732  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.732  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.732  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.732  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.733  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:53.733  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.733  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.733  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.733  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.733  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.733  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.733  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.733  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.733  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.733  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.733  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.733  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.734  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.734  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.734  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.734  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.734  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.734  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.735  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.735  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.736  3766  3818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:02:53.736  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:53.737  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:02:53.737  3766  3818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:02:53.737  3766  3818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 19:02:53.737  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:02:53.738  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:02:53.738  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:02:53.738  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.738  3766  3818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:02:53.738  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 19:02:53.738  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.738  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:53.738  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:53.738  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:53.739  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.739  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.739  3766  3835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:02:53.739  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:53.740  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.740  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:53.740  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.740  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:53.740  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:53.740  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.740  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.740  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.740  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.740  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.740  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.740  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.740  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.740  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.741  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.741  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.741  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.741  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.741  3766  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 19:02:53.741  3766  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:02:53.741  3766  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:02:53.741  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.741  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.742  3766  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 19:02:53.742  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.742  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.743  3766  3818 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:02:53.743  3766  3818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:53.743  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:53.743  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:53.743  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.743  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.744  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.744  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.744  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.744  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.744  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.744  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.744  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.744  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.744  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.744  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.744  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.744  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.745  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.745  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.745  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.745  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.748  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.748  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.748  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.748  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.748  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.748  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.748  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.748  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.748  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.748  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.748  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.748  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.749  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.749  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.749  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.749  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.749  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.749  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.750  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:53.750  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:53.750  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:53.750  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:53.751  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.751  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.751  3766  3818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53a577a not in the list
08-26 19:02:53.751  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.751  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.751  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:53.751  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.751  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.751  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:53.751  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:53.752  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:53.752  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:53.752  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:53.752  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da9b2b not in the list
08-26 19:02:53.753  3766  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:02:53.753  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:53.753  3766  3818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:02:53.753  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:53.753  3766  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:02:53.753  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:53.755  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:53.755  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:02:53.756  3766  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 19:02:53.756  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:02:53.756  3766  3818 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:02:53.756  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:02:53.756  3766  3818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:02:53.756  3766  3818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 19:02:53.757  3766  3818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:02:53.757  3766  3818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:02:53.757  3766  3818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:02:53.757  3766  3818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 19:02:53.758  3766  3818 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:02:53.758  3766  3818 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 19:02:53.759  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:53.759  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb64415 added. We now have 2 listener(s)
08-26 19:02:53.759  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:53.760  3766  3818 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 19:02:53.760   872  1957 D WifiService: setWifiEnabled: true pid=3766, uid=10000
08-26 19:02:53.760   872  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:02:53.761  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:53.761  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@297932a added. We now have 3 listener(s)
08-26 19:02:53.761  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:53.765  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:53.765  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5dca51b added. We now have 4 listener(s)
08-26 19:02:53.765  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:53.767  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:53.767  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@722b6b8 added. We now have 5 listener(s)
08-26 19:02:53.767  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:02:53.768   872  1388 D WifiService: setWifiEnabled: false pid=3766, uid=10000
08-26 19:02:53.768   872  1388 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:02:53.772  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:53.772  2620  2661 D BluetoothAdapterState: Current state: ON, message: 23
08-26 19:02:53.772  2620  2661 D BluetoothAdapterProperties: Setting state to 13
08-26 19:02:53.772  2620  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:02:53.773  2620  2661 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:02:53.774  2620  2661 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:02:53.774  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.774  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:53.775  2620  2665 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:02:53.776  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.776  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.776  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:53.777  2620  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 19:02:53.779  2620  2620 D BluetoothMapService: onReceive
08-26 19:02:53.779  2620  2620 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:53.779  2620  2620 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:02:53.779  2620  2620 D BluetoothMapService: MAP Service closeService in
08-26 19:02:53.779  2620  2620 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 19:02:53.779  2620  2620 D ObexServerSockets0: shutdown(block = true)
08-26 19:02:53.780  2620  2620 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:02:53.780  2620  2620 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:02:53.781  2620  2756 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 19:02:53.781  2620  2755 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 19:02:53.781  2620  2740 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 19:02:53.782  2620  2620 I BtOppRfcommListener: stopping Accept Thread
08-26 19:02:53.782  2620  3385 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:53.782  2620  3385 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:02:53.784  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.786  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.786  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:02:53.788   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:02:53.788   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 19:02:53.788   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:02:53.788   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:02:53.788  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:53.788  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:53.789  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:53.789  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:53.791  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.794  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.796   872  2054 D DhcpClient: Clearing IP address
,08-26 19:02:53.796   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:02:53.796  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.803  1495  2529 V NativeCrypto: Read error: ssl=0x9b2e9c00: I/O error during system call, Connection timed out
,08-26 19:02:53.804  1495  2529 V NativeCrypto: SSL shutdown failed: ssl=0x9b2e9c00: I/O error during system call, Broken pipe
,08-26 19:02:53.804   371   870 D CommandListener: Setting iface cfg
,08-26 19:02:53.807   872  2223 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-26 19:02:53.807   872  2048 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 19:02:53.807   872   885 I ActivityManager: Start proc 3838:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 19:02:53.809   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:02:53.809   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 19:02:53.811  2620  2620 D HeadsetService: Received stop request...Stopping profile...
08-26 19:02:53.812   872  2048 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 19:02:53.813   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 19:02:53.813   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 19:02:53.814   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:02:53.814  1341  1357 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:53.814   394   394 E Parcel  : Reading a NULL string not supported here.
08-26 19:02:53.814  1341  1341 D HeadsetProfile: Bluetooth service disconnected
08-26 19:02:53.815   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:53.815   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:53.815  2620  2620 D A2dpService: Received stop request...Stopping profile...
,08-26 19:02:53.815  1920  2265 D BluetoothHeadset: Proxy object disconnected
08-26 19:02:53.815  2620  2748 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:02:53.818   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:02:53.818   872   872 D BluetoothA2dp: Proxy object disconnected
08-26 19:02:53.818   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 19:02:53.819  2620  2620 V BluetoothAdapterState: isTurningOff()=true
08-26 19:02:53.819  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.819  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:02:53.819  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:02:53.820   872  2089 D DhcpClient: Receive thread stopped
08-26 19:02:53.824  2620  2620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:02:53.824  2620  2665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 19:02:53.825  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.825  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.825  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.825  2620  2665 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-26 19:02:53.824  2620  2620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:02:53.827  2620  2620 D HidService: Received stop request...Stopping profile...
08-26 19:02:53.827  2620  2620 D HidService: Stopping Bluetooth HidService
08-26 19:02:53.829   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 19:02:53.829  1341  1341 D BluetoothInputDevice: Proxy object disconnected
08-26 19:02:53.829  1341  1341 D HidProfile: Bluetooth service disconnected
08-26 19:02:53.830  2620  2620 D HealthService: Received stop request...Stopping profile...
08-26 19:02:53.831  2620  2620 V BluetoothAdapterState: isTurningOff()=true
,08-26 19:02:53.831  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.831  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:02:53.831  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:02:53.832  1341  1341 D BluetoothA2dp: Proxy object disconnected
08-26 19:02:53.834  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:53.834  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:53.834  2620  2620 D PanService: Received stop request...Stopping profile...
,08-26 19:02:53.834   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:02:53.836  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.836  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:53.837  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.837  2620  2665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 19:02:53.837  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.837  2620  2702 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:02:53.837  2620  2702 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 19:02:53.837  2620  2702 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:02:53.837  2620  2702 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:53.837  1341  1341 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:02:53.838  1341  1341 D PanProfile: Bluetooth service disconnected
08-26 19:02:53.838  2620  2620 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:02:53.838  2620  2620 D BluetoothMapService: stop()
08-26 19:02:53.838  2620  2620 D BluetoothMapAppObserver: deinitObservers()
08-26 19:02:53.838  2620  2620 D BluetoothMapAppObserver: removeReceiver()
08-26 19:02:53.838  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:53.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:02:53.839  1341  1341 D BluetoothMap: Proxy object disconnected
08-26 19:02:53.839  1341  1341 D MapProfile: Bluetooth service disconnected
08-26 19:02:53.839  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:53.839  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:53.840  2620  2620 V BluetoothAdapterState: isTurningOff()=true
08-26 19:02:53.840  2102  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:53.840  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.840  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:02:53.840  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:02:53.841  2620  2620 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:02:53.841  2620  2620 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:02:53.841  2620  2665 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 19:02:53.841  2620  2620 V BluetoothAdapterState: isTurningOff()=true
08-26 19:02:53.841  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.841  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:02:53.841  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:02:53.842  2620  2620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:02:53.842  2620  2665 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 19:02:53.842  2620  2620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:02:53.842  2620  2620 V BluetoothAdapterState: isTurningOff()=true
08-26 19:02:53.842  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.842  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:02:53.843  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:02:53.843  2620  2620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:02:53.844  2620  2620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:02:53.844  2620  2620 D BluetoothMapService: MAP Service closeService in
08-26 19:02:53.845  2620  2620 V BluetoothAdapterState: isTurningOff()=true
,08-26 19:02:53.845  2620  2620 V BluetoothAdapterState: isTurningOn()=false
08-26 19:02:53.845  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:02:53.845  2620  2620 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:02:53.845  2620  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 19:02:53.845  2620  2661 D BluetoothAdapterProperties: Setting state to 15
08-26 19:02:53.845  2620  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 19:02:53.846  2620  2661 I BluetoothAdapterState: Entering BleOnState
08-26 19:02:53.847  1341  1357 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:02:53.848   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:53.848  1341  1358 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 19:02:53.849   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:53.849  1341  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 19:02:53.849  1341  1357 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:02:53.849  2620  2620 D BluetoothMapService: cleanup()
08-26 19:02:53.849  2620  2620 D BluetoothMapService: MAP Service closeService in
08-26 19:02:53.851  1341  1358 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:02:53.851  1920  1943 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:53.852   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:02:53.852  1341  1364 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:02:53.852   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:02:53.855  2620  2661 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 19:02:53.855  2620  2661 D BluetoothAdapterProperties: Setting state to 16
,08-26 19:02:53.855  2620  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 19:02:53.855  2620  2661 D BluetoothAdapterProperties: onBleDisable
08-26 19:02:53.856  2620  2661 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:02:53.856  2620  2662 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 19:02:53.857  2620  2665 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:02:53.858  2620  2702 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 19:02:53.858  2620  2702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:02:53.858  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.860  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.861  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.863  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.864   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 19:02:53.877  3838  3838 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-26 19:02:53.883   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 19:02:53.883   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 19:02:53.884   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:53.886   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 19:02:53.888  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:53.888  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:53.888  3377  3377 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@72c9f2a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 19:02:53.898  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:02:53.903  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:02:53.904   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99b3317:true
,08-26 19:02:53.915   872  1388 I ActivityManager: Start proc 3858:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 19:02:53.934   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 19:02:53.935   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:02:53.935   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:02:53.948  3858  3858 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 19:02:53.950  3838  3838 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 19:02:53.952  3838  3838 D BluetoothMap: Create BluetoothMap proxy object
,08-26 19:02:53.959  3838  3838 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 19:02:53.970  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:02:53.976   872  2230 I ActivityManager: Killing 2390:com.google.android.talk/u0a61 (adj 15): empty #17
,08-26 19:02:54.062  2620  2665 I bt_hci  : shut_down
,08-26 19:02:54.063  2620  2669 D bt_hwcfg: hw_epilog_process
08-26 19:02:54.064  2620  2669 I bt_vendor: low_power_mode_cb
,08-26 19:02:54.089  2620  2669 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 19:02:54.089  2620  2669 I bt_vendor: epilog_cb
08-26 19:02:54.089  2620  2669 I bt_hci  : epilog_finished_callback
,08-26 19:02:54.095  2620  2665 I bt_hci_h4: hal_close
,08-26 19:02:54.097  2620  2665 I bt_userial_vendor: device fd = 51 close
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.169  3858  3858 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.169  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.170  3858  3858 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.170  3858  3858 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:02:54.170  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:02:54.206   872   882 I ActivityManager: Start proc 3889:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-26 19:02:54.207   872   882 I ActivityManager: Killing 3532:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-26 19:02:54.241  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:02:54.269  2620  2662 D bt_stack_manager: event_shut_down_stack finished.
08-26 19:02:54.269  2620  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 19:02:54.271  2620  2620 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:02:54.271  2620  2661 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 19:02:54.271  2620  2620 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:02:54.271  2620  2620 D BtGatt.GattService: stop()
,08-26 19:02:54.271  2620  2620 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 19:02:54.272  2620  2620 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:02:54.272  2620  2620 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:02:54.273  2620  2620 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:02:54.273  2620  2620 V BluetoothAdapterState: isBleTurningOff()=true
08-26 19:02:54.273  2620  2661 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 19:02:54.273  2620  2661 D BluetoothAdapterProperties: Setting state to 10
08-26 19:02:54.273  2620  2661 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 19:02:54.273  2620  2661 I BluetoothAdapterState: Entering OffState
08-26 19:02:54.274   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 19:02:54.279  2620  2620 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 19:02:54.279  2620  2620 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 19:02:54.280  2620  2620 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 19:02:54.280  2620  2662 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 19:02:54.283  2620  2662 D bt_stack_manager: event_clean_up_stack finished.
,08-26 19:02:54.288  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-26 19:02:54.301  2620  2620 I art     : System.exit called, status: 0
,08-26 19:02:54.301  2620  2620 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 19:02:54.376   872  1957 I ActivityManager: Process com.android.bluetooth (pid 2620) has died
,08-26 19:02:54.456  3858  3886 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 19:02:54.524  3889  3909 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-26 19:02:54.524  3889  3909 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 19:02:54.535  3889  3909 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-26 19:02:54.535  3889  3909 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 19:02:54.596  3889  3909 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 19:02:54.596  3889  3909 I Babel_SMS: MmsConfig.loadFromResources
,08-26 19:02:54.597  3889  3909 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 19:02:54.598  3889  3909 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-26 19:02:54.643  3889  3889 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:54.646  3889  3889 I Babel_Crash: startup - clean
,08-26 19:02:54.683  3889  3889 I Babel_telephony: TeleModule.launchCompleted
,08-26 19:02:54.697   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a91fef:true
,08-26 19:02:54.715   872  2229 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 19:02:54.731  3889  3889 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-26 19:02:54.739  3889  3889 W Babel   : BAM#gBA: invalid account id: -1
,08-26 19:02:54.740  3889  3889 W Babel   : BAM#gBA: invalid account id: -1
08-26 19:02:54.740  3889  3889 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-26 19:02:54.745  3889  3914 I Babel   : deleted: false for 0
,08-26 19:02:54.745   872   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 19:02:54.769   872  1884 I ActivityManager: Start proc 3916:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-26 19:02:54.803  3889  3889 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:54.840  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 19:02:54.863  3889  3889 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:02:54.883  3889  3889 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:54.895  3889  3889 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:54.899  3889  3889 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:54.922  3889  3889 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:54.934  3889  3889 I vclib   : onServiceConnected
,08-26 19:02:54.962  3916  3916 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 19:02:54.993  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:02:55.021   872  3102 I ActivityManager: Start proc 3941:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 19:02:55.024  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:02:55.027   872  1884 I ActivityManager: Killing 3377:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 19:02:55.106  3941  3941 D AdapterServiceConfig: Adding HeadsetService
,08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding A2dpService
08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding HidService
,08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding HealthService
08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding PanService
,08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding GattService
,08-26 19:02:55.107  3941  3941 D AdapterServiceConfig: Adding BluetoothMapService
08-26 19:02:55.109   872  1885 I ActivityManager: Killing 3425:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 19:02:55.147  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:02:55.169  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:02:55.172  1710  1710 D SystemUpdateService: onCreate
,08-26 19:02:55.175  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:02:55.181  1710  3953 I SystemUpdateService: active receiver: enabled
,08-26 19:02:55.191  1710  3953 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:02:55.193  1710  3953 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 19:02:55.194  1710  3953 I SystemUpdateService: now status is 0 (complete)
08-26 19:02:55.194  1710  3953 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 19:02:55.194  1710  3953 I SystemUpdateService: file has been verified
08-26 19:02:55.194  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-26 19:02:55.194  1710  3953 I SystemUpdateService: OTA package size = 12249756
,08-26 19:02:55.202  1710  2495 I iu.UploadsManager: num queued entries: 0
,08-26 19:02:55.204  1710  2495 I iu.UploadsManager: num updated entries: 0
,08-26 19:02:55.206  1710  2495 I iu.SyncManager: NEXT; no task,
,08-26 19:02:55.207  1710  3953 I SystemUpdateService: showing system update notification
,08-26 19:02:55.213  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:02:55.214  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:02:55.239   872  1957 I ActivityManager: Start proc 3955:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
08-26 19:02:55.241  1710  1710 D SystemUpdateService: onDestroy
,08-26 19:02:55.284  3955  3955 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 19:02:55.287  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:55.294  3955  3955 D SprintDMHelper: simOperator: 
,08-26 19:02:55.295  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:02:55.319   872  2224 I ActivityManager: Start proc 3967:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 19:02:55.321   872  2224 I ActivityManager: Killing 3461:android.process.acore/u0a5 (adj 15): empty #17
,08-26 19:02:55.467   872  1885 I ActivityManager: Start proc 3982:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 19:02:55.470  3889  3981 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 19:02:55.475   872  1386 I ActivityManager: Killing 3650:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 19:02:55.537  3982  3982 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 19:02:55.592  3982  3982 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 19:02:55.592  3982  3982 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:02:55.592  3982  3982 I GAv4    :   adb logcat -s GAv4
,08-26 19:02:55.607  3982  3982 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:55.613  3982  3982 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:55.642  3982  3999 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:55.751  3982  3982 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 19:02:55.790  3982  3982 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 19:02:55.802  3982  3982 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3766-3772)
08-26 19:02:55.802  3982  3982 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 19:02:55.815  3982  3982 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {54326da}
,08-26 19:02:55.816  3982  3982 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 19:02:55.817  3982  3982 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:02:55.826  3982  3982 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 19:02:55.829  3982  3982 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 19:02:55.845  3982  3982 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 19:02:55.863  3982  3982 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 19:02:55.863  3982  3982 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:02:55.864  3982  3982 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:02:55.864  3982  3982 I Adreno  : Build Date                       : 10/20/15
08-26 19:02:55.864  3982  3982 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:02:55.864  3982  3982 I Adreno  : Local Branch                     : M14
08-26 19:02:55.864  3982  3982 I Adreno  : Remote Branch                    : 
08-26 19:02:55.864  3982  3982 I Adreno  : Remote Branch                    : 
08-26 19:02:55.864  3982  3982 I Adreno  : Reconstruct Branch               : 
,08-26 19:02:55.932  3982  3982 I NSApplication: Starting up...
,08-26 19:02:55.940  3982  4028 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 19:02:55.964   872  1957 I ActivityManager: Start proc 4033:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 19:02:55.970   872  1957 I ActivityManager: Killing 3667:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 19:02:56.086  4033  4033 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 19:02:56.302   872  2224 I ActivityManager: Killing 2225:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 19:02:56.781   872  2230 D WifiService: setWifiEnabled: true pid=3766, uid=10000
08-26 19:02:56.781   872  2230 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:02:56.794   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:02:56.802  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.803  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:02:56.804  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:56.805  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:56.808  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:02:56.809  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.809  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:02:56.827   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-26 19:02:56.828   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 19:02:56.828   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 19:02:56.829   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 19:02:56.830   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 19:02:56.830   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 19:02:56.830   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 19:02:56.844   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 19:02:56.845   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=11.00 delta 1000 -> 994
,08-26 19:02:56.847   371   870 D CommandListener: Setting iface cfg
,08-26 19:02:56.848   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 19:02:56.848   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 19:02:56.855   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 19:02:56.855   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:02:56.855   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 19:02:56.863   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 19:02:56.863   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 19:02:56.939   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 19:02:56.943  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 19:02:57.368  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 19:02:57.412  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 19:02:57.413  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 19:02:57.418   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:02:57.438   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:02:57.438   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 19:02:57.438   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:02:57.457   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:02:57.471   371   870 D CommandListener: Setting iface cfg
,08-26 19:02:57.473   872  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 19:02:57.485   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:02:57.486   872  1303 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 19:02:57.487   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 19:02:57.496   872  4058 D DhcpClient: Receive thread started
,08-26 19:02:57.581   872  1301 E native  : do suspend false
,08-26 19:02:57.602   872  2054 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 19:02:57.619   872  4058 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,08-26 19:02:57.621   872  2054 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,08-26 19:02:57.627   872  2054 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 19:02:57.641   872  4058 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 19:02:57.642   872  2054 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 19:02:57.649   371   870 D CommandListener: Setting iface cfg
,08-26 19:02:57.661   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 19:02:57.662   872  2054 D DhcpClient: Scheduling renewal in 86399s
,08-26 19:02:57.682   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 19:02:57.687   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 19:02:57.690   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 19:02:57.693   872  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 19:02:57.712   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 19:02:57.746   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:02:57.746   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 19:02:57.747   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 19:02:57.749   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 19:02:57.750   872  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 19:02:57.757   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 19:02:57.761   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 19:02:57.762   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 19:02:57.762   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 19:02:57.762   872  1303 D ConnectivityService:    accepting network in place of null
08-26 19:02:57.762   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 19:02:57.763   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:02:57.763   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:02:57.783   872  4057 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135753, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 19:02:57.791   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:02:57.838   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:02:57.842   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 19:02:57.842   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:57.847   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:02:57.846   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 19:02:57.856  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:57.856  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:57.856  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:57.857  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:57.861   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e,
,08-26 19:02:57.868  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:57.868  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:57.868  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:57.868  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:57.881  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:02:57.885  1710  1710 D SystemUpdateService: onCreate
,08-26 19:02:57.888  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:02:57.891  1710  4070 I SystemUpdateService: active receiver: enabled
,08-26 19:02:57.894  1710  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:02:57.898  1710  4070 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 19:02:57.898  1710  4070 I SystemUpdateService: now status is 0 (complete)
08-26 19:02:57.898  1710  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 19:02:57.898  1710  4070 I SystemUpdateService: file has been verified
08-26 19:02:57.898  1710  4070 I SystemUpdateService: OTA package size = 12249756
,08-26 19:02:57.907  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 19:02:57.910  1710  4070 I SystemUpdateService: showing system update notification
,08-26 19:02:57.915  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:02:57.916  1710  2495 I iu.UploadsManager: num queued entries: 0
,08-26 19:02:57.917  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:02:57.918  1710  2495 I iu.UploadsManager: num updated entries: 0
,08-26 19:02:57.918  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:57.920  1710  2495 I iu.SyncManager: NEXT; no task
,08-26 19:02:57.921  1710  4074 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 19:02:57.921  1710  4074 W BaseAppContext: Using Auth Proxy for data requests.
08-26 19:02:57.923  1710  4074 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 19:02:57.928  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:02:57.930  3955  3955 D SprintDMHelper: simOperator: 
,08-26 19:02:57.931  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:02:57.931  1710  1710 D SystemUpdateService: onDestroy
,08-26 19:02:57.932  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:02:57.954  1495  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 19:02:57.955  1495  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 19:02:57.955  1495  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:02:57.955  1495  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:57.977  1710  4074 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-26 19:02:58.003   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:02:57 GMT], X-Android-Received-Millis=[1472230978003], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472230977907]}
,08-26 19:02:58.008   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:02:58.008   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 19:02:58.008   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:02:58.009   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:02:58.021  1495  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 19:02:58.022  1495  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 19:02:58.022  1495  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:02:58.022  1495  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:58.035  3515  4069 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 19:02:58.035  3515  4069 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jdm.a(PG:82)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jcs.o(PG:406)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jcn.a(PG:1379)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jcs.i(PG:143)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at blb.a(PG:3937)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at czp.a(PG:18188)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at czp.a(PG:9081)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at czq.run(PG:1686)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 19:02:58.035  3515  4069 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jdj.a(PG:4091)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jdj.a(PG:1125)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jdm.a(PG:77)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	... 12 more
08-26 19:02:58.035  3515  4069 E HttpOperation: Caused by: faj: BadAuthentication
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at fal.a(PG:38)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	at jdj.a(PG:4089)
08-26 19:02:58.035  3515  4069 E HttpOperation: 	... 14 more
,08-26 19:02:58.067  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 19:02:58.068  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 19:02:58.068  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:02:58.068  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:02:58.086  3515  4069 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 19:02:58.086  3515  4069 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jdm.a(PG:82)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jcs.o(PG:406)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jcn.a(PG:1379)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jcs.i(PG:143)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at hec.a(PG:42)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at hee.a(PG:102)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at czr.a(PG:65)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at kka.a(PG:108)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at czp.a(PG:19176)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at czp.a(PG:9081)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at czq.run(PG:1686)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 19:02:58.086  3515  4069 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jdj.a(PG:4091)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jdj.a(PG:1125)
08-26 19:02:58.086  3515  4069 E HttpOperation: ,	at jdm.a(PG:77)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	... 15 more
08-26 19:02:58.086  3515  4069 E HttpOperation: Caused by: faj: BadAuthentication
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at fal.a(PG:38)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	at jdj.a(PG:4089)
08-26 19:02:58.086  3515  4069 E HttpOperation: 	... 17 more
08-26 19:02:58.087  3515  4069 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 19:02:58.087  3515  4069 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at hec.a(PG:42)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at hee.a(PG:102)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at czr.a(PG:65)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at kka.a(PG:108)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	... 15 more
08-26 19:02:58.087  3515  4069 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at fal.a(PG:38)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 19:02:58.087  3515  4069 E ExperimentLoader: 	... 17 more
,08-26 19:02:58.108  3889  4076 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 19:02:58.192   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 132141, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 19:02:58.843   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 19:02:59.656   872  1386 I ActivityManager: Killing 3697:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 19:02:59.788   872  1957 D WifiService: setWifiEnabled: false pid=3766, uid=10000
08-26 19:02:59.788   872  1957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:02:59.827  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 19:02:59.836   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 19:02:59.837   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 19:02:59.837   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 19:02:59.838   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:02:59.859   872  2054 D DhcpClient: Clearing IP address
,08-26 19:02:59.860   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:02:59.869  1495  4083 V NativeCrypto: Read error: ssl=0x9b299400: I/O error during system call, Connection timed out
,08-26 19:02:59.872  1495  4083 V NativeCrypto: SSL shutdown failed: ssl=0x9b299400: I/O error during system call, Broken pipe
,08-26 19:02:59.872   371   870 D CommandListener: Setting iface cfg
,08-26 19:02:59.874   872  4058 D DhcpClient: Receive thread stopped
,08-26 19:02:59.882   872  1884 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 19:02:59.883   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 19:02:59.886   872  4056 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-26 19:02:59.888   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 19:02:59.888   394   394 E Parcel  : Reading a NULL string not supported here.
08-26 19:02:59.889   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-26 19:02:59.889   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 19:02:59.889   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
08-26 19:02:59.890   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 19:02:59.895   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:02:59.896   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:02:59.899   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 19:02:59.907   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 19:02:59.909  2102  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:02:59.911  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:59.911  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:59.911  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:59.911  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:59.912  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:59.912  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:59.912  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:59.912  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:59.913   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:02:59.915   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 19:02:59.944   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:02:59.973   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:02:59.974   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 19:02:59.975   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:59.981   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:02:59.986  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:59.986  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:59.992  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:59.992  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:59.995  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:02:59.998  1710  1710 D SystemUpdateService: onCreate
,08-26 19:03:00.002  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:03:00.006  1710  4096 I SystemUpdateService: active receiver: enabled
,08-26 19:03:00.011  1710  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:03:00.012  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 19:03:00.014  1710  2495 I iu.UploadsManager: num queued entries: 0
08-26 19:03:00.015  1710  2495 I iu.UploadsManager: num updated entries: 0
,08-26 19:03:00.020  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:03:00.021  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:03:00.023  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:00.026  3955  3955 D SprintDMHelper: simOperator: 
,08-26 19:03:00.027  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:03:00.028  1710  4096 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 19:03:00.028  1710  4096 I SystemUpdateService: now status is 0 (complete)
,08-26 19:03:00.028  1710  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 19:03:00.028  1710  4096 I SystemUpdateService: file has been verified
,08-26 19:03:00.056  1710  4096 I SystemUpdateService: OTA package size = 12249756
,08-26 19:03:00.057   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 19:03:00.060   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:03:00.060   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:03:00.065  1710  2495 I iu.SyncManager: NEXT; no task
,08-26 19:03:00.065  3889  4100 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 19:03:00.071  1710  4096 I SystemUpdateService: showing system update notification
,08-26 19:03:00.078  1710  1710 D SystemUpdateService: onDestroy
,08-26 19:03:00.649  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:00.687  1495  2969 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 19:03:00.687  1495  2969 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 19:03:00.688  1495  2969 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:03:00.688  1495  2969 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:03:00.708  3477  3477 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 19:03:00.708  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 19:03:00.709  3477  3477 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 19:03:02.845  3941  3941 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 19:03:02.845   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8df2d5a:true
,08-26 19:03:02.851  3941  3941 I bt_bluedroid: init
,08-26 19:03:02.851  3941  4105 I BluetoothAdapterState: Entering OffState
,08-26 19:03:02.854  3941  4106 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 19:03:02.854  3941  4106 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 19:03:02.854  3941  4106 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 19:03:02.854  3941  4106 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 19:03:02.855  3941  3941 I bt_bluedroid: get_profile_interface socket
08-26 19:03:02.857  3941  3941 I bt_bluedroid: get_profile_interface sdp
,08-26 19:03:02.861  3941  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:03:02.862  3941  3951 I bt_bluedroid: config_hci_snoop_log
08-26 19:03:02.864  3941  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:03:02.867   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 19:03:02.877  3941  4105 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 19:03:02.877  3941  4105 D BluetoothAdapterProperties: Setting state to 14
,08-26 19:03:02.878  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 19:03:02.880  3941  4105 D BluetoothBondStateMachine: make
,08-26 19:03:02.885  3941  4110 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 19:03:02.888  3941  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:03:02.890  3941  3941 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 19:03:02.892  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:02.893  3941  3941 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:03:02.894  3941  3941 D BtGatt.GattService: Received start request. Starting profile...
,08-26 19:03:02.894  3941  3941 D BtGatt.GattService: start()
08-26 19:03:02.894  3941  3941 I bt_bluedroid: get_profile_interface gatt
08-26 19:03:02.895  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:02.895  3941  3941 D BtGatt.AdvertiseManager: advertise manager created
,08-26 19:03:02.902  3941  3941 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:02.902  3941  3941 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:03:02.902  3941  3941 V BluetoothAdapterState: isBleTurningOn()=true
08-26 19:03:02.902  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:02.903  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 19:03:02.903  3941  4105 I bt_bluedroid: enable
,08-26 19:03:02.903  3941  4106 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 19:03:02.904  3941  4106 I bt_hci  : start_up
,08-26 19:03:02.915  3941  4106 I bt_vendor: alloc value 0xb39e9189
,08-26 19:03:02.915  3941  4106 I bt_vendor: init
08-26 19:03:02.915  3941  4106 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 19:03:02.915  3941  4106 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 19:03:03.022  3941  4106 D bt_hci  : start_up starting async portion
,08-26 19:03:03.022  3941  4113 I bt_hci  : event_finish_startup
,08-26 19:03:03.022  3941  4113 I bt_hci_h4: hal_open
,08-26 19:03:03.023  3941  4113 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 19:03:03.030  3941  4113 I bt_userial_vendor: device fd = 51 open
,08-26 19:03:03.064  3941  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:03:03.096  3941  4113 D bt_hwcfg: Chipset BCM4354A2
,08-26 19:03:03.096  3941  4113 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 19:03:03.097  3941  4113 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 19:03:03.757  3941  4113 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 19:03:03.758  3941  4113 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 19:03:03.759  3941  4113 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 19:03:03.875  3941  4113 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:03:03.877  3941  4113 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 19:03:03.906  3941  4113 I bt_hwcfg: vendor lib fwcfg completed
08-26 19:03:03.907  3941  4113 I bt_vendor: firmware callback
08-26 19:03:03.907  3941  4113 I bt_hci  : firmware_config_callback
,08-26 19:03:03.918  3941  4115 I bt_btu  : btu_task pending for preload complete event
08-26 19:03:03.918  3941  4115 I bt_btu_task: Bluetooth chip preload is complete
08-26 19:03:03.918  3941  4115 I bt_btu  : btu_task received preload complete event
,08-26 19:03:03.928  3941  4115 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 19:03:03.928  3941  4115 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:03:03.929  3941  4115 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:03:03.929  3941  4115 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:03:03.929  3941  4115 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:03:03.930  3941  4115 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 19:03:03.930  3941  4115 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 19:03:03.930  3941  4115 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 19:03:03.931  3941  4115 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:03:03.931  3941  4115 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 19:03:03.931  3941  4115 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 19:03:03.931  3941  4115 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:03:03.932  3941  4115 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:03:03.932  3941  4115 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:03:03.932  3941  4115 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:03:04.067  3941  4115 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
08-26 19:03:04.067  3941  4115 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-26 19:03:04.078  3941  4109 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 19:03:04.080  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 19:03:04.081  3941  4109 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:03:04.085  3941  4109 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:03:04.088  3941  4109 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:04.088  3941  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:03:04.089  3941  4109 D bt_hci  : do_postload posting postload work item
08-26 19:03:04.089  3941  4113 I bt_hci  : event_postload
08-26 19:03:04.089  3941  4113 I bt_vendor: sco_config_cb
,08-26 19:03:04.089  3941  4113 I bt_hci  : sco_config_callback postload finished.
08-26 19:03:04.092  3941  4109 D bt_bte_conf: Device ID record 1 : primary
,08-26 19:03:04.092  3941  4109 D bt_bte_conf:   vendorId            = 000f
08-26 19:03:04.092  3941  4109 D bt_bte_conf:   vendorIdSource      = 0001
08-26 19:03:04.092  3941  4109 D bt_bte_conf:   product             = 1200
,08-26 19:03:04.093  3941  4109 D bt_bte_conf:   version             = 1436
,08-26 19:03:04.093  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:04.093  3941  4109 D bt_bte_conf:   clientExecutableURL = 
,08-26 19:03:04.093  3941  4109 D bt_bte_conf:   serviceDescription  = 
,08-26 19:03:04.093  3941  4109 D bt_bte_conf:   documentationURL    = 
08-26 19:03:04.094  3941  4109 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 19:03:04.095  3941  4106 D bt_stack_manager: event_start_up_stack finished
08-26 19:03:04.095  3941  4113 I bt_vendor: low_power_mode_cb
08-26 19:03:04.095  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 19:03:04.096  3941  4105 D BluetoothAdapterProperties: Setting state to 15
08-26 19:03:04.096  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 19:03:04.096  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:04.097  3941  4105 I BluetoothAdapterState: Entering BleOnState
,08-26 19:03:04.103  3941  4105 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 19:03:04.103  3941  4105 D BluetoothAdapterProperties: Setting state to 11
08-26 19:03:04.104  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 19:03:04.110  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:04.112  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:04.113  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:04.114  3941  3941 D HeadsetService: Received start request. Starting profile...
08-26 19:03:04.120  3941  3941 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:03:04.120  3941  3941 D HeadsetStateMachine: make
,08-26 19:03:04.124  3941  4105 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:03:04.137  3941  3941 D HeadsetStateMachine: max_hf_connections = 1
,08-26 19:03:04.137  3941  3941 I bt_bluedroid: get_profile_interface handsfree
08-26 19:03:04.137  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 19:03:04.137  3941  4109 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 19:03:04.144  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:04.145  3941  3941 D A2dpService: Received start request. Starting profile...
,08-26 19:03:04.146  3941  3941 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 19:03:04.146  3941  3941 I bt_bluedroid: get_profile_interface avrcp
,08-26 19:03:04.152  3941  3941 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:03:04.153  3941  3941 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:04.153  3941  3941 D A2dpStateMachine: make
,08-26 19:03:04.154  3941  3941 I bt_bluedroid: get_profile_interface a2dp
,08-26 19:03:04.155  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 19:03:04.156  3941  4124 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:03:04.156  3941  3941 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 19:03:04.157  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:04.158  3941  3941 D HidService: Received start request. Starting profile...
08-26 19:03:04.158  3941  3941 I bt_bluedroid: get_profile_interface hidhost
08-26 19:03:04.159  3941  4109 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-26 19:03:04.159  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 19:03:04.159  3941  3941 D HidService: setHidService(): set to: null
08-26 19:03:04.159  3941  3941 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:03:04.160  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:04.161  3941  3941 D HealthService: Received start request. Starting profile...
08-26 19:03:04.162  3941  3941 I bt_bluedroid: get_profile_interface health
08-26 19:03:04.163  3941  3941 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:03:04.163  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:04.167  3941  3941 D PanService: Received start request. Starting profile...
,08-26 19:03:04.167  3941  3941 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 19:03:04.167  3941  3941 I bt_bluedroid: get_profile_interface pan
08-26 19:03:04.167  3941  4109 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 19:03:04.170  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:04.172  3941  3941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:04.174  3838  3838 D BluetoothInputDevice: Proxy object connected
08-26 19:03:04.174  3838  3838 D HidProfile: Bluetooth service connected
08-26 19:03:04.176  3941  3941 D BluetoothMapService: Received start request. Starting profile...
08-26 19:03:04.176  3941  3941 D BluetoothMapService: start()
08-26 19:03:04.176  3838  3838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:03:04.177  3838  3838 D PanProfile: Bluetooth service connected
08-26 19:03:04.177  3838  3838 D BluetoothMap: Proxy object connected
08-26 19:03:04.177  3838  3838 D MapProfile: Bluetooth service connected
08-26 19:03:04.177  3838  3838 D BluetoothMap: getConnectedDevices()
08-26 19:03:04.178  3838  3838 D BluetoothMap: Bluetooth is Not enabled
,08-26 19:03:04.179  3941  3941 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 19:03:04.179  3941  3941 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 19:03:04.179  3941  3941 D BluetoothMapAppObserver: createReceiver()
,08-26 19:03:04.181  3941  3941 D BluetoothMapAppObserver: initObservers()
08-26 19:03:04.181  3941  3941 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 19:03:04.192  3941  3941 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:04.192  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.192  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.192  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:04.194  3941  4122 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 19:03:04.194  3941  3941 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:04.195  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:04.196  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:04.196  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 19:03:04.196  3941  4105 D BluetoothAdapterProperties: ScanMode =  20
,08-26 19:03:04.196  3941  4105 D BluetoothAdapterProperties: State =  11
08-26 19:03:04.198  3941  4109 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:03:04.199  3941  4109 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:04.199  3941  4105 D BluetoothAdapterProperties: Setting state to 12
08-26 19:03:04.199  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:03:04.200  1341  1364 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:04.199  3941  4105 I BluetoothAdapterState: Entering OnState
08-26 19:03:04.201   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:04.201  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:04.201  1341  1357 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:03:04.203   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:04.203  1341  1341 D BluetoothInputDevice: Proxy object connected
,08-26 19:03:04.203  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:04.203  1341  1341 D HidProfile: Bluetooth service connected
08-26 19:03:04.203  1341  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:03:04.203  1341  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:04.205  3838  3851 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:04.206  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:04.206  1341  1341 D BluetoothA2dp: Proxy object connected
08-26 19:03:04.207  1341  1358 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:04.208  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:04.209  1341  1341 D BluetoothMap: Proxy object connected
,08-26 19:03:04.209  1920  1943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:04.209  1341  1341 D MapProfile: Bluetooth service connected
08-26 19:03:04.209  1341  1341 D BluetoothMap: getConnectedDevices()
08-26 19:03:04.209   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:04.209  3838  3850 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:03:04.210  3838  3851 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:03:04.210  1341  1364 D BluetoothPan: onBluetoothStateChange on: true
,08-26 19:03:04.210  3941  3941 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 19:03:04.211  3941  3941 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 19:03:04.211   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:04.211  1341  1341 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:04.212  1341  1341 D PanProfile: Bluetooth service connected
08-26 19:03:04.212   872   872 D BluetoothA2dp: Proxy object connected
,08-26 19:03:04.212  3838  3850 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:03:04.212  3941  3941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:04.214   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 19:03:04.215  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:04.216  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:04.219  3838  3838 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 19:03:04.220  3941  3941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:04.221  3941  3941 D ObexServerSockets: Succeed to create listening sockets 
08-26 19:03:04.221  3941  3941 D ObexServerSockets0: startAccept()
08-26 19:03:04.221  3941  3941 D ObexServerSockets0: prepareForNewConnect()
08-26 19:03:04.222  3838  3838 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 19:03:04.223  3941  3941 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 19:03:04.223  3941  3941 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 19:03:04.224  3941  3941 D BluetoothMapService: onReceive
08-26 19:03:04.224  3941  3941 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:04.224  3941  3941 D BluetoothMapService: STATE_ON
08-26 19:03:04.225  3941  4132 D ObexServerSockets0: Accepting socket connection...
08-26 19:03:04.225  3941  4133 D ObexServerSockets0: Accepting socket connection...
,08-26 19:03:04.229  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:04.232  3838  3838 D BluetoothA2dp: Proxy object connected
,08-26 19:03:04.235  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:04.237  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:04.242  1341  1341 D BluetoothPbap: Proxy object connected
08-26 19:03:04.242  1341  1341 D PbapServerProfile: Bluetooth service connected
08-26 19:03:04.242  3838  3838 D BluetoothPbap: Proxy object connected
08-26 19:03:04.242  3838  3838 D PbapServerProfile: Bluetooth service connected
,08-26 19:03:04.249  3941  3941 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 19:03:04.249  3941  3941 D ObexServerSockets0: prepareForNewConnect()
08-26 19:03:04.251  3941  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:04.273  3941  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:04.274  3941  4141 I BtOppRfcommListener: Accept thread started.
,08-26 19:03:04.303   872   872 D BluetoothHeadset: Proxy object connected
08-26 19:03:04.303   872   889 D BluetoothHeadset: Proxy object connected
08-26 19:03:04.304  1341  1364 D BluetoothHeadset: Proxy object connected
,08-26 19:03:04.304  1341  1357 D BluetoothHeadset: Proxy object connected
08-26 19:03:04.304  1341  1341 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:04.304   872   872 D BluetoothHeadset: Proxy object connected
08-26 19:03:04.304   872   872 D BluetoothHeadset: Proxy object connected
,08-26 19:03:04.305  1920  2055 D BluetoothHeadset: Proxy object connected
,08-26 19:03:04.307  1341  1341 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:04.309  1920  2265 D BluetoothHeadset: Proxy object connected
08-26 19:03:04.310   872   889 D BluetoothHeadset: Proxy object connected
,08-26 19:03:04.326  3838  3850 D BluetoothHeadset: Proxy object connected
,08-26 19:03:04.327  3838  3838 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:05.767   872  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-26 19:03:05.807  3941  4105 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 19:03:05.807  3941  4105 D BluetoothAdapterProperties: Setting state to 13
,08-26 19:03:05.807  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 19:03:05.809  3941  4105 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 19:03:05.819  3941  3941 D BluetoothMapService: onReceive
,08-26 19:03:05.819  3941  3941 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.820  3941  3941 D BluetoothMapService: STATE_TURNING_OFF
,08-26 19:03:05.820  3941  4105 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:03:05.821  3941  3941 D BluetoothMapService: MAP Service closeService in
08-26 19:03:05.821  3941  3941 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 19:03:05.821  3941  3941 D ObexServerSockets0: shutdown(block = true)
08-26 19:03:05.822  3941  4132 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 19:03:05.827  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:05.827  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:05.828  3941  3941 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:03:05.829  3941  4133 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 19:03:05.834  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:05.834  3941  4118 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 19:03:05.834  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:05.835  3941  3941 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:03:05.835  3941  3941 I BtOppRfcommListener: stopping Accept Thread
08-26 19:03:05.836  3941  4141 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:03:05.837  3941  4141 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 19:03:05.838  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:05.838  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:05.839  3941  4109 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:05.839  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:05.839  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 19:03:05.839  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:05.841  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.842  3941  3941 D HeadsetService: Received stop request...Stopping profile...
08-26 19:03:05.842  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 19:03:05.842  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.849  3838  3850 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.849   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.850  1341  1358 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.850   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.850   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.850  1341  1341 D HeadsetProfile: Bluetooth service disconnected
08-26 19:03:05.850  1920  1934 D BluetoothHeadset: Proxy object disconnected
08-26 19:03:05.851  3941  3941 D A2dpService: Received stop request...Stopping profile...
,08-26 19:03:05.854  3941  4124 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:03:05.857   872   872 D BluetoothA2dp: Proxy object disconnected
,08-26 19:03:05.858  3941  3941 D HidService: Received stop request...Stopping profile...
08-26 19:03:05.858  3941  3941 D HidService: Stopping Bluetooth HidService
08-26 19:03:05.858  1341  1341 D BluetoothA2dp: Proxy object disconnected
08-26 19:03:05.859  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.859  3941  3941 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:05.859  1341  1341 D BluetoothInputDevice: Proxy object disconnected
08-26 19:03:05.859  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:03:05.859  1341  1341 D HidProfile: Bluetooth service disconnected
08-26 19:03:05.859  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:05.859  3838  3838 D DockEventReceiver: finishStartingService: stopping service
08-26 19:03:05.860  3941  3941 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:03:05.860  3941  3941 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:03:05.861  3838  3838 D HeadsetProfile: Bluetooth service disconnected
,08-26 19:03:05.861  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:03:05.861  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:03:05.861  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:03:05.861  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 19:03:05.862  3941  4109 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-26 19:03:05.862  3838  3838 D BluetoothA2dp: Proxy object disconnected
,08-26 19:03:05.864  3941  3941 D HealthService: Received stop request...Stopping profile...
,08-26 19:03:05.866  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:05.867  3838  3838 D BluetoothInputDevice: Proxy object disconnected
08-26 19:03:05.867  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.867  3941  3941 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:05.867  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:05.867  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:05.868  3941  3941 D PanService: Received stop request...Stopping profile...
08-26 19:03:05.867  3838  3838 D HidProfile: Bluetooth service disconnected
08-26 19:03:05.870  1341  1341 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:03:05.870  1341  1341 D PanProfile: Bluetooth service disconnected
08-26 19:03:05.870  3941  3941 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:03:05.870  3941  3941 D BluetoothMapService: stop()
08-26 19:03:05.870  3838  3838 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:03:05.871  3838  3838 D PanProfile: Bluetooth service disconnected
,08-26 19:03:05.871  3941  3941 D BluetoothMapAppObserver: deinitObservers()
08-26 19:03:05.871  3941  3941 D BluetoothMapAppObserver: removeReceiver()
,08-26 19:03:05.872  3838  3838 D BluetoothMap: Proxy object disconnected
,08-26 19:03:05.872  3838  3838 D MapProfile: Bluetooth service disconnected
,08-26 19:03:05.872  1341  1341 D BluetoothMap: Proxy object disconnected
08-26 19:03:05.873  1341  1341 D MapProfile: Bluetooth service disconnected
,08-26 19:03:05.874  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 19:03:05.874  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 19:03:05.874  3941  4115 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:05.874  3941  4115 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:05.874  3941  4115 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:05.874  3941  4115 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:05.874  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 19:03:05.875  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.876  3941  3941 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:05.876  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:05.876  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:05.876  3941  3941 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:03:05.876  3941  3941 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:03:05.876  3941  4109 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 19:03:05.879  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.879  3941  3941 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:05.879  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:05.879  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:05.879  3941  3941 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:03:05.879  1341  1341 D BluetoothPbap: Proxy object disconnected
08-26 19:03:05.879  1341  1341 D PbapServerProfile: Bluetooth service disconnected
08-26 19:03:05.879  3941  4109 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 19:03:05.880  3941  3941 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:03:05.880  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.880  3941  3941 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:03:05.880  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:05.880  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:05.883  3941  3941 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-26 19:03:05.879  3838  3838 D BluetoothPbap: Proxy object disconnected
,08-26 19:03:05.886  3838  3838 D PbapServerProfile: Bluetooth service disconnected
,08-26 19:03:05.883  3941  3941 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:03:05.887  3941  3941 D BluetoothMapService: MAP Service closeService in
,08-26 19:03:05.888  3941  3941 V BluetoothAdapterState: isTurningOff()=true
08-26 19:03:05.888  3941  3941 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:05.888  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:05.888  3941  3941 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:05.888  3941  3941 D BluetoothMapService: cleanup()
08-26 19:03:05.888  3941  3941 D BluetoothMapService: MAP Service closeService in
,08-26 19:03:05.889  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 19:03:05.889  3941  4105 D BluetoothAdapterProperties: Setting state to 15
08-26 19:03:05.889  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 19:03:05.889  3941  4105 I BluetoothAdapterState: Entering BleOnState
08-26 19:03:05.889  1341  1358 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:03:05.890   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:05.890  1341  1357 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:03:05.890   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:05.891  1341  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:05.891  1341  1358 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:03:05.891  3838  3851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:05.892  3838  3850 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:03:05.892  1341  1357 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:03:05.893  1920  1943 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 19:03:05.893   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:03:05.893  3838  3851 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:03:05.894  3838  3850 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:03:05.894  3838  3851 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:03:05.895  1341  1364 D BluetoothPan: onBluetoothStateChange on: false
,08-26 19:03:05.895   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:03:05.895  3838  3850 D BluetoothPan: onBluetoothStateChange on: false
,08-26 19:03:05.896  3941  4105 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 19:03:05.896  3941  4105 D BluetoothAdapterProperties: Setting state to 16
08-26 19:03:05.896  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 19:03:05.899  3941  4105 D BluetoothAdapterProperties: onBleDisable
,08-26 19:03:05.899  3941  4105 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:03:05.899  3941  4106 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 19:03:05.900  3941  4115 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 19:03:05.900  3941  4115 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:03:05.901  3941  4109 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:05.902  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.903  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 19:03:05.903  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.905  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.907  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.907  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,08-26 19:03:05.908  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:06.101  3941  4109 I bt_hci  : shut_down
,08-26 19:03:06.101  3941  4113 D bt_hwcfg: hw_epilog_process
,08-26 19:03:06.115  3941  4113 I bt_vendor: low_power_mode_cb
,08-26 19:03:06.137  3941  4113 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 19:03:06.137  3941  4113 I bt_vendor: epilog_cb
08-26 19:03:06.138  3941  4113 I bt_hci  : epilog_finished_callback
,08-26 19:03:06.147  3941  4109 I bt_hci_h4: hal_close
,08-26 19:03:06.148  3941  4109 I bt_userial_vendor: device fd = 51 close
,08-26 19:03:06.268  3941  4106 D bt_stack_manager: event_shut_down_stack finished.
,08-26 19:03:06.269  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 19:03:06.277  3941  3941 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:03:06.277  3941  4105 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 19:03:06.279  3941  3941 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 19:03:06.280  3941  3941 D BtGatt.GattService: stop()
,08-26 19:03:06.281  3941  3941 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 19:03:06.288  3941  3941 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:06.288  3941  3941 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:03:06.288  3941  3941 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:03:06.289  3941  3941 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 19:03:06.289  3941  4105 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 19:03:06.290  3941  4105 D BluetoothAdapterProperties: Setting state to 10
08-26 19:03:06.291  3941  4105 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 19:03:06.292  3941  4105 I BluetoothAdapterState: Entering OffState
08-26 19:03:06.294   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 19:03:06.321  3941  3941 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 19:03:06.322  3941  3941 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 19:03:06.322  3941  4106 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 19:03:06.334  3941  3941 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 19:03:06.337  3941  4106 D bt_stack_manager: event_clean_up_stack finished.
,08-26 19:03:06.342  3941  3941 I art     : System.exit called, status: 0
,08-26 19:03:06.342  3941  3941 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 19:03:06.391   872  1884 I ActivityManager: Process com.android.bluetooth (pid 3941) has died
,08-26 19:03:08.804  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:03:08.804  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:11.812  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:11.812  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@373b7f6 added. We now have 6 listener(s)
08-26 19:03:11.813  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:11.816  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:11.817  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89677f7 added. We now have 7 listener(s)
08-26 19:03:11.817  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:11.819  3766  3818 I System.out: IsBluetoothEnabled
,08-26 19:03:11.830  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:11.873   872   889 I ActivityManager: Start proc 4154:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 19:03:11.880   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 19:03:11.891  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-26 19:03:11.912   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:03:11.912   872   892 I Adreno  : Build Date                       : 10/20/15
08-26 19:03:11.912   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:03:11.912   872   892 I Adreno  : Local Branch                     : M14
08-26 19:03:11.912   872   892 I Adreno  : Remote Branch                    : 
08-26 19:03:11.912   872   892 I Adreno  : Remote Branch                    : 
08-26 19:03:11.912   872   892 I Adreno  : Reconstruct Branch               : 
,08-26 19:03:11.937   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (177 us)
,08-26 19:03:11.978  4154  4154 D AdapterServiceConfig: Adding HeadsetService
,08-26 19:03:11.980  4154  4154 D AdapterServiceConfig: Adding A2dpService
08-26 19:03:11.980  4154  4154 D AdapterServiceConfig: Adding HidService
,08-26 19:03:11.980  4154  4154 D AdapterServiceConfig: Adding HealthService
08-26 19:03:11.981  4154  4154 D AdapterServiceConfig: Adding PanService
,08-26 19:03:11.981  4154  4154 D AdapterServiceConfig: Adding GattService
08-26 19:03:11.981  4154  4154 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 19:03:12.000   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7aec41a:true
,08-26 19:03:12.001  4154  4154 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 19:03:12.006  4154  4154 I bt_bluedroid: init
,08-26 19:03:12.006  4154  4168 I BluetoothAdapterState: Entering OffState
,08-26 19:03:12.008  4154  4169 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 19:03:12.008  4154  4169 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 19:03:12.008  4154  4169 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 19:03:12.009  4154  4169 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:03:12.009  4154  4154 I bt_bluedroid: get_profile_interface socket
,08-26 19:03:12.011  4154  4154 I bt_bluedroid: get_profile_interface sdp
,08-26 19:03:12.014  4154  4172 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:03:12.018  4154  4172 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:03:12.014  4154  4165 I bt_bluedroid: config_hci_snoop_log
,08-26 19:03:12.023   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 19:03:12.036  4154  4168 D BluetoothAdapterState: Current state: OFF, message: 0
08-26 19:03:12.037  4154  4168 D BluetoothAdapterProperties: Setting state to 14
08-26 19:03:12.037  4154  4168 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 19:03:12.040  4154  4168 D BluetoothBondStateMachine: make
,08-26 19:03:12.043  4154  4173 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 19:03:12.046  4154  4168 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:03:12.049  4154  4154 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 19:03:12.053  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:12.054  4154  4154 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:03:12.055  4154  4154 D BtGatt.GattService: Received start request. Starting profile...
,08-26 19:03:12.055  4154  4154 D BtGatt.GattService: start()
08-26 19:03:12.055  4154  4154 I bt_bluedroid: get_profile_interface gatt
,08-26 19:03:12.056  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:12.056  4154  4154 D BtGatt.AdvertiseManager: advertise manager created
,08-26 19:03:12.066  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:12.066  4154  4154 V BluetoothAdapterState: isTurningOn()=false
08-26 19:03:12.066  4154  4154 V BluetoothAdapterState: isBleTurningOn()=true
08-26 19:03:12.066  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:12.067  4154  4168 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 19:03:12.067  4154  4168 I bt_bluedroid: enable
08-26 19:03:12.068  4154  4169 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 19:03:12.068  4154  4169 I bt_hci  : start_up
,08-26 19:03:12.078  4154  4169 I bt_vendor: alloc value 0xb3a48189
,08-26 19:03:12.078  4154  4169 I bt_vendor: init
08-26 19:03:12.078  4154  4169 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 19:03:12.078  4154  4169 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 19:03:12.185  4154  4169 D bt_hci  : start_up starting async portion
,08-26 19:03:12.185  4154  4176 I bt_hci  : event_finish_startup
,08-26 19:03:12.186  4154  4176 I bt_hci_h4: hal_open
08-26 19:03:12.186  4154  4176 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 19:03:12.194  4154  4176 I bt_userial_vendor: device fd = 51 open
,08-26 19:03:12.227  4154  4176 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:03:12.259  4154  4176 D bt_hwcfg: Chipset BCM4354A2
08-26 19:03:12.259  4154  4176 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 19:03:12.260  4154  4176 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 19:03:12.544  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:03:12.544  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 19:03:12.579  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d0c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a88664, 16908290=android.view.AbsSavedState$1@a88664}, android:focusedViewId=100}]}]
,08-26 19:03:12.579  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 19:03:12.580  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 19:03:12.580  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 19:03:12.581   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
08-26 19:03:12.592   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-26 19:03:12.598   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 19:03:12.600   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-26 19:03:12.600   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 19:03:12.616   872   881 I art     : Background partial concurrent mark sweep GC freed 15427(1281KB) AllocSpace objects, 10(392KB) LOS objects, 33% free, 28MB/43MB, paused 1.097ms total 100.183ms
,08-26 19:03:12.836   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 19:03:12.840   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-26 19:03:12.841   872  1326 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,08-26 19:03:12.846   872   892 I DreamManagerService: Entering dreamland.
,08-26 19:03:12.848   872   892 I PowerManagerService: Dozing...
08-26 19:03:12.850   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 19:03:12.909   375  1274 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 19:03:12.909   375  1274 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 19:03:12.914   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:03:12.920   872  1301 E native  : do suspend false
,08-26 19:03:12.922  4154  4176 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-26 19:03:12.923  4154  4176 D bt_hwcfg: Settlement delay -- 100 ms
08-26 19:03:12.923  4154  4176 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 19:03:12.931  1912  4179 D NfcService: Discovery configuration equal, not updating.
,08-26 19:03:12.961   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:03:12.964   872  1301 E native  : do suspend true
,08-26 19:03:13.039  4154  4176 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:03:13.039  4154  4176 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 19:03:13.042   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 19:03:13.043   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 19:03:13.072  4154  4176 I bt_hwcfg: vendor lib fwcfg completed
,08-26 19:03:13.072  4154  4176 I bt_vendor: firmware callback
08-26 19:03:13.072  4154  4176 I bt_hci  : firmware_config_callback
,08-26 19:03:13.088  4154  4183 I bt_btu  : btu_task pending for preload complete event
,08-26 19:03:13.088  4154  4183 I bt_btu_task: Bluetooth chip preload is complete
08-26 19:03:13.089  4154  4183 I bt_btu  : btu_task received preload complete event
,08-26 19:03:13.095  4154  4183 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 19:03:13.095  4154  4183 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:03:13.096  4154  4183 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 19:03:13.096  4154  4183 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:03:13.096  4154  4183 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:03:13.096  4154  4183 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:03:13.097  4154  4183 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 19:03:13.097  4154  4183 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 19:03:13.097  4154  4183 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:03:13.097  4154  4183 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:03:13.097  4154  4183 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 19:03:13.098  4154  4183 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:03:13.098  4154  4183 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:03:13.098  4154  4183 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:03:13.098  4154  4183 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:03:13.227  4154  4183 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c5d9d
,08-26 19:03:13.227  4154  4183 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c5d9d 
,08-26 19:03:13.239  4154  4172 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 19:03:13.241  4154  4172 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 19:03:13.243  4154  4172 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 19:03:13.246  4154  4172 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 19:03:13.248  4154  4172 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:13.248  4154  4172 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:13.249  4154  4172 D bt_hci  : do_postload posting postload work item
08-26 19:03:13.249  4154  4176 I bt_hci  : event_postload
08-26 19:03:13.249  4154  4176 I bt_vendor: sco_config_cb
08-26 19:03:13.249  4154  4176 I bt_hci  : sco_config_callback postload finished.
,08-26 19:03:13.252  4154  4172 D bt_bte_conf: Device ID record 1 : primary
08-26 19:03:13.253  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:13.253  4154  4172 D bt_bte_conf:   vendorId            = 000f
,08-26 19:03:13.253  4154  4172 D bt_bte_conf:   vendorIdSource      = 0001
08-26 19:03:13.253  4154  4172 D bt_bte_conf:   product             = 1200
08-26 19:03:13.253  4154  4172 D bt_bte_conf:   version             = 1436
08-26 19:03:13.254  4154  4172 D bt_bte_conf:   clientExecutableURL = 
08-26 19:03:13.254  4154  4172 D bt_bte_conf:   serviceDescription  = 
,08-26 19:03:13.254  4154  4172 D bt_bte_conf:   documentationURL    = 
08-26 19:03:13.254  4154  4172 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 19:03:13.255  4154  4169 D bt_stack_manager: event_start_up_stack finished
08-26 19:03:13.259  4154  4168 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 19:03:13.259  4154  4168 D BluetoothAdapterProperties: Setting state to 15
,08-26 19:03:13.260  4154  4168 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 19:03:13.261  4154  4168 I BluetoothAdapterState: Entering BleOnState
,08-26 19:03:13.263  4154  4176 I bt_vendor: low_power_mode_cb
,08-26 19:03:13.266  4154  4168 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 19:03:13.266  4154  4168 D BluetoothAdapterProperties: Setting state to 11
,08-26 19:03:13.267  4154  4168 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 19:03:13.275  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:13.276  4154  4154 D HeadsetService: Received start request. Starting profile...
08-26 19:03:13.282  4154  4154 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 19:03:13.282  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:13.282  4154  4154 D HeadsetStateMachine: make
,08-26 19:03:13.297  4154  4154 D HeadsetStateMachine: max_hf_connections = 1
,08-26 19:03:13.297  4154  4168 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:03:13.298  4154  4154 I bt_bluedroid: get_profile_interface handsfree
08-26 19:03:13.298  4154  4172 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 19:03:13.298  4154  4172 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 19:03:13.304  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:13.305  4154  4154 D A2dpService: Received start request. Starting profile...
,08-26 19:03:13.306  4154  4154 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 19:03:13.307  4154  4154 I bt_bluedroid: get_profile_interface avrcp
,08-26 19:03:13.317  4154  4154 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:03:13.317  4154  4154 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:03:13.317  4154  4154 D A2dpStateMachine: make
,08-26 19:03:13.320  4154  4154 I bt_bluedroid: get_profile_interface a2dp
,08-26 19:03:13.321  4154  4172 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 19:03:13.323  4154  4192 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:03:13.324  4154  4154 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 19:03:13.325  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:13.326  4154  4154 D HidService: Received start request. Starting profile...
08-26 19:03:13.326  4154  4154 I bt_bluedroid: get_profile_interface hidhost
08-26 19:03:13.326  4154  4154 D HidService: setHidService(): set to: null
,08-26 19:03:13.327  4154  4172 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a73e5
08-26 19:03:13.327  4154  4172 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 19:03:13.328  4154  4154 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:03:13.330  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:13.331  4154  4154 D HealthService: Received start request. Starting profile...
,08-26 19:03:13.333  4154  4154 I bt_bluedroid: get_profile_interface health
08-26 19:03:13.335  4154  4154 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:03:13.336  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:13.336  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:03:13.337  4154  4154 D PanService: Received start request. Starting profile...
08-26 19:03:13.337  4154  4154 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:03:13.338  4154  4154 I bt_bluedroid: get_profile_interface pan
08-26 19:03:13.339  4154  4172 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:03:13.345  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
,08-26 19:03:13.347  4154  4154 D BluetoothMapService: Received start request. Starting profile...
,08-26 19:03:13.347  4154  4154 D BluetoothMapService: start()
,08-26 19:03:13.352  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 19:03:13.355  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 19:03:13.355  4154  4154 D BluetoothMapAppObserver: createReceiver()
,08-26 19:03:13.358  4154  4154 D BluetoothMapAppObserver: initObservers()
,08-26 19:03:13.358  4154  4154 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 19:03:13.381  4154  4190 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 19:03:13.383  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:13.383  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:03:13.383  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:03:13.384  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:13.385  4154  4154 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:13.385  4154  4154 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isTurningOn()=true
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:13.386  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:13.387  4154  4154 V BluetoothAdapterState: isTurningOff()=false
08-26 19:03:13.387  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:03:13.387  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:03:13.388  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:03:13.388  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:03:13.388  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:03:13.388  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:03:13.388  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false,
08-26 19:03:13.388  4154  4168 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 19:03:13.389  4154  4168 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:03:13.389  4154  4168 D BluetoothAdapterProperties: State =  11
,08-26 19:03:13.389  4154  4168 D BluetoothAdapterProperties: Setting state to 12
08-26 19:03:13.389  4154  4168 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
08-26 19:03:13.390  1341  1358 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 19:03:13.391  4154  4168 I BluetoothAdapterState: Entering OnState
,08-26 19:03:13.392  4154  4172 D BluetoothAdapterProperties: Scan Mode:21
,08-26 19:03:13.393  4154  4172 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:03:13.393   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:03:13.393  1341  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:03:13.397   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:13.397  1341  1357 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:13.398  1341  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:13.398  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:13.399  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:13.400  3838  3850 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:13.401  4154  4154 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 19:03:13.401  3838  3851 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:13.403  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:13.403  1341  1364 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:13.403  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:13.405  1920  1934 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:03:13.406   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:03:13.406  3838  3850 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:13.406  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:13.407  4154  4154 D ObexServerSockets: Succeed to create listening sockets 
,08-26 19:03:13.407  4154  4154 D ObexServerSockets0: startAccept()
08-26 19:03:13.407  4154  4154 D ObexServerSockets0: prepareForNewConnect()
,08-26 19:03:13.408  3838  3851 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:03:13.409  4154  4154 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 19:03:13.410  4154  4154 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 19:03:13.411  3838  3850 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:13.411  1341  1341 D BluetoothInputDevice: Proxy object connected
08-26 19:03:13.411  1341  1341 D HidProfile: Bluetooth service connected
08-26 19:03:13.413  1341  1364 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:03:13.414  1341  1341 D BluetoothA2dp: Proxy object connected
,08-26 19:03:13.414  4154  4199 D ObexServerSockets0: Accepting socket connection...
08-26 19:03:13.415   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:13.415   872   872 D BluetoothA2dp: Proxy object connected
08-26 19:03:13.415  3838  3850 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:03:13.416  1341  1341 D BluetoothMap: Proxy object connected
,08-26 19:03:13.416  4154  4198 D ObexServerSockets0: Accepting socket connection...
,08-26 19:03:13.416  1341  1341 D MapProfile: Bluetooth service connected
08-26 19:03:13.417  1341  1341 D BluetoothMap: getConnectedDevices()
,08-26 19:03:13.419   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 19:03:13.420  1341  1341 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:13.420  1341  1341 D PanProfile: Bluetooth service connected
08-26 19:03:13.420  4154  4154 D BluetoothMapService: onReceive
08-26 19:03:13.420  4154  4154 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:13.420  4154  4154 D BluetoothMapService: STATE_ON
08-26 19:03:13.422  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:13.422  3838  3838 D BluetoothInputDevice: Proxy object connected
08-26 19:03:13.422  3838  3838 D HidProfile: Bluetooth service connected
,08-26 19:03:13.424  3838  3838 D BluetoothA2dp: Proxy object connected
,08-26 19:03:13.427  3838  3838 D BluetoothMap: Proxy object connected
,08-26 19:03:13.427  3838  3838 D MapProfile: Bluetooth service connected
08-26 19:03:13.427  3838  3838 D BluetoothMap: getConnectedDevices()
,08-26 19:03:13.429  3838  3838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:03:13.429  3838  3838 D PanProfile: Bluetooth service connected
,08-26 19:03:13.434  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:13.441  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:13.442  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:13.450  3838  3838 D BluetoothPbap: Proxy object connected
,08-26 19:03:13.450  1341  1341 D BluetoothPbap: Proxy object connected
08-26 19:03:13.450  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 19:03:13.450  3838  3838 D PbapServerProfile: Bluetooth service connected
08-26 19:03:13.450  1341  1341 D PbapServerProfile: Bluetooth service connected
,08-26 19:03:13.450  4154  4154 D ObexServerSockets0: prepareForNewConnect()
,08-26 19:03:13.458  4154  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:13.477  4154  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:13.478  4154  4208 I BtOppRfcommListener: Accept thread started.
,08-26 19:03:13.495  3838  3850 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.495   872   872 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.495  3838  3838 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:13.495  1341  1357 D BluetoothHeadset: Proxy object connected
08-26 19:03:13.496   872   872 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.496  1341  1341 D HeadsetProfile: Bluetooth service connected
08-26 19:03:13.496   872   872 D BluetoothHeadset: Proxy object connected
08-26 19:03:13.496  1920  1943 D BluetoothHeadset: Proxy object connected
08-26 19:03:13.497   872   889 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.497  1341  1364 D BluetoothHeadset: Proxy object connected
08-26 19:03:13.499  1341  1341 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:13.502  3838  4200 D BluetoothHeadset: Proxy object connected
08-26 19:03:13.502  3838  3838 D HeadsetProfile: Bluetooth service connected
,08-26 19:03:13.506  1920  2055 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.506   872   889 D BluetoothHeadset: Proxy object connected
,08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:13.854  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:13.861  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-26 19:03:13.864  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:13.864  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60be0cd added. We now have 8 listener(s)
08-26 19:03:13.865  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:13.870   872  2230 D WifiService: setWifiEnabled: false pid=3766, uid=10000
08-26 19:03:13.870   872  2230 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:03:13.882  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:13.884   872   882 D WifiService: setWifiEnabled: true pid=3766, uid=10000
,08-26 19:03:13.884   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:03:13.900   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:13.920  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:13.928  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:13.931   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-26 19:03:13.932   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-26 19:03:13.933   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 19:03:13.934   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:03:13.934   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 19:03:13.934   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 19:03:13.935   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 19:03:13.952   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 19:03:13.953   371   870 D CommandListener: Setting iface cfg
,08-26 19:03:13.954   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
08-26 19:03:13.954   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 19:03:13.954   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:03:13.956   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 19:03:13.957   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 19:03:13.958   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 19:03:13.974   872  1301 E native  : do suspend true
,08-26 19:03:14.000   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 19:03:14.000   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:14.012   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 19:03:14.073   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 19:03:14.076  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 19:03:14.497  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 19:03:14.535  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 19:03:14.536  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 19:03:14.538   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:03:14.553   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:03:14.553   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:14.553   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 19:03:14.583   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:14.595   371   870 D CommandListener: Setting iface cfg
,08-26 19:03:14.596   872  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 19:03:14.604   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 19:03:14.646   872  4216 D DhcpClient: Receive thread started
,08-26 19:03:14.733   872  1301 E native  : do suspend false
,08-26 19:03:14.754   872  2054 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 19:03:14.771   872  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 19:03:14.772   872  2054 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 19:03:14.777   872  2054 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 19:03:14.794   872  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 19:03:14.795   872  2054 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 19:03:14.801   371   870 D CommandListener: Setting iface cfg
,08-26 19:03:14.812   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 19:03:14.814   872  2054 D DhcpClient: Scheduling renewal in 86399s
,08-26 19:03:14.815   872  1301 E native  : do suspend true
,08-26 19:03:14.835   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 19:03:14.838   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 19:03:14.840   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 19:03:14.842   872  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 19:03:14.852   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:14.908  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:14.910  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:14.914  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 19:03:14.915  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 19:03:14.917  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5d0c Bundle[{}]
,08-26 19:03:14.918  3766  3818 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 19:03:14.919  3766  3818 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 19:03:14.919  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:03:14.920  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 19:03:14.921  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 19:03:14.922  3766  3818 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 19:03:14.931   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 19:03:14.931   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 19:03:14.933   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 19:03:14.935   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 19:03:14.937   872  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 19:03:14.938  3766  3818 I System.out: Running OutgoingSocketThread
,08-26 19:03:14.943  3766  4219 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-26 19:03:14.944  3766  4219 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43455
08-26 19:03:14.944  3766  4219 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 19:03:14.951   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 19:03:14.956   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 19:03:14.956   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 19:03:14.957   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 19:03:14.957   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:03:14.958   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 19:03:14.958   872  1303 D ConnectivityService:    accepting network in place of null
,08-26 19:03:14.960   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:03:14.978   872  4215 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152947, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 19:03:14.989   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:03:15.021   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:03:15.026   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 19:03:15.026   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:15.043   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 19:03:15.049   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:15.061  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:15.061   872  4214 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
08-26 19:03:15.065  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:03:15.075  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:03:15.079  1710  1710 D SystemUpdateService: onCreate
,08-26 19:03:15.082  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:03:15.096  1710  4226 I SystemUpdateService: active receiver: enabled
,08-26 19:03:15.106  1710  4226 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:03:15.109  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 19:03:15.111  1710  2495 I iu.UploadsManager: num queued entries: 0
,08-26 19:03:15.112  1710  2495 I iu.UploadsManager: num updated entries: 0
,08-26 19:03:15.115  1710  4226 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 19:03:15.115  1710  4226 I SystemUpdateService: now status is 0 (complete)
08-26 19:03:15.115  1710  4226 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 19:03:15.115  1710  4226 I SystemUpdateService: file has been verified
08-26 19:03:15.115  1710  4226 I SystemUpdateService: OTA package size = 12249756
,08-26 19:03:15.121  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:03:15.122  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:03:15.124  3955  3955 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:15.128  1710  4229 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 19:03:15.128  1710  4229 W BaseAppContext: Using Auth Proxy for data requests.
08-26 19:03:15.129  1710  4229 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 19:03:15.132  3955  3955 D SprintDMHelper: simOperator: 
08-26 19:03:15.132  3955  3955 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:03:15.148   872  4214 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:03:15 GMT], X-Android-Received-Millis=[1472230995144], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472230995107]}
,08-26 19:03:15.150   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:03:15.151   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 19:03:15.152   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 19:03:15.158   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:03:15.167  1710  2495 I iu.SyncManager: NEXT; no task
,08-26 19:03:15.170  1710  4226 I SystemUpdateService: showing system update notification
,08-26 19:03:15.172  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:15.178  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:15.202  1710  1710 D SystemUpdateService: onDestroy
,08-26 19:03:15.215  1495  2320 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 19:03:15.215  1495  2320 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 19:03:15.216  1495  2320 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:03:15.216  1495  2320 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:03:15.235  1710  4229 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-26 19:03:15.286  3889  4231 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 19:03:15.941  3766  3818 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-26 19:03:15.941  3766  3818 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-26 19:03:15.951  3766  3818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-26 19:03:15.953  3766  3818 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 19:03:15.953  3766  3818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-26 19:03:15.959  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:15.959  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b5d82 added. We now have 2 listener(s)
,08-26 19:03:15.961  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:03:15.961  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:15.961  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:15.961  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:15.961  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb09c93 added. We now have 9 listener(s)
,08-26 19:03:15.961  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:15.962  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:15.967  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:15.974  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:15.977  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:03:15.978  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:03:15.978  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:15.978  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c82bcc9 added. We now have 3 listener(s)
08-26 19:03:15.980  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:03:15.980  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:15.980  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:15.980  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:15.980  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a5cfce added. We now have 10 listener(s)
08-26 19:03:15.980  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:15.980  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:15.981  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:15.981  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:15.981  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:15.981  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:15.981  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:15.981  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:15.981  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b5d82 removed from the list
08-26 19:03:15.981  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:15.981  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb09c93 removed from the list
08-26 19:03:15.983  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:15.987  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:15.988  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:15.988  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:15.988  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:15.988  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:15.990  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:15.990  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:15.990  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:15.990  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb09c93 not in the list
08-26 19:03:15.990  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:15.990  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:15.991  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:15.992  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:15.992  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:15.992  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a5cfce removed from the list
08-26 19:03:15.992  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:15.992  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:15.992  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:15.992  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:15.992  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c82bcc9 removed from the list
08-26 19:03:15.993  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:15.993  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43e6eef added. We now have 2 listener(s)
08-26 19:03:15.995  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:03:15.995  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:15.995  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:15.995  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:15.995  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3dfc added. We now have 9 listener(s)
08-26 19:03:15.995  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:15.996  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:03:16.003  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:16.010  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:16.014  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.014  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:16.015  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:16.015  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b531ada added. We now have 3 listener(s)
08-26 19:03:16.017  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:03:16.017  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:16.017  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:16.017  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:16.017  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d0b0b added. We now have 10 listener(s)
08-26 19:03:16.017  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:16.018  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:16.018  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:16.018  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:16.018  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:16.018  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:03:16.020  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.023  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 19:03:16.024  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:03:16.024  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.026   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-26 19:03:16.034  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:03:16.035  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 19:03:16.036  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:03:16.042  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:03:16.043  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:03:16.043  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:03:16.045  3766  3818 D BluetoothAdapter: STATE_ON
08-26 19:03:16.051  4154  4165 D BtGatt.GattService: registerClient() - UUID=544780dc-2210-4e01-a983-cf05aa2ad692
08-26 19:03:16.052  4154  4172 D BtGatt.GattService: onClientRegistered() - UUID=544780dc-2210-4e01-a983-cf05aa2ad692, clientIf=5
08-26 19:03:16.054  3766  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:03:16.055  4154  4164 D BtGatt.GattService: start scan with filters
,08-26 19:03:16.059  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:03:16.060  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:03:16.060  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 19:03:16.060  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:03:16.060  4154  4175 D BtGatt.ScanManager: handling starting scan
,08-26 19:03:16.063  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:03:16.064  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:03:16.064  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:03:16.064  4154  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eeef2e0
08-26 19:03:16.066  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 19:03:16.069  3766  3818 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:03:16.069  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:16.069  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:03:16.069  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.069  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 19:03:16.069  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:03:16.069  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:03:16.069  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:03:16.070  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:03:16.070  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:16.070  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:03:16.071  3766  3818 D BluetoothAdapter: STATE_ON
08-26 19:03:16.072  4154  4172 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 19:03:16.072  4154  4197 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:03:16.073  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.074  4154  4175 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 19:03:16.074  4154  4189 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:03:16.075  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:16.076  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:03:16.076  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 19:03:16.077  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:03:16.077  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:03:16.079  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:16.079  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:03:16.079  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:03:16.079  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:03:16.080  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:16.082  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:16.082  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:16.083  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:16.085  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,08-26 19:03:16.085  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-26 19:03:16.087  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:03:16.088  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 19:03:16.088  4154  4175 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:03:16.088  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:16.088  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.088  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:03:16.088  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 19:03:16.088  4154  4175 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-26 19:03:16.088  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:03:16.088  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@43e6eef removed from the list
,08-26 19:03:16.088  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.088  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3dfc removed from the list,
,08-26 19:03:16.089  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:16.089  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.091  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.092  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.095  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:16.095  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.095  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.095  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3dfc not in the list
08-26 19:03:16.096  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.096  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.098  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.098  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:16.098  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.099  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d0b0b removed from the list
08-26 19:03:16.099  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.099  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.099  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.100  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:03:16.100  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b531ada removed from the list
,08-26 19:03:16.103  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:16.103  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11f4ce7 added. We now have 2 listener(s)
,08-26 19:03:16.109  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:03:16.110  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:16.110  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.111  4154  4172 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:03:16.111  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.111  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:16.112  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56c5094 added. We now have 9 listener(s)
,08-26 19:03:16.112  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:16.113  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:16.118  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:16.120  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:03:16.121  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:16.124  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:16.128  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:03:16.128  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:03:16.128  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:16.129  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6a2b32 added. We now have 3 listener(s)
,08-26 19:03:16.131  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 19:03:16.132  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.132  4154  4175 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:03:16.132  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:03:16.132  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:16.133  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.133  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:16.133  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d083 added. We now have 10 listener(s)
,08-26 19:03:16.133  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:16.133  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:16.133  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:03:16.135  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:03:16.136  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:16.136  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:03:16.136  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:16.136  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:03:16.138  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.140  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:03:16.141  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:03:16.142  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:03:16.142  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.144  4154  4175 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 19:03:16.148  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:03:16.149  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:03:16.150  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:03:16.151  4154  4172 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:03:16.152  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.155  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:03:16.155  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:03:16.155  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:03:16.155  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:03:16.158  4154  4189 D BtGatt.GattService: registerClient() - UUID=249e888a-1249-4b4f-9733-374ca0aba6e9
,08-26 19:03:16.159  4154  4172 D BtGatt.GattService: onClientRegistered() - UUID=249e888a-1249-4b4f-9733-374ca0aba6e9, clientIf=5
,08-26 19:03:16.159  3766  3813 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 19:03:16.160  4154  4197 D BtGatt.GattService: start scan with filters
,08-26 19:03:16.163  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:03:16.164  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:03:16.164  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:03:16.164  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:03:16.164  4154  4175 D BtGatt.ScanManager: handling starting scan
,08-26 19:03:16.167  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:03:16.168  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:16.168  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-26 19:03:16.169  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:03:16.174  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:03:16.174  3766  3818 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 19:03:16.174  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:03:16.174  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:16.174  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:16.175  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.175  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.175  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 19:03:16.175  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:16.175  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11f4ce7 removed from the list
08-26 19:03:16.175  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.175  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56c5094 removed from the list
08-26 19:03:16.175  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:16.175  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:16.176  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.176  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:03:16.176  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.176  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:16.178  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:03:16.178  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.178  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.178  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56c5094 not in the list
08-26 19:03:16.178  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 19:03:16.178  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:03:16.178  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:03:16.179  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:16.179  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:03:16.180  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:03:16.180  4154  4165 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:03:16.181  4154  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 19:03:16.181  4154  4172 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:03:16.181  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:03:16.181  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.181  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 19:03:16.182  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:03:16.182  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 19:03:16.182  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:03:16.182  4154  4175 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 19:03:16.183  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:03:16.183  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:03:16.183  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:03:16.183  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:03:16.184  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.185  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:03:16.185  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:03:16.185  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:03:16.185  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d083 removed from the list
08-26 19:03:16.185  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:16.185  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:03:16.186  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:16.186  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:03:16.186  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.186  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:16.186  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:03:16.186  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6a2b32 removed from the list,
08-26 19:03:16.187  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:16.187  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ef1df added. We now have 2 listener(s)
,08-26 19:03:16.188  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:03:16.189  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:16.189  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.189  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:16.189  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6091e2c added. We now have 9 listener(s)
08-26 19:03:16.189  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:16.190  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:16.193  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:16.198  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:03:16.199  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:16.199  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:03:16.199  4154  4175 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:03:16.199  4154  4175 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:03:16.201  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.202  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:16.203  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:16.203  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@997ee8a added. We now have 3 listener(s)
,08-26 19:03:16.205  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:03:16.206  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:16.207  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:16.209  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.209  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:16.210  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91accfb added. We now have 10 listener(s)
08-26 19:03:16.210  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:16.210  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.210  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:16.211  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:16.211  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:03:16.211  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:16.211  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:03:16.216  4154  4172 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:03:16.216  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.217  3766  3818 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 19:03:16.217  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:03:16.221  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:03:16.221  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:03:16.222  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:03:16.224  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:03:16.224  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.225  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:03:16.225  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 19:03:16.226  3766  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:03:16.226  3766  3818 D BluetoothAdapter: STATE_ON
,08-26 19:03:16.229  4154  4164 D BtGatt.GattService: registerClient() - UUID=24f33c3f-eaa0-4fed-90c2-7e53d6855b42
,08-26 19:03:16.229  4154  4172 D BtGatt.GattService: onClientRegistered() - UUID=24f33c3f-eaa0-4fed-90c2-7e53d6855b42, clientIf=5
08-26 19:03:16.229  3766  3775 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 19:03:16.230  4154  4165 D BtGatt.GattService: start scan with filters
,08-26 19:03:16.231  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:03:16.231  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.231  4154  4175 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:03:16.233  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:03:16.233  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:03:16.234  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 19:03:16.234  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:03:16.238  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 19:03:16.238  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.238  4154  4175 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:03:16.239  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:16.239  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:16.239  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:03:16.241  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:03:16.243  4154  4172 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 19:03:16.243  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.244  4154  4175 D BtGatt.ScanManager: handling starting scan
,08-26 19:03:16.247  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:03:16.247  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:16.247  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:16.247  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:03:16.247  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.247  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:03:16.247  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:16.248  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ef1df removed from the list
,08-26 19:03:16.248  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.248  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6091e2c removed from the list
08-26 19:03:16.248  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:16.248  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:16.249  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:03:16.249  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 19:03:16.249  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:03:16.249  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:16.250  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:03:16.250  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:03:16.250  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:03:16.250  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6091e2c not in the list
08-26 19:03:16.250  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-26 19:03:16.250  4154  4172 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 19:03:16.250  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 19:03:16.250  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.250  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:03:16.251  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:16.251  4154  4175 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 19:03:16.251  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-26 19:03:16.251  3766  3818 D BluetoothAdapter: STATE_ON
08-26 19:03:16.252  4154  4165 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:03:16.253  4154  4197 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-26 19:03:16.253  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:16.253  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:03:16.253  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 19:03:16.253  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:03:16.253  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:03:16.254  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-26 19:03:16.255  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:03:16.255  3766  3818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:03:16.255  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:03:16.255  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.256  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.257  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:16.257  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:03:16.257  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91accfb removed from the list
08-26 19:03:16.257  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.257  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.257  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:16.257  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:03:16.257  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:16.257  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@997ee8a removed from the list
08-26 19:03:16.257  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:16.257  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:03:16.258  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.258  4154  4175 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:03:16.257  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:03:16.259  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:16.259  4154  4175 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 19:03:16.259  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bf3dd7 added. We now have 2 listener(s)
08-26 19:03:16.261  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:03:16.261  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:16.261  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.261  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:16.262  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58f06c4 added. We now have 9 listener(s)
08-26 19:03:16.262  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:16.262  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:16.266  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:16.270  4154  4172 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:03:16.270  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:16.272  3766  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:16.274  3766  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:03:16.274  3766  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:03:16.274  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:16.275  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fc4e2 added. We now have 3 listener(s)
,08-26 19:03:16.275  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:03:16.275  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.277  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:16.277  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:03:16.278  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:16.278  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:03:16.278  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:16.278  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcfe073 added. We now have 10 listener(s)
,08-26 19:03:16.278  3766  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:16.278  3766  3818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:16.278  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:16.278  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:16.278  3766  3818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:16.278  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.278  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.278  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:16.278  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:16.279  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bf3dd7 removed from the list
08-26 19:03:16.279  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.279  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58f06c4 removed from the list
08-26 19:03:16.279  3766  3818 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:16.279  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.279  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.279  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.281  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:16.281  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.281  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.281  3766  3818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58f06c4 not in the list
08-26 19:03:16.281  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.281  3766  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.282  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:16.282  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:16.282  3766  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:16.282  3766  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcfe073 removed from the list
08-26 19:03:16.282  3766  3818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:16.282  3766  3818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:16.282  3766  3818 D org.thaliproject.p2p.btconnectorlib.intern,al.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:16.282  3766  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:16.282  3766  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59fc4e2 removed from the list
08-26 19:03:16.283  4154  4172 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:03:16.283  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 19:03:16.283  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:03:16.283  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 19:03:16.284  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:16.284  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 19:03:16.284  3766  3818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:16.285  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.285  4154  4175 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:03:16.289  3766  4238 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name),
08-26 19:03:16.289  3766  4238 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
,08-26 19:03:16.289  3766  4238 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 19:03:16.290  3766  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-26 19:03:16.290  3766  4239 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-26 19:03:16.290  3766  4239 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
,08-26 19:03:16.292  4154  4172 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 19:03:16.292  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:03:16.292  4154  4175 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-26 19:03:16.292  3766  3818 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 19:03:16.292  3766  3818 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-26 19:03:16.292  3766  3818 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-26 19:03:16.292  3766  3818 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-26 19:03:16.293  3766  3818 D com.test.thalitest.ThaliTestRunner: Total duration: 22814 ms
,08-26 19:03:16.294  3766  3818 I jxcore-log: *Native tests were executed*
08-26 19:03:16.294  3766  3818 I jxcore-log: 
,08-26 19:03:16.295  3766  3818 I jxcore-log: Total number of executed tests:  80
08-26 19:03:16.295  3766  3818 I jxcore-log: 
,08-26 19:03:16.295  3766  3818 I jxcore-log: Number of passed tests:  80
08-26 19:03:16.295  3766  3818 I jxcore-log: 
,08-26 19:03:16.295  3766  3818 I jxcore-log: Number of failed tests:  0
08-26 19:03:16.295  3766  3818 I jxcore-log: 
08-26 19:03:16.295  3766  3818 I jxcore-log: Number of ignored tests:  0
,08-26 19:03:16.295  3766  3818 I jxcore-log: 
08-26 19:03:16.296  3766  3818 I jxcore-log: Total duration:  22814
08-26 19:03:16.296  3766  3818 I jxcore-log: ,
08-26 19:03:16.296  3766  3818 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:03:16.296  3766  3818 I jxcore-log: 
,08-26 19:03:16.299  4154  4172 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:03:16.299  4154  4172 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:03:16.300  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.300  3766  3818 I jxcore-log: 
08-26 19:03:16.303  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.303  3766  3818 I jxcore-log: 
08-26 19:03:16.304  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.304  3766  3818 I jxcore-log: 
08-26 19:03:16.304  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.304  3766  3818 I jxcore-log: 
08-26 19:03:16.305  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.305  3766  3818 I jxcore-log: 
08-26 19:03:16.306  3766  3766 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:03:16.307  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.307  3766  3818 I jxcore-log: 
08-26 19:03:16.308  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.308  3766  3818 I jxcore-log: 
08-26 19:03:16.310  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.310  3766  3818 I jxcore-log: 
08-26 19:03:16.310  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.310  3766  3818 I jxcore-log: 
08-26 19:03:16.311  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:16.311  3766  3818 I jxcore-log: 
08-26 19:03:16.312  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:16.312  3766  3818 I jxcore-log: 
08-26 19:03:16.312  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:16.312  3766  3818 I jxcore-log: 
08-26 19:03:16.313  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.313  3766  3818 I jxcore-log: 
08-26 19:03:16.314  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.314  3766  3818 I jxcore-log: 
08-26 19:03:16.314  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.314  3766  3818 I jxcore-log: 
08-26 19:03:16.315  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.315  3766  3818 I jxcore-log: 
08-26 19:03:16.315  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.315  3766  3818 I jxcore-log: 
08-26 19:03:16.316  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.316  3766  3818 I jxcore-log: 
08-26 19:03:16.316  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.316  3766  3818 I jxcore-log: 
08-26 19:03:16.317  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.317  3766  3818 I jxcore-log: 
08-26 19:03:16.318  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.318  3766  3818 I jxcore-log: 
08-26 19:03:16.319  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:16.319  3766  3818 I jxcore-log: 
08-26 19:03:16.319  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:16.319  3766  3818 I jxcore-log: 
08-26 19:03:16.320  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:16.320  3766  3818 I jxcore-log: 
08-26 19:03:16.322  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.322  3766  3818 I jxcore-log: 
08-26 19:03:16.325  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.325  3766  3818 I jxcore-log: 
,08-26 19:03:16.327  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.327  3766  3818 I jxcore-log: 
,08-26 19:03:16.329  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.329  3766  3818 I jxcore-log: 
,08-26 19:03:16.331  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.331  3766  3818 I jxcore-log: 
,08-26 19:03:16.334  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:16.334  3766  3818 I jxcore-log: 
,08-26 19:03:16.584  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:03:16.587  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:16.587  3766  3818 I jxcore-log: 
,08-26 19:03:16.687  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:03:16.690  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:16.690  3766  3818 I jxcore-log: 
,08-26 19:03:16.759  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:03:16.762  3766  3818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:16.762  3766  3818 I jxcore-log: 
,08-26 19:03:16.977  4240  4240 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 19:03:16.982  4240  4240 D AndroidRuntime: CheckJNI is OFF
,08-26 19:03:17.024  4240  4240 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 19:03:17.071  4240  4240 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 19:03:17.093  4240  4240 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 19:03:17.104   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 19:03:17.105   872   885 I ActivityManager: Killing 3766:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 19:03:17.219   872   895 W PackageSettings: Skipping PackageSetting{62260ad com.example.hello/10273} due to missing metadata
,08-26 19:03:17.224   872  2224 D GraphicsStats: Buffer count: 2
,08-26 19:03:17.225   872  1885 I WindowState: WIN DEATH: Window{57f5177 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:03:17.226   872  1302 D WifiService: Client connection lost with reason: 4
,08-26 19:03:17.260   872   895 I art     : Starting a blocking GC Explicit
,08-26 19:03:17.277   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 19:03:17.277   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 19:03:17.278   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-26 19:03:17.278   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 19:03:17.278   872   885 E ActivityManager: 	,at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 19:03:17.278   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.278   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.278   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:03:17.278   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 19:03:17.279   872   885 I ActivityManager:   Force finishing activity ActivityRecord{6ae10ec u0 com.test.thalitest/.MainActivity t2}
,08-26 19:03:17.283   872  2224 W ActivityManager: Spurious death for ProcessRecord{2f422af 0:com.test.thalitest/u0a0}, curProc for 3766: null
,08-26 19:03:17.332   872   895 I art     : Explicit concurrent mark sweep GC freed 56963(3MB) AllocSpace objects, 11(396KB) LOS objects, 33% free, 29MB/43MB, paused 1.263ms total 71.796ms
,08-26 19:03:17.356   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 19:03:17.359  4240  4240 I art     : System.exit called, status: 0
,08-26 19:03:17.359  4240  4240 I AndroidRuntime: VM exiting with result code 0.
,08-26 19:03:17.366   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 19:03:17.377   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 19:03:17.381  4154  4154 D BluetoothMapAppObserver: onReceive
,08-26 19:03:17.381  4154  4154 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 19:03:17.388  2102  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 19:03:17.392   872  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:03:17.397  1341  1355 I art     : Background partial concurrent mark sweep GC freed 26425(1309KB) AllocSpace objects, 5(560KB) LOS objects, 23% free, 52MB/68MB, paused 5.273ms total 24.648ms
,08-26 19:03:17.398  3636  3636 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 19:03:17.399  1854  1854 I Keyboard.Facilitator: resetDictionaries() : en_US
08-26 19:03:17.402  1854  4252 I Keyboard.Facilitator.DecoderInitializer: run()
08-26 19:03:17.403  1854  4252 I Decoder : createOrResetDecoder
,08-26 19:03:17.425  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 19:03:17.439   872  1885 I ActivityManager: Start proc 4255:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 19:03:17.442  1495  1495 I ConfigService: onCreate
,08-26 19:03:17.461  1854  4252 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 19:03:17.473  4255  4255 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 19:03:17.490  1854  4252 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 19:03:17.493   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 19:03:17.496  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 19:03:17.497   872  1885 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3766 uid 10000
,08-26 19:03:17.497  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-26 19:03:17.496  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 19:03:17.505  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 19:03:17.505  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 19:03:17.506  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 19:03:17.506  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 19:03:17.507  1854  4252 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 19:03:17.507  1854  4252 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 19:03:17.507  1854  4252 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 19:03:17.507  1854  4252 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 19:03:17.507  1854  4252 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 19:03:17.507  1854  4252 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 19:03:17.532   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 19:03:17.532   872   884 E PackageManager: Failed to write settings, restoring backup
08-26 19:03:17.532   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 19:03:17.532   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 19:03:17.532   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 19:03:17.532   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 19:03:17.532   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 19:03:17.532   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.532   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.532   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:03:17.534  4255  4255 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 19:03:17.537   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 19:03:17.537   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 19:03:17.537   872   8,85 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:03:17.537   872   885 E DropBoxManagerService: 	... 13 more
,08-26 19:03:17.538  1937  2004 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 19:03:17.544  4255  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.544  4255  4270 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.545  4255  4270 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:03:17.552   872  1884 I ActivityManager: Start proc 4272:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-26 19:03:17.553  1937  2004 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 19:03:17.553  1937  2004 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1937
08-26 19:03:17.553  1937  2004 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.553  1937  2004 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:03:17.556   872  2224 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 19:03:17.556   872  4278 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:03:17.556   872  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:03:17.556   872  4278 E DropBoxManagerService: 	... 5 more
,08-26 19:03:17.561  4255  4282 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 19:03:17.569   872   882 I ActivityManager: Start proc 4286:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 19:03:17.571  1937  2004 I Process : Sending signal. PID: 1937 SIG: 9
,08-26 19:03:17.617  4286  4286 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 19:03:17.642  1495  1495 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 19:03:17.643  1495  1495 D AndroidRuntime: Shutting down VM
08-26 19:03:17.644  1495  1495 E AndroidRuntime: FATAL EXCEPTION: main
08-26 19:03:17.644  1495  1495 E AndroidRuntime: Process: com.google.process.gapps, PID: 1495
08-26 19:03:17.644  1495  1495 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 19:03:17.644  1495  1495 E AndroidRuntime: 	... 8 more
,08-26 19:03:17.647   872  4304 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:03:17.647   872  4304 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:03:17.647   872  4304 E DropBoxManagerService: 	... 5 more
,08-26 19:03:17.647  1495  1495 I Process : Sending signal. PID: 1495 SIG: 9
,08-26 19:03:17.676   872  1302 D WifiService: Client connection lost with reason: 4
,08-26 19:03:17.681   872  2223 I ActivityManager: Process com.google.process.gapps (pid 1495) has died
,08-26 19:03:17.681   872  2223 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-26 19:03:17.682   872  2223 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-26 19:03:17.682   872  2223 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
08-26 19:03:17.682   872  2223 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-26 19:03:17.690  1710  1710 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 19:03:17.700   872  1388 I ActivityManager: Start proc 4307:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-26 19:03:17.731  4307  4307 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-26 19:03:17.740  4307  4307 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:03:17.740  4307  4307 I MultiDex: install
,08-26 19:03:17.740  4307  4307 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 19:03:17.744  4307  4307 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-26 19:03:17.747   872  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-26 19:03:17.748  4307  4307 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 19:03:17.750  4307  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:03:17.750  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:03:17.750  4307  4307 D AndroidRuntime: Shutting down VM
08-26 19:03:17.751  4307  4307 E AndroidRuntime: FATAL EXCEPTION: main
08-26 19:03:17.751  4307  4307 E AndroidRuntime: Process: com.google.process.gapps, PID: 4307
08-26 19:03:17.751  4307  4307 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 19,:03:17.751  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 19:03:17.751  4307  4307 E AndroidRuntime: 	... 10 more
,08-26 19:03:17.754  4307  4307 I Process : Sending signal. PID: 4307 SIG: 9
,08-26 19:03:17.755   872  4319 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:03:17.755   872  4319 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:03:17.755   872  4319 E DropBoxManagerService: 	... 5 more
,08-26 19:03:17.819   872  1386 I ActivityManager: Process com.google.process.gapps (pid 4307) has died
,08-26 19:03:17.820   872  1386 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{fcf644b u0 com.google.android.gms/.gcm.GcmService}
08-26 19:03:17.820   872  1386 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{fb39b25 u0 com.google.android.gms/.config.ConfigService}
08-26 19:03:17.820   872  1386 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{c3e10cf u0 com.google.android.gms/.auth.GetToken}
08-26 19:03:17.820   872  1386 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ae59654 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,08-26 19:03:17.850  4255  4270 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 19:03:17.860  4255  4282 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.860  4255  4282 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:03:17.860  4255  4282 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 19:03:17.860  4255  4282 E AndroidRuntime: Process: android.process.acore, PID: 4255
08-26 19:03:17.860  4255  4282 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:03:17.860  4255  4282 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:03:17.863  4255  4270 I Process : Sending signal. PID: 4255 SIG: 9
,08-26 19:03:17.868   872  1386 I ActivityManager: Start proc 4322:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-26 19:03:17.872   872  4327 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:03:17.872   872  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:03:17.872   872  4327 E DropBoxManagerService: 	... 5 more
08-26 19:03:17.874  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 19:03:17.874  1710  1710 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded

```
