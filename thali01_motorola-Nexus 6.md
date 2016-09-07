#### Test 83627337140e0c5_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 09:06:13.108   874  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 09:06:13.822  3985  3985 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 09:06:13.827  3985  3985 D AndroidRuntime: CheckJNI is OFF
09-07 09:06:13.863  3985  3985 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 09:06:13.904  3985  3985 I Radio-JNI: register_android_hardware_Radio DONE
09-07 09:06:13.924  3985  3985 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 09:06:13.930   874  2092 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 09:06:13.951  2002  2151 W SearchService: Abort, client detached.
09-07 09:06:13.954  2002  2002 I HotwordDetector: Closing mic
09-07 09:06:13.957  2002  2362 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@46f602a
09-07 09:06:13.958  2002  2367 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 09:06:13.965  3985  3985 D AndroidRuntime: Shutting down VM
09-07 09:06:13.973  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 09:06:13.997   874  2097 I ActivityManager: Start proc 3994:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 09:06:14.007  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 09:06:14.010  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 09:06:14.025   377  2369 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 09:06:14.027   377  2369 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 09:06:14.033   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 09:06:14.034  2002  2365 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 09:06:14.035  2002  2366 I MicroRecognitionRnrImpl: Detection finished
09-07 09:06:14.043  1526  3330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 09:06:14.044  1526  3330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 09:06:14.044  1526  3330 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:06:14.044  1526  3330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 09:06:14.070  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 09:06:14.071  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 09:06:14.071  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-07 09:06:14.102  3994  3994 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 09:06:14.135  3994  3994 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 09:06:14.146  3994  3994 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3430-3435)
09-07 09:06:14.147  3994  3994 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:06:14.172  3994  3994 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c4cea3}
09-07 09:06:14.173  3994  3994 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:06:14.174  3994  3994 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 09:06:14.185  3994  3994 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 09:06:14.188  3994  3994 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 09:06:14.209  3994  3994 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 09:06:14.226  3994  3994 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 09:06:14.226  3994  3994 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 09:06:14.226  3994  3994 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:06:14.226  3994  3994 I Adreno  : Build Date                       : 10/20/15
09-07 09:06:14.226  3994  3994 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:06:14.226  3994  3994 I Adreno  : Local Branch                     : M14
09-07 09:06:14.226  3994  3994 I Adreno  : Remote Branch                    : 
09-07 09:06:14.226  3994  3994 I Adreno  : Remote Branch                    : 
09-07 09:06:14.226  3994  3994 I Adreno  : Reconstruct Branch               : 
,09-07 09:06:14.312   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a91d93a:true
,09-07 09:06:14.352  3994  3994 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 09:06:14.365  3994  3994 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 09:06:14.428  3994  4032 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 09:06:14.438  3994  4019 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 09:06:14.467  3994  4032 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 09:06:14.538   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +556ms
,09-07 09:06:14.541  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 09:06:14.613  3994  3994 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3994
,09-07 09:06:14.754  3994  3994 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 09:06:14.840   874  1422 I ActivityManager: Killing 3163:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 09:06:14.882   874  1422 I ActivityManager: Killing 3377:com.google.android.gm/u0a78 (adj 15): empty #18
,09-07 09:06:14.987  3994  4034 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1700792016
,09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
,09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
,09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 09:06:14.996  3994  4034 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@673ddb7 added. We now have 1 listener(s)
,09-07 09:06:15.001  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 09:06:15.003  3994  4034 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:06:15.004  3994  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 09:06:15.004  3994  4034 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 09:06:15.008  3994  4034 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4e42 added. We now have 1 listener(s)
,09-07 09:06:15.008  3994  4034 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:06:15.011   874  1316 D WifiService: New client listening to asynchronous messages
,09-07 09:06:15.012  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:06:15.012  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 09:06:15.012  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 09:06:15.012  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 09:06:15.012  3994  4034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 09:06:15.015  3994  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:15.015  3994  4034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-07 09:06:15.022  3994  4034 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:15.022  3994  4034 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:06:15.022  3994  4034 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-07 09:06:15.022  3994  4034 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:15.023  3994  4034 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 09:06:15.024  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:15.026  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:15.050  3994  3994 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 09:06:15.948  3994  4042 W jxcore-log: Initializing JXcore engine
09-07 09:06:15.948  3994  4042 W jxcore-log: JXcore engine is ready
,09-07 09:06:16.024  4042  4042 W Thread-368: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 09:06:16.024  4042  4042 W Thread-368: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11799]" dev="sockfs" ino=11799 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 09:06:16.024  4042  4042 W Thread-368: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 09:06:16.024  4042  4042 W Thread-368: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26936]" dev="sockfs" ino=26936 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 09:06:16.040  3994  4042 W jxcore-log: Starting JXcore engine
,09-07 09:06:16.133  3994  4042 W jxcore-log: Platform android,
09-07 09:06:16.133  3994  4042 W jxcore-log: 
09-07 09:06:16.134  3994  4042 W jxcore-log: Process ARCH arm
09-07 09:06:16.134  3994  4042 W jxcore-log: 
,09-07 09:06:16.411  3994  4042 I jxcore-log: JXcore Cordova bridge is ready!
09-07 09:06:16.411  3994  4042 I jxcore-log: 
09-07 09:06:16.412  3994  4042 W jxcore-log: JXcore engine is started
,09-07 09:06:16.416  3994  4034 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 09:06:16.419  3994  3994 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 09:06:20.052  3253  4051 V KeepSync: Connecting to GoogleApiClient
,09-07 09:06:20.053   874  2096 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 09:06:20.089  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:20.090  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:20.118  1526  3330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 09:06:20.118  1526  3330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 09:06:20.119  1526  3330 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:06:20.119  1526  3330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:20.135  1748  4052 V BaseAuthAsyncOperation: access token request failed
,09-07 09:06:20.136  3253  4051 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 09:06:20.181  1526  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 09:06:20.181  1526  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 09:06:20.181  1526  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:06:20.181  1526  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:20.197  3253  4051 E KeepSync: IOException
09-07 09:06:20.197  3253  4051 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 09:06:20.197  3253  4051 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 09:06:20.197  3253  4051 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 09:06:20.197  3253  4051 E KeepSync: 	... 10 more
,09-07 09:06:20.197  3253  4051 W KeepSync: Sync result 2
,09-07 09:06:20.210   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129180, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:06:26.582  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 09:06:26.582  3994  4042 I jxcore-log: 
,09-07 09:06:26.585  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 09:06:26.585  3994  4042 I jxcore-log: 
,09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:26.594  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:06:26.600  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:06:26.602  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 09:06:26.602  3994  4042 I jxcore-log: 
,09-07 09:06:26.604  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 09:06:26.604  3994  4042 I jxcore-log: 
,09-07 09:06:27.110  3994  4042 I jxcore-log: Unit Test app is loaded
09-07 09:06:27.110  3994  4042 I jxcore-log: 
,09-07 09:06:27.120  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:06:27.120  3994  4042 I jxcore-log: 
,09-07 09:06:27.124  3994  3994 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 09:06:27.128  3994  4042 D executeNativeTests: Running unit tests
,09-07 09:06:27.187  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 09:06:27.187  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 added. We now have 2 listener(s)
,09-07 09:06:27.188  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:06:27.188  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:06:27.188  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:06:27.188  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:06:27.188  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 added. We now have 2 listener(s)
,09-07 09:06:27.188  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:06:27.188  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 09:06:27.192  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:27.206  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:06:27.210  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:06:27.210  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:06:27.227  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:06:27.227  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:27.230  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 09:06:27.231  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:27.232  3994  4042 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 09:06:27.232  3994  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 09:06:27.232  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:06:27.232  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:06:27.232  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 09:06:27.232  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:27.233  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:27.233  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:06:27.233  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 09:06:27.233  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 removed from the list
,09-07 09:06:27.233  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:27.233  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 removed from the list
,09-07 09:06:27.239  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:27.239  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop,
09-07 09:06:27.240  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:27.242  3994  4042 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 09:06:27.242  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:27.242  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:27.242  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:27.242  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:27.242  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:27.243  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:27.244  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:27.244  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:27.244  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:06:27.248  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-07 09:06:27.249  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 09:06:27.250  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 09:06:27.250  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:06:27.250  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
,09-07 09:06:27.250  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-07 09:06:27.250  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:27.250  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:27.250  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:27.250  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:06:27.250  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:06:27.250  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:27.250  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:27.250  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:27.250  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:27.251  3994  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 09:06:27.253  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:27.258  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:06:27.260  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:06:27.260  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:27.261  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-07 09:06:27.261  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-07 09:06:27.261  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:06:27.261  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 09:06:27.261  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 09:06:27.261  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:27.262  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:06:27.263  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:06:27.263  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 09:06:27.263  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:06:27.264  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 09:06:27.264  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:27.264  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:06:27.267  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:27.268  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:06:27.268  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:06:27.270  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:06:27.270  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:06:27.272  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 09:06:27.273  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:06:27.273  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:06:27.275  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 09:06:27.275  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:06:27.275  3994  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:06:27.276  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-07 09:06:27.276  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:06:27.277  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:06:27.277  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 09:06:27.277  3994  4042 D BluetoothAdapter: STATE_ON
09-07 09:06:27.277  3994  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:06:27.281  2717  2884 D BtGatt.GattService: registerClient() - UUID=0f50c550-9059-4585-bf45-022d243950c4
09-07 09:06:27.282  2717  2767 D BtGatt.GattService: onClientRegistered() - UUID=0f50c550-9059-4585-bf45-022d243950c4, clientIf=5
09-07 09:06:27.283  3994  4006 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-07 09:06:27.284  2717  2772 D BtGatt.AdvertiseManager: message : 0
,09-07 09:06:27.287  2717  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:06:27.301  2717  2767 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:06:27.308  2717  2767 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:06:27.309  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:06:27.309  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:06:27.310  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:06:27.311  3994  4042 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:06:27.311  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:06:27.311  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:06:27.312  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:06:27.312  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:06:27.312  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:06:27.312  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:06:27.314  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 09:06:27.314  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:27.816  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:06:27.816  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-07 09:06:27.817  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:06:30.121   874  1994 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 09:06:33.316  3994  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 09:06:33.317  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 09:06:33.318  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 09:06:33.318  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 09:06:33.318  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:06:33.319  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:06:33.320  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:06:33.320  3994  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:06:33.320  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:06:33.320  3994  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 09:06:33.321  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:06:33.321  3994  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:06:33.321  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:06:33.321  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:06:33.321  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 09:06:33.321  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:06:33.323  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:06:33.326  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:06:33.327  3994  4042 D BluetoothLeScanner: could not find callback wrapper
09-07 09:06:33.328  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 09:06:33.328  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:06:33.331  2717  2772 D BtGatt.AdvertiseManager: message : 1
,09-07 09:06:33.332  2717  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:06:33.342  2717  2767 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:06:33.343  2717  2767 D BtGatt.GattService: Client app is not null!
,09-07 09:06:33.344  2717  2728 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:06:33.344  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:06:33.344  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:06:33.344  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 09:06:33.345  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:06:33.345  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:06:33.347  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:06:33.347  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:06:33.348  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:06:33.349  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:33.352  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:06:33.352  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:06:33.353  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 09:06:33.353  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:06:33.353  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 09:06:33.353  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:06:33.854  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:06:34.355  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:34.371  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:34.378  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:34.456  1526  3174 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:06:34.456  1526  3174 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.,
,09-07 09:06:34.457  1526  3174 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:06:34.457  1526  3174 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:34.522  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 09:06:34.524  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 09:06:34.525  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 09:06:36.356  3994  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 09:06:36.357  3994  4042 V io.jxcore.node.ConnectivityMonitor: start: Already started,
09-07 09:06:36.357  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-07 09:06:36.357  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-07 09:06:36.358  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:06:36.359  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 09:06:36.359  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:06:36.359  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:36.362  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:06:36.363  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:06:36.363  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:06:36.364  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:06:36.364  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:06:36.364  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:06:36.365  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:06:36.365  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:06:36.368  3994  4060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:06:36.377  3994  4060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 09:06:36.377  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:06:36.378  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:06:36.382  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:06:36.383  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 09:06:36.383  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:06:36.385  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 09:06:36.386  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:06:36.386  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-07 09:06:36.386  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:06:36.386  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:06:36.386  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:06:36.387  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:06:36.390  2717  2873 D BtGatt.GattService: registerClient() - UUID=38821538-0329-4379-aa70-5800d65be629
,09-07 09:06:36.390  2717  2767 D BtGatt.GattService: onClientRegistered() - UUID=38821538-0329-4379-aa70-5800d65be629, clientIf=5
,09-07 09:06:36.391  3994  4005 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:06:36.392  2717  2772 D BtGatt.AdvertiseManager: message : 0
,09-07 09:06:36.395  2717  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:06:36.417  2717  2767 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:06:36.433  2717  2767 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:06:36.435  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:06:36.435  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:06:36.441  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:06:36.443  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:06:36.443  3994  4042 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:06:36.444  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 09:06:36.444  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 09:06:36.444  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 09:06:36.444  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 09:06:36.444  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:06:36.446  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:36.446  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:36.947  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:06:36.948  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:06:36.948  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:06:40.894   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 09:06:40.903  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 09:06:40.915   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:06:40.915   874   894 I Adreno  : Build Date                       : 10/20/15
09-07 09:06:40.915   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:06:40.915   874   894 I Adreno  : Local Branch                     : M14
09-07 09:06:40.915   874   894 I Adreno  : Remote Branch                    : 
09-07 09:06:40.915   874   894 I Adreno  : Remote Branch                    : 
09-07 09:06:40.915   874   894 I Adreno  : Reconstruct Branch               : 
,09-07 09:06:40.954   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,09-07 09:06:41.576  3994  3994 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 09:06:41.576  3994  3994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 09:06:41.630   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 09:06:41.632  3994  3994 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e0e691 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@81dd88c, 16908290=android.view.AbsSavedState$1@81dd88c}, android:focusedViewId=100}]}]
09-07 09:06:41.632  3994  3994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 09:06:41.632  3994  3994 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 09:06:41.632  3994  3994 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 09:06:41.646   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 09:06:41.652   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 09:06:41.652   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-07 09:06:41.652   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 09:06:41.913   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 09:06:41.918   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 09:06:41.924   874  1339 D SurfaceControl: Excessive delay in setPowerMode(): 272ms
,09-07 09:06:41.928   874   894 I DreamManagerService: Entering dreamland.
09-07 09:06:41.929   874   894 I PowerManagerService: Dozing...
09-07 09:06:41.930   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 09:06:42.006   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 09:06:42.006   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 09:06:42.016   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:06:42.032   874  1315 E native  : do suspend false
,09-07 09:06:42.036  1915  4066 D NfcService: Discovery configuration equal, not updating.
,09-07 09:06:42.052   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 09:06:42.087   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:06:42.095   874  1315 E native  : do suspend true
,09-07 09:06:42.140   377  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 09:06:42.141   377  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 09:06:42.449  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:42.449  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:06:42.450  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:06:42.450  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:06:42.451  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:06:42.451  3994  4060 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:06:42.451  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:06:42.451  3994  4060 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 09:06:42.451  3994  4060 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:06:42.452  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:06:42.452  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 09:06:42.453  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:42.454  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:42.454  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 09:06:42.454  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:06:42.455  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:06:42.456  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:06:42.459  3994  4042 D BluetoothAdapter: STATE_ON
09-07 09:06:42.459  3994  4042 D BluetoothLeScanner: could not find callback wrapper
,09-07 09:06:42.460  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:06:42.460  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:06:42.462  2717  2772 D BtGatt.AdvertiseManager: message : 1
09-07 09:06:42.464  2717  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:06:42.480  2717  2767 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:06:42.480  2717  2767 D BtGatt.GattService: Client app is not null!
09-07 09:06:42.481  2717  2873 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:06:42.482  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:06:42.482  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:06:42.482  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 09:06:42.482  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:06:42.482  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:06:42.484  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:06:42.484  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:06:42.485  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:42.487  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:42.490  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:06:42.490  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:06:42.490  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:06:42.491  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
,09-07 09:06:42.491  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:42.491  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:42.493  3994  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 09:06:42.499  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:42.510  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:06:42.515  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:06:42.516  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:06:42.516  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-07 09:06:42.516  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-07 09:06:42.518  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:06:42.518  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:06:42.518  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 09:06:42.518  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:42.520  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:06:42.521  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 09:06:42.521   874  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
09-07 09:06:42.521  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 09:06:42.521  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 09:06:42.521  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 09:06:42.521  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:42.522  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:06:42.525  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:42.526  3994  4070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:06:42.531  3994  4070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 09:06:42.531  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:06:42.531  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:06:42.539  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:42.539  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 09:06:42.542  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:06:42.543  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:06:42.544  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:06:42.548  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:06:42.548  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:06:42.549  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
,09-07 09:06:42.549  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:06:42.550  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:06:42.550  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:06:42.552  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:06:42.558  2717  2884 D BtGatt.GattService: registerClient() - UUID=7e4d4f5d-dba2-4ca6-a832-c1c0a8d40cf2
,09-07 09:06:42.559  2717  2767 D BtGatt.GattService: onClientRegistered() - UUID=7e4d4f5d-dba2-4ca6-a832-c1c0a8d40cf2, clientIf=5
,09-07 09:06:42.559  3994  4006 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:06:42.561  2717  2772 D BtGatt.AdvertiseManager: message : 0
,09-07 09:06:42.567  2717  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:06:42.588  2717  2767 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:06:42.601  2717  2767 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:06:42.603  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:06:42.603  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:06:42.609  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:06:42.613  3994  4042 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:06:42.613  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:06:42.613  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 09:06:42.614  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:06:42.614  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 09:06:42.614  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:06:42.614  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:06:42.623  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:42.623  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:43.125  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:06:43.126  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:06:43.126  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:06:48.619  3994  4042 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 09:06:48.619  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-07 09:06:48.619  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 09:06:48.620  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:06:48.620  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:06:48.621  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:06:48.622  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:06:48.622  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:06:48.623  3994  4070 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:06:48.623  3994  4070 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:06:48.623  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:06:48.624  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 09:06:48.624  3994  4070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:06:48.624  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:06:48.624  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:06:48.624  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 09:06:48.625  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:06:48.628  3994  4042 D BluetoothAdapter: STATE_ON
09-07 09:06:48.628  3994  4042 D BluetoothLeScanner: could not find callback wrapper
09-07 09:06:48.628  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:06:48.629  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:06:48.631  2717  2772 D BtGatt.AdvertiseManager: message : 1
09-07 09:06:48.633  2717  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:06:48.645  2717  2767 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:06:48.645  2717  2767 D BtGatt.GattService: Client app is not null!
,09-07 09:06:48.647  2717  2728 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:06:48.648  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:06:48.648  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:06:48.648  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:06:48.648  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:06:48.648  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:06:48.651  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:06:48.651  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:06:48.651  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:06:48.653  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:48.656  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:06:48.656  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:06:48.657  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:06:48.657  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:06:48.657  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:06:48.658  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:06:49.027  2138  2788 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 09:06:49.158  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:06:50.559  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:50.564  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:50.640  1526  2100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 09:06:50.641  1526  2100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 09:06:50.641  1526  2100 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:06:50.642  1526  2100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:50.706  3725  4075 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 09:06:50.706  3725  4075 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jdm.a(PG:82)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jcs.o(PG:406)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jcn.a(PG:1379)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jcs.i(PG:143)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at blb.a(PG:3937)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at czp.a(PG:18188)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at czp.a(PG:9081)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at czq.run(PG:1686)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:06:50.706  3725  4075 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jdj.a(PG:4091)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jdj.a(PG:1125)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jdm.a(PG:77)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	... 12 more
09-07 09:06:50.706  3725  4075 E HttpOperation: Caused by: faj: BadAuthentication
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at fal.a(PG:38)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	at jdj.a(PG:4089)
09-07 09:06:50.706  3725  4075 E HttpOperation: 	... 14 more
,09-07 09:06:50.801  1526  3330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 09:06:50.801  1526  3330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 09:06:50.801  1526  3330 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:06:50.801  1526  3330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:50.845  3725  4075 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 09:06:50.845  3725  4075 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jdm.a(PG:82)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jcs.o(PG:406)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jcn.a(PG:1379)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jcs.i(PG:143)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at hec.a(PG:42)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at hee.a(PG:102)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at czr.a(PG:65)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at kka.a(PG:108)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at czp.a(PG:19176)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at czp.a(PG:9081)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at czq.run(PG:1686)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:06:50.845  3725  4075 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jdj.a(PG:4091)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jdj.a(PG:1125)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jdm.a(PG:77)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	... 15 more
09-07 09:06:50.845  3725  4075 E HttpOperation: Caused by: faj: BadAuthentication
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at fal.a(PG:38)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	at jdj.a(PG:4089)
09-07 09:06:50.845  3725  4075 E HttpOperation: 	... 17 more
,09-07 09:06:50.850  3725  4075 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 09:06:50.850  3725  4075 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at hec.a(PG:42)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at hee.a(PG:102)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at czr.a(PG:65)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at kka.a(PG:108)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	... 15 more
09-07 09:06:50.850  3725  4075 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at fal.a(PG:38)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 09:06:50.850  3725  4075 E ExperimentLoader: 	... 17 more
,09-07 09:06:50.981   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131561, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:06:51.663  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:51.663  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.664  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:51.664  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.664  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:06:51.665  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.667  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:51.668  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.671  3994  4042 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 09:06:51.673  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:51.673  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.674  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.674  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.674  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:06:51.675  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
,09-07 09:06:51.675  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:51.675  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.676  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.679  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 09:06:51.679  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:51.680  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.680  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.681  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.681  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.681  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.681  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:51.682  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.682  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.683  3994  4042 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 09:06:51.684  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:51.684  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.684  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.685  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:06:51.685  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.685  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
,09-07 09:06:51.686  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:51.686  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:51.686  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.688  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 09:06:51.688  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:51.688  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.689  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.689  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.689  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:06:51.689  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.689  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:51.690  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:51.690  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.692  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:06:51.692  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:51.692  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-07 09:06:51.693  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:06:51.693  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:06:51.694  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:06:51.694  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:51.694  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.694  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.695  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.695  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.695  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.695  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:51.696  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.696  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.698  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:51.698  3994  4042 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:06:51.699  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 09:06:51.706  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 09:06:51.707  3994  4042 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-07 09:06:51.707  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:06:51.708  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:06:51.709  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:06:51.710  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:06:51.710  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 09:06:51.710  3994  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 09:06:51.710  3994  4042 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 09:06:51.710  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:51.711  3994  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:06:51.711  3994  4042 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 09:06:51.711  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:51.711  3994  4042 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:06:51.711  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 09:06:51.720  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 09:06:51.722  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 09:06:51.722  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 09:06:51.724  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 09:06:51.724  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 09:06:51.724  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 09:06:51.725  3994  4077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 468)
,09-07 09:06:51.725  3994  4042 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:06:51.725  3994  4042 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 09:06:51.726  3994  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:06:51.728  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:51.728  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:51.728  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.729  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-07 09:06:51.731  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:06:51.731  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.731  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
,09-07 09:06:51.731  3994  4078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 468,
09-07 09:06:51.731  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:51.734  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:06:51.734  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:06:51.734  3994  4078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 468)
09-07 09:06:51.734  2717  2871 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
09-07 09:06:51.734  3994  4077 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 468)
09-07 09:06:51.734  3994  4078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 468)
09-07 09:06:51.736  3994  4042 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 09:06:51.736  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:51.736  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.736  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.736  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.737  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.737  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.737  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:51.737  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.737  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.738  3994  4042 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 09:06:51.738  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:06:51.738  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.738  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.738  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:51.738  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.738  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
,09-07 09:06:51.738  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:06:51.738  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.738  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.739  3994  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-07 09:06:51.739  3994  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 09:06:51.739  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:06:51.739  3994  4042 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-07 09:06:51.739  3994  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:06:51.739  3994  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 09:06:51.739  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:06:51.740  3994  4042 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-07 09:06:51.740  3994  4042 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:06:51.740  3994  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:06:51.740  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 09:06:51.740  3994  4042 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-07 09:06:51.740  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:51.740  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.740  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.740  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:06:51.740  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:06:51.740  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:51.740  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:51.740  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:06:51.741  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:51.741  3994  4042 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 09:06:51.742  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:06:51.746  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:06:51.747  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:06:51.748  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:06:51.748  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-07 09:06:51.748  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-07 09:06:51.750  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:51.750  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:06:51.750  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything,
09-07 09:06:51.750  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:06:51.750  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:51.752  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:06:51.752  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:06:51.752  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 09:06:51.752  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:06:51.753  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:06:51.753  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:06:51.753  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:06:51.753  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:06:51.753  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:06:51.755  3994  4079 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:06:51.756  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:06:51.756  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:06:51.757  3994  4079 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:06:51.759  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:06:51.760  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 09:06:51.760  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:06:51.761  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:06:51.761  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:06:51.761  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-07 09:06:51.762  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:06:51.762  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:06:51.762  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 09:06:51.762  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:06:51.764  2717  2728 D BtGatt.GattService: registerClient() - UUID=7a9a9231-94db-444b-92f9-4b3f24982dbc
,09-07 09:06:51.765  2717  2767 D BtGatt.GattService: onClientRegistered() - UUID=7a9a9231-94db-444b-92f9-4b3f24982dbc, clientIf=5
09-07 09:06:51.765  3994  4005 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:06:51.765  2717  2772 D BtGatt.AdvertiseManager: message : 0
,09-07 09:06:51.767  2717  2772 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:06:51.777  2717  2767 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:06:51.783  2717  2767 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:06:51.783  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:06:51.783  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:06:51.785  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:06:51.786  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:06:51.786  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:06:51.786  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 09:06:51.786  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:06:51.787  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 09:06:51.787  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-07 09:06:51.787  3994  4042 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:06:51.789  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:51.789  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:06:52.290  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:06:52.291  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:06:52.291  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:06:53.122   874  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-07 09:06:54.688  3791  4081 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 09:06:54.723  1526  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 09:06:54.723  1526  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-07 09:06:54.723  1526  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:06:54.723  1526  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:54.748  3791  4081 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 09:06:54.749  3791  4081 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 09:06:54.846  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:06:54.895  1526  2100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:06:54.895  1526  2100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 09:06:54.895  1526  2100 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:06:54.896  1526  2100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:06:54.924  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 09:06:54.924  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 09:06:54.924  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 09:06:56.857  2717  2862 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-07 09:06:56.857  2717  2862 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-07 09:06:57.791  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:06:57.791  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:06:57.791  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:06:57.792  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:06:57.792  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:06:57.793  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:06:57.794  3994  4079 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:06:57.794  3994  4079 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:06:57.795  3994  4079 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:06:57.795  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:06:57.795  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:06:57.795  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:06:57.795  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:06:57.795  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 09:06:57.796  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:06:57.796  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:06:57.796  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 09:06:57.799  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:06:57.799  3994  4042 D BluetoothLeScanner: could not find callback wrapper
09-07 09:06:57.800  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:06:57.800  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:06:57.803  2717  2772 D BtGatt.AdvertiseManager: message : 1
09-07 09:06:57.804  2717  2772 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:06:57.818  2717  2767 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-07 09:06:57.818  2717  2767 D BtGatt.GattService: Client app is not null!
,09-07 09:06:57.820  2717  2884 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 09:06:57.821  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:06:57.821  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:06:57.822  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 09:06:57.822  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:06:57.822  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:06:57.824  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:06:57.824  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:06:57.825  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:06:57.825  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:06:57.827  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:06:57.827  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:06:57.828  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:06:57.828  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:06:57.828  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:06:57.828  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:06:58.329  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:07:00.836  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:00.836  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:00.837  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:00.837  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:07:00.838  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:07:00.838  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:07:00.838  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:00.838  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.839  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:00.844  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:07:00.844  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:07:00.847  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:07:00.848  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:07:00.849  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:07:00.849  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:07:00.850  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:07:00.850  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:07:00.851  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:07:00.851  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 09:07:00.852  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:07:00.852  3994  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:07:00.852  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:07:00.852  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.853  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:07:00.853  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
,09-07 09:07:00.854  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:07:00.854  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:07:00.853  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:07:00.855  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 09:07:00.855  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:07:00.855  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.855  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-07 09:07:00.857  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:07:00.857  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:07:00.857  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:07:00.857  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:07:00.857  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.857  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:07:00.857  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.857  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:07:00.859  3994  4042 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 09:07:00.859  3994  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 09:07:00.859  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:07:00.861  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:07:00.861  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:07:00.861  3994  4083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:07:00.861  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.861  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.861  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:07:00.861  3994  4083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:07:00.861  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:07:00.861  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:07:00.861  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:00.861  3994  4083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:07:00.861  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.862  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:07:00.861  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.867  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:07:00.867  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.867  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.867  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:07:00.867  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:07:00.868  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19e,f4 not in the list
09-07 09:07:00.868  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:00.868  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.868  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.869  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:00.869  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:00.869  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.870  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c958c7 not in the list
09-07 09:07:00.870  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:07:00.870  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19ef4 not in the list
09-07 09:07:00.870  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:00.870  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:00.870  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:00.871  3994  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 09:07:00.871  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:07:00.871  3994  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-07 09:07:00.871  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:07:00.872  3994  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 09:07:00.872  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:07:00.875  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 09:07:00.875  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 09:07:00.876  3994  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 09:07:00.876  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 09:07:00.876  3994  4042 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-07 09:07:00.876  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 09:07:00.876  3994  4042 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 09:07:00.876  3994  4042 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-07 09:07:00.877  3994  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 09:07:00.877  3994  4042 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-07 09:07:00.877  3994  4042 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 09:07:00.878  3994  4042 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-07 09:07:00.878  3994  4042 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 09:07:00.878  3994  4042 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 09:07:00.879  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:07:00.879  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6c242 added. We now have 2 listener(s)
,09-07 09:07:00.879  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:07:00.881  3994  4042 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 09:07:00.881   874  1422 D WifiService: setWifiEnabled: true pid=3994, uid=10000
09-07 09:07:00.881   874  1422 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:00.882  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:07:00.882  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43d0253 added. We now have 3 listener(s)
09-07 09:07:00.883  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:07:00.888  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:07:00.888  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e17790 added. We now have 4 listener(s)
09-07 09:07:00.888  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:07:00.890  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:07:00.890  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cdf889 added. We now have 5 listener(s)
,09-07 09:07:00.890  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:07:00.892   874  2097 D WifiService: setWifiEnabled: false pid=3994, uid=10000
09-07 09:07:00.892   874  2097 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:00.897  2717  2758 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 09:07:00.898  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:07:00.898  2717  2758 D BluetoothAdapterProperties: Setting state to 13
,09-07 09:07:00.907  2717  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 09:07:00.908  2717  2758 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 09:07:00.911  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:00.911  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:07:00.911  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 09:07:00.912  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.912  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:00.912  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:07:00.914   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 09:07:00.914   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 09:07:00.914   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 09:07:00.914   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 09:07:00.915  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.918  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.919  2717  2758 I BluetoothAdapterState: Entering PendingCommandState
09-07 09:07:00.919  2717  2767 D BluetoothAdapterProperties: Scan Mode:20
09-07 09:07:00.920  2717  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 09:07:00.922  2717  2717 D HeadsetService: Received stop request...Stopping profile...
09-07 09:07:00.924   874  1315 E native  : do suspend true
,09-07 09:07:00.925  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:00.925  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:07:00.926  2717  2717 D A2dpService: Received stop request...Stopping profile...
,09-07 09:07:00.926  1923  1944 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:00.926  2717  2877 D A2dpStateMachine: Exit Disconnected: -1
09-07 09:07:00.927   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:00.927  1358  1371 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:00.927  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.927  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:00.927  1358  1358 D HeadsetProfile: Bluetooth service disconnected
09-07 09:07:00.927   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:00.927   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:00.928   874   874 D BluetoothA2dp: Proxy object disconnected
,09-07 09:07:00.928  1358  1358 D BluetoothA2dp: Proxy object disconnected
09-07 09:07:00.928  2717  2717 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:00.929  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:00.929  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:00.929  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:00.930  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.930  2717  2717 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 09:07:00.930  2717  2717 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 09:07:00.931  2717  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 09:07:00.931  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:00.931  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:00.931  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 09:07:00.932  2717  2767 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 09:07:00.934  2717  2717 D HidService: Received stop request...Stopping profile...
09-07 09:07:00.934  2717  2717 D HidService: Stopping Bluetooth HidService
09-07 09:07:00.935  1358  1358 D BluetoothInputDevice: Proxy object disconnected
09-07 09:07:00.935  1358  1358 D HidProfile: Bluetooth service disconnected
,09-07 09:07:00.935  2717  2717 D HealthService: Received stop request...Stopping profile...
,09-07 09:07:00.937  2717  2717 D PanService: Received stop request...Stopping profile...
,09-07 09:07:00.938  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 09:07:00.938  2717  2717 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:00.938  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:00.938  1358  1358 D PanProfile: Bluetooth service disconnected
09-07 09:07:00.938  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:00.938  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:00.940  2717  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 09:07:00.940  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:00.940  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 09:07:00.940  2717  2862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:07:00.940  2717  2862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:07:00.940  2717  2862 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:07:00.940  2717  2717 D BluetoothMapService: Received stop request...Stopping profile...
09-07 09:07:00.940  2717  2862 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:07:00.940  2717  2717 D BluetoothMapService: stop()
,09-07 09:07:00.941  2717  2717 D BluetoothMapAppObserver: deinitObservers()
09-07 09:07:00.941  2717  2717 D BluetoothMapAppObserver: removeReceiver()
,09-07 09:07:00.942  1358  1358 D BluetoothMap: Proxy object disconnected
09-07 09:07:00.942  2717  2717 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:00.942  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:00.942  1358  1358 D MapProfile: Bluetooth service disconnected
,09-07 09:07:00.942  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:00.942  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:00.942  2717  2717 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 09:07:00.943  2717  2767 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:07:00.943  2717  2717 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 09:07:00.943  2717  2717 V BluetoothAdapterState: isTurningOff()=true
,09-07 09:07:00.943  2717  2717 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:07:00.943  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:07:00.943  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:00.943  2717  2717 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 09:07:00.944  2717  2767 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 09:07:00.944  2717  2717 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 09:07:00.944  2717  2717 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:00.944  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:00.944   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:07:00.944  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:00.944  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:00.944   874  1999 D DhcpClient: Clearing IP address
,09-07 09:07:00.945  2717  2717 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 09:07:00.945  2717  2717 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 09:07:00.946  2717  2717 D BluetoothMapService: MAP Service closeService in
09-07 09:07:00.946  2717  2717 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 09:07:00.946  2717  2717 D ObexServerSockets0: shutdown(block = true)
09-07 09:07:00.946  2717  2886 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 09:07:00.947  2717  2717 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:07:00.947  2717  2887 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 09:07:00.948  2717  2717 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:07:00.948  2717  2871 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 09:07:00.948  2717  2717 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:00.949  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:00.949  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:00.950  2717  2717 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:00.950  2717  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 09:07:00.950  2717  2758 D BluetoothAdapterProperties: Setting state to 15
09-07 09:07:00.950  2717  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 09:07:00.951  2717  2758 I BluetoothAdapterState: Entering BleOnState
09-07 09:07:00.952  2717  2717 D BluetoothMapService: cleanup()
09-07 09:07:00.952  2717  2717 D BluetoothMapService: MAP Service closeService in
09-07 09:07:00.953  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.954   373   872 D CommandListener: Setting iface cfg
09-07 09:07:00.955  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.955  2717  2717 I BtOppRfcommListener: stopping Accept Thread
09-07 09:07:00.955  2717  3589 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 09:07:00.956  2717  3589 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 09:07:00.962  1526  3604 V NativeCrypto: Read error: ssl=0x9a93b400: I/O error during system call, Connection timed out
09-07 09:07:00.964   874   887 I ActivityManager: Start proc 4086:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-07 09:07:00.964  1526  3604 V NativeCrypto: SSL shutdown failed: ssl=0x9a93b400: I/O error during system call, Broken pipe
09-07 09:07:00.964  1923  2094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:00.965  1358  1371 D BluetoothPan: onBluetoothStateChange on: false
09-07 09:07:00.966   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 09:07:00.966   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 09:07:00.966   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 09:07:00.967   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:07:00.967   874  1315 E native  : do suspend true
09-07 09:07:00.969   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 09:07:00.972   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 09:07:00.973   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:00.973   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:00.973   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:00.973  1358  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:00.973   874   891 D BluetoothA2dp: onBluet,oothStateChange: up=false
09-07 09:07:00.973  1358  2026 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:07:00.974  1358  1371 D BluetoothMap: onBluetoothStateChange: up=false
09-07 09:07:00.975  1358  1370 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 09:07:00.975  1358  2026 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 09:07:00.976  2717  2758 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 09:07:00.976  2717  2758 D BluetoothAdapterProperties: Setting state to 16
09-07 09:07:00.976  2717  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 09:07:00.977  2717  2758 D BluetoothAdapterProperties: onBleDisable
09-07 09:07:00.977  2717  2758 I BluetoothAdapterState: Entering PendingCommandState
09-07 09:07:00.977  2717  2761 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 09:07:00.979  2717  2862 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 09:07:00.979  2717  2862 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:00.982  2717  2767 D BluetoothAdapterProperties: Scan Mode:20
09-07 09:07:00.983  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:00.983  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:07:00.984  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.984  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:00.986  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:00.986  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:00.987  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.987  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:00.988  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:00.988  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:00.989  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:00.991   874  2018 D DhcpClient: Receive thread stopped
09-07 09:07:01.008   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 09:07:01.010  4086  4086 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-07 09:07:01.020  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:07:01.024   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 09:07:01.024   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:07:01.026   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 09:07:01.026  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:07:01.026   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 09:07:01.026   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 09:07:01.027   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3378de6:true
09-07 09:07:01.029   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 09:07:01.031  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:01.032  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:01.033  3590  3590 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@673ddb7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-07 09:07:01.045   874  2092 I ActivityManager: Start proc 4104:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 09:07:01.046   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 09:07:01.050  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:01.050  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:01.051  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:01.051  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:01.051   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 09:07:01.052  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:01.052  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:01.053  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:01.053  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:01.054  2138  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:07:01.072  4086  4086 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 09:07:01.077  4104  4104 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
09-07 09:07:01.079  4086  4086 D BluetoothMap: Create BluetoothMap proxy object
,09-07 09:07:01.083  4086  4086 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 09:07:01.100  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:07:01.103   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 09:07:01.103   874  3297 I ActivityManager: Killing 3590:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 09:07:01.186  2717  2767 I bt_hci  : shut_down
09-07 09:07:01.187  2717  2774 D bt_hwcfg: hw_epilog_process
,09-07 09:07:01.256  2717  2774 I bt_vendor: low_power_mode_cb
,09-07 09:07:01.282  2717  2774 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 09:07:01.283  2717  2774 I bt_vendor: epilog_cb
09-07 09:07:01.283  2717  2774 I bt_hci  : epilog_finished_callback
,09-07 09:07:01.289  2717  2767 I bt_hci_h4: hal_close
,09-07 09:07:01.290  2717  2767 I bt_userial_vendor: device fd = 51 close
,09-07 09:07:01.358  4104  4104 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.358  4104  4104 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.358  4104  4104 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.358  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 09:07:01.358  4104  4104 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.358  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.359  4104  4104 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.359  4104  4104 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.359  4104  4104 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.359  4104  4104 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:01.359  4104  4104 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:01.365  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:07:01.377  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:07:01.386  4086  4086 D DockEventReceiver: finishStartingService: stopping service
09-07 09:07:01.398   874  2092 I ActivityManager: Killing 3639:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 09:07:01.449  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:07:01.452  2717  2761 D bt_stack_manager: event_shut_down_stack finished.
,09-07 09:07:01.453  2717  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 09:07:01.454  1748  1748 D SystemUpdateService: onCreate
,09-07 09:07:01.455  2717  2758 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 09:07:01.455  2717  2717 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 09:07:01.458  2717  2717 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 09:07:01.458  2717  2717 D BtGatt.GattService: stop()
,09-07 09:07:01.459  2717  2717 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 09:07:01.462  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:07:01.464  2717  2717 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:01.464  2717  2717 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:01.464  2717  2717 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:07:01.464  2717  2717 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 09:07:01.465  2717  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 09:07:01.465  2717  2758 D BluetoothAdapterProperties: Setting state to 10
09-07 09:07:01.466  2717  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 09:07:01.467  2717  2758 I BluetoothAdapterState: Entering OffState
,09-07 09:07:01.468   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 09:07:01.494  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 09:07:01.495  1748  4138 I SystemUpdateService: active receiver: enabled
,09-07 09:07:01.500  2717  2717 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 09:07:01.500  2717  2717 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 09:07:01.500  2717  2717 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 09:07:01.501  2717  2761 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 09:07:01.507  2717  2761 D bt_stack_manager: event_clean_up_stack finished.
,09-07 09:07:01.507  1748  2476 I iu.UploadsManager: num queued entries: 0
,09-07 09:07:01.512  2717  2717 I art     : System.exit called, status: 0
,09-07 09:07:01.512  2717  2717 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 09:07:01.516  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:07:01.520  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:07:01.522  1748  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:07:01.525  1748  2476 I iu.UploadsManager: num updated entries: 0
,09-07 09:07:01.534  1748  4138 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 09:07:01.534  1748  4138 I SystemUpdateService: now status is 0 (complete)
09-07 09:07:01.534  1748  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:07:01.534  1748  4138 I SystemUpdateService: file has been verified
09-07 09:07:01.535  1748  4138 I SystemUpdateService: OTA package size = 12249756
,09-07 09:07:01.536   874  2091 I ActivityManager: Start proc 4141:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 09:07:01.538  1748  2476 I iu.SyncManager: NEXT; no task
,09-07 09:07:01.545  1748  4138 I SystemUpdateService: showing system update notification
,09-07 09:07:01.578  1748  1748 D SystemUpdateService: onDestroy
,09-07 09:07:01.584   874  1422 I ActivityManager: Process com.android.bluetooth (pid 2717) has died
09-07 09:07:01.589  4141  4141 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 09:07:01.592  4141  4141 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:01.602  4141  4141 D SprintDMHelper: simOperator: 
,09-07 09:07:01.602  4141  4141 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:07:01.613  4104  4130 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 09:07:01.624   874  1422 I ActivityManager: Start proc 4155:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 09:07:01.625   874  1422 I ActivityManager: Killing 1695:android.process.acore/u0a5 (adj 15): empty #17
,09-07 09:07:01.646   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76b7721:true
,09-07 09:07:01.787   874  2092 I ActivityManager: Start proc 4170:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 09:07:01.816  4170  4170 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 09:07:01.862  4170  4170 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 09:07:01.862  4170  4170 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 09:07:01.862  4170  4170 I GAv4    :   adb logcat -s GAv4
,09-07 09:07:01.874  4170  4170 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:07:01.879  4170  4170 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:07:01.914  4170  4187 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:07:02.017  4170  4170 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 09:07:02.068  4170  4170 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 09:07:02.077  4170  4170 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1363-1366)
,09-07 09:07:02.077  4170  4170 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 09:07:02.089  4170  4170 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f01a2a7}
,09-07 09:07:02.089  4170  4170 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 09:07:02.090  4170  4170 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 09:07:02.099  4170  4170 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 09:07:02.101  4170  4170 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 09:07:02.120  4170  4170 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 09:07:02.134  4170  4170 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 09:07:02.134  4170  4170 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:07:02.134  4170  4170 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:07:02.134  4170  4170 I Adreno  : Build Date                       : 10/20/15
09-07 09:07:02.134  4170  4170 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:07:02.134  4170  4170 I Adreno  : Local Branch                     : M14
09-07 09:07:02.134  4170  4170 I Adreno  : Remote Branch                    : 
09-07 09:07:02.134  4170  4170 I Adreno  : Remote Branch                    : 
09-07 09:07:02.134  4170  4170 I Adreno  : Reconstruct Branch               : 
,09-07 09:07:02.201  4170  4170 I NSApplication: Starting up...
,09-07 09:07:02.212  4170  4216 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 09:07:02.243   874  2093 I ActivityManager: Start proc 4221:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 09:07:02.244   874  2093 I ActivityManager: Killing 3838:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 09:07:02.322  4221  4221 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 09:07:02.500   874  2092 I ActivityManager: Killing 3853:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 09:07:03.917   874   884 D WifiService: setWifiEnabled: true pid=3994, uid=10000
,09-07 09:07:03.917   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:03.938   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-07 09:07:03.938  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:03.939  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:03.939  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:03.940  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:03.943  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:03.943  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:03.943  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:03.944  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:03.969   874  1315 D WifiConfigStore: loaded 0 passpoint configs
09-07 09:07:03.970   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 09:07:03.971   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 09:07:03.972   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 09:07:03.972   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 09:07:03.972   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 09:07:03.972   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 09:07:03.986   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 09:07:03.986   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:07:03.989   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:03.997   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-07 09:07:03.997   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 09:07:03.998   874  1315 E native  : do suspend true
,09-07 09:07:04.011   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:07:04.031   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
09-07 09:07:04.033   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 09:07:05.288   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:07:05.353   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.38 rxSuccessRate=11.81 delta 1000 -> 994
,09-07 09:07:05.355   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 09:07:05.355   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:05.370   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 09:07:05.421   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 09:07:05.424  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 09:07:05.852  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 09:07:05.894  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 09:07:05.894  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-07 09:07:05.899   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:07:05.904   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 09:07:05.905   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:05.905   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 09:07:05.927   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:05.937   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:05.938   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 09:07:05.946   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 09:07:05.962   874  4247 D DhcpClient: Receive thread started
,09-07 09:07:06.044   874  1315 E native  : do suspend false
,09-07 09:07:06.058   874  1999 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 09:07:06.080   874  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172646, domain null
,09-07 09:07:06.081   874  1999 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172646 seconds
,09-07 09:07:06.083   874  1999 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 09:07:06.096   874  4247 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 09:07:06.097   874  1999 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 09:07:06.099   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:06.105   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 09:07:06.109   874  1315 E native  : do suspend true
,09-07 09:07:06.113   874  1999 D DhcpClient: Scheduling renewal in 86399s
,09-07 09:07:06.132   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 09:07:06.137   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 09:07:06.138   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 09:07:06.141   874  1317 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 09:07:06.152   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 09:07:06.184   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 09:07:06.184   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 09:07:06.185   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 09:07:06.186   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 09:07:06.187   874  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 09:07:06.193   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 09:07:06.198   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 09:07:06.199   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-07 09:07:06.199   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 09:07:06.199   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 09:07:06.199   874  1317 D ConnectivityService:    accepting network in place of null
,09-07 09:07:06.199   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:07:06.200   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:07:06.216   874  4246 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175506, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 09:07:06.222   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:06.241   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:06.245   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 09:07:06.245   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:06.248   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 09:07:06.253   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 09:07:06.257  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:06.258  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:07:06.258  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:06.258  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:06.261  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:06.261  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:07:06.262  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:06.262  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:06.265  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 09:07:06.269  1748  1748 D SystemUpdateService: onCreate
09-07 09:07:06.274  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-07 09:07:06.279  1748  4257 I SystemUpdateService: active receiver: enabled
09-07 09:07:06.283  1748  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-07 09:07:06.284  1748  4257 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 09:07:06.284  1748  4257 I SystemUpdateService: now status is 0 (complete)
09-07 09:07:06.284  1748  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:07:06.284  1748  4257 I SystemUpdateService: file has been verified
09-07 09:07:06.285  1748  4257 I SystemUpdateService: OTA package size = 12249756
09-07 09:07:06.289  1748  4257 I SystemUpdateService: showing system update notification
09-07 09:07:06.298   874  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-07 09:07:06.304  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-07 09:07:06.304  1748  1748 D SystemUpdateService: onDestroy
09-07 09:07:06.307  1748  2476 I iu.UploadsManager: num queued entries: 0
09-07 09:07:06.308  1748  2476 I iu.UploadsManager: num updated entries: 0
09-07 09:07:06.310  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 09:07:06.311  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 09:07:06.312  1748  4262 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 09:07:06.312  1748  4262 W BaseAppContext: Using Auth Proxy for data requests.
09-07 09:07:06.313  4141  4141 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 09:07:06.314  1748  4262 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 09:07:06.309  1748  2476 I iu.SyncManager: NEXT; no task
09-07 09:07:06.316  3938  4264 I BooksSync: Starting books sync for 61035162, extras: ade
09-07 09:07:06.317  4141  4141 D SprintDMHelper: simOperator: 
09-07 09:07:06.317  4141  4141 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 09:07:06.327  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 09:07:06.329  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:07:06.353  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 09:07:06.353  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 09:07:06.353  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:07:06.353  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:07:06.367  3938  4269 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 09:07:06.369  1748  4262 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-07 09:07:06.387   874  4245 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 07:07:06 GMT], X-Android-Received-Millis=[1473232026386], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473232026347]}
,09-07 09:07:06.388   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 09:07:06.388   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-07 09:07:06.388   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 09:07:06.391   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 09:07:06.393  1526  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 09:07:06.393  1526  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 09:07:06.393  1526  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:07:06.393  1526  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:07:06.442  1526  3174 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 09:07:06.442  1526  3174 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 09:07:06.443  1526  3174 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:07:06.443  1526  3174 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:07:06.466  2499  4265 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 09:07:06.474  3938  4269 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 09:07:06.475  3938  4264 E BooksSync: Soft error
09-07 09:07:06.475  3938  4264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 09:07:06.475  3938  4264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 09:07:06.475  3938  4264 E BooksSync: Sync error
09-07 09:07:06.475  3938  4264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 09:07:06.475  3938  4264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 09:07:06.476  3938  4264 I BooksSync: Finished books sync
,09-07 09:07:06.484   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164111, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:07:06.818   874  1422 I ActivityManager: Killing 2247:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 09:07:06.927   874  2096 D WifiService: setWifiEnabled: false pid=3994, uid=10000
09-07 09:07:06.927   874  2096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:06.949  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 09:07:06.951   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 09:07:06.952   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 09:07:06.952   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:07:06.952   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:06.962   874  1315 E native  : do suspend true
,09-07 09:07:06.967   874  1999 D DhcpClient: Clearing IP address
,09-07 09:07:06.967   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 09:07:06.970   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:06.979  1526  4272 V NativeCrypto: Read error: ssl=0x9ad87c00: I/O error during system call, Connection timed out
,09-07 09:07:06.981  1526  4272 V NativeCrypto: SSL shutdown failed: ssl=0x9ad87c00: I/O error during system call, Broken pipe
,09-07 09:07:06.986   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 09:07:06.986   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 09:07:06.986   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 09:07:06.988   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 09:07:06.988   874  1315 E native  : do suspend true
,09-07 09:07:06.993   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 09:07:06.994   874  4247 D DhcpClient: Receive thread stopped
,09-07 09:07:07.000   874  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 09:07:07.000   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:07:07.002   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:07:07.016   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:07:07.019  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:07.019  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:07.019  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:07.019  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:07.021   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 09:07:07.021  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:07.021  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:07.021  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:07.022  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:07.028  2138  2310 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:07:07.032   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:07.069   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:07.069   874  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 09:07:07.069   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:07.071   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 09:07:07.087  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:07.089  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:07.094  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:07:07.098  1748  1748 D SystemUpdateService: onCreate
,09-07 09:07:07.101  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:07:07.111  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-07 09:07:07.113  1748  2476 I iu.UploadsManager: num queued entries: 0
09-07 09:07:07.113  1748  2476 I iu.UploadsManager: num updated entries: 0
,09-07 09:07:07.117  1748  4282 I SystemUpdateService: active receiver: enabled
,09-07 09:07:07.120  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:07:07.121  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:07:07.122  4141  4141 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:07.128  4141  4141 D SprintDMHelper: simOperator: 
09-07 09:07:07.128  4141  4141 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:07:07.132  1748  2476 I iu.SyncManager: NEXT; no task
,09-07 09:07:07.135  1748  4282 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:07:07.137  1748  4282 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 09:07:07.137  1748  4282 I SystemUpdateService: now status is 0 (complete)
09-07 09:07:07.137  1748  4282 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:07:07.137  1748  4282 I SystemUpdateService: file has been verified
,09-07 09:07:07.138  1748  4282 I SystemUpdateService: OTA package size = 12249756
,09-07 09:07:07.155  2499  4286 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 09:07:07.160   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 09:07:07.165  1748  4282 I SystemUpdateService: showing system update notification
,09-07 09:07:07.179  1748  1748 D SystemUpdateService: onDestroy
,09-07 09:07:07.245   874  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 09:07:09.983   874   891 I ActivityManager: Start proc 4288:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 09:07:10.114  4288  4288 D AdapterServiceConfig: Adding HeadsetService
,09-07 09:07:10.114  4288  4288 D AdapterServiceConfig: Adding A2dpService
,09-07 09:07:10.115  4288  4288 D AdapterServiceConfig: Adding HidService
,09-07 09:07:10.115  4288  4288 D AdapterServiceConfig: Adding HealthService
,09-07 09:07:10.115  4288  4288 D AdapterServiceConfig: Adding PanService
,09-07 09:07:10.115  4288  4288 D AdapterServiceConfig: Adding GattService
,09-07 09:07:10.115  4288  4288 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 09:07:10.131  4288  4288 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 09:07:10.131   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec3a96d:true
,09-07 09:07:10.136  4288  4288 I bt_bluedroid: init
,09-07 09:07:10.136  4288  4300 I BluetoothAdapterState: Entering OffState
,09-07 09:07:10.141  4288  4301 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 09:07:10.142  4288  4301 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 09:07:10.142  4288  4301 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 09:07:10.142  4288  4301 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 09:07:10.144  4288  4288 I bt_bluedroid: get_profile_interface socket
,09-07 09:07:10.146  4288  4288 I bt_bluedroid: get_profile_interface sdp
09-07 09:07:10.146  4288  4304 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 09:07:10.148  4288  4304 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:07:10.152  4288  4299 I bt_bluedroid: config_hci_snoop_log
,09-07 09:07:10.155   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 09:07:10.164  4288  4300 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 09:07:10.165  4288  4300 D BluetoothAdapterProperties: Setting state to 14
09-07 09:07:10.165  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 09:07:10.169  4288  4300 D BluetoothBondStateMachine: make
,09-07 09:07:10.174  4288  4305 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 09:07:10.185  4288  4300 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:07:10.186  4288  4288 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 09:07:10.196  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:10.198  4288  4288 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 09:07:10.200  4288  4288 D BtGatt.GattService: Received start request. Starting profile...
09-07 09:07:10.200  4288  4288 D BtGatt.GattService: start()
,09-07 09:07:10.201  4288  4288 I bt_bluedroid: get_profile_interface gatt
,09-07 09:07:10.203  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:10.204  4288  4288 D BtGatt.AdvertiseManager: advertise manager created
,09-07 09:07:10.217  4288  4288 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:10.217  4288  4288 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:10.217  4288  4288 V BluetoothAdapterState: isBleTurningOn()=true
09-07 09:07:10.217  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:10.217  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 09:07:10.218  4288  4300 I bt_bluedroid: enable
,09-07 09:07:10.219  4288  4301 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 09:07:10.219  4288  4301 I bt_hci  : start_up
,09-07 09:07:10.240  4288  4301 I bt_vendor: alloc value 0xb3a04189
,09-07 09:07:10.240  4288  4301 I bt_vendor: init
09-07 09:07:10.240  4288  4301 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 09:07:10.240  4288  4301 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 09:07:10.348  4288  4301 D bt_hci  : start_up starting async portion
,09-07 09:07:10.349  4288  4308 I bt_hci  : event_finish_startup
,09-07 09:07:10.349  4288  4308 I bt_hci_h4: hal_open
09-07 09:07:10.350  4288  4308 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 09:07:10.361  4288  4308 I bt_userial_vendor: device fd = 51 open
,09-07 09:07:10.391  4288  4308 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:07:10.423  4288  4308 D bt_hwcfg: Chipset BCM4354A2
,09-07 09:07:10.423  4288  4308 D bt_hwcfg: Target name = [BCM4354A2]
09-07 09:07:10.424  4288  4308 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 09:07:11.083  4288  4308 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 09:07:11.085  4288  4308 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 09:07:11.085  4288  4308 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 09:07:11.202  4288  4308 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:07:11.204  4288  4308 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 09:07:11.232  4288  4308 I bt_hwcfg: vendor lib fwcfg completed
,09-07 09:07:11.232  4288  4308 I bt_vendor: firmware callback
09-07 09:07:11.232  4288  4308 I bt_hci  : firmware_config_callback
,09-07 09:07:11.245  4288  4310 I bt_btu  : btu_task pending for preload complete event
,09-07 09:07:11.245  4288  4310 I bt_btu_task: Bluetooth chip preload is complete
09-07 09:07:11.246  4288  4310 I bt_btu  : btu_task received preload complete event
,09-07 09:07:11.256  4288  4310 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 09:07:11.256  4288  4310 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 09:07:11.257  4288  4310 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 09:07:11.257  4288  4310 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 09:07:11.257  4288  4310 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 09:07:11.257  4288  4310 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 09:07:11.258  4288  4310 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 09:07:11.258  4288  4310 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 09:07:11.258  4288  4310 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 09:07:11.258  4288  4310 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 09:07:11.259  4288  4310 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 09:07:11.259  4288  4310 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 09:07:11.259  4288  4310 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 09:07:11.259  4288  4310 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 09:07:11.260  4288  4310 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 09:07:11.391  4288  4310 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3981d9d
,09-07 09:07:11.392  4288  4310 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3981d9d 
,09-07 09:07:11.416  4288  4304 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 09:07:11.418  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:07:11.419  4288  4304 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:07:11.421  4288  4304 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:07:11.424  4288  4304 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:07:11.425  4288  4304 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 09:07:11.425  4288  4304 D bt_hci  : do_postload posting postload work item
,09-07 09:07:11.425  4288  4308 I bt_hci  : event_postload
09-07 09:07:11.426  4288  4308 I bt_vendor: sco_config_cb
,09-07 09:07:11.426  4288  4308 I bt_hci  : sco_config_callback postload finished.
,09-07 09:07:11.428  4288  4304 D bt_bte_conf: Device ID record 1 : primary
09-07 09:07:11.429  4288  4304 D bt_bte_conf:   vendorId            = 000f
,09-07 09:07:11.429  4288  4304 D bt_bte_conf:   vendorIdSource      = 0001
09-07 09:07:11.429  4288  4304 D bt_bte_conf:   product             = 1200
,09-07 09:07:11.429  4288  4304 D bt_bte_conf:   version             = 1436
09-07 09:07:11.430  4288  4304 D bt_bte_conf:   clientExecutableURL = 
09-07 09:07:11.430  4288  4304 D bt_bte_conf:   serviceDescription  = 
09-07 09:07:11.430  4288  4304 D bt_bte_conf:   documentationURL    = 
09-07 09:07:11.432  4288  4304 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 09:07:11.432  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:11.432  4288  4301 D bt_stack_manager: event_start_up_stack finished
09-07 09:07:11.435  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 09:07:11.435  4288  4300 D BluetoothAdapterProperties: Setting state to 15
,09-07 09:07:11.436  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 09:07:11.436  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:11.437  4288  4300 I BluetoothAdapterState: Entering BleOnState
09-07 09:07:11.438  4288  4308 I bt_vendor: low_power_mode_cb
,09-07 09:07:11.441  4288  4300 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 09:07:11.441  4288  4300 D BluetoothAdapterProperties: Setting state to 11
,09-07 09:07:11.441  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 09:07:11.447  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:11.455  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:11.455  4288  4288 D HeadsetService: Received start request. Starting profile...
09-07 09:07:11.459  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:11.460  4288  4300 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:07:11.461  4288  4288 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 09:07:11.461  4288  4288 D HeadsetStateMachine: make
,09-07 09:07:11.473  4288  4288 D HeadsetStateMachine: max_hf_connections = 1
,09-07 09:07:11.473  4288  4288 I bt_bluedroid: get_profile_interface handsfree
,09-07 09:07:11.473  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-07 09:07:11.474  4288  4304 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-07 09:07:11.478  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:11.479  4288  4288 D A2dpService: Received start request. Starting profile...
,09-07 09:07:11.480  4288  4288 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 09:07:11.480  4288  4288 I bt_bluedroid: get_profile_interface avrcp
,09-07 09:07:11.486  4288  4288 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 09:07:11.487  4288  4288 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 09:07:11.487  4288  4288 D A2dpStateMachine: make
,09-07 09:07:11.488  4288  4288 I bt_bluedroid: get_profile_interface a2dp,
,09-07 09:07:11.489  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 09:07:11.491  4288  4319 D A2dpStateMachine: Enter Disconnected: -2
,09-07 09:07:11.491  4288  4288 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 09:07:11.492  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:11.493  4086  4086 D BluetoothInputDevice: Proxy object connected
09-07 09:07:11.493  4288  4288 D HidService: Received start request. Starting profile...
,09-07 09:07:11.493  4288  4288 I bt_bluedroid: get_profile_interface hidhost
09-07 09:07:11.494  4288  4304 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39633e5
,09-07 09:07:11.494  4288  4288 D HidService: setHidService(): set to: null
09-07 09:07:11.494  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 09:07:11.494  4288  4288 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 09:07:11.495  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:11.495  4288  4288 D HealthService: Received start request. Starting profile...
,09-07 09:07:11.497  4288  4288 I bt_bluedroid: get_profile_interface health
,09-07 09:07:11.497  4288  4288 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 09:07:11.497  4086  4086 D HidProfile: Bluetooth service connected
,09-07 09:07:11.498  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:11.499  4288  4288 D PanService: Received start request. Starting profile...
,09-07 09:07:11.499  4086  4086 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 09:07:11.499  4288  4288 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 09:07:11.499  4288  4288 I bt_bluedroid: get_profile_interface pan
09-07 09:07:11.499  4086  4086 D PanProfile: Bluetooth service connected
09-07 09:07:11.500  4288  4304 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 09:07:11.501  4288  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:11.502  4288  4288 D BluetoothMapService: Received start request. Starting profile...
,09-07 09:07:11.502  4288  4288 D BluetoothMapService: start()
,09-07 09:07:11.502  4086  4086 D BluetoothMap: Proxy object connected
09-07 09:07:11.503  4086  4086 D MapProfile: Bluetooth service connected
,09-07 09:07:11.503  4086  4086 D BluetoothMap: getConnectedDevices()
09-07 09:07:11.504  4086  4086 D BluetoothMap: Bluetooth is Not enabled
09-07 09:07:11.504  4288  4288 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 09:07:11.505  4288  4288 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 09:07:11.505  4288  4288 D BluetoothMapAppObserver: createReceiver()
,09-07 09:07:11.506  4288  4288 D BluetoothMapAppObserver: initObservers()
09-07 09:07:11.506  4288  4288 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 09:07:11.514  4288  4288 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:11.514  4288  4288 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:11.514  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:11.514  4288  4317 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 09:07:11.514  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:11.514  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:07:11.515  4288  4288 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:11.515  4288  4288 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:11.515  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:11.515  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false,
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:07:11.516  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:07:11.517  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:11.517  4288  4288 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:11.517  4288  4288 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:07:11.517  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:11.517  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:11.517  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 09:07:11.517  4288  4300 D BluetoothAdapterProperties: ScanMode =  20
,09-07 09:07:11.517  4288  4300 D BluetoothAdapterProperties: State =  11
,09-07 09:07:11.518  4288  4300 D BluetoothAdapterProperties: Setting state to 12,
,09-07 09:07:11.518  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 09:07:11.518  1923  1942 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:07:11.519  4288  4300 I BluetoothAdapterState: Entering OnState
09-07 09:07:11.519  1358  2026 D BluetoothPan: onBluetoothStateChange on: true
09-07 09:07:11.520  4288  4304 D BluetoothAdapterProperties: Scan Mode:21
,09-07 09:07:11.520  4288  4304 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 09:07:11.522  3994  3994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 09:07:11.524  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 09:07:11.524  1358  1358 D PanProfile: Bluetooth service connected
09-07 09:07:11.524  3994  3994 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 09:07:11.525   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:07:11.525  4086  4096 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:07:11.525   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:11.526  4086  4097 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:11.527  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:11.527  4086  4096 D BluetoothPan: onBluetoothStateChange on: true
,09-07 09:07:11.528   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:11.528  4086  4097 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 09:07:11.528  1358  1371 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:11.529  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:11.529   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:07:11.530  1358  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:07:11.530   874   874 D BluetoothA2dp: Proxy object connected
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:11.532  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:11.533  1358  1358 D BluetoothA2dp: Proxy object connected
09-07 09:07:11.534  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:11.534  1358  1371 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:07:11.536  4288  4288 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 09:07:11.537  4288  4288 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 09:07:11.537  1358  1358 D BluetoothMap: Proxy object connected
09-07 09:07:11.538  1358  1358 D MapProfile: Bluetooth service connected
09-07 09:07:11.538  1358  1358 D BluetoothMap: getConnectedDevices()
09-07 09:07:11.538  1358  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:07:11.538  4288  4288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:07:11.543  1358  1358 D BluetoothInputDevice: Proxy object connected
09-07 09:07:11.543  1358  1358 D HidProfile: Bluetooth service connected
09-07 09:07:11.543  1358  1371 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 09:07:11.544  4288  4288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:07:11.545   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 09:07:11.548  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:11.548  4288  4288 D ObexServerSockets: Succeed to create listening sockets 
09-07 09:07:11.548  4288  4288 D ObexServerSockets0: startAccept()
09-07 09:07:11.548  4288  4288 D ObexServerSockets0: prepareForNewConnect()
09-07 09:07:11.549  4086  4086 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 09:07:11.549  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:11.551  4288  4288 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 09:07:11.551  4288  4288 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 09:07:11.552  4288  4288 D BluetoothMapService: onReceive
09-07 09:07:11.552  4288  4288 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 09:07:11.552  4288  4288 D BluetoothMapService: STATE_ON
09-07 09:07:11.553  4086  4086 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 09:07:11.553  4288  4325 D ObexServerSockets0: Accepting socket connection...
09-07 09:07:11.553  4288  4326 D ObexServerSockets0: Accepting socket connection...
,09-07 09:07:11.559  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:07:11.561  4086  4086 D BluetoothA2dp: Proxy object connected
,09-07 09:07:11.564  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:07:11.568  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:07:11.573  4086  4086 D BluetoothPbap: Proxy object connected
,09-07 09:07:11.573  4086  4086 D PbapServerProfile: Bluetooth service connected
09-07 09:07:11.573  1358  1358 D BluetoothPbap: Proxy object connected
09-07 09:07:11.573  1358  1358 D PbapServerProfile: Bluetooth service connected
,09-07 09:07:11.579  4288  4288 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 09:07:11.579  4288  4288 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:07:11.580  4288  4330 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:11.597  4288  4334 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:11.598  4288  4334 I BtOppRfcommListener: Accept thread started.
,09-07 09:07:11.621  1923  1944 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.621   874   874 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.622  1358  1370 D BluetoothHeadset: Proxy object connected
09-07 09:07:11.622   874   874 D BluetoothHeadset: Proxy object connected
09-07 09:07:11.622  1358  1358 D HeadsetProfile: Bluetooth service connected
09-07 09:07:11.622   874   874 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.625   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.625   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.628   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.629  1358  2026 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.629  1358  1358 D HeadsetProfile: Bluetooth service connected
,09-07 09:07:11.657  4086  4097 D BluetoothHeadset: Proxy object connected
,09-07 09:07:11.658  4086  4086 D HeadsetProfile: Bluetooth service connected
,09-07 09:07:12.944  4288  4300 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 09:07:12.944  4288  4300 D BluetoothAdapterProperties: Setting state to 13
,09-07 09:07:12.945  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 09:07:12.946  4288  4300 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 09:07:12.948  4288  4300 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:07:12.956  4288  4288 D BluetoothMapService: onReceive
,09-07 09:07:12.956  4288  4288 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 09:07:12.958  4288  4288 D BluetoothMapService: STATE_TURNING_OFF
09-07 09:07:12.959  4288  4288 D BluetoothMapService: MAP Service closeService in
09-07 09:07:12.959  4288  4288 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 09:07:12.959  4288  4288 D ObexServerSockets0: shutdown(block = true)
09-07 09:07:12.960  4288  4325 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 09:07:12.964  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:12.964  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:07:12.965  4288  4288 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:07:12.966  4288  4326 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 09:07:12.967  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:12.968  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:12.970  4288  4288 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 09:07:12.971  4288  4288 I BtOppRfcommListener: stopping Accept Thread
,09-07 09:07:12.972  4288  4312 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 09:07:12.972  4288  4334 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 09:07:12.974  4288  4334 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 09:07:12.974  4288  4304 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:07:12.975  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 09:07:12.975  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:12.975  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:12.976  3994  3994 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:07:12.977  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:12.979  4288  4288 D HeadsetService: Received stop request...Stopping profile...
09-07 09:07:12.980  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:12.982  1923  2094 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.983   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.983  1358  1371 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.983  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:12.983  4288  4288 D A2dpService: Received stop request...Stopping profile...
09-07 09:07:12.983  4288  4319 D A2dpStateMachine: Exit Disconnected: -1
,09-07 09:07:12.984  4086  4096 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.984   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.984   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 09:07:12.984  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:07:12.984  1358  1358 D HeadsetProfile: Bluetooth service disconnected
09-07 09:07:12.988   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 09:07:12.989  1358  1358 D BluetoothA2dp: Proxy object disconnected
09-07 09:07:12.989  4288  4288 D HidService: Received stop request...Stopping profile...
09-07 09:07:12.989  4288  4288 D HidService: Stopping Bluetooth HidService
,09-07 09:07:12.991  1358  1358 D BluetoothInputDevice: Proxy object disconnected
09-07 09:07:12.991  4086  4086 D HeadsetProfile: Bluetooth service disconnected
09-07 09:07:12.991  1358  1358 D HidProfile: Bluetooth service disconnected
09-07 09:07:12.991  4288  4288 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:12.991  4288  4288 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:12.991  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:12.991  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:12.992  4288  4288 D HealthService: Received stop request...Stopping profile...
09-07 09:07:12.994  4288  4288 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 09:07:12.994  4288  4288 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 09:07:12.995  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 09:07:12.995  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:12.995  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:12.995  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:12.995  4288  4304 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
09-07 09:07:12.997  4288  4288 D PanService: Received stop request...Stopping profile...
,09-07 09:07:12.999  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 09:07:12.999  1358  1358 D PanProfile: Bluetooth service disconnected
09-07 09:07:12.999  4288  4288 D BluetoothMapService: Received stop request...Stopping profile...
09-07 09:07:12.999  4288  4288 D BluetoothMapService: stop()
09-07 09:07:12.999  4086  4086 D DockEventReceiver: finishStartingService: stopping service
09-07 09:07:13.000  4288  4288 D BluetoothMapAppObserver: deinitObservers()
09-07 09:07:13.000  4288  4288 D BluetoothMapAppObserver: removeReceiver()
,09-07 09:07:13.001  1358  1358 D BluetoothMap: Proxy object disconnected
,09-07 09:07:13.001  1358  1358 D MapProfile: Bluetooth service disconnected
09-07 09:07:13.001  4086  4086 D BluetoothA2dp: Proxy object disconnected
09-07 09:07:13.002  4086  4086 D BluetoothInputDevice: Proxy object disconnected
09-07 09:07:13.002  4288  4288 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:13.002  4086  4086 D HidProfile: Bluetooth service disconnected
09-07 09:07:13.002  4288  4288 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:07:13.002  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.002  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:13.002  4086  4086 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 09:07:13.003  4086  4086 D PanProfile: Bluetooth service disconnected
,09-07 09:07:13.003  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:13.003  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:13.004  4288  4310 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:07:13.004  4288  4310 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:07:13.004  4288  4310 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:07:13.004  4288  4310 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:07:13.004  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-07 09:07:13.004  4288  4288 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:13.004  4288  4288 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:13.004  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.005  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:13.008  4288  4288 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 09:07:13.008  4288  4288 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 09:07:13.008  4288  4304 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:07:13.008  4288  4288 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:13.008  4288  4288 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:13.008  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.008  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:13.009  4288  4288 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 09:07:13.009  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:07:13.009  4288  4304 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 09:07:13.009  4288  4288 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 09:07:13.010  4288  4288 V BluetoothAdapterState: isTurningOff()=true
,09-07 09:07:13.010  4288  4288 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:13.010  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.010  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:13.011  4288  4288 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 09:07:13.011  4288  4288 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 09:07:13.011  4086  4086 D BluetoothMap: Proxy object disconnected
09-07 09:07:13.012  4288  4288 D BluetoothMapService: MAP Service closeService in
09-07 09:07:13.012  4086  4086 D MapProfile: Bluetooth service disconnected
09-07 09:07:13.012  4288  4288 V BluetoothAdapterState: isTurningOff()=true
09-07 09:07:13.012  4288  4288 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:07:13.012  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.012  4288  4288 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:13.012  4288  4288 D BluetoothMapService: cleanup()
09-07 09:07:13.013  4288  4288 D BluetoothMapService: MAP Service closeService in
09-07 09:07:13.013  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 09:07:13.013  4288  4300 D BluetoothAdapterProperties: Setting state to 15
09-07 09:07:13.013  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 09:07:13.014  4288  4300 I BluetoothAdapterState: Entering BleOnState
09-07 09:07:13.014  4086  4086 D BluetoothPbap: Proxy object disconnected
09-07 09:07:13.014  4086  4086 D PbapServerProfile: Bluetooth service disconnected
09-07 09:07:13.014  1923  2095 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.015  1358  1358 D BluetoothPbap: Proxy object disconnected
,09-07 09:07:13.015  1358  1358 D PbapServerProfile: Bluetooth service disconnected
09-07 09:07:13.015  1358  2026 D BluetoothPan: onBluetoothStateChange on: false
09-07 09:07:13.016   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.016  4086  4097 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 09:07:13.017   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.018  4086  4339 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 09:07:13.018  4086  4096 D BluetoothPan: onBluetoothStateChange on: false
,09-07 09:07:13.019   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.019  4086  4339 D BluetoothMap: onBluetoothStateChange: up=false
09-07 09:07:13.020  4086  4097 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 09:07:13.020  1358  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.021  4086  4096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:07:13.021   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:07:13.021  1358  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 09:07:13.022  1358  2026 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 09:07:13.024  1358  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 09:07:13.025  1358  1370 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 09:07:13.025  4288  4300 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 09:07:13.025  4288  4300 D BluetoothAdapterProperties: Setting state to 16
09-07 09:07:13.025  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 09:07:13.026  4288  4300 D BluetoothAdapterProperties: onBleDisable
09-07 09:07:13.026  4288  4300 I BluetoothAdapterState: Entering PendingCommandState
09-07 09:07:13.026  4288  4301 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 09:07:13.027  4288  4310 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 09:07:13.027  4288  4310 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:07:13.029  4288  4304 D BluetoothAdapterProperties: Scan Mode:20
09-07 09:07:13.030  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:13.030  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:07:13.031  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:13.032  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:13.033  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:13.036  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:07:13.040  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:07:13.228  4288  4304 I bt_hci  : shut_down
,09-07 09:07:13.229  4288  4308 D bt_hwcfg: hw_epilog_process
09-07 09:07:13.230  4288  4308 I bt_vendor: low_power_mode_cb
,09-07 09:07:13.250  4288  4308 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 09:07:13.250  4288  4308 I bt_vendor: epilog_cb
09-07 09:07:13.250  4288  4308 I bt_hci  : epilog_finished_callback
,09-07 09:07:13.259  4288  4304 I bt_hci_h4: hal_close
,09-07 09:07:13.260  4288  4304 I bt_userial_vendor: device fd = 51 close
,09-07 09:07:13.393  4288  4301 D bt_stack_manager: event_shut_down_stack finished.
,09-07 09:07:13.394  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 09:07:13.400  4288  4300 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 09:07:13.400  4288  4288 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 09:07:13.402  4288  4288 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 09:07:13.402  4288  4288 D BtGatt.GattService: stop()
09-07 09:07:13.402  4288  4288 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 09:07:13.408  4288  4288 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:13.408  4288  4288 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:07:13.408  4288  4288 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:13.409  4288  4288 V BluetoothAdapterState: isBleTurningOff()=true
09-07 09:07:13.409  4288  4300 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 09:07:13.410  4288  4300 D BluetoothAdapterProperties: Setting state to 10
09-07 09:07:13.410  4288  4300 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 09:07:13.412  4288  4300 I BluetoothAdapterState: Entering OffState
,09-07 09:07:13.414   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 09:07:13.443  4288  4288 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 09:07:13.443  4288  4288 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 09:07:13.444  4288  4301 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 09:07:13.450  4288  4301 D bt_stack_manager: event_clean_up_stack finished.
,09-07 09:07:13.451  4288  4288 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 09:07:13.454  4288  4288 I art     : System.exit called, status: 0
09-07 09:07:13.454  4288  4288 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 09:07:13.516   874  1943 I ActivityManager: Process com.android.bluetooth (pid 4288) has died
,09-07 09:07:14.206   874  1317 D ConnectivityService: handlePromptUnvalidated 101
,09-07 09:07:15.941  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:07:15.941  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:15.950  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:07:15.950  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8b70af added. We now have 6 listener(s)
,09-07 09:07:15.951  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:07:15.956  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:07:15.956  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7cbc added. We now have 7 listener(s)
09-07 09:07:15.956  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:07:15.958  3994  4042 I System.out: IsBluetoothEnabled
,09-07 09:07:15.969  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:16.012   874   891 I ActivityManager: Start proc 4345:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 09:07:16.149  4345  4345 D AdapterServiceConfig: Adding HeadsetService
,09-07 09:07:16.150  4345  4345 D AdapterServiceConfig: Adding A2dpService
09-07 09:07:16.151  4345  4345 D AdapterServiceConfig: Adding HidService
09-07 09:07:16.152  4345  4345 D AdapterServiceConfig: Adding HealthService
09-07 09:07:16.153  4345  4345 D AdapterServiceConfig: Adding PanService
,09-07 09:07:16.154  4345  4345 D AdapterServiceConfig: Adding GattService
,09-07 09:07:16.157  4345  4345 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 09:07:16.194   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd514d6:true
,09-07 09:07:16.195  4345  4345 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 09:07:16.199  4345  4345 I bt_bluedroid: init
09-07 09:07:16.199  4345  4357 I BluetoothAdapterState: Entering OffState
,09-07 09:07:16.203  4345  4358 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 09:07:16.203  4345  4358 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 09:07:16.203  4345  4358 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 09:07:16.203  4345  4358 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 09:07:16.205  4345  4345 I bt_bluedroid: get_profile_interface socket
,09-07 09:07:16.207  4345  4345 I bt_bluedroid: get_profile_interface sdp
,09-07 09:07:16.210  4345  4361 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:07:16.211  4345  4356 I bt_bluedroid: config_hci_snoop_log
,09-07 09:07:16.213  4345  4361 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:07:16.214   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 09:07:16.221  4345  4357 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 09:07:16.221  4345  4357 D BluetoothAdapterProperties: Setting state to 14
09-07 09:07:16.221  4345  4357 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 09:07:16.224  4345  4357 D BluetoothBondStateMachine: make
,09-07 09:07:16.228  4345  4363 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 09:07:16.233  4345  4345 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-07 09:07:16.234  4345  4357 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:07:16.238  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:16.239  4345  4345 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 09:07:16.240  4345  4345 D BtGatt.GattService: Received start request. Starting profile...
,09-07 09:07:16.240  4345  4345 D BtGatt.GattService: start()
09-07 09:07:16.240  4345  4345 I bt_bluedroid: get_profile_interface gatt
09-07 09:07:16.241  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:16.242  4345  4345 D BtGatt.AdvertiseManager: advertise manager created
,09-07 09:07:16.250  4345  4345 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:16.250  4345  4345 V BluetoothAdapterState: isTurningOn()=false
09-07 09:07:16.250  4345  4345 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 09:07:16.250  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:16.251  4345  4357 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 09:07:16.251  4345  4357 I bt_bluedroid: enable
09-07 09:07:16.252  4345  4358 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 09:07:16.252  4345  4358 I bt_hci  : start_up
,09-07 09:07:16.272  4345  4358 I bt_vendor: alloc value 0xb3a04189
09-07 09:07:16.272  4345  4358 I bt_vendor: init
,09-07 09:07:16.273  4345  4358 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 09:07:16.273  4345  4358 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 09:07:16.382  4345  4358 D bt_hci  : start_up starting async portion
,09-07 09:07:16.383  4345  4366 I bt_hci  : event_finish_startup
09-07 09:07:16.383  4345  4366 I bt_hci_h4: hal_open
09-07 09:07:16.384  4345  4366 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 09:07:16.392  4345  4366 I bt_userial_vendor: device fd = 51 open
,09-07 09:07:16.425  4345  4366 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:07:16.456  4345  4366 D bt_hwcfg: Chipset BCM4354A2
,09-07 09:07:16.457  4345  4366 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 09:07:16.457  4345  4366 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 09:07:17.132  4345  4366 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 09:07:17.133  4345  4366 D bt_hwcfg: Settlement delay -- 100 ms
09-07 09:07:17.134  4345  4366 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 09:07:17.251  4345  4366 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:07:17.252  4345  4366 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 09:07:17.281  4345  4366 I bt_hwcfg: vendor lib fwcfg completed
,09-07 09:07:17.281  4345  4366 I bt_vendor: firmware callback
,09-07 09:07:17.281  4345  4366 I bt_hci  : firmware_config_callback
,09-07 09:07:17.291  4345  4369 I bt_btu  : btu_task pending for preload complete event
,09-07 09:07:17.291  4345  4369 I bt_btu_task: Bluetooth chip preload is complete,
,09-07 09:07:17.292  4345  4369 I bt_btu  : btu_task received preload complete event
,09-07 09:07:17.300  4345  4369 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 09:07:17.300  4345  4369 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 09:07:17.300  4345  4369 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 09:07:17.300  4345  4369 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 09:07:17.301  4345  4369 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 09:07:17.301  4345  4369 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 09:07:17.301  4345  4369 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 09:07:17.301  4345  4369 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 09:07:17.301  4345  4369 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 09:07:17.302  4345  4369 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 09:07:17.302  4345  4369 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 09:07:17.302  4345  4369 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 09:07:17.302  4345  4369 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 09:07:17.302  4345  4369 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 09:07:17.303  4345  4369 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 09:07:17.436  4345  4369 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3981d9d
,09-07 09:07:17.436  4345  4369 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3981d9d 
,09-07 09:07:17.443  4345  4361 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 09:07:17.445  4345  4361 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:07:17.446  4345  4361 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:07:17.450  4345  4361 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:07:17.455  4345  4361 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:07:17.455  4345  4361 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 09:07:17.455  4345  4361 D bt_hci  : do_postload posting postload work item
09-07 09:07:17.456  4345  4366 I bt_hci  : event_postload
09-07 09:07:17.456  4345  4366 I bt_vendor: sco_config_cb
09-07 09:07:17.456  4345  4366 I bt_hci  : sco_config_callback postload finished.
,09-07 09:07:17.459  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:17.460  4345  4361 D bt_bte_conf: Device ID record 1 : primary
09-07 09:07:17.461  4345  4361 D bt_bte_conf:   vendorId            = 000f
09-07 09:07:17.461  4345  4361 D bt_bte_conf:   vendorIdSource      = 0001
09-07 09:07:17.461  4345  4361 D bt_bte_conf:   product             = 1200
09-07 09:07:17.461  4345  4361 D bt_bte_conf:   version             = 1436
09-07 09:07:17.461  4345  4361 D bt_bte_conf:   clientExecutableURL = 
09-07 09:07:17.462  4345  4366 I bt_vendor: low_power_mode_cb
09-07 09:07:17.462  4345  4361 D bt_bte_conf:   serviceDescription  = 
,09-07 09:07:17.462  4345  4361 D bt_bte_conf:   documentationURL    = 
09-07 09:07:17.463  4345  4361 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 09:07:17.463  4345  4358 D bt_stack_manager: event_start_up_stack finished
09-07 09:07:17.464  4345  4357 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 09:07:17.465  4345  4357 D BluetoothAdapterProperties: Setting state to 15
09-07 09:07:17.465  4345  4357 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 09:07:17.466  4345  4357 I BluetoothAdapterState: Entering BleOnState
,09-07 09:07:17.469  4345  4357 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 09:07:17.469  4345  4357 D BluetoothAdapterProperties: Setting state to 11
,09-07 09:07:17.469  4345  4357 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 09:07:17.474  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:17.476  4345  4345 D HeadsetService: Received start request. Starting profile...
09-07 09:07:17.479  4345  4345 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 09:07:17.480  4345  4345 D HeadsetStateMachine: make
09-07 09:07:17.485  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:17.491  4345  4357 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:07:17.494  4345  4345 D HeadsetStateMachine: max_hf_connections = 1
,09-07 09:07:17.494  4345  4345 I bt_bluedroid: get_profile_interface handsfree
09-07 09:07:17.495  4345  4361 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 09:07:17.495  4345  4361 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-07 09:07:17.498  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:17.498  4345  4345 D A2dpService: Received start request. Starting profile...
09-07 09:07:17.499  4345  4345 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 09:07:17.499  4345  4345 I bt_bluedroid: get_profile_interface avrcp
,09-07 09:07:17.506  4345  4345 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 09:07:17.506  4345  4345 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 09:07:17.506  4345  4345 D A2dpStateMachine: make
,09-07 09:07:17.507  4345  4345 I bt_bluedroid: get_profile_interface a2dp
09-07 09:07:17.508  4345  4361 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 09:07:17.512  4345  4377 D A2dpStateMachine: Enter Disconnected: -2
,09-07 09:07:17.513  4345  4345 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 09:07:17.514  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:17.515  4345  4345 D HidService: Received start request. Starting profile...
,09-07 09:07:17.515  4345  4345 I bt_bluedroid: get_profile_interface hidhost
09-07 09:07:17.515  4345  4345 D HidService: setHidService(): set to: null
09-07 09:07:17.515  4345  4361 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39633e5
09-07 09:07:17.515  4345  4361 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 09:07:17.516  4345  4345 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 09:07:17.516  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:17.517  4345  4345 D HealthService: Received start request. Starting profile...
,09-07 09:07:17.520  4345  4345 I bt_bluedroid: get_profile_interface health
,09-07 09:07:17.521  4345  4345 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 09:07:17.522  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
09-07 09:07:17.522  4345  4345 D PanService: Received start request. Starting profile...
,09-07 09:07:17.523  4345  4345 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 09:07:17.523  4345  4345 I bt_bluedroid: get_profile_interface pan
,09-07 09:07:17.523  4345  4361 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 09:07:17.526  4345  4345 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:17.527  4345  4345 D BluetoothMapService: Received start request. Starting profile...
09-07 09:07:17.528  4345  4345 D BluetoothMapService: start()
,09-07 09:07:17.531  4345  4345 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 09:07:17.531  4345  4345 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 09:07:17.532  4345  4345 D BluetoothMapAppObserver: createReceiver()
09-07 09:07:17.533  4345  4345 D BluetoothMapAppObserver: initObservers()
09-07 09:07:17.533  4345  4345 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 09:07:17.553  4345  4345 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:17.554  4345  4345 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:17.554  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.554  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:17.556  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.557  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:17.558  4345  4345 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:17.557  4345  4375 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 09:07:17.559  4345  4345 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:17.559  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.559  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isTurningOff()=false
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isTurningOn()=true
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:07:17.560  4345  4345 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:07:17.561  4345  4357 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 09:07:17.561  4345  4357 D BluetoothAdapterProperties: ScanMode =  20
,09-07 09:07:17.561  4345  4357 D BluetoothAdapterProperties: State =  11
09-07 09:07:17.561  4345  4357 D BluetoothAdapterProperties: Setting state to 12
,09-07 09:07:17.561  4345  4357 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 09:07:17.563  1923  2094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.564  4345  4357 I BluetoothAdapterState: Entering OnState
09-07 09:07:17.564  1358  1371 D BluetoothPan: onBluetoothStateChange on: true
09-07 09:07:17.564  4345  4361 D BluetoothAdapterProperties: Scan Mode:21
,09-07 09:07:17.565  4345  4361 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 09:07:17.568   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.569  4086  4339 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:07:17.569  4345  4345 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 09:07:17.569  4345  4345 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 09:07:17.571   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.571  4086  4097 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 09:07:17.571  4345  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:17.571  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:17.573  4086  4096 D BluetoothPan: onBluetoothStateChange on: true
,09-07 09:07:17.575  4345  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:07:17.576   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.576  4086  4339 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:07:17.577  4345  4345 D ObexServerSockets: Succeed to create listening sockets 
09-07 09:07:17.577  4345  4345 D ObexServerSockets0: startAccept()
09-07 09:07:17.577  4345  4345 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:07:17.579  4086  4097 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:07:17.580  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:07:17.583  1358  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.583  4345  4345 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 09:07:17.583  4345  4345 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-07 09:07:17.583  4086  4096 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:07:17.584   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 09:07:17.586  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 09:07:17.586  1358  1358 D PanProfile: Bluetooth service connected
09-07 09:07:17.586  1358  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:07:17.588  4345  4382 D ObexServerSockets0: Accepting socket connection...
,09-07 09:07:17.590  4086  4086 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 09:07:17.590   874   874 D BluetoothA2dp: Proxy object connected
09-07 09:07:17.590  4086  4086 D PanProfile: Bluetooth service connected
09-07 09:07:17.590  4086  4086 D BluetoothInputDevice: Proxy object connected
09-07 09:07:17.590  4086  4086 D HidProfile: Bluetooth service connected
09-07 09:07:17.591  1358  1358 D BluetoothA2dp: Proxy object connected
,09-07 09:07:17.591  4345  4383 D ObexServerSockets0: Accepting socket connection...
09-07 09:07:17.592  1358  1371 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:07:17.593  4086  4086 D BluetoothMap: Proxy object connected
09-07 09:07:17.593  4086  4086 D MapProfile: Bluetooth service connected
,09-07 09:07:17.593  4086  4086 D BluetoothMap: getConnectedDevices()
,09-07 09:07:17.594  1358  1358 D BluetoothMap: Proxy object connected
,09-07 09:07:17.594  1358  1358 D MapProfile: Bluetooth service connected
09-07 09:07:17.594  1358  1358 D BluetoothMap: getConnectedDevices()
,09-07 09:07:17.594  1358  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:07:17.597  1358  1358 D BluetoothInputDevice: Proxy object connected
09-07 09:07:17.597  1358  1358 D HidProfile: Bluetooth service connected
09-07 09:07:17.597  4086  4086 D BluetoothA2dp: Proxy object connected
09-07 09:07:17.597  1358  1371 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 09:07:17.602   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 09:07:17.603  4345  4345 D BluetoothMapService: onReceive
,09-07 09:07:17.603  4345  4345 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 09:07:17.603  4345  4345 D BluetoothMapService: STATE_ON
,09-07 09:07:17.605  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:07:17.609  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:07:17.615  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:07:17.616  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:07:17.624  4086  4086 D BluetoothPbap: Proxy object connected
,09-07 09:07:17.624  4086  4086 D PbapServerProfile: Bluetooth service connected
,09-07 09:07:17.629  1358  1358 D BluetoothPbap: Proxy object connected
09-07 09:07:17.629  1358  1358 D PbapServerProfile: Bluetooth service connected
,09-07 09:07:17.629  4345  4345 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 09:07:17.629  4345  4345 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:07:17.633  4345  4388 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:17.647  4345  4392 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:17.648  4345  4392 I BtOppRfcommListener: Accept thread started.
,09-07 09:07:17.665  1923  2095 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.665   874   874 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.666  1358  2026 D BluetoothHeadset: Proxy object connected
09-07 09:07:17.667  1358  1358 D HeadsetProfile: Bluetooth service connected
09-07 09:07:17.667  4086  4097 D BluetoothHeadset: Proxy object connected
09-07 09:07:17.667   874   874 D BluetoothHeadset: Proxy object connected
09-07 09:07:17.667  4086  4086 D HeadsetProfile: Bluetooth service connected
09-07 09:07:17.667   874   874 D BluetoothHeadset: Proxy object connected
09-07 09:07:17.669   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.671   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.675   874   891 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.683  1358  1370 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.683  1358  1358 D HeadsetProfile: Bluetooth service connected
,09-07 09:07:17.685  4086  4096 D BluetoothHeadset: Proxy object connected
,09-07 09:07:17.685  4086  4086 D HeadsetProfile: Bluetooth service connected
,09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:17.992  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:17.998  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:18.004  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:07:18.004  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5949445 added. We now have 8 listener(s)
,09-07 09:07:18.005  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:07:18.012   874  1945 D WifiService: setWifiEnabled: false pid=3994, uid=10000
,09-07 09:07:18.012   874  1945 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:18.024  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:18.025   874  1952 D WifiService: setWifiEnabled: true pid=3994, uid=10000
,09-07 09:07:18.026   874  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:07:18.041   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:18.059  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:18.066  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:18.068   874  1315 D WifiConfigStore: loaded 0 passpoint configs
09-07 09:07:18.069   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 09:07:18.070   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 09:07:18.071   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 09:07:18.072   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 09:07:18.072   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 09:07:18.072   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 09:07:18.089   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 09:07:18.090   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:18.091   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-07 09:07:18.091   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 09:07:18.091   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:07:18.096   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 09:07:18.146   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 09:07:18.152   874  1315 E native  : do suspend true
,09-07 09:07:18.195   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:07:19.053  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:07:19.059  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:07:19.075  3994  4398 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-07 09:07:19.076  3994  4398 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 09:07:19.467   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:07:19.605   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.06 rxSuccessRate=13.25 delta 1000 -> 994
,09-07 09:07:19.610   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 09:07:19.611   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:19.626   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 09:07:19.700   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 09:07:19.703  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 09:07:20.233  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 09:07:20.277  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 09:07:20.277  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 09:07:20.282   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:07:20.288   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:07:20.288   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 09:07:20.288   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 09:07:20.307   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:07:20.320   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:20.322   874  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 09:07:20.329   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 09:07:20.340   874  4402 D DhcpClient: Receive thread started
,09-07 09:07:20.425   874  1315 E native  : do suspend false
,09-07 09:07:20.445   874  1999 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 09:07:20.463   874  4402 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172786, domain null
,09-07 09:07:20.465   874  1999 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172786 seconds
,09-07 09:07:20.469   874  1999 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 09:07:20.494   874  4402 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 09:07:20.495   874  1999 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 09:07:20.500   373   872 D CommandListener: Setting iface cfg
,09-07 09:07:20.512   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 09:07:20.513   874  1999 D DhcpClient: Scheduling renewal in 86399s
,09-07 09:07:20.518   874  1315 E native  : do suspend true
,09-07 09:07:20.541   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 09:07:20.544   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 09:07:20.546   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 09:07:20.550   874  1317 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 09:07:20.557   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 09:07:20.595   874  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 09:07:20.596   874  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 09:07:20.598   874  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 09:07:20.600   874  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 09:07:20.603   874  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 09:07:20.611   874  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 09:07:20.616   874  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-07 09:07:20.616   874  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 09:07:20.616   874  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 09:07:20.616   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 09:07:20.616   874  1317 D ConnectivityService:    accepting network in place of null
,09-07 09:07:20.617   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:07:20.617   874  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:07:20.644   874  4401 D NetlinkSocketObserver: NeighborEvent{elapsedMs=189933, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 09:07:20.661   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:20.719   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:07:20.724   874  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-07 09:07:20.724   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:20.726   874  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 09:07:20.727   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:20.759  3994  3994 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:07:20.763  3994  3994 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:07:20.764   874  4400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-07 09:07:20.770  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:07:20.777  1748  1748 D SystemUpdateService: onCreate
,09-07 09:07:20.782  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:07:20.802  1748  4411 I SystemUpdateService: active receiver: enabled
,09-07 09:07:20.807  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 09:07:20.815  1748  4411 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:07:20.818  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:07:20.822  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:07:20.825  4141  4141 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:07:20.830  4141  4141 D SprintDMHelper: simOperator: 
,09-07 09:07:20.830  4141  4141 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:07:20.832  1748  4414 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 09:07:20.832  1748  4414 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 09:07:20.833  1748  4414 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 09:07:20.834  1748  2476 I iu.UploadsManager: num queued entries: 0
09-07 09:07:20.834  1748  2476 I iu.UploadsManager: num updated entries: 0
09-07 09:07:20.835  1748  4411 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 09:07:20.835  1748  4411 I SystemUpdateService: now status is 0 (complete)
09-07 09:07:20.836  1748  4411 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:07:20.836  1748  4411 I SystemUpdateService: file has been verified
09-07 09:07:20.836  1748  4411 I SystemUpdateService: OTA package size = 12249756
,09-07 09:07:20.844  1748  2476 I iu.SyncManager: NEXT; no task
,09-07 09:07:20.850   874  4400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 07:07:20 GMT], X-Android-Received-Millis=[1473232040850], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473232040825]}
,09-07 09:07:20.851   874  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 09:07:20.852   874  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-07 09:07:20.852   874  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 09:07:20.859   874  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 09:07:20.862  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:07:20.873  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:07:20.898  1748  4411 I SystemUpdateService: showing system update notification
,09-07 09:07:20.934  1748  1748 D SystemUpdateService: onDestroy
,09-07 09:07:20.943  1526  3330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 09:07:20.943  1526  3330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 09:07:20.943  1526  3330 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:07:20.943  1526  3330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:07:20.966  1748  4414 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-07 09:07:21.007  2499  4417 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 09:07:21.392  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:07:21.429  1526  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 09:07:21.430  1526  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 09:07:21.430  1526  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:07:21.431  1526  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:07:21.470  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 09:07:21.470  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 09:07:21.471  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 09:07:22.095  3994  4398 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-07 09:07:22.095  3994  4423 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-07 09:07:22.096  3994  4423 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 09:07:22.096  3994  4398 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 09:07:22.098  3994  4398 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:07:22.098  3994  4423 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:07:22.098  3994  4398 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:07:22.099  3994  4398 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 09:07:22.099  3994  4423 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 09:07:22.102  3994  4426 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 526, name: OutgoingSocketThread/Sender)
09-07 09:07:22.106  3994  4427 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 525, name: IncomingSocketThread/Sender)
,09-07 09:07:22.109  3994  4423 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 09:07:22.111  3994  4428 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 527, name: OutgoingSocketThread/Receiver)
,09-07 09:07:22.113  3994  4429 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 528, name: IncomingSocketThread/Receiver)
,09-07 09:07:22.113  3994  4428 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 527, thread name: OutgoingSocketThread/Receiver)
09-07 09:07:22.113  3994  4428 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 09:07:22.114  3994  4428 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 527, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 09:07:22.115  3994  4429 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 528, thread name: IncomingSocketThread/Receiver)
,09-07 09:07:22.116  3994  4429 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 09:07:22.116  3994  4429 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 528, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 09:07:25.099  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 09:07:25.103  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 09:07:25.107  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3e0e691 Bundle[{}]
,09-07 09:07:25.108  3994  4042 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 09:07:25.108  3994  4042 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 09:07:25.109  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 09:07:25.110  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 09:07:25.111  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 09:07:25.112  3994  4042 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 09:07:25.122  3994  4430 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 09:07:25.123  3994  4430 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 09:07:25.134  3994  4432 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 09:07:25.135  3994  4432 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 09:07:25.135  3994  4430 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-07 09:07:25.135  3994  4430 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 09:07:25.135  3994  4432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:07:25.136  3994  4430 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 09:07:25.136  3994  4432 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 09:07:25.136  3994  4430 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 09:07:25.139  3994  4435 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 539, name: IncomingSocketThread/Sender)
09-07 09:07:25.140  3994  4436 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 540, name: OutgoingSocketThread/Sender)
,09-07 09:07:25.141  3994  4432 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 09:07:25.141  3994  4430 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 09:07:25.144  3994  4437 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 541, name: IncomingSocketThread/Receiver)
,09-07 09:07:25.145  3994  4437 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 541, thread name: IncomingSocketThread/Receiver)
09-07 09:07:25.145  3994  4437 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 09:07:25.145  3994  4437 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 541, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 09:07:25.151  3994  4438 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 542, name: OutgoingSocketThread/Receiver)
,09-07 09:07:25.152  3994  4438 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 542, thread name: OutgoingSocketThread/Receiver)
,09-07 09:07:25.152  3994  4438 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 09:07:25.153  3994  4438 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 542, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 09:07:28.147  3994  4042 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 551)
,09-07 09:07:28.151  3994  4042 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 09:07:28.151  3994  4042 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 552)
,09-07 09:07:28.157  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 09:07:28.157  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a added. We now have 2 listener(s)
,09-07 09:07:28.159  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:07:28.159  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 09:07:28.159  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:07:28.159  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:07:28.159  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb added. We now have 9 listener(s)
09-07 09:07:28.159  3994  4042 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:07:28.160  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 09:07:28.163  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:07:28.170  3994  4042 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:07:28.174  3994  4042 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:07:28.175  3994  4042 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:07:28.180  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:28.180  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:28.180  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:07:28.180  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 09:07:28.180  3994  4042 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a removed from the list
,09-07 09:07:28.180  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:07:28.181  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb removed from the list,
,09-07 09:07:28.181  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:28.181  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:28.181  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:28.182  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-07 09:07:28.183  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-07 09:07:28.183  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:07:28.183  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 09:07:28.183  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:07:28.183  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:07:28.185  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:07:28.186  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:07:28.186  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:07:28.186  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:07:28.186  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:07:28.186  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:07:28.186  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:07:28.186  3994  3994 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:07:28.187  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:07:28.191  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:07:28.191  3994  4439 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:28.191  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:07:28.197  3994  4439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:07:28.202  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:07:28.204  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:07:28.204  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:07:28.209  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:07:28.209  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:07:28.210  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-07 09:07:28.210  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:07:28.210  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:07:28.211  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:07:28.213  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:07:28.219  4345  4356 D BtGatt.GattService: registerClient() - UUID=2a1911b9-bc46-484a-9603-b7e5c253973e
,09-07 09:07:28.221  4345  4361 D BtGatt.GattService: onClientRegistered() - UUID=2a1911b9-bc46-484a-9603-b7e5c253973e, clientIf=5
,09-07 09:07:28.222  3994  4006 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:07:28.226  4345  4364 D BtGatt.AdvertiseManager: message : 0
,09-07 09:07:28.231  4345  4364 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:07:28.262  4345  4361 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:07:28.276  4345  4361 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:07:28.278  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:07:28.278  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:07:28.281  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:07:28.284  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:07:28.285  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:07:28.285  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:07:28.286  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 09:07:28.286  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:07:28.286  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:07:28.295  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:07:28.296  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:07:28.624   874  1317 D ConnectivityService: handlePromptUnvalidated 102
,09-07 09:07:28.797  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:07:28.798  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:07:28.798  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:07:34.289  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-07 09:07:34.290  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 09:07:34.290  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:07:34.290  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:07:34.291  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:07:34.293  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:07:34.293  3994  4439 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:07:34.293  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:07:34.294  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:07:34.294  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 09:07:34.294  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:07:34.294  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:07:34.293  3994  4439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:07:34.295  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:07:34.295  3994  4439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:07:34.295  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 09:07:34.298  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:07:34.298  3994  4042 D BluetoothLeScanner: could not find callback wrapper
09-07 09:07:34.298  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 09:07:34.299  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:07:34.301  4345  4364 D BtGatt.AdvertiseManager: message : 1
09-07 09:07:34.302  4345  4364 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:07:34.311  4345  4361 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-07 09:07:34.311  4345  4361 D BtGatt.GattService: Client app is not null!
,09-07 09:07:34.313  4345  4362 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:07:34.315  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:07:34.315  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:07:34.315  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:07:34.316  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:07:34.316  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:07:34.320  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:07:34.320  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:07:34.320  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:07:34.322  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:34.325  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:07:34.325  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:07:34.326  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:07:34.326  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:07:34.326  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:07:34.327  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:07:34.828  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:07:37.331  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:37.331  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:37.332  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:37.332  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a not in the list
,09-07 09:07:37.332  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:07:37.333  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb not in the list
09-07 09:07:37.333  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:37.333  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:37.334  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:37.336  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:07:37.338  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 09:07:37.338  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:07:37.339  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 09:07:37.339  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:07:37.339  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:07:37.354  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:07:37.355  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:07:37.369  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:07:37.372  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:07:37.372  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:07:37.386  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 09:07:37.387  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 09:07:37.391  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 09:07:37.396  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:07:37.406  4345  4384 D BtGatt.GattService: registerClient() - UUID=4b9eeafc-3dca-4bbd-bb6b-108a6d1b97c8
09-07 09:07:37.408  4345  4361 D BtGatt.GattService: onClientRegistered() - UUID=4b9eeafc-3dca-4bbd-bb6b-108a6d1b97c8, clientIf=5
,09-07 09:07:37.409  3994  4006 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 09:07:37.412  4345  4356 D BtGatt.GattService: start scan with filters
,09-07 09:07:37.425  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 09:07:37.426  4345  4365 D BtGatt.ScanManager: handling starting scan
,09-07 09:07:37.426  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 09:07:37.427  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 09:07:37.427  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 09:07:37.433  4345  4365 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fd97e15
,09-07 09:07:37.443  4345  4361 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 09:07:37.443  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:07:37.444  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 09:07:37.445  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 09:07:37.445  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 09:07:37.445  4345  4365 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 09:07:37.453  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:07:37.461  4345  4361 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 09:07:37.462  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:07:37.462  4345  4365 D BtGatt.ScanManager: Starting BLE batch scan
09-07 09:07:37.463  4345  4365 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 09:07:37.481  4345  4361 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 09:07:37.482  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:07:37.496  4345  4361 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 09:07:37.496  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:07:37.947  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-07 09:07:37.948  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:07:37.948  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:07:39.002  4345  4345 D BtGatt.ScanManager: awakened up at time 208291
,09-07 09:07:39.008  4345  4365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 09:07:39.074  4345  4361 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-07 09:07:39.074  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:07:39.075  4345  4361 D BtGatt.GattService: current time is 208364671657
,09-07 09:07:39.076  4345  4361 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -116, -117, 15, 18, 31, 67, 1, -128, -76, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -112, -25, -60, -2, -84, -17, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 87, 45, 110, 28, -13, -4, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0]
,09-07 09:07:39.079  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 09:07:39.082  4345  4361 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -112, -25, -60, -2, -84, -17]
,09-07 09:07:39.083  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 09:07:39.083  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 09:07:39.084  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 09:07:39.084  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
,09-07 09:07:39.085  4345  4361 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 09:07:39.085  4345  4361 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
,09-07 09:07:39.092  3994  3994 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 6], added - the peer count is 1
,09-07 09:07:39.093  3994  3994 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 6], added - the peer count is 2
,09-07 09:07:39.093  3994  3994 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 6], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-07 09:07:39.094  3994  3994 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 6], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,09-07 09:07:40.463  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:40.464  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:40.464  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:07:40.465  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a not in the list
,09-07 09:07:40.465  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:07:40.465  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 09:07:40.466  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 09:07:40.466  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 09:07:40.466  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:07:40.467  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 09:07:40.469  3994  4042 D BluetoothAdapter: STATE_ON
09-07 09:07:40.472  4345  4356 D BtGatt.GattService: stopScan() - queue size =1
,09-07 09:07:40.474  4345  4384 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 09:07:40.475  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 09:07:40.475  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 09:07:40.476  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 09:07:40.476  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 09:07:40.477  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 09:07:40.481  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:07:40.481  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:07:40.481  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:07:40.482  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:07:40.483  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:40.484  3994  4042 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-07 09:07:40.487  4345  4345 D BtGatt.ScanManager: awakened up at time 209776
09-07 09:07:40.487  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:07:40.487  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb not in the list
09-07 09:07:40.488  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:40.488  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:07:40.488  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:40.488  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:07:40.488  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:40.490  3994  4042 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-07 09:07:40.490  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-07 09:07:40.491  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:07:40.491  3994  4042 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:07:40.491  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:07:40.491  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:07:40.493  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:07:40.494  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:07:40.495  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:07:40.495  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 09:07:40.495  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:07:40.495  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:07:40.496  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:07:40.496  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:07:40.503  3994  4442 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:07:40.504  4345  4361 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 09:07:40.505  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:07:40.505  4345  4365 D BtGatt.ScanManager: stopping BLe Batch
09-07 09:07:40.506  3994  4442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:07:40.507  3994  4042 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:07:40.507  3994  4042 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:07:40.511  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:07:40.511  4345  4361 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 09:07:40.511  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:07:40.512  4345  4365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 09:07:40.512  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:07:40.512  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:07:40.514  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 09:07:40.514  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:07:40.514  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-07 09:07:40.514  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:07:40.514  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:07:40.515  3994  4042 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:07:40.515  3994  4042 D BluetoothAdapter: STATE_ON
,09-07 09:07:40.517  4345  4361 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 09:07:40.517  4345  4361 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:07:40.518  4345  4355 D BtGatt.GattService: registerClient() - UUID=11e6991b-8493-4b0a-b331-8b9beb43aa83
09-07 09:07:40.518  4345  4361 D BtGatt.GattService: onClientRegistered() - UUID=11e6991b-8493-4b0a-b331-8b9beb43aa83, clientIf=5
09-07 09:07:40.519  3994  4006 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:07:40.519  4345  4364 D BtGatt.AdvertiseManager: message : 0
,09-07 09:07:40.521  4345  4364 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:07:40.532  4345  4361 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:07:40.538  4345  4361 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:07:40.539  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:07:40.539  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:07:40.540  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:07:40.542  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:07:40.543  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:07:40.543  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:07:40.543  3994  3994 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:07:40.543  3994  3994 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:07:40.543  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:07:40.546  3994  3994 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 09:07:40.546  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:07:40.944  1874  1910 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 09:07:40.944  1874  1910 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 09:07:40.994  1526  1526 I ConfigService: onCreate
,09-07 09:07:41.047  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:07:41.047  3994  3994 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:07:41.048  3994  3994 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:07:46.076  1526  1526 I ConfigService: onDestroy
,09-07 09:07:46.546  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:07:46.546  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:07:46.546  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:07:46.546  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:07:46.548  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:07:46.548  3994  4042 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:07:46.548  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a not in the list
09-07 09:07:46.549  3994  3994 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:07:46.549  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:07:46.549  3994  4442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:07:46.549  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:07:46.549  3994  4442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:07:46.549  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 09:07:46.550  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:07:46.550  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:07:46.551  3994  4442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:07:46.553  3994  4042 D BluetoothAdapter: STATE_ON
09-07 09:07:46.554  3994  4042 D BluetoothLeScanner: could not find callback wrapper
09-07 09:07:46.554  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:07:46.554  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-07 09:07:46.557  4345  4364 D BtGatt.AdvertiseManager: message : 1
09-07 09:07:46.559  4345  4364 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:07:46.570  4345  4361 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:07:46.571  4345  4361 D BtGatt.GattService: Client app is not null!
,09-07 09:07:46.573  4345  4384 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:07:46.575  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 09:07:46.575  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:07:46.576  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:07:46.577  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:07:46.578  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:07:46.581  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:07:46.582  3994  4042 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:07:46.582  3994  4042 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:07:46.586  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:46.592  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb not in the list
,09-07 09:07:46.592  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:07:46.592  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:46.592  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:07:46.592  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:07:46.593  3994  3994 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:07:46.593  3994  3994 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:07:46.593  3994  4042 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:07:46.593  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:07:46.593  3994  3994 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:07:46.594  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:46.594  3994  4042 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ce579a not in the list
09-07 09:07:46.594  3994  4042 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:07:46.594  3994  4042 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca868cb not in the list
09-07 09:07:46.594  3994  4042 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:07:46.594  3994  4042 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:07:46.594  3994  4042 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:07:46.595  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 09:07:46.595  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:07:46.595  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 09:07:46.596  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:07:46.596  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 09:07:46.596  3994  4042 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 09:07:46.604  3994  4447 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 572, name: My test thread name)
,09-07 09:07:47.095  3994  3994 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:07:48.603  3994  4042 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 572
,09-07 09:07:48.604  3994  4042 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 572, name: My test thread name)
,09-07 09:07:48.610  3994  4448 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 573, name: My test thread name)
09-07 09:07:48.610  3994  4448 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 573, thread name: My test thread name)
,09-07 09:07:48.611  3994  4448 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 573, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-07 09:07:48.615  3994  4042 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:07:48.624  3994  4449 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 577, name: My test thread name)
,09-07 09:07:48.625  3994  4449 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 577, thread name: My test thread name): Test exception.
,09-07 09:07:48.626  3994  4449 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 577, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-07 09:07:48.628  3994  4042 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
09-07 09:07:48.629  3994  4042 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
,09-07 09:07:48.629  3994  4042 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-07 09:07:48.629  3994  4042 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 09:07:48.630  3994  4042 D com.test.thalitest.ThaliTestRunner: Total duration: 81442 ms
,09-07 09:07:48.634  3994  4042 I jxcore-log: Total number of executed tests:  82
09-07 09:07:48.634  3994  4042 I jxcore-log: 
09-07 09:07:48.636  3994  4042 I jxcore-log: Number of passed tests:  82
09-07 09:07:48.636  3994  4042 I jxcore-log: 
,09-07 09:07:48.636  3994  4042 I jxcore-log: Number of failed tests:  0
09-07 09:07:48.636  3994  4042 I jxcore-log: 
,09-07 09:07:48.639  3994  4042 I jxcore-log: Number of ignored tests:  0
09-07 09:07:48.639  3994  4042 I jxcore-log: 
09-07 09:07:48.639  3994  4042 I jxcore-log: Total duration:  81442
09-07 09:07:48.639  3994  4042 I jxcore-log: 
,09-07 09:07:48.645  3994  4042 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 09:07:48.645  3994  4042 I jxcore-log: 
09-07 09:07:48.645  3994  4447 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 572, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-07 09:07:48.648  3994  4042 I jxcore-log: My device name is: motorola-Nexus 6
09-07 09:07:48.648  3994  4042 I jxcore-log: 
09-07 09:07:48.651  3994  4042 I jxcore-log: WARN testUtils: myNameCallback not set!
09-07 09:07:48.651  3994  4042 I jxcore-log: 
09-07 09:07:48.653  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.653  3994  4042 I jxcore-log: 
,09-07 09:07:48.655  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.655  3994  4042 I jxcore-log: 
09-07 09:07:48.656  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.656  3994  4042 I jxcore-log: 
,09-07 09:07:48.658  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.658  3994  4042 I jxcore-log: 
,09-07 09:07:48.660  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.660  3994  4042 I jxcore-log: 
09-07 09:07:48.663  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.663  3994  4042 I jxcore-log: 
09-07 09:07:48.664  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.664  3994  4042 I jxcore-log: 
09-07 09:07:48.665  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.665  3994  4042 I jxcore-log: 
09-07 09:07:48.665  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.665  3994  4042 I jxcore-log: 
09-07 09:07:48.666  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.666  3994  4042 I jxcore-log: 
09-07 09:07:48.667  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.667  3994  4042 I jxcore-log: 
09-07 09:07:48.668  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.668  3994  4042 I jxcore-log: 
09-07 09:07:48.669  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.669  3994  4042 I jxcore-log: 
,09-07 09:07:48.669  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.669  3994  4042 I jxcore-log: 
,09-07 09:07:48.670  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.670  3994  4042 I jxcore-log: 
,09-07 09:07:48.671  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.671  3994  4042 I jxcore-log: 
,09-07 09:07:48.672  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.672  3994  4042 I jxcore-log: 
,09-07 09:07:48.673  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.673  3994  4042 I jxcore-log: 
,09-07 09:07:48.674  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.674  3994  4042 I jxcore-log: 
,09-07 09:07:48.675  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.675  3994  4042 I jxcore-log: 
09-07 09:07:48.676  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.676  3994  4042 I jxcore-log: 
,09-07 09:07:48.676  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.676  3994  4042 I jxcore-log: 
,09-07 09:07:48.677  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.677  3994  4042 I jxcore-log: 
09-07 09:07:48.678  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.678  3994  4042 I jxcore-log: 
09-07 09:07:48.679  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.679  3994  4042 I jxcore-log: 
,09-07 09:07:48.680  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.680  3994  4042 I jxcore-log: 
,09-07 09:07:48.681  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.681  3994  4042 I jxcore-log: 
,09-07 09:07:48.682  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.682  3994  4042 I jxcore-log: 
09-07 09:07:48.682  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.682  3994  4042 I jxcore-log: 
09-07 09:07:48.683  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:07:48.683  3994  4042 I jxcore-log: 
09-07 09:07:48.684  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.684  3994  4042 I jxcore-log: 
09-07 09:07:48.685  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 09:07:48.685  3994  4042 I jxcore-log: 
09-07 09:07:48.686  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.686  3994  4042 I jxcore-log: 
09-07 09:07:48.688  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:07:48.688  3994  4042 I jxcore-log: 
09-07 09:07:48.689  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.689  3994  4042 I jxcore-log: 
,09-07 09:07:48.690  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.690  3994  4042 I jxcore-log: 
09-07 09:07:48.691  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-07 09:07:48.691  3994  4042 I jxcore-log: 
09-07 09:07:48.693  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 09:07:48.693  3994  4042 I jxcore-log: 
09-07 09:07:48.695  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 09:07:48.695  3994  4042 I jxcore-log: 
09-07 09:07:48.695  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:07:48.695  3994  4042 I jxcore-log: 
09-07 09:07:48.696  3994  4042 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:07:48.696  3994  4042 I jxcore-log: 
,09-07 09:07:49.311  4450  4450 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 09:07:49.318  4450  4450 D AndroidRuntime: CheckJNI is OFF
,09-07 09:07:49.365  4450  4450 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 09:07:49.409  4450  4450 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 09:07:49.430  4450  4450 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 09:07:49.442   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 09:07:49.443   874   887 I ActivityManager: Killing 3994:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 09:07:49.546   874  2099 I WindowState: WIN DEATH: Window{8b304ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 09:07:49.547   874  1952 D GraphicsStats: Buffer count: 2
09-07 09:07:49.546   874  1316 D WifiService: Client connection lost with reason: 4
,09-07 09:07:49.599   874   897 W PackageSettings: Skipping PackageSetting{a898ee com.example.hello/10273} due to missing metadata
,09-07 09:07:49.627   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-07 09:07:49.627   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 09:07:49.628   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-07 09:07:49.628   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 09:07:49.628   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:49.628   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:49.628   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:07:49.628   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 09:07:49.628   874   887 I ActivityManager:   Force finishing activity ActivityRecord{4a6def u0 com.test.thalitest/.MainActivity t4}
09-07 09:07:49.629   874   897 I art     : Starting a blocking GC Explicit
,09-07 09:07:49.634   874  2092 W ActivityManager: Spurious death for ProcessRecord{bb2cedf 0:com.test.thalitest/u0a0}, curProc for 3994: null
,09-07 09:07:49.685   874   897 I art     : Explicit concurrent mark sweep GC freed 16695(1116KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.099ms total 56.171ms
,09-07 09:07:49.718   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 09:07:49.721  4450  4450 I art     : System.exit called, status: 0
,09-07 09:07:49.721  4450  4450 I AndroidRuntime: VM exiting with result code 0.
09-07 09:07:49.724   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 09:07:49.739   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-07 09:07:49.748  4345  4345 D BluetoothMapAppObserver: onReceive
09-07 09:07:49.748  4345  4345 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-07 09:07:49.749  2138  2289 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 09:07:49.753   874  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 09:07:49.761  3824  3824 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-07 09:07:49.773  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 09:07:49.782  1874  4462 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 09:07:49.788  1874  4462 I Decoder : createOrResetDecoder
,09-07 09:07:49.811  1923  1923 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 09:07:49.812   874  1945 I ActivityManager: Start proc 4465:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 09:07:49.824  1526  1526 I ConfigService: onCreate
,09-07 09:07:49.846  1874  4462 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 09:07:49.869   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 09:07:49.875   874  1389 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3994 uid 10000
,09-07 09:07:49.877  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-07 09:07:49.877  4465  4465 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 09:07:49.886  1874  4462 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-07 09:07:49.888  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-07 09:07:49.888  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-07 09:07:49.890  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-07 09:07:49.890  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-07 09:07:49.891  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 09:07:49.891  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-07 09:07:49.899  1874  4462 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-07 09:07:49.899  1874  4462 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 09:07:49.899  1874  4462 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-07 09:07:49.900  1874  4462 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-07 09:07:49.900  1874  4462 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 09:07:49.900  1874  4462 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 09:07:49.901  1946  2025 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 09:07:49.902   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-07 09:07:49.902   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 09:07:49.902   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 09:07:49.902   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 09:07:49.902   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 09:07:49.902   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 09:07:49.902   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 09:07:49.902   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:49.902   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:49.902   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:07:49.907   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 09:07:49.907   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 09:07:49.907   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:49.907   874   887 E DropBoxManagerService: 	... 13 more
,09-07 09:07:49.914   874  2096 I ActivityManager: Start proc 4479:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-07 09:07:49.915  1946  2025 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 09:07:49.915  1946  2025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1946
09-07 09:07:49.915  1946  2025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:49.915  1946  2025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:07:49.917   874  4484 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:49.917   874  4484 E DropBoxManagerService: 	... 5 more
,09-07 09:07:49.917   874  1422 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 09:07:49.921  1946  2025 I Process : Sending signal. PID: 1946 SIG: 9
,09-07 09:07:49.952  4465  4465 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 09:07:49.965   874  1952 D GraphicsStats: Buffer count: 1
,09-07 09:07:49.965   874  2097 I WindowState: WIN DEATH: Window{3cd55d0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-07 09:07:49.973   874  2091 I ActivityManager: Start proc 4496:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-07 09:07:49.978   874  1952 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1946) has died
,09-07 09:07:49.979   874  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-07 09:07:49.980   874  1952 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 09:07:49.982  4465  4495 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 09:07:50.001   874   887 I ActivityManager: Start proc 4509:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:07:50.028  4496  4496 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 09:07:50.048  4509  4509 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:50.048  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:07:50.048  4509  4509 D AndroidRuntime: Shutting down VM
,09-07 09:07:50.053  4509  4509 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:07:50.053  4509  4509 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4509
09-07 09:07:50.053  4509  4509 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.053  4509  4509 E AndroidRuntime: ,	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:07:50.053  4509  4509 E AndroidRuntime: 	... 10 more
,09-07 09:07:50.054   874  1943 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:07:50.055  4509  4509 I Process : Sending signal. PID: 4509 SIG: 9
09-07 09:07:50.056   874  4524 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:07:50.056   874  4524 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:50.056   874  4524 E DropBoxManagerService: 	... 5 more
,09-07 09:07:50.075  1748  4523 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 09:07:50.075  1748  4523 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 09:07:50.080  1748  4523 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 09:07:50.081  1748  4523 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 09:07:50.086  4465  4493 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.086  4465  4493 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.086  4465  4493 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:07:50.089  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-07 09:07:50.091  1526  1526 D AndroidRuntime: Shutting down VM
09-07 09:07:50.092  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:07:50.092  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
09-07 09:07:50.092  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 09:07:50.092  1526  1526 E AndroidRuntime: 	... 8 more
,09-07 09:07:50.094   874  4526 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:07:50.094   874  4526 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:50.094   874  4526 E DropBoxManagerService: 	... 5 more
,09-07 09:07:50.095  1526  1526 I Process : Sending signal. PID: 1526 SIG: 9
09-07 09:07:50.096   874  2099 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4509) has died
09-07 09:07:50.097   874  2099 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 09:07:50.111   874   887 I ActivityManager: Start proc 4528:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:07:50.112   874  1976 I ActivityManager: Killing 3876:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 09:07:50.141   874  1316 D WifiService: Client connection lost with reason: 4
09-07 09:07:50.156  4465  4493 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 09:07:50.162  4465  4495 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.162  4465  4495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 09:07:50.162  4465  4495 E AndroidRuntime: Process: android.process.acore, PID: 4465
09-07 09:07:50.162  4465  4495 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.162  4465  4495 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.162  4465  4495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:07:50.164  4465  4493 I Process : Sending signal. PID: 4465 SIG: 9
,09-07 09:07:50.176   874  2099 I ActivityManager: Process com.google.process.gapps (pid 1526) has died
,09-07 09:07:50.177   874  2099 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-07 09:07:50.177   874  2099 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,09-07 09:07:50.177   874  2099 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,09-07 09:07:50.187   874  4540 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:07:50.187   874  4540 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:50.187   874  4540 E DropBoxManagerService: 	... 5 more
,09-07 09:07:50.204   874   885 I ActivityManager: Start proc 4541:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-07 09:07:50.205  1748  1748 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-07 09:07:50.219   874  1976 I ActivityManager: Process android.process.acore (pid 4465) has died
09-07 09:07:50.219   874  1976 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 20958ms
,09-07 09:07:50.221  4528  4528 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:50.221  4528  4528 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:07:50.222  4528  4528 D AndroidRuntime: Shutting down VM
,09-07 09:07:50.237  4528  4528 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:07:50.237  4528  4528 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4528
09-07 09:07:50.237  4528  4528 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:07:50.237  4528  4528 E AndroidRuntime: 	... 10 more
09-07 09:07:50.242  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 09:07:50.243  1748  1748 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 09:07:50.246   874  3297 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 09:07:50.247  4528  4528 I Process : Sending signal. PID: 4528 SIG: 9
09-07 09:07:50.248   874  4555 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:07:50.248   874  4555 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:07:50.248   874  4555 E DropBoxManagerService: 	... 5 more

```
