#### Test 82912030648592a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 16:30:44.731  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 16:30:44.744  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 16:30:44.748  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 16:30:44.794  1507  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 16:30:44.795  1507  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 16:30:44.795  1507  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:30:44.795  1507  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 16:30:44.832  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 16:30:44.833  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 16:30:44.835  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-08 16:30:45.748  3740  3740 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 16:30:45.753  3740  3740 D AndroidRuntime: CheckJNI is OFF
09-08 16:30:45.796  3740  3740 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 16:30:45.848  3740  3740 I Radio-JNI: register_android_hardware_Radio DONE
09-08 16:30:45.871  3740  3740 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 16:30:45.875   873  1389 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 16:30:45.907  2044  2228 W SearchService: Abort, client detached.
09-08 16:30:45.920  2044  2044 I HotwordDetector: Closing mic
09-08 16:30:45.921  2044  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@de82dbb
09-08 16:30:45.922  2044  2353 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 16:30:45.923  3740  3740 D AndroidRuntime: Shutting down VM
09-08 16:30:45.938   873  1995 I ActivityManager: Start proc 3750:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 16:30:45.969   376  2355 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 16:30:45.970   376  2355 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 16:30:45.974   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 16:30:45.977  2044  2346 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 16:30:45.977  2044  2352 I MicroRecognitionRnrImpl: Detection finished
09-08 16:30:46.022  3750  3750 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 16:30:46.044  3750  3750 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 16:30:46.052  3750  3750 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 46-49)
09-08 16:30:46.052  3750  3750 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 16:30:46.068  3750  3750 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b83b9a}
09-08 16:30:46.069  3750  3750 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 16:30:46.069  3750  3750 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 16:30:46.076  3750  3750 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 16:30:46.077  3750  3750 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 16:30:46.089  3750  3750 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 16:30:46.099  3750  3750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 16:30:46.099  3750  3750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 16:30:46.099  3750  3750 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 16:30:46.099  3750  3750 I Adreno  : Build Date                       : 10/20/15
09-08 16:30:46.099  3750  3750 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 16:30:46.099  3750  3750 I Adreno  : Local Branch                     : M14
09-08 16:30:46.099  3750  3750 I Adreno  : Remote Branch                    : 
09-08 16:30:46.099  3750  3750 I Adreno  : Remote Branch                    : 
09-08 16:30:46.099  3750  3750 I Adreno  : Reconstruct Branch               : 
,09-08 16:30:46.164   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f60a3e7:true
,09-08 16:30:46.200  3750  3750 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 16:30:46.213  3750  3750 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 16:30:46.278  3750  3788 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 16:30:46.288  3750  3775 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 16:30:46.337  3750  3788 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 16:30:46.431   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms
,09-08 16:30:46.432  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-08 16:30:46.493  3750  3750 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3750
,09-08 16:30:46.585  3750  3750 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 16:30:46.735   873  2057 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 16:30:46.742  3750  3791 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700792016
,09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 16:30:46.747  3750  3791 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9697b9 added. We now have 1 listener(s)
,09-08 16:30:46.751  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 16:30:46.752  3750  3791 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:30:46.753  3750  3791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 16:30:46.753  3750  3791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 16:30:46.758  3750  3791 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3e49ac added. We now have 1 listener(s)
09-08 16:30:46.758  3750  3791 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:30:46.761   873  1304 D WifiService: New client listening to asynchronous messages
,09-08 16:30:46.762  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 16:30:46.762  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 16:30:46.762  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 16:30:46.762  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 16:30:46.762  3750  3791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 16:30:46.783   873  2057 I ActivityManager: Killing 3091:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-08 16:30:46.823  3750  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:30:46.824  3750  3791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 16:30:46.829  3750  3791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:30:46.830  3750  3791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:30:46.830  3750  3791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 16:30:46.830  3750  3791 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:30:46.832  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:30:46.833  3750  3791 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 16:30:46.835  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:30:46.970  3750  3750 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 16:30:47.788  3750  3799 W jxcore-log: Initializing JXcore engine
,09-08 16:30:47.788  3750  3799 W jxcore-log: JXcore engine is ready
,09-08 16:30:47.824  3799  3799 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8959 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 16:30:47.824  3799  3799 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13315]" dev="sockfs" ino=13315 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 16:30:47.824  3799  3799 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-08 16:30:47.824  3799  3799 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25114]" dev="sockfs" ino=25114 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 16:30:47.838  3750  3799 W jxcore-log: Starting JXcore engine
,09-08 16:30:47.951  3750  3799 W jxcore-log: Platform android
09-08 16:30:47.951  3750  3799 W jxcore-log: 
,09-08 16:30:47.952  3750  3799 W jxcore-log: Process ARCH arm
09-08 16:30:47.952  3750  3799 W jxcore-log: 
,09-08 16:30:48.266  3750  3799 I jxcore-log: JXcore Cordova bridge is ready!
09-08 16:30:48.266  3750  3799 I jxcore-log: 
,09-08 16:30:48.267  3750  3799 W jxcore-log: JXcore engine is started
,09-08 16:30:48.274  3750  3791 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 16:30:48.281  3750  3750 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 16:30:49.739   873  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 16:30:49.999   873  2092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123996, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:30:51.908  3018  3807 V KeepSync: Connecting to GoogleApiClient
09-08 16:30:51.909   873  1681 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 16:30:51.980  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:30:51.981  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:30:52.015  1507  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 16:30:52.016  1507  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 16:30:52.016  1507  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:30:52.016  1507  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:30:52.032  1699  3808 V BaseAuthAsyncOperation: access token request failed
,09-08 16:30:52.033  3018  3807 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 16:30:52.084  1507  3611 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 16:30:52.085  1507  3611 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 16:30:52.086  1507  3611 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:30:52.086  1507  3611 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:30:52.110  3018  3807 E KeepSync: IOException
09-08 16:30:52.110  3018  3807 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 16:30:52.110  3018  3807 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:30:52.110  3018  3807 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 16:30:52.110  3018  3807 E KeepSync: 	... 10 more
,09-08 16:30:52.110  3018  3807 W KeepSync: Sync result 2
,09-08 16:30:52.125   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125726, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:31:02.828  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 16:31:02.828  3750  3799 I jxcore-log: 
,09-08 16:31:02.831  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 16:31:02.831  3750  3799 I jxcore-log: 
,09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:02.841  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:02.844  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:02.846  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 16:31:02.846  3750  3799 I jxcore-log: 
09-08 16:31:02.848  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 16:31:02.848  3750  3799 I jxcore-log: 
,09-08 16:31:03.210  3750  3799 I jxcore-log: Running unit tests
09-08 16:31:03.210  3750  3799 I jxcore-log: 
,09-08 16:31:03.211  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:31:03.211  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7d3c7e added. We now have 2 listener(s)
,09-08 16:31:03.212  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:31:03.213  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:31:03.213  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 16:31:03.213  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:31:03.213  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13555df added. We now have 2 listener(s)
09-08 16:31:03.213  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:03.214  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 16:31:03.219  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:03.236  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:03.245  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:03.246  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:31:03.247  3750  3799 D executeNativeTests: Running unit tests
09-08 16:31:03.248  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.259  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.344  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:31:03.344  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 added. We now have 3 listener(s)
,09-08 16:31:03.345  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:31:03.345  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 16:31:03.345  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:31:03.345  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:03.345  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a added. We now have 3 listener(s)
09-08 16:31:03.345  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:31:03.346  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:31:03.358  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:03.371  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:03.377  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:03.378  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:31:03.382  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.385  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 16:31:03.385  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:03.385  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 16:31:03.386  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:03.386  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.390  3750  3799 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 16:31:03.391  3750  3799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 16:31:03.392  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 16:31:03.392  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:31:03.392  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 16:31:03.393  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 16:31:03.394  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:03.395  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:03.395  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:03.396  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:03.396  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:03.397  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:31:03.397  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:31:03.399  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 removed from the list
09-08 16:31:03.399  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:03.399  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a removed from the list
09-08 16:31:03.399  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:03.399  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:03.400  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:03.402  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:03.404  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:03.404  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:03.404  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:03.405  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:03.406  3750  3799 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 16:31:03.407  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:03.407  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:31:03.407  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:31:03.408  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:03.408  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:03.408  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.409  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:03.409  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:03.409  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:03.409  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:03.409  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:03.409  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.409  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:03.409  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.411  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:31:03.411  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:03.411  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:03.412  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:03.418  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 16:31:03.418  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 16:31:03.418  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 16:31:03.419  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 16:31:03.420  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-08 16:31:03.421  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 16:31:03.421  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:03.421  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:03.422  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:03.422  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:03.422  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:03.422  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.422  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
,09-08 16:31:03.422  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:03.422  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:03.422  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:03.422  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:03.422  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.423  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:03.423  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:03.424  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:03.424  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:03.424  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:03.424  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:03.425  3750  3799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 16:31:03.428  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:03.437  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:03.443  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:03.443  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:31:03.443  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:31:03.444  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 16:31:03.444  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:31:03.444  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:31:03.444  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 16:31:03.450  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.454  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:31:03.454  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:31:03.456  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:03.466  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:31:03.469  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 16:31:03.470  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:31:03.475  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 16:31:03.479  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 16:31:03.479  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 16:31:03.479  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:31:03.480  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:31:03.481  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:31:03.487  2676  2818 D BtGatt.GattService: registerClient() - UUID=92df6f3d-a71d-4f80-b5b5-bd0c1bc30783
,09-08 16:31:03.488  2676  2700 D BtGatt.GattService: onClientRegistered() - UUID=92df6f3d-a71d-4f80-b5b5-bd0c1bc30783, clientIf=5
,09-08 16:31:03.489  3750  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:31:03.490  2676  2688 D BtGatt.GattService: start scan with filters
,09-08 16:31:03.493  2676  2704 D BtGatt.ScanManager: handling starting scan
09-08 16:31:03.493  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 16:31:03.495  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 16:31:03.495  2676  2704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
09-08 16:31:03.495  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:31:03.495  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 16:31:03.499  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:31:03.499  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 16:31:03.500  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:31:03.502  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:31:03.502  2676  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 16:31:03.502  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:03.503  2676  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:31:03.507  3750  3799 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 16:31:03.510  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:31:03.510  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:03.510  2676  2704 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:31:03.510  2676  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:31:03.520  2676  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:31:03.520  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:03.526  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 16:31:03.526  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:04.003  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:31:04.004  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:31:04.004  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:31:04.504   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 16:31:05.033  2676  2676 D BtGatt.ScanManager: awakened up at time 139031
,09-08 16:31:05.036  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:05.114  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 16:31:05.114  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:05.114  2676  2700 D BtGatt.GattService: current time is 139113074387
09-08 16:31:05.115  2676  2700 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -95, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:31:05.117  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:31:05.117  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 16:31:05.118  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:31:05.118  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:31:05.118  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:31:05.118  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:31:05.244  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:05.253  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:05.256  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:05.292  1507  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 16:31:05.292  1507  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 16:31:05.292  1507  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:31:05.292  1507  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:05.323  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 16:31:05.324  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 16:31:05.324  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 16:31:06.621  2676  2676 D BtGatt.ScanManager: awakened up at time 140619
,09-08 16:31:06.623  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:06.639  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:31:06.640  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:07.540   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 16:31:08.142  2676  2676 D BtGatt.ScanManager: awakened up at time 142140
,09-08 16:31:08.145  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:08.200  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 16:31:08.200  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:08.200  2676  2700 D BtGatt.GattService: current time is 142198903965,
,09-08 16:31:08.201  2676  2700 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -85, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -89, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
,09-08 16:31:08.202  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-08 16:31:08.203  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-08 16:31:08.203  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-08 16:31:08.204  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:31:08.205  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:31:08.207  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-08 16:31:08.516  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:08.517  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:08.517  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 16:31:08.517  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:08.518  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 16:31:08.518  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:31:08.518  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:31:08.519  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:31:08.519  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:31:08.521  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:31:08.521  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 16:31:08.524  3750  3799 D BluetoothAdapter: STATE_ON
09-08 16:31:08.526  2676  2688 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:31:08.529  2676  2686 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 16:31:08.532  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 16:31:08.532  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 16:31:08.533  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 16:31:08.533  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:31:08.533  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:31:08.537  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:31:08.539  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 16:31:08.539  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:31:08.540  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:31:08.542  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:31:08.546  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:31:08.546  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:31:08.547  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:31:08.547  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:08.548  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:08.548  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:31:08.548  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
,09-08 16:31:08.549  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:08.549  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:08.550  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:08.550  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:08.550  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 16:31:08.551  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:08.551  2676  2704 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:31:08.562  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:31:08.562  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:08.563  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:08.570  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:31:08.571  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:09.048  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:31:10.558   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 16:31:13.552  3750  3799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 16:31:13.558  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:13.574  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:13.582  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:13.583  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:31:13.584  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:31:13.584  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 16:31:13.585  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:31:13.585  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:31:13.586  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 16:31:13.598  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:31:13.598  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:31:13.599  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:13.607  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:13.615  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:31:13.618  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 16:31:13.618  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:31:13.629  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 16:31:13.629  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:31:13.630  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:31:13.633  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:31:13.640  2676  2686 D BtGatt.GattService: registerClient() - UUID=0a01ec27-b7be-4aa5-bc37-d56dcc95838c
,09-08 16:31:13.641  2676  2700 D BtGatt.GattService: onClientRegistered() - UUID=0a01ec27-b7be-4aa5-bc37-d56dcc95838c, clientIf=5
,09-08 16:31:13.642  3750  3762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:31:13.643  2676  2810 D BtGatt.GattService: start scan with filters
,09-08 16:31:13.651  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:31:13.652  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 16:31:13.652  2676  2704 D BtGatt.ScanManager: handling starting scan
,09-08 16:31:13.652  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:31:13.652  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 16:31:13.664  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:31:13.665  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:31:13.665  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 16:31:13.673  2676  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 16:31:13.673  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 16:31:13.673  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.674  2676  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:31:13.680  3750  3799 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 16:31:13.686  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:13.686  3750  3799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 16:31:13.687  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:13.687  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:31:13.687  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:13.687  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:31:13.688  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:31:13.688  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:31:13.688  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:31:13.689  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:31:13.689  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:31:13.689  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 16:31:13.690  3750  3799 D BluetoothAdapter: STATE_ON
09-08 16:31:13.691  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:31:13.691  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:13.692  2676  2810 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:31:13.692  2676  2704 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:31:13.692  2676  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 16:31:13.694  2676  2818 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:31:13.695  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:31:13.695  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:31:13.695  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 16:31:13.696  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:31:13.696  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:31:13.699  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:31:13.699  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:31:13.700  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:31:13.700  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:31:13.701  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:31:13.704  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:13.704  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:13.704  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:31:13.704  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:31:13.704  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:13.704  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:13.704  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:31:13.704  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:13.704  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:13.704  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:13.704  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:31:13.705  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:13.705  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:13.706  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:13.706  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:13.706  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:13.707  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:13.707  3750  3799 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 16:31:13.710  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:13.715  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:13.716  2676  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:31:13.716  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:13.717  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:13.718  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:31:13.718  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:31:13.718  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 16:31:13.718  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 16:31:13.718  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:31:13.718  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:31:13.722  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
09-08 16:31:13.722  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:31:13.723  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:13.726  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:13.727  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 16:31:13.728  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 16:31:13.728  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.728  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:31:13.729  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:31:13.734  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 16:31:13.734  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:31:13.734  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 16:31:13.735  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:31:13.738  2676  2688 D BtGatt.GattService: registerClient() - UUID=ac0e81a3-1340-495c-a1ef-434dd5158dd7
,09-08 16:31:13.739  2676  2700 D BtGatt.GattService: onClientRegistered() - UUID=ac0e81a3-1340-495c-a1ef-434dd5158dd7, clientIf=5
09-08 16:31:13.739  3750  3761 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 16:31:13.740  2676  2686 D BtGatt.GattService: start scan with filters
,09-08 16:31:13.742  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:31:13.742  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 16:31:13.743  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:31:13.743  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 16:31:13.743  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:31:13.743  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.743  2676  2704 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:31:13.745  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:31:13.746  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:31:13.746  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:31:13.748  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:31:13.750  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:31:13.750  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.750  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 16:31:13.750  3750  3799 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 16:31:13.755  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:31:13.755  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.757  2676  2704 D BtGatt.ScanManager: handling starting scan
,09-08 16:31:13.762  2676  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 16:31:13.763  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.763  2676  2704 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:31:13.767  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 16:31:13.768  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:13.768  2676  2704 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:31:13.768  2676  2704 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:31:13.779  2676  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:31:13.780  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:13.785  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 16:31:13.790  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:14.247  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:31:14.247  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:31:14.248  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:31:15.294  2676  2676 D BtGatt.ScanManager: awakened up at time 149292
,09-08 16:31:15.297  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:15.332  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-08 16:31:15.332  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:15.333  2676  2700 D BtGatt.GattService: current time is 149331549936
09-08 16:31:15.334  2676  2700 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -93, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:31:15.335  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:31:15.335  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 16:31:15.336  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:31:15.337  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:31:15.338  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:31:15.339  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:31:16.445   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 16:31:16.455  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-08 16:31:16.472   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 16:31:16.472   873   893 I Adreno  : Build Date                       : 10/20/15
09-08 16:31:16.472   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 16:31:16.472   873   893 I Adreno  : Local Branch                     : M14
09-08 16:31:16.472   873   893 I Adreno  : Remote Branch                    : 
09-08 16:31:16.472   873   893 I Adreno  : Remote Branch                    : 
09-08 16:31:16.472   873   893 I Adreno  : Reconstruct Branch               : 
,09-08 16:31:16.512   281  2013 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (290 us)
,09-08 16:31:16.617   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 16:31:16.839  2676  2676 D BtGatt.ScanManager: awakened up at time 150837
,09-08 16:31:16.842  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:16.885  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-08 16:31:16.885  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:16.886  2676  2700 D BtGatt.GattService: current time is 150884449830
,09-08 16:31:16.887  2676  2700 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 16:31:16.887  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:31:16.889  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:31:16.890  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 16:31:17.183  3750  3750 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 16:31:17.183  3750  3750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 16:31:17.218   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 16:31:17.219  3750  3750 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dbaa3f2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@dd32fbf, 16908290=android.view.AbsSavedState$1@dd32fbf}, android:focusedViewId=100}]}]
,09-08 16:31:17.219  3750  3750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 16:31:17.221  3750  3750 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 16:31:17.222  3750  3750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 16:31:17.232   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-08 16:31:17.236   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-08 16:31:17.236   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-08 16:31:17.236   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-08 16:31:17.263   873   882 I art     : Background partial concurrent mark sweep GC freed 27678(1788KB) AllocSpace objects, 7(184KB) LOS objects, 33% free, 29MB/43MB, paused 887us total 107.293ms
,09-08 16:31:17.460   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 16:31:17.464   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 16:31:17.465   873  1331 D SurfaceControl: Excessive delay in setPowerMode(): 229ms
,09-08 16:31:17.475   873   893 I DreamManagerService: Entering dreamland.
,09-08 16:31:17.476   873   893 I PowerManagerService: Dozing...
,09-08 16:31:17.479   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 16:31:17.519   376  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-08 16:31:17.519   376  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 16:31:17.522  2676  2676 D BtGatt.ScanManager: awakened up at time 151520
,09-08 16:31:17.522  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:17.530   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:31:17.538  1968  3819 D NfcService: Discovery configuration equal, not updating.
09-08 16:31:17.540  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-08 16:31:17.541  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:31:17.541  2676  2700 D BtGatt.GattService: current time is 151539259479
,09-08 16:31:17.541  2676  2700 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -79, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:31:17.541  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 16:31:17.542  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:31:17.542  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:31:17.542  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:31:17.543   873  1303 E native  : do suspend false
,09-08 16:31:17.560   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 16:31:17.572   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:31:17.576   873  1303 E native  : do suspend true
,09-08 16:31:17.660   376  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 16:31:17.660   376  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 16:31:18.034   873  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-08 16:31:18.751  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:18.752  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:31:18.752  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:31:18.752  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:18.753  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:31:18.753  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:31:18.753  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:31:18.753  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:31:18.754  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:31:18.754  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:31:18.754  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 16:31:18.757  3750  3799 D BluetoothAdapter: STATE_ON
09-08 16:31:18.759  2676  2810 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:31:18.761  2676  2818 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:31:18.762  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:31:18.763  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:31:18.763  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 16:31:18.763  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 16:31:18.764  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:31:18.767  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:31:18.768  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,09-08 16:31:18.768  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 16:31:18.769  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 16:31:18.770  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:31:18.774  2676  2676 D BtGatt.ScanManager: awakened up at time 152772
09-08 16:31:18.775  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:31:18.775  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:31:18.776  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:31:18.781  2676  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 16:31:18.781  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:18.781  2676  2704 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:31:18.796  2676  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:31:18.796  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:18.797  2676  2704 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:31:18.824  2676  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 16:31:18.825  2676  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:31:18.825  2676  2700 D BtGatt.GattService: current time is 152823678312
,09-08 16:31:18.825  2676  2700 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:31:18.826  2676  2700 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:31:19.277  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:31:19.277  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:31:19.278  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:31:22.284  3555  3824 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 16:31:22.319  3555  3827 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 16:31:22.353  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:22.356  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:22.394  1507  2410 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 16:31:22.394  1507  2410 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 16:31:22.394  1507  2410 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:22.395  1507  2410 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:22.453  1507  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 16:31:22.453  1507  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 16:31:22.454  1507  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:22.454  1507  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:22.461  1507  1945 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 16:31:22.461  1507  1945 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 16:31:22.461  1507  1945 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:22.462  1507  1945 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:22.480  2991  3826 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 16:31:22.480  2991  3826 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at blb.a(PG:3937)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at czp.a(PG:18188)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:31:22.480  2991  3826 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	... 12 more
09-08 16:31:22.480  2991  3826 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at fal.a(PG:38)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:31:22.480  2991  3826 E HttpOperation: 	... 14 more
,09-08 16:31:22.494  3555  3827 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 16:31:22.496  3555  3824 E BooksSync: Soft error
09-08 16:31:22.496  3555  3824 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:31:22.496  3555  3824 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 16:31:22.501  3555  3824 E BooksSync: Sync error
09-08 16:31:22.501  3555  3824 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:31:22.501  3555  3824 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 16:31:22.501  3555  3824 I BooksSync: Finished books sync
,09-08 16:31:22.515   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126427, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:31:22.549  1507  3611 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 16:31:22.549  1507  3611 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 16:31:22.549  1507  3611 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:22.549  1507  3611 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:22.578  2991  3826 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 16:31:22.578  2991  3826 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at hec.a(PG:42)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at hee.a(PG:102)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at czr.a(PG:65)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at kka.a(PG:108)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at czp.a(PG:19176)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:31:22.578  2991  3826 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	... 15 more
09-08 16:31:22.578  2991  3826 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at fal.a(PG:38)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:31:22.578  2991  3826 E HttpOperation: 	... 17 more
,09-08 16:31:22.578  2991  3826 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 16:31:22.578  2991  3826 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at hec.a(PG:42)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at hee.a(PG:102)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at czr.a(PG:65)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at kka.a(PG:108)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	... 15 more
09-08 16:31:22.578  2991  3826 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at fal.a(PG:38)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 16:31:22.578  2991  3826 E ExperimentLoader: 	... 17 more
,09-08 16:31:22.599  1859  2643 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 16:31:22.733   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131568, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:31:23.776  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:23.777  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.777  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.777  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.778  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:23.778  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:31:23.779  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.779  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.779  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:23.780  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.780  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.781  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.782  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:23.787  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:31:23.788  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.788  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.788  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:23.790  3750  3799 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 16:31:23.793  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:23.793  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.793  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.794  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:23.794  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:23.794  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.795  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.795  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:23.796  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.796  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.796  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.796  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:23.797  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.797  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:23.800  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.800  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.800  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.801  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:23.804  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 16:31:23.804  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.804  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.805  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:31:23.805  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.805  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.806  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.806  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
,09-08 16:31:23.806  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:23.807  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.807  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.807  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:23.807  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.808  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:23.808  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.811  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.811  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.812  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.812  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:23.814  3750  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-08 16:31:23.814  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.815  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.815  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.816  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.816  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.816  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.816  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.817  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.817  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.817  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.817  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.817  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.817  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.817  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.819  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.819  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.819  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.819  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.820  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 16:31:23.820  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.820  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.820  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.820  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.820  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.820  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.820  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.820  3750  3799 I org.thaliproject.p2p.btconnectorlib.Di,scoveryManager: dispose
09-08 16:31:23.820  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.820  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.821  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.821  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.821  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.821  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.822  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.822  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.822  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.822  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.823  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 16:31:23.823  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:23.823  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:23.824  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 16:31:23.824  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:31:23.824  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:31:23.824  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 16:31:23.824  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:23.824  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:31:23.824  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.824  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.824  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.825  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.825  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.825  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.825  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.825  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.825  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.825  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.825  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.825  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.825  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.825  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.829  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.829  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.829  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.829  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.830  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:31:23.831  3750  3799 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 16:31:23.831  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 16:31:23.838  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:31:23.838  3750  3799 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 16:31:23.838  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 16:31:23.839  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 16:31:23.840  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 16:31:23.841  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 16:31:23.841  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 16:31:23.842  3750  3799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 16:31:23.842  3750  3799 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 16:31:23.842  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:31:23.842  3750  3799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 16:31:23.842  3750  3799 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 16:31:23.842  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:31:23.842  3750  3799 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 16:31:23.842  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 16:31:23.845  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 16:31:23.847  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 16:31:23.847  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 16:31:23.847  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 16:31:23.847  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 16:31:23.848  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 16:31:23.848  3750  3799 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:31:23.848  3750  3799 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 16:31:23.848  3750  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
09-08 16:31:23.849  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.849  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.849  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.849  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.849  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.849  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.849  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 16:31:23.850  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.850  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.850  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.850  3750  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:31:23.851  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:23.851  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.851  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.851  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.851  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.852  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.852  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.852  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.852  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.854  3750  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
09-08 16:31:23.854  3750  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 382)
09-08 16:31:23.855  3750  3799 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 16:31:23.855  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.856  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.856  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.856  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.856  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.856  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.856  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.856  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.856  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.857  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.857  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.857  2676  2807 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-08 16:31:23.857  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.857  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.857  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.857  3750  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 382)
09-08 16:31:23.857  3750  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
09-08 16:31:23.858  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.858  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.858  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.858  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.859  3750  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 16:31:23.859  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.859  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.859  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.860  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.860  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.860  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.860  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.860  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.860  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.860  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.860  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.860  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.860  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.861  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.862  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.862  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.862  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.862  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.862  3750  3799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 16:31:23.863  3750  3799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 16:31:23.863  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 16:31:23.863  3750  3799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 16:31:23.863  3750  3799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 16:31:23.863  3750  3799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 16:31:23.863  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 16:31:23.863  3750  3799 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 16:31:23.863  3750  3799 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 16:31:23.863  3750  3799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 16:31:23.864  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 16:31:23.864  3750  3799 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 16:31:23.864  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:23.864  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:23.864  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:23.864  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.864  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.865  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.865  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.865  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.865  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.865  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.865  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.865  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.865  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.865  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.866  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:23.866  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:23.866  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.867  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.867  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:23.867  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.867  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:23.867  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:23.868  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:23.868  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:23.868  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:23.868  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:23.868  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:25.470  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:25.714  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:25.740  1507  3832 I VacuumService: Vacuum at: now=1473345085740 tag=VacuumService
,09-08 16:31:25.804  1507  1517 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 16:31:25.804  1507  1517 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 16:31:25.804  1507  1517 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:25.804  1507  1517 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:25.828  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 16:31:25.829  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 16:31:25.829  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 16:31:25.910  1507  3833 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 16:31:25.913  1507  3833 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 16:31:25.939  1507  3833 W Uploader:  no longer exists, so no auth token.
,09-08 16:31:28.869  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:28.869  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.870  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:28.870  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.870  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:28.871  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:28.871  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:28.872  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:28.872  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:28.873  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:28.873  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.873  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.874  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:28.874  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:28.874  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:28.875  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:28.875  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.875  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:28.876  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.876  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.879  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:31:28.880  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:28.880  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.880  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.886  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 16:31:28.887  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:31:28.889  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 16:31:28.891  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 16:31:28.892  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 16:31:28.892  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 16:31:28.893  3750  3750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 16:31:28.893  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:31:28.894  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:28.894  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 16:31:28.894  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 16:31:28.894  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 16:31:28.895  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:28.895  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 16:31:28.895  3750  3750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 16:31:28.895  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:28.896  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:28.896  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:31:28.896  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:31:28.896  3750  3840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:31:28.896  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:31:28.897  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.897  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.900  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:31:28.900  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.900  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:31:28.901  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:28.901  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:31:28.901  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:28.901  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:31:28.901  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:31:28.902  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:28.902  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.902  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.902  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:28.903  3750  3840 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 16:31:28.903  3750  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 16:31:28.903  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.903  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:28.903  3750  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 16:31:28.903  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:28.904  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.904  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.904  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.904  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.904  3750  3750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 16:31:28.907  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:28.907  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:28.907  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.907  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.910  3750  3799 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 16:31:28.910  3750  3799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 16:31:28.910  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 16:31:28.910  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:31:28.910  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 16:31:28.911  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:28.911  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:28.911  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:28.911  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:31:28.911  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.911  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.911  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
,09-08 16:31:28.911  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.912  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:28.912  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:28.912  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.912  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.912  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.912  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:28.914  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:31:28.914  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:31:28.914  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.914  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.918  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:31:28.918  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:31:28.918  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:28.919  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:28.919  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.919  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.919  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
,09-08 16:31:28.919  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.919  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.919  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:28.919  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.919  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:28.919  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.920  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.921  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:28.921  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:31:28.921  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.921  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.922  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:31:28.922  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:31:28.922  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:31:28.922  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:31:28.922  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:28.923  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.923  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9b8565 not in the list
09-08 16:31:28.923  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.923  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
,09-08 16:31:28.923  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:28.923  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.923  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.923  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:28.923  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:28.924  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:31:28.924  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:31:28.924  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:28.925  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fac23a not in the list
09-08 16:31:28.926  3750  3799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 16:31:28.926  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 16:31:28.926  3750  3799 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 16:31:28.926  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 16:31:28.926  3750  3799 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 16:31:28.926  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 16:31:28.930  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 16:31:28.930  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 16:31:28.930  3750  3799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 16:31:28.931  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 16:31:28.931  3750  3799 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 16:31:28.931  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-08 16:31:28.931  3750  3799 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 16:31:28.931  3750  3799 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 16:31:28.932  3750  3799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 16:31:28.932  3750  3799 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 16:31:28.932  3750  3799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-08 16:31:28.932  3750  3799 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 16:31:28.932  3750  3799 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 16:31:28.933  3750  3799 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 16:31:28.934  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:28.934  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1191d5 added. We now have 3 listener(s)
09-08 16:31:28.934  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:28.936  3750  3799 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 16:31:28.936   873   883 D WifiService: setWifiEnabled: true pid=3750, uid=10000
09-08 16:31:28.937   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:31:28.981  2676  2787 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 16:31:28.981  2676  2787 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 16:31:29.402  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:31:29.755   873  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-08 16:31:30.959   873  2092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 16:31:32.703  1507  3833 I art     : Waiting for a blocking GC DisableMovingGc
,09-08 16:31:32.718  1507  3833 I art     : WaitForGcToComplete blocked for 15.578ms for cause DisableMovingGc
,09-08 16:31:32.718  1507  3833 I art     : Starting a blocking GC DisableMovingGc
,09-08 16:31:33.135  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:33.137  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:33.180  1507  3833 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 16:31:33.180  1507  3833 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 16:31:33.180  1507  3833 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:33.180  1507  3833 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:33.198  1507  3833 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 16:31:33.198  1507  3833 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 16:31:33.198  1507  3833 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 16:31:33.435  1507  3833 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 16:31:33.435  1507  3833 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 16:31:33.435  1507  3833 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:31:33.435  1507  3833 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:33.455  1507  3833 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 16:31:33.455  1507  3833 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 16:31:33.455  1507  3833 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 16:31:33.945  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:33.946  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a82dea added. We now have 4 listener(s)
09-08 16:31:33.946  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:33.961  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:31:33.962  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a82dea removed from the list
,09-08 16:31:33.962  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:33.962  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:33.963  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:33.964  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:33.965  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69508db added. We now have 4 listener(s)
,09-08 16:31:33.965  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:33.968  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:33.968  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69508db removed from the list
,09-08 16:31:33.968  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:33.969  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:33.969  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:31:33.971  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:33.971  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a89af78 added. We now have 4 listener(s)
09-08 16:31:33.971  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:33.976   873  1389 D WifiService: setWifiEnabled: false pid=3750, uid=10000
09-08 16:31:33.977   873  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:31:33.989  2676  2695 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 16:31:33.989  2676  2695 D BluetoothAdapterProperties: Setting state to 13,
,09-08 16:31:33.989  2676  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 16:31:33.990  2676  2695 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 16:31:33.992  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-08 16:31:33.992  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 16:31:33.995   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 16:31:33.995   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 16:31:33.995   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 16:31:33.996   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 16:31:33.993  2676  2695 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:31:34.004  2676  2700 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:31:34.005  2676  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 16:31:34.007  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:34.007  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:31:34.008  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.008  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.008  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:31:34.011  2676  2676 D BluetoothMapService: onReceive
09-08 16:31:34.011  2676  2676 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 16:31:34.012  2676  2676 D BluetoothMapService: STATE_TURNING_OFF
,09-08 16:31:34.012  2676  2676 D BluetoothMapService: MAP Service closeService in
,09-08 16:31:34.012  2676  2676 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 16:31:34.012  2676  2676 D ObexServerSockets0: shutdown(block = true)
,09-08 16:31:34.012   873  1303 E native  : do suspend true
,09-08 16:31:34.012  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:31:34.013  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:31:34.013  2676  2823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 16:31:34.013  2676  2824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 16:31:34.013  2676  2807 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 16:31:34.013  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.016  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:34.016  2676  2676 I BtOppRfcommListener: stopping Accept Thread
,09-08 16:31:34.017  2676  3441 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 16:31:34.017  2676  3441 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 16:31:34.019  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:34.019  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:31:34.020  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.020  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.022   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 16:31:34.022   873  2093 D DhcpClient: Clearing IP address
09-08 16:31:34.025   372   871 D CommandListener: Setting iface cfg
09-08 16:31:34.026  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:34.026  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:34.027  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.027  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:34.028   873  2107 D DhcpClient: Receive thread stopped
09-08 16:31:34.030  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.031   873   886 I ActivityManager: Start proc 3849:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-08 16:31:34.033  2676  2676 D HeadsetService: Received stop request...Stopping profile...
09-08 16:31:34.033  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.036  1348  1366 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:34.036   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:34.036  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.036  1986  2061 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:34.037   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:34.037   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:34.041  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.041  2676  2676 D A2dpService: Received stop request...Stopping profile...
09-08 16:31:34.041  2676  2813 D A2dpStateMachine: Exit Disconnected: -1
09-08 16:31:34.043   873   873 D BluetoothA2dp: Proxy object disconnected
09-08 16:31:34.044   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 16:31:34.045   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 16:31:34.045   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 16:31:34.045   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 16:31:34.045   873  1303 E native  : do suspend true
09-08 16:31:34.049  2676  2676 D HidService: Received stop request...Stopping profile...
09-08 16:31:34.049  1348  1348 D HeadsetProfile: Bluetooth service disconnected
09-08 16:31:34.049  2676  2676 D HidService: Stopping Bluetooth HidService
09-08 16:31:34.049  1348  1348 D BluetoothA2dp: Proxy object disconnected
09-08 16:31:34.050   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 16:31:34.052  2676  2676 D HealthService: Received stop request...Stopping profile...
09-08 16:31:34.054   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 16:31:34.054  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:34.054  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.054  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:34.054  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:34.056  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 16:31:34.057  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.057  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.057  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.057  2676  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 16:31:34.057  2676  2700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 16:31:34.057  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 16:31:34.058  2676  2676 D PanService: Received stop request...Stopping p,rofile...
09-08 16:31:34.059  2676  2676 D BluetoothMapService: Received stop request...Stopping profile...
09-08 16:31:34.060  2676  2676 D BluetoothMapService: stop()
09-08 16:31:34.060  2676  2676 D BluetoothMapAppObserver: deinitObservers()
09-08 16:31:34.060  2676  2676 D BluetoothMapAppObserver: removeReceiver()
09-08 16:31:34.062   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-08 16:31:34.062  1507  2540 V NativeCrypto: Read error: ssl=0x9aaa5c00: I/O error during system call, Connection timed out
09-08 16:31:34.061  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:34.063  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.063  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:34.063  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:34.064  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:34.064  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.064  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:34.064  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:34.064  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 16:31:34.065  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 16:31:34.065  2676  2676 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:34.065  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.065  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:34.065  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:34.065  2676  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 16:31:34.065  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.065  2676  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 16:31:34.065  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.065  2676  2787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:31:34.065  2676  2787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:31:34.065  2676  2787 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:31:34.065  2676  2787 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:31:34.066  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 16:31:34.066  2676  2700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 16:31:34.066  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 16:31:34.068  1507  3833 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-08 16:31:34.075  2676  2676 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:31:34.075  2676  2676 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:31:34.075  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:34.075  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:34.075  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 16:31:34.075  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 16:31:34.076  2676  2676 D BluetoothMapService: MAP Service closeService in
,09-08 16:31:34.076  2676  2676 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:31:34.076  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.076  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:34.076  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:34.076  2676  2676 D BluetoothMapService: cleanup()
09-08 16:31:34.077  2676  2676 D BluetoothMapService: MAP Service closeService in
09-08 16:31:34.077  2676  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 16:31:34.077  2676  2695 D BluetoothAdapterProperties: Setting state to 15
,09-08 16:31:34.077  2676  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 16:31:34.078  1348  1695 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:31:34.078  2676  2695 I BluetoothAdapterState: Entering BleOnState
,09-08 16:31:34.079  1348  1348 D BluetoothInputDevice: Proxy object disconnected
09-08 16:31:34.079  1348  1348 D HidProfile: Bluetooth service disconnected
09-08 16:31:34.079   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:34.079  1348  1366 D BluetoothMap: onBluetoothStateChange: up=false
09-08 16:31:34.080  1986  2002 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:34.080  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:31:34.080  1348  1348 D PanProfile: Bluetooth service disconnected
09-08 16:31:34.080   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:31:34.080  1348  1695 D BluetoothPan: onBluetoothStateChange on: false
09-08 16:31:34.080   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:34.080  1348  1366 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 16:31:34.081  1348  1368 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:31:34.081  1348  1695 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 16:31:34.081  1507  2540 V NativeCrypto: SSL shutdown failed: ssl=0x9aaa5c00: I/O error during system call, Broken pipe
,09-08 16:31:34.082   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 16:31:34.082  2676  2695 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 16:31:34.082  2676  2695 D BluetoothAdapterProperties: Setting state to 16
,09-08 16:31:34.082  2676  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 16:31:34.083  2676  2695 D BluetoothAdapterProperties: onBleDisable
09-08 16:31:34.085  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.085  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:34.086  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.086  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:34.086  2676  2695 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:31:34.086  2676  2697 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 16:31:34.088  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.088  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:34.089  2676  2787 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 16:31:34.089  2676  2787 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:34.089  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.090  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:34.091  2676  2700 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:31:34.092  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.092  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:34.093  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.093  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:34.094  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.095  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:34.095  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.096   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 16:31:34.115   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 16:31:34.116   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-08 16:31:34.116   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:31:34.116   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:34.120   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:31:34.121  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.122  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:34.123  3374  3374 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6f27fe and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 16:31:34.123  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:34.130   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:31:34.131  1859  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 16:31:34.132  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.132  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:34.132  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.133  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:34.133   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 16:31:34.134  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.134  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:34.134  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.134  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:34.136  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:34.136  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:34.136  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:34.136  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:34.142  3849  3849 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 16:31:34.152  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:31:34.156  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:31:34.161   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f5ded:true
,09-08 16:31:34.168   873  1520 I ActivityManager: Start proc 3872:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 16:31:34.177   372   871 E Netd    : netlink response contains error (No such file or directory)
09-08 16:31:34.178  3849  3849 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 16:31:34.179  3849  3849 D BluetoothMap: Create BluetoothMap proxy object
,09-08 16:31:34.204  3849  3849 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 16:31:34.215  3872  3872 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 16:31:34.218  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:31:34.227   873  1520 I ActivityManager: Killing 3195:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 16:31:34.291  2676  2700 I bt_hci  : shut_down
,09-08 16:31:34.299  2676  2705 D bt_hwcfg: hw_epilog_process
,09-08 16:31:34.300  2676  2705 I bt_vendor: low_power_mode_cb
,09-08 16:31:34.316  2676  2705 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 16:31:34.316  2676  2705 I bt_vendor: epilog_cb
,09-08 16:31:34.316  2676  2705 I bt_hci  : epilog_finished_callback
,09-08 16:31:34.322  2676  2700 I bt_hci_h4: hal_close
,09-08 16:31:34.323  2676  2700 I bt_userial_vendor: device fd = 51 close
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.439  3872  3872 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.439  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.440  3872  3872 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:31:34.440  3872  3872 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:31:34.440  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:31:34.446  2676  2697 D bt_stack_manager: event_shut_down_stack finished.
,09-08 16:31:34.447  2676  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-08 16:31:34.449  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 16:31:34.455  2676  2695 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 16:31:34.456  2676  2676 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 16:31:34.457  2676  2676 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 16:31:34.457  2676  2676 D BtGatt.GattService: stop()
,09-08 16:31:34.457  2676  2676 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 16:31:34.461  2676  2676 V BluetoothAdapterState: isTurningOff()=false
09-08 16:31:34.462  2676  2676 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:34.462  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:34.462  2676  2676 V BluetoothAdapterState: isBleTurningOff()=true
09-08 16:31:34.463  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 16:31:34.463  2676  2695 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 16:31:34.465  2676  2695 D BluetoothAdapterProperties: Setting state to 10
,09-08 16:31:34.466  2676  2695 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 16:31:34.480  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 16:31:34.483  2676  2695 I BluetoothAdapterState: Entering OffState
,09-08 16:31:34.484   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-08 16:31:34.492  1699  1699 D SystemUpdateService: onCreate
,09-08 16:31:34.498  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:31:34.503  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:31:34.512  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 16:31:34.512  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 16:31:34.512  2676  2676 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 16:31:34.513  2676  2697 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 16:31:34.516  2676  2697 D bt_stack_manager: event_clean_up_stack finished.
,09-08 16:31:34.518  2676  2676 I art     : System.exit called, status: 0
,09-08 16:31:34.518  2676  2676 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 16:31:34.524  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 16:31:34.527  1699  2518 I iu.UploadsManager: num queued entries: 0
,09-08 16:31:34.527  1699  2518 I iu.UploadsManager: num updated entries: 0
,09-08 16:31:34.543  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 16:31:34.544  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:31:34.546  1699  3902 I SystemUpdateService: active receiver: enabled
,09-08 16:31:34.563   873  2031 I ActivityManager: Start proc 3905:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 16:31:34.570  1699  2518 I iu.SyncManager: NEXT; no task
,09-08 16:31:34.572  1699  3902 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:31:34.581  1699  3902 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 16:31:34.581  1699  3902 I SystemUpdateService: now status is 0 (complete)
,09-08 16:31:34.585  1699  3902 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 16:31:34.585  1699  3902 I SystemUpdateService: file has been verified
,09-08 16:31:34.585  1699  3902 I SystemUpdateService: OTA package size = 12249756
,09-08 16:31:34.599   873  1681 I ActivityManager: Process com.android.bluetooth (pid 2676) has died
,09-08 16:31:34.599  1699  3902 I SystemUpdateService: showing system update notification
,09-08 16:31:34.636  3905  3905 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 16:31:34.639  3905  3905 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:34.647  3905  3905 D SprintDMHelper: simOperator: 
,09-08 16:31:34.647  3905  3905 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:31:34.669   873  1683 I ActivityManager: Start proc 3918:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 16:31:34.671   873  1683 I ActivityManager: Killing 3374:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 16:31:34.716  1699  1699 D SystemUpdateService: onDestroy
,09-08 16:31:34.740   873   883 I ActivityManager: Killing 2774:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 16:31:34.886   873  1683 I ActivityManager: Start proc 3935:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 16:31:34.897  3872  3890 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 16:31:34.914   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a23edce:true
,09-08 16:31:34.940  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 16:31:34.996  3935  3935 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 16:31:34.996  3935  3935 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 16:31:34.996  3935  3935 I GAv4    :   adb logcat -s GAv4
,09-08 16:31:35.006  3935  3935 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:31:35.013  3935  3935 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:31:35.023  3935  3952 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:31:35.151  3935  3935 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 16:31:35.189  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 16:31:35.199  3935  3935 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9194-9197)
,09-08 16:31:35.200  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 16:31:35.217  3935  3935 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4b38cae}
,09-08 16:31:35.217  3935  3935 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 16:31:35.218  3935  3935 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 16:31:35.227  3935  3935 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 16:31:35.229  3935  3935 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 16:31:35.248  3935  3935 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 16:31:35.264  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 16:31:35.264  3935  3935 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 16:31:35.264  3935  3935 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 16:31:35.264  3935  3935 I Adreno  : Build Date                       : 10/20/15
09-08 16:31:35.264  3935  3935 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 16:31:35.264  3935  3935 I Adreno  : Local Branch                     : M14
09-08 16:31:35.264  3935  3935 I Adreno  : Remote Branch                    : 
09-08 16:31:35.264  3935  3935 I Adreno  : Remote Branch                    : 
09-08 16:31:35.264  3935  3935 I Adreno  : Reconstruct Branch               : 
,09-08 16:31:35.329  3935  3935 I NSApplication: Starting up...
,09-08 16:31:35.340  3935  3981 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 16:31:35.375   873  2031 I ActivityManager: Start proc 3986:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 16:31:35.376   873  2031 I ActivityManager: Killing 1715:android.process.acore/u0a5 (adj 15): empty #17
,09-08 16:31:35.453  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 16:31:35.657   873  2031 I ActivityManager: Killing 3633:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 16:31:35.745   873  1683 I ActivityManager: Start proc 4000:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 16:31:35.798  4000  4000 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 16:31:35.849  4000  4000 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 16:31:35.907   873  2065 I ActivityManager: Killing 3648:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 16:31:39.012   873  3104 D WifiService: setWifiEnabled: true pid=3750, uid=10000
,09-08 16:31:39.012   873  3104 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:31:39.025   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-08 16:31:39.034  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:39.035  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:39.035  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:39.036  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:39.038  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:39.039  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:39.039  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:39.039  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:39.042  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:39.042  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:39.042  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
09-08 16:31:39.043  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:39.048   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-08 16:31:39.049   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 16:31:39.050   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 16:31:39.051   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 16:31:39.051   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 16:31:39.051   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 16:31:39.051   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 16:31:39.073   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 16:31:39.073   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:31:39.075   372   871 D CommandListener: Setting iface cfg
,09-08 16:31:39.076   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 16:31:39.076   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 16:31:39.086   873  1303 E native  : do suspend true
,09-08 16:31:39.092   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 16:31:39.092   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 16:31:39.103   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:31:39.967   873  2031 I ActivityManager: Killing 3400:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 16:31:40.395   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:31:40.483   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.81 rxSuccessRate=13.38 delta 1000 -> 1000
,09-08 16:31:40.485   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 16:31:40.485   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:31:40.510   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 16:31:40.575   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 16:31:40.580  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 16:31:41.015  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 16:31:41.056  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 16:31:41.057  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 16:31:41.059   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:31:41.067   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:31:41.067   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:31:41.068   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 16:31:41.084   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:31:41.097   372   871 D CommandListener: Setting iface cfg
,09-08 16:31:41.098   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 16:31:41.106   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 16:31:41.147   873  4037 D DhcpClient: Receive thread started
,09-08 16:31:41.234   873  1303 E native  : do suspend false
,09-08 16:31:41.256   873  2093 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 16:31:41.272   873  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,09-08 16:31:41.273   873  2093 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,09-08 16:31:41.277   873  2093 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 16:31:41.293   873  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 16:31:41.294   873  2093 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 16:31:41.299   372   871 D CommandListener: Setting iface cfg
,09-08 16:31:41.310   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 16:31:41.310   873  2093 D DhcpClient: Scheduling renewal in 86399s
09-08 16:31:41.312   873  1303 E native  : do suspend true
,09-08 16:31:41.336   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 16:31:41.337   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 16:31:41.338   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 16:31:41.339   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 16:31:41.340   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 16:31:41.434   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 16:31:41.435   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 16:31:41.438   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 16:31:41.441   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 16:31:41.444   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 16:31:41.464   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 16:31:41.473   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 16:31:41.474   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 16:31:41.474   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 16:31:41.474   873  1305 D ConnectivityService:    accepting network in place of null
09-08 16:31:41.474   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 16:31:41.476   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
09-08 16:31:41.476   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:31:41.523   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:31:41.534   873  4036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:31:41.604   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:31:41.613   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 16:31:41.614   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:41.621   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 16:31:41.625   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:31:41.643  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:41.643  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:31:41.643  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:41.643  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:41.646  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:41.646  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:31:41.646  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:41.646  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:41.648  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:31:41.648  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:31:41.648  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:41.648  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:31:41.653   873  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 16:31:41.656  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 16:31:41.664  1699  1699 D SystemUpdateService: onCreate
,09-08 16:31:41.668  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:31:41.691  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 16:31:41.698  1699  2518 I iu.UploadsManager: num queued entries: 0
,09-08 16:31:41.699  1699  4047 I SystemUpdateService: active receiver: enabled
,09-08 16:31:41.703  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 16:31:41.704  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:31:41.706  3905  3905 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:41.712  1699  4049 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 16:31:41.712  1699  4049 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 16:31:41.712  3905  3905 D SprintDMHelper: simOperator: 
09-08 16:31:41.712  3905  3905 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:31:41.715  1699  4049 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 16:31:41.724  1699  2518 I iu.UploadsManager: num updated entries: 0
09-08 16:31:41.725  1699  2518 I iu.SyncManager: NEXT; no task
,09-08 16:31:41.731  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:41.733  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:41.741   873  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 14:31:41 GMT], X-Android-Received-Millis=[1473345101740], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473345101694]}
,09-08 16:31:41.743   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 16:31:41.743   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 16:31:41.743   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 16:31:41.745   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 16:31:41.764  1699  4047 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:31:41.781  1699  4047 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 16:31:41.781  1699  4047 I SystemUpdateService: now status is 0 (complete)
09-08 16:31:41.781  1699  4047 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 16:31:41.781  1699  4047 I SystemUpdateService: file has been verified
09-08 16:31:41.781  1699  4047 I SystemUpdateService: OTA package size = 12249756
,09-08 16:31:41.801  1699  4047 I SystemUpdateService: showing system update notification
,09-08 16:31:41.815  1507  3611 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 16:31:41.815  1507  3611 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 16:31:41.815  1507  3611 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:41.815  1507  3611 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:41.832  1699  1699 D SystemUpdateService: onDestroy
,09-08 16:31:41.837  1699  4049 E MDM     : [174] SitrepService.a: Error sending sitrep.
,09-08 16:31:41.860  2130  4052 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 16:31:42.612   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 16:31:44.019   873  1995 D WifiService: setWifiEnabled: false pid=3750, uid=10000
,09-08 16:31:44.020   873  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:31:44.052  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 16:31:44.061   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 16:31:44.061   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 16:31:44.062   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 16:31:44.062   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:31:44.095   873  1303 E native  : do suspend true
,09-08 16:31:44.107   873  2093 D DhcpClient: Clearing IP address
,09-08 16:31:44.108   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-08 16:31:44.112   372   871 D CommandListener: Setting iface cfg
,09-08 16:31:44.119  1507  4060 V NativeCrypto: Read error: ssl=0x99c71c00: I/O error during system call, Connection timed out
,09-08 16:31:44.124   873  4037 D DhcpClient: Receive thread stopped
,09-08 16:31:44.129   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 16:31:44.131   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 16:31:44.137   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 16:31:44.138   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 16:31:44.140  1507  4060 V NativeCrypto: SSL shutdown failed: ssl=0x99c71c00: I/O error during system call, Broken pipe
09-08 16:31:44.140   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:31:44.141   873  1303 E native  : do suspend true
09-08 16:31:44.143   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 16:31:44.179   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:31:44.224   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:31:44.224   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-08 16:31:44.226   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 16:31:44.226   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:44.230   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:31:44.241  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.241  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:44.241  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:44.242  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:44.243  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.243  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:44.243  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.244  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:44.244   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 16:31:44.245  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.245  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:44.246  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.246  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:44.257  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 16:31:44.262   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 16:31:44.265  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.265  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:44.265  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.265  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:44.267  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.267  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:44.267  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.267   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 16:31:44.267  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:44.267  1859  2283 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 16:31:44.268  1699  1699 D SystemUpdateService: onCreate
09-08 16:31:44.268  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:44.268  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:44.268  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:44.268  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:44.274  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:31:44.290  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 16:31:44.295  1699  4070 I SystemUpdateService: active receiver: enabled
,09-08 16:31:44.296  1699  2518 I iu.UploadsManager: num queued entries: 0
,09-08 16:31:44.297  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 16:31:44.299  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:31:44.301  3905  3905 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:31:44.305  3905  3905 D SprintDMHelper: simOperator: 
,09-08 16:31:44.305  3905  3905 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 16:31:44.306  1699  2518 I iu.UploadsManager: num updated entries: 0
09-08 16:31:44.307  1699  2518 I iu.SyncManager: NEXT; no task
,09-08 16:31:44.307  1699  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:31:44.309  1699  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 16:31:44.309  1699  4070 I SystemUpdateService: now status is 0 (complete)
09-08 16:31:44.309  1699  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 16:31:44.309  1699  4070 I SystemUpdateService: file has been verified
09-08 16:31:44.309  1699  4070 I SystemUpdateService: OTA package size = 12249756
09-08 16:31:44.314   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-08 16:31:44.346  2130  4074 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 16:31:44.352  1699  4070 I SystemUpdateService: showing system update notification
,09-08 16:31:44.365  1699  1699 D SystemUpdateService: onDestroy
,09-08 16:31:49.079   873   890 I ActivityManager: Start proc 4077:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 16:31:49.176  4077  4077 D AdapterServiceConfig: Adding HeadsetService
,09-08 16:31:49.176  4077  4077 D AdapterServiceConfig: Adding A2dpService
09-08 16:31:49.176  4077  4077 D AdapterServiceConfig: Adding HidService
09-08 16:31:49.176  4077  4077 D AdapterServiceConfig: Adding HealthService,
09-08 16:31:49.176  4077  4077 D AdapterServiceConfig: Adding PanService
09-08 16:31:49.177  4077  4077 D AdapterServiceConfig: Adding GattService
,09-08 16:31:49.177  4077  4077 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 16:31:49.208  4077  4077 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 16:31:49.208   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5eaa584:true
,09-08 16:31:49.213  4077  4077 I bt_bluedroid: init
,09-08 16:31:49.213  4077  4089 I BluetoothAdapterState: Entering OffState
,09-08 16:31:49.218  4077  4090 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 16:31:49.219  4077  4090 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 16:31:49.219  4077  4090 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 16:31:49.220  4077  4090 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 16:31:49.221  4077  4077 I bt_bluedroid: get_profile_interface socket
,09-08 16:31:49.223  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-08 16:31:49.223  4077  4077 I bt_bluedroid: get_profile_interface sdp
,09-08 16:31:49.225  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:31:49.228  4077  4088 I bt_bluedroid: config_hci_snoop_log
,09-08 16:31:49.230   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 16:31:49.239  4077  4089 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 16:31:49.240  4077  4089 D BluetoothAdapterProperties: Setting state to 14
,09-08 16:31:49.240  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 16:31:49.244  4077  4089 D BluetoothBondStateMachine: make
,09-08 16:31:49.247  4077  4094 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 16:31:49.253  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:31:49.256  4077  4077 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 16:31:49.262  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:49.264  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:31:49.265  4077  4077 D BtGatt.GattService: Received start request. Starting profile...
,09-08 16:31:49.265  4077  4077 D BtGatt.GattService: start()
,09-08 16:31:49.265  4077  4077 I bt_bluedroid: get_profile_interface gatt
,09-08 16:31:49.267  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:49.268  4077  4077 D BtGatt.AdvertiseManager: advertise manager created
,09-08 16:31:49.280  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:31:49.281  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:49.281  4077  4077 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 16:31:49.281  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:49.283  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 16:31:49.284  4077  4089 I bt_bluedroid: enable
,09-08 16:31:49.285  4077  4090 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 16:31:49.287  4077  4090 I bt_hci  : start_up
,09-08 16:31:49.297  4077  4090 I bt_vendor: alloc value 0xb39a4189
,09-08 16:31:49.297  4077  4090 I bt_vendor: init
09-08 16:31:49.297  4077  4090 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 16:31:49.297  4077  4090 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 16:31:49.406  4077  4090 D bt_hci  : start_up starting async portion
,09-08 16:31:49.406  4077  4097 I bt_hci  : event_finish_startup
,09-08 16:31:49.407  4077  4097 I bt_hci_h4: hal_open
,09-08 16:31:49.407  4077  4097 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 16:31:49.414  4077  4097 I bt_userial_vendor: device fd = 51 open
,09-08 16:31:49.449  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:31:49.479   873  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-08 16:31:49.481  4077  4097 D bt_hwcfg: Chipset BCM4354A2
,09-08 16:31:49.482  4077  4097 D bt_hwcfg: Target name = [BCM4354A2]
09-08 16:31:49.482  4077  4097 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 16:31:50.143  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 16:31:50.144  4077  4097 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 16:31:50.145  4077  4097 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 16:31:50.262  4077  4097 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:31:50.264  4077  4097 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 16:31:50.291  4077  4097 I bt_hwcfg: vendor lib fwcfg completed
,09-08 16:31:50.292  4077  4097 I bt_vendor: firmware callback
09-08 16:31:50.292  4077  4097 I bt_hci  : firmware_config_callback
,09-08 16:31:50.305  4077  4099 I bt_btu  : btu_task pending for preload complete event
,09-08 16:31:50.305  4077  4099 I bt_btu_task: Bluetooth chip preload is complete
,09-08 16:31:50.305  4077  4099 I bt_btu  : btu_task received preload complete event
,09-08 16:31:50.315  4077  4099 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 16:31:50.316  4077  4099 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 16:31:50.316  4077  4099 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 16:31:50.316  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 16:31:50.317  4077  4099 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 16:31:50.317  4077  4099 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 16:31:50.317  4077  4099 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 16:31:50.318  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 16:31:50.318  4077  4099 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 16:31:50.318  4077  4099 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 16:31:50.318  4077  4099 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 16:31:50.319  4077  4099 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 16:31:50.319  4077  4099 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 16:31:50.319  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 16:31:50.319  4077  4099 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 16:31:50.453  4077  4099 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3921d9d
,09-08 16:31:50.453  4077  4099 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3921d9d 
,09-08 16:31:50.475  4077  4093 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 16:31:50.477  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 16:31:50.478  4077  4093 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:31:50.481  4077  4093 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:31:50.484  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:31:50.489  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 16:31:50.490  4077  4093 D bt_hci  : do_postload posting postload work item
09-08 16:31:50.490  4077  4097 I bt_hci  : event_postload
09-08 16:31:50.490  4077  4097 I bt_vendor: sco_config_cb
09-08 16:31:50.490  4077  4097 I bt_hci  : sco_config_callback postload finished.
09-08 16:31:50.491  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:50.493  4077  4093 D bt_bte_conf: Device ID record 1 : primary
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   vendorId            = 000f
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 16:31:50.493  4077  4093 D bt_bte_conf:   product             = 1200
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   version             = 1436
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   clientExecutableURL = 
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   serviceDescription  = 
09-08 16:31:50.493  4077  4093 D bt_bte_conf:   documentationURL    = 
09-08 16:31:50.494  4077  4093 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 16:31:50.494  4077  4090 D bt_stack_manager: event_start_up_stack finished
09-08 16:31:50.495  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:50.496  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 16:31:50.496  4077  4089 D BluetoothAdapterProperties: Setting state to 15
,09-08 16:31:50.497  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 16:31:50.499  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:50.500  4077  4089 I BluetoothAdapterState: Entering BleOnState
,09-08 16:31:50.502  4077  4097 I bt_vendor: low_power_mode_cb
,09-08 16:31:50.502  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 16:31:50.503  4077  4089 D BluetoothAdapterProperties: Setting state to 11
,09-08 16:31:50.504  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 16:31:50.516  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:50.517  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:50.519  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:50.519  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.521  4077  4077 D HeadsetService: Received start request. Starting profile...
,09-08 16:31:50.524  4077  4077 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 16:31:50.525  4077  4077 D HeadsetStateMachine: make
,09-08 16:31:50.528  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:31:50.533  4077  4077 D HeadsetStateMachine: max_hf_connections = 1
,09-08 16:31:50.533  4077  4077 I bt_bluedroid: get_profile_interface handsfree
09-08 16:31:50.534  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 16:31:50.534  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 16:31:50.538  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.538  4077  4077 D A2dpService: Received start request. Starting profile...
,09-08 16:31:50.539  4077  4077 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 16:31:50.539  4077  4077 I bt_bluedroid: get_profile_interface avrcp
,09-08 16:31:50.545  4077  4077 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 16:31:50.545  4077  4077 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 16:31:50.546  4077  4077 D A2dpStateMachine: make
,09-08 16:31:50.547  4077  4077 I bt_bluedroid: get_profile_interface a2dp
09-08 16:31:50.547  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 16:31:50.549  4077  4108 D A2dpStateMachine: Enter Disconnected: -2
,09-08 16:31:50.550  4077  4077 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 16:31:50.551  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.552  4077  4077 D HidService: Received start request. Starting profile...
,09-08 16:31:50.552  4077  4077 I bt_bluedroid: get_profile_interface hidhost
09-08 16:31:50.552  4077  4093 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39033e5
,09-08 16:31:50.552  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 16:31:50.553  4077  4077 D HidService: setHidService(): set to: null
,09-08 16:31:50.553  4077  4077 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 16:31:50.554  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.554  3849  3849 D BluetoothInputDevice: Proxy object connected
09-08 16:31:50.555  4077  4077 D HealthService: Received start request. Starting profile...
09-08 16:31:50.556  3849  3849 D HidProfile: Bluetooth service connected
09-08 16:31:50.556  4077  4077 I bt_bluedroid: get_profile_interface health
,09-08 16:31:50.558  4077  4077 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 16:31:50.559  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.560  4077  4077 D PanService: Received start request. Starting profile...
,09-08 16:31:50.560  4077  4077 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 16:31:50.560  4077  4077 I bt_bluedroid: get_profile_interface pan
09-08 16:31:50.561  4077  4093 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 16:31:50.562  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:31:50.563  4077  4077 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:31:50.566  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 16:31:50.566  4077  4077 D BluetoothMapService: Received start request. Starting profile...
09-08 16:31:50.566  4077  4077 D BluetoothMapService: start()
,09-08 16:31:50.567  3849  3849 D PanProfile: Bluetooth service connected
,09-08 16:31:50.567  3849  3849 D BluetoothMap: Proxy object connected
09-08 16:31:50.568  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 16:31:50.569  4077  4077 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 16:31:50.569  3849  3849 D MapProfile: Bluetooth service connected
09-08 16:31:50.569  4077  4077 D BluetoothMapAppObserver: createReceiver()
,09-08 16:31:50.569  3849  3849 D BluetoothMap: getConnectedDevices()
,09-08 16:31:50.570  4077  4077 D BluetoothMapAppObserver: initObservers()
09-08 16:31:50.570  4077  4077 D BluetoothMapAppObserver: getEnabledAccountItems()
09-08 16:31:50.571  3849  3849 D BluetoothMap: Bluetooth is Not enabled
,09-08 16:31:50.578  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:31:50.578  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-08 16:31:50.578  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:50.578  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:50.578  4077  4106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 16:31:50.580  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:31:50.580  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-08 16:31:50.580  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:50.580  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:50.581  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isTurningOn()=true
09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isTurningOff()=false
09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isTurningOn()=true
,09-08 16:31:50.582  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:50.583  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:50.583  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 16:31:50.583  4077  4089 D BluetoothAdapterProperties: ScanMode =  20
09-08 16:31:50.583  4077  4089 D BluetoothAdapterProperties: State =  11
,09-08 16:31:50.586  4077  4093 D BluetoothAdapterProperties: Scan Mode:21
09-08 16:31:50.586  4077  4089 D BluetoothAdapterProperties: Setting state to 12
,09-08 16:31:50.586  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 16:31:50.586  4077  4093 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 16:31:50.586  4077  4089 I BluetoothAdapterState: Entering OnState
,09-08 16:31:50.587  1348  1695 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:31:50.589   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:31:50.589  1348  1348 D BluetoothInputDevice: Proxy object connected
09-08 16:31:50.590  1348  1348 D HidProfile: Bluetooth service connected
,09-08 16:31:50.590  1348  1368 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:50.590  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:50.593  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:50.594  3849  3860 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 16:31:50.594  1348  1348 D BluetoothMap: Proxy object connected
09-08 16:31:50.594  1348  1348 D MapProfile: Bluetooth service connected
09-08 16:31:50.594  1348  1348 D BluetoothMap: getConnectedDevices()
,09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:50.596  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:50.596  1986  2004 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:31:50.597  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:31:50.598  4077  4077 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 16:31:50.598  3849  3862 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:31:50.599  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:31:50.599  3849  3860 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:31:50.599  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:31:50.599   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:31:50.600  1348  1695 D BluetoothPan: onBluetoothStateChange on: true
,09-08 16:31:50.601  4077  4077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:31:50.603  4077  4077 D ObexServerSockets: Succeed to create listening sockets 
,09-08 16:31:50.603  4077  4077 D ObexServerSockets0: startAccept()
,09-08 16:31:50.603  4077  4077 D ObexServerSockets0: prepareForNewConnect()
,09-08 16:31:50.603  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 16:31:50.603   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:50.603  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:50.603  1348  1348 D PanProfile: Bluetooth service connected
,09-08 16:31:50.604  1348  1366 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 16:31:50.606  4077  4077 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 16:31:50.606  4077  4077 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 16:31:50.606  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:50.607  1348  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:31:50.608  1348  1348 D BluetoothA2dp: Proxy object connected
09-08 16:31:50.608  1348  1366 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:31:50.609  4077  4115 D ObexServerSockets0: Accepting socket connection...
09-08 16:31:50.609  4077  4114 D ObexServerSockets0: Accepting socket connection...
09-08 16:31:50.610  3849  3862 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:31:50.611   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:31:50.611   873   873 D BluetoothA2dp: Proxy object connected
,09-08 16:31:50.614   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 16:31:50.615  4077  4077 D BluetoothMapService: onReceive
09-08 16:31:50.615  4077  4077 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 16:31:50.615  4077  4077 D BluetoothMapService: STATE_ON
09-08 16:31:50.617  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:50.619  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:50.619  3849  3849 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 16:31:50.621  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:50.630  3849  3849 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 16:31:50.636  4077  4077 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 16:31:50.636  4077  4077 D ObexServerSockets0: prepareForNewConnect()
09-08 16:31:50.636  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:31:50.641  3849  3849 D BluetoothA2dp: Proxy object connected
,09-08 16:31:50.644  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:31:50.651  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:31:50.655  1348  1348 D BluetoothPbap: Proxy object connected
,09-08 16:31:50.655  1348  1348 D PbapServerProfile: Bluetooth service connected
,09-08 16:31:50.655  3849  3849 D BluetoothPbap: Proxy object connected
09-08 16:31:50.656  3849  3849 D PbapServerProfile: Bluetooth service connected
,09-08 16:31:50.666  4077  4120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:31:50.686  4077  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:31:50.689  4077  4124 I BtOppRfcommListener: Accept thread started.
,09-08 16:31:50.692  1348  1695 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.692  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 16:31:50.692   873   873 D BluetoothHeadset: Proxy object connected
09-08 16:31:50.692  1986  2278 D BluetoothHeadset: Proxy object connected
09-08 16:31:50.692   873   873 D BluetoothHeadset: Proxy object connected,
09-08 16:31:50.692   873   873 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.697  1986  2061 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.700   873   890 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.704   873   890 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.708  1348  1368 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.709  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 16:31:50.733  3849  3862 D BluetoothHeadset: Proxy object connected
,09-08 16:31:50.734  3849  3849 D HeadsetProfile: Bluetooth service connected
,09-08 16:31:51.410  1507  2176 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 16:31:54.033  4077  4089 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 16:31:54.034  4077  4089 D BluetoothAdapterProperties: Setting state to 13
09-08 16:31:54.034  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 16:31:54.035  4077  4089 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 16:31:54.036  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:31:54.041  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:31:54.042  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 16:31:54.044  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:54.044  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:54.045  4077  4077 D HeadsetService: Received stop request...Stopping profile...
,09-08 16:31:54.047  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:54.047  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:54.049  1348  1368 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:54.049  1348  1348 D HeadsetProfile: Bluetooth service disconnected
09-08 16:31:54.049   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:54.050  1986  2061 D BluetoothHeadset: Proxy object disconnected
,09-08 16:31:54.050   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:54.050   873   873 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:54.050  4077  4077 D A2dpService: Received stop request...Stopping profile...
09-08 16:31:54.050  3849  3860 D BluetoothHeadset: Proxy object disconnected
09-08 16:31:54.051  4077  4108 D A2dpStateMachine: Exit Disconnected: -1
09-08 16:31:54.051  3849  3849 D HeadsetProfile: Bluetooth service disconnected
09-08 16:31:54.053   873   873 D BluetoothA2dp: Proxy object disconnected
,09-08 16:31:54.054  1348  1348 D BluetoothA2dp: Proxy object disconnected
09-08 16:31:54.054  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:54.054  4077  4077 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:31:54.054  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:31:54.054  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:54.054  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:54.054  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:31:54.054  3849  3849 D BluetoothA2dp: Proxy object disconnected
09-08 16:31:54.055  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:54.055  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:54.057  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:54.058  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:31:54.058  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:31:54.058  4077  4077 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 16:31:54.058  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 16:31:54.058  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.058  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.058  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.059  4077  4093 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 16:31:54.059  3750  3750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:31:54.059  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:31:54.060  4077  4077 D HidService: Received stop request...Stopping profile...
09-08 16:31:54.060  4077  4077 D HidService: Stopping Bluetooth HidService
09-08 16:31:54.064  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:54.064  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:54.064  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:54.064  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.065  1348  1348 D BluetoothInputDevice: Proxy object disconnected
09-08 16:31:54.065  1348  1348 D HidProfile: Bluetooth service disconnected
09-08 16:31:54.066  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.066  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.066  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 16:31:54.066  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:31:54.066  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:31:54.066  4077  4099 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:31:54.066  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-08 16:31:54.067  4077  4077 D HealthService: Received stop request...Stopping profile...
09-08 16:31:54.071  4077  4077 D PanService: Received stop request...Stopping profile...
,09-08 16:31:54.073  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:31:54.073  1348  1348 D PanProfile: Bluetooth service disconnected
,09-08 16:31:54.073  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:31:54.073  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:54.073  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:54.073  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.074  4077  4077 D BluetoothMapService: Received stop request...Stopping profile...
09-08 16:31:54.074  4077  4077 D BluetoothMapService: stop()
09-08 16:31:54.074  4077  4077 D BluetoothMapAppObserver: deinitObservers()
09-08 16:31:54.075  4077  4077 D BluetoothMapAppObserver: removeReceiver()
,09-08 16:31:54.075  3849  3849 D BluetoothInputDevice: Proxy object disconnected
09-08 16:31:54.075  3849  3849 D HidProfile: Bluetooth service disconnected
,09-08 16:31:54.075  3849  3849 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:31:54.075  3849  3849 D PanProfile: Bluetooth service disconnected
09-08 16:31:54.076  3849  3849 D BluetoothMap: Proxy object disconnected
09-08 16:31:54.076  3849  3849 D MapProfile: Bluetooth service disconnected
09-08 16:31:54.076  1348  1348 D BluetoothMap: Proxy object disconnected
09-08 16:31:54.077  1348  1348 D MapProfile: Bluetooth service disconnected
09-08 16:31:54.077  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 16:31:54.077  4077  4077 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-08 16:31:54.078  4077  4077 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:31:54.078  4077  4077 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:31:54.078  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:54.078  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.078  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 16:31:54.078  4077  4093 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 16:31:54.078  4077  4093 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 16:31:54.079  4077  4077 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 16:31:54.079  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:54.079  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:54.079  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:54.079  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.079  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 16:31:54.079  4077  4077 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 16:31:54.080  4077  4077 D BluetoothMapService: MAP Service closeService in
09-08 16:31:54.080  4077  4077 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 16:31:54.080  4077  4077 D ObexServerSockets0: shutdown(block = true)
09-08 16:31:54.081  4077  4114 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 16:31:54.081  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:31:54.082  4077  4101 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 16:31:54.082  4077  4115 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 16:31:54.082  4077  4077 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 16:31:54.082  4077  4077 V BluetoothAdapterState: isTurningOff()=true
09-08 16:31:54.082  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:54.082  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:31:54.082  4077  4077 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:31:54.082  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 16:31:54.083  4077  4089 D BluetoothAdapterProperties: Setting state to 15
09-08 16:31:54.083  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 16:31:54.083  4077  4077 D BluetoothMapService: cleanup()
09-08 16:31:54.083  4077  4077 D BluetoothMapService: MAP Service closeService in
,09-08 16:31:54.083  4077  4089 I BluetoothAdapterState: Entering BleOnState
09-08 16:31:54.086  4077  4077 I BtOppRfcommListener: stopping Accept Thread
,09-08 16:31:54.086  4077  4124 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 16:31:54.087  4077  4124 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 16:31:54.087  1348  1366 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:31:54.089   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:54.089  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:54.089  1348  1695 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 16:31:54.090  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 16:31:54.090  3849  3862 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 16:31:54.090  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:54.091  1986  2002 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:54.092  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:54.092  3849  3860 D BluetoothPan: onBluetoothStateChange on: false
,09-08 16:31:54.093  3849  3862 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:31:54.097   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:31:54.097  3849  3860 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:31:54.098  1348  1695 D BluetoothPan: onBluetoothStateChange on: false
,09-08 16:31:54.099   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:31:54.099  1348  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 16:31:54.099  1348  1366 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:31:54.100  1348  1695 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 16:31:54.101  3849  3862 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 16:31:54.103  3849  3860 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 16:31:54.103   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 16:31:54.104  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 16:31:54.104  4077  4089 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 16:31:54.104  4077  4089 D BluetoothAdapterProperties: Setting state to 16
,09-08 16:31:54.104  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 16:31:54.105  4077  4089 D BluetoothAdapterProperties: onBleDisable
09-08 16:31:54.105  4077  4089 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:31:54.105  4077  4090 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 16:31:54.106  4077  4099 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 16:31:54.106  4077  4099 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:31:54.107  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:54.108  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:54.109  4077  4093 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:31:54.110  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:54.111  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:54.112  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:31:54.113  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:31:54.120  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:31:54.121  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:31:54.124  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:31:54.131  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:31:54.204  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:54.213  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:54.215  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:31:54.255  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 16:31:54.255  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 16:31:54.256  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:31:54.256  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:31:54.293  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 16:31:54.293  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 16:31:54.294  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 16:31:54.315  4077  4093 I bt_hci  : shut_down
,09-08 16:31:54.323  4077  4097 D bt_hwcfg: hw_epilog_process
,09-08 16:31:54.323  4077  4097 I bt_vendor: low_power_mode_cb
,09-08 16:31:54.347  4077  4097 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 16:31:54.347  4077  4097 I bt_vendor: epilog_cb
,09-08 16:31:54.347  4077  4097 I bt_hci  : epilog_finished_callback
,09-08 16:31:54.350  4077  4093 I bt_hci_h4: hal_close
,09-08 16:31:54.351  4077  4093 I bt_userial_vendor: device fd = 51 close
,09-08 16:31:54.480  4077  4090 D bt_stack_manager: event_shut_down_stack finished.
,09-08 16:31:54.482  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 16:31:54.486  4077  4089 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 16:31:54.487  4077  4077 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:31:54.488  4077  4077 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 16:31:54.488  4077  4077 D BtGatt.GattService: stop()
,09-08 16:31:54.489  4077  4077 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 16:31:54.492  4077  4077 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:31:54.492  4077  4077 V BluetoothAdapterState: isTurningOn()=false
09-08 16:31:54.492  4077  4077 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:31:54.492  4077  4077 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 16:31:54.494  4077  4089 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 16:31:54.495  4077  4089 D BluetoothAdapterProperties: Setting state to 10
,09-08 16:31:54.496  4077  4089 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 16:31:54.498  4077  4089 I BluetoothAdapterState: Entering OffState
,09-08 16:31:54.499   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 16:31:54.517  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-08 16:31:54.518  4077  4077 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 16:31:54.518  4077  4090 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 16:31:54.521  4077  4090 D bt_stack_manager: event_clean_up_stack finished.
09-08 16:31:54.521  4077  4077 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 16:31:54.523  4077  4077 I art     : System.exit called, status: 0
,09-08 16:31:54.523  4077  4077 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 16:31:54.599   873  1389 I ActivityManager: Process com.android.bluetooth (pid 4077) has died
,09-08 16:31:59.033  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:59.033  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:59.039  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:59.039  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a89af78 removed from the list
,09-08 16:31:59.040  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:31:59.040  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:31:59.040  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:59.045  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:31:59.046  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d33eb6 added. We now have 4 listener(s)
,09-08 16:31:59.047  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:31:59.049  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:31:59.049  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d33eb6 removed from the list
09-08 16:31:59.049  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:31:59.050  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:31:59.050  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:31:59.053  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:31:59.053  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d157b7 added. We now have 4 listener(s)
09-08 16:31:59.053  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:32:04.064  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:04.114   873   890 I ActivityManager: Start proc 4136:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 16:32:04.240  4136  4136 D AdapterServiceConfig: Adding HeadsetService
09-08 16:32:04.241  4136  4136 D AdapterServiceConfig: Adding A2dpService
,09-08 16:32:04.241  4136  4136 D AdapterServiceConfig: Adding HidService
09-08 16:32:04.241  4136  4136 D AdapterServiceConfig: Adding HealthService
09-08 16:32:04.241  4136  4136 D AdapterServiceConfig: Adding PanService
09-08 16:32:04.241  4136  4136 D AdapterServiceConfig: Adding GattService
,09-08 16:32:04.242  4136  4136 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 16:32:04.256  4136  4136 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 16:32:04.257   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@47ef06b:true
,09-08 16:32:04.267  4136  4148 I BluetoothAdapterState: Entering OffState
,09-08 16:32:04.267  4136  4136 I bt_bluedroid: init
,09-08 16:32:04.275  4136  4149 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-08 16:32:04.276  4136  4149 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 16:32:04.276  4136  4149 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 16:32:04.276  4136  4149 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 16:32:04.278  4136  4136 I bt_bluedroid: get_profile_interface socket
,09-08 16:32:04.284  4136  4136 I bt_bluedroid: get_profile_interface sdp
09-08 16:32:04.284  4136  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:32:04.288  4136  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:32:04.294  4136  4147 I bt_bluedroid: config_hci_snoop_log
,09-08 16:32:04.296   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 16:32:04.309  4136  4148 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 16:32:04.310  4136  4148 D BluetoothAdapterProperties: Setting state to 14
09-08 16:32:04.310  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 16:32:04.316  4136  4148 D BluetoothBondStateMachine: make
,09-08 16:32:04.321  4136  4153 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 16:32:04.333  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:32:04.334  4136  4136 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 16:32:04.343  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:32:04.345  4136  4136 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:32:04.346  4136  4136 D BtGatt.GattService: Received start request. Starting profile...
09-08 16:32:04.347  4136  4136 D BtGatt.GattService: start()
,09-08 16:32:04.347  4136  4136 I bt_bluedroid: get_profile_interface gatt
,09-08 16:32:04.350  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
09-08 16:32:04.350  4136  4136 D BtGatt.AdvertiseManager: advertise manager created
,09-08 16:32:04.359  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:32:04.359  4136  4136 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:32:04.359  4136  4136 V BluetoothAdapterState: isBleTurningOn()=true
09-08 16:32:04.359  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:32:04.359  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 16:32:04.360  4136  4148 I bt_bluedroid: enable
09-08 16:32:04.360  4136  4149 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 16:32:04.361  4136  4149 I bt_hci  : start_up
,09-08 16:32:04.368  4136  4149 I bt_vendor: alloc value 0xb39a4189
,09-08 16:32:04.368  4136  4149 I bt_vendor: init
09-08 16:32:04.368  4136  4149 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 16:32:04.368  4136  4149 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 16:32:04.477  4136  4149 D bt_hci  : start_up starting async portion
,09-08 16:32:04.478  4136  4156 I bt_hci  : event_finish_startup
09-08 16:32:04.479  4136  4156 I bt_hci_h4: hal_open
,09-08 16:32:04.479  4136  4156 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 16:32:04.488  4136  4156 I bt_userial_vendor: device fd = 51 open
,09-08 16:32:04.520  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:32:04.552  4136  4156 D bt_hwcfg: Chipset BCM4354A2
,09-08 16:32:04.552  4136  4156 D bt_hwcfg: Target name = [BCM4354A2]
09-08 16:32:04.553  4136  4156 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 16:32:05.391  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 16:32:05.392  4136  4156 D bt_hwcfg: Settlement delay -- 100 ms
09-08 16:32:05.392  4136  4156 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 16:32:05.510  4136  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:32:05.512  4136  4156 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 16:32:05.540  4136  4156 I bt_hwcfg: vendor lib fwcfg completed
,09-08 16:32:05.541  4136  4156 I bt_vendor: firmware callback
09-08 16:32:05.541  4136  4156 I bt_hci  : firmware_config_callback
,09-08 16:32:05.554  4136  4158 I bt_btu  : btu_task pending for preload complete event
,09-08 16:32:05.554  4136  4158 I bt_btu_task: Bluetooth chip preload is complete
09-08 16:32:05.554  4136  4158 I bt_btu  : btu_task received preload complete event
,09-08 16:32:05.567  4136  4158 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 16:32:05.567  4136  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 16:32:05.567  4136  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 16:32:05.568  4136  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 16:32:05.568  4136  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 16:32:05.568  4136  4158 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 16:32:05.568  4136  4158 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 16:32:05.569  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 16:32:05.569  4136  4158 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 16:32:05.570  4136  4158 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 16:32:05.570  4136  4158 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 16:32:05.570  4136  4158 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 16:32:05.571  4136  4158 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 16:32:05.571  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 16:32:05.571  4136  4158 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 16:32:05.715  4136  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3921d9d
,09-08 16:32:05.716  4136  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3921d9d 
,09-08 16:32:05.725  4136  4152 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-08 16:32:05.727  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
09-08 16:32:05.728  4136  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:32:05.731  4136  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:32:05.735  4136  4152 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:32:05.735  4136  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 16:32:05.736  4136  4152 D bt_hci  : do_postload posting postload work item
09-08 16:32:05.736  4136  4156 I bt_hci  : event_postload
,09-08 16:32:05.737  4136  4156 I bt_vendor: sco_config_cb
09-08 16:32:05.737  4136  4156 I bt_hci  : sco_config_callback postload finished.
,09-08 16:32:05.739  4136  4152 D bt_bte_conf: Device ID record 1 : primary
09-08 16:32:05.740  4136  4152 D bt_bte_conf:   vendorId            = 000f
09-08 16:32:05.740  4136  4152 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 16:32:05.740  4136  4152 D bt_bte_conf:   product             = 1200
,09-08 16:32:05.740  4136  4152 D bt_bte_conf:   version             = 1436
,09-08 16:32:05.740  4136  4152 D bt_bte_conf:   clientExecutableURL = 
,09-08 16:32:05.741  4136  4152 D bt_bte_conf:   serviceDescription  = 
09-08 16:32:05.741  4136  4152 D bt_bte_conf:   documentationURL    = 
09-08 16:32:05.741  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:05.742  4136  4152 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 16:32:05.743  4136  4149 D bt_stack_manager: event_start_up_stack finished
09-08 16:32:05.744  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 16:32:05.744  4136  4148 D BluetoothAdapterProperties: Setting state to 15
09-08 16:32:05.744  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 16:32:05.745  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:05.746  4136  4156 I bt_vendor: low_power_mode_cb
09-08 16:32:05.746  4136  4148 I BluetoothAdapterState: Entering BleOnState
,09-08 16:32:05.750  4136  4148 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 16:32:05.751  4136  4148 D BluetoothAdapterProperties: Setting state to 11
,09-08 16:32:05.751  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 16:32:05.758  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:05.760  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:05.763  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:32:05.764  4136  4136 D HeadsetService: Received start request. Starting profile...
09-08 16:32:05.769  4136  4136 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 16:32:05.770  4136  4136 D HeadsetStateMachine: make,
09-08 16:32:05.774  4136  4148 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:32:05.780  4136  4136 D HeadsetStateMachine: max_hf_connections = 1
,09-08 16:32:05.781  4136  4136 I bt_bluedroid: get_profile_interface handsfree
,09-08 16:32:05.781  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 16:32:05.782  4136  4152 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-08 16:32:05.785  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:32:05.786  4136  4136 D A2dpService: Received start request. Starting profile...
,09-08 16:32:05.787  4136  4136 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 16:32:05.787  4136  4136 I bt_bluedroid: get_profile_interface avrcp
,09-08 16:32:05.787  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:32:05.792  4136  4136 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 16:32:05.793  4136  4136 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 16:32:05.793  4136  4136 D A2dpStateMachine: make
09-08 16:32:05.794  4136  4136 I bt_bluedroid: get_profile_interface a2dp
,09-08 16:32:05.794  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 16:32:05.796  4136  4167 D A2dpStateMachine: Enter Disconnected: -2
,09-08 16:32:05.796  4136  4136 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 16:32:05.797  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:32:05.797  4136  4136 D HidService: Received start request. Starting profile...
,09-08 16:32:05.797  4136  4136 I bt_bluedroid: get_profile_interface hidhost
09-08 16:32:05.797  4136  4136 D HidService: setHidService(): set to: null
09-08 16:32:05.798  4136  4152 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39033e5
09-08 16:32:05.798  4136  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 16:32:05.798  4136  4136 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 16:32:05.799  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
09-08 16:32:05.799  4136  4136 D HealthService: Received start request. Starting profile...
,09-08 16:32:05.801  4136  4136 I bt_bluedroid: get_profile_interface health
,09-08 16:32:05.802  4136  4136 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 16:32:05.802  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
09-08 16:32:05.803  4136  4136 D PanService: Received start request. Starting profile...
09-08 16:32:05.803  4136  4136 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 16:32:05.803  4136  4136 I bt_bluedroid: get_profile_interface pan
09-08 16:32:05.803  4136  4152 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 16:32:05.806  4136  4136 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
09-08 16:32:05.806  4136  4136 D BluetoothMapService: Received start request. Starting profile...
09-08 16:32:05.806  4136  4136 D BluetoothMapService: start()
,09-08 16:32:05.809  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 16:32:05.811  4136  4136 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 16:32:05.811  4136  4136 D BluetoothMapAppObserver: createReceiver()
,09-08 16:32:05.812  4136  4136 D BluetoothMapAppObserver: initObservers()
,09-08 16:32:05.812  4136  4136 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 16:32:05.819  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:32:05.819  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-08 16:32:05.819  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:32:05.819  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:32:05.819  4136  4165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 16:32:05.821  4136  4136 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:32:05.821  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-08 16:32:05.821  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:32:05.821  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isTurningOn()=true
,09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:32:05.822  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isTurningOn()=true
,09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isTurningOff()=false
09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isTurningOn()=true
09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:32:05.823  4136  4136 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:32:05.823  4136  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 16:32:05.823  4136  4148 D BluetoothAdapterProperties: ScanMode =  20
09-08 16:32:05.824  4136  4148 D BluetoothAdapterProperties: State =  11
09-08 16:32:05.826  4136  4152 D BluetoothAdapterProperties: Scan Mode:21
09-08 16:32:05.826  4136  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 16:32:05.827  4136  4148 D BluetoothAdapterProperties: Setting state to 12
,09-08 16:32:05.827  4136  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 16:32:05.827  4136  4148 I BluetoothAdapterState: Entering OnState
09-08 16:32:05.827  1348  1366 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:32:05.830  1348  1348 D BluetoothInputDevice: Proxy object connected
09-08 16:32:05.830  1348  1348 D HidProfile: Bluetooth service connected
09-08 16:32:05.830   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:32:05.830  1348  1695 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:32:05.831  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:32:05.832  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:32:05.833  1348  1348 D BluetoothMap: Proxy object connected
09-08 16:32:05.833  1348  1348 D MapProfile: Bluetooth service connected
09-08 16:32:05.833  1348  1348 D BluetoothMap: getConnectedDevices()
09-08 16:32:05.833  3849  3862 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:32:05.835  1986  2061 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:32:05.836  3849  3860 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:32:05.836  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:32:05.838  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:32:05.838  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:32:05.838  3849  4130 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:32:05.839  4136  4136 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 16:32:05.840  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:32:05.840   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:32:05.841  3849  3860 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:32:05.841  3849  3849 D BluetoothInputDevice: Proxy object connected
,09-08 16:32:05.841  1348  1368 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:32:05.842  3849  3849 D HidProfile: Bluetooth service connected
,09-08 16:32:05.842  4136  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:32:05.843   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:32:05.843  1348  1695 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:32:05.843  4136  4136 D ObexServerSockets: Succeed to create listening sockets 
09-08 16:32:05.844  4136  4136 D ObexServerSockets0: startAccept()
09-08 16:32:05.844  4136  4136 D ObexServerSockets0: prepareForNewConnect()
09-08 16:32:05.844  1348  1366 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:32:05.845  1348  1368 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:32:05.846  4136  4136 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 16:32:05.846  4136  4136 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 16:32:05.846  3849  3862 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:32:05.846  4136  4173 D ObexServerSockets0: Accepting socket connection...
09-08 16:32:05.847  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 16:32:05.847  1348  1348 D PanProfile: Bluetooth service connected
09-08 16:32:05.847  1348  1348 D BluetoothA2dp: Proxy object connected
09-08 16:32:05.848  4136  4174 D ObexServerSockets0: Accepting socket connection...
09-08 16:32:05.848  3849  4130 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:32:05.850   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:32:05.850   873   873 D BluetoothA2dp: Proxy object connected
09-08 16:32:05.852  3849  3849 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 16:32:05.852  3849  3849 D PanProfile: Bluetooth service connected
09-08 16:32:05.852  4136  4136 D BluetoothMapService: onReceive
09-08 16:32:05.852  4136  4136 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 16:32:05.852  3849  3849 D BluetoothMap: Proxy object connected
09-08 16:32:05.852  3849  3849 D MapProfile: Bluetooth service connected
09-08 16:32:05.852  4136  4136 D BluetoothMapService: STATE_ON
09-08 16:32:05.852  3849  3849 D BluetoothMap: getConnectedDevices()
09-08 16:32:05.853  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:05.853   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 16:32:05.854  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:05.854  3849  3849 D BluetoothA2dp: Proxy object connected
,09-08 16:32:05.861  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:32:05.866  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:32:05.868  3849  3849 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:32:05.874  3849  3849 D BluetoothPbap: Proxy object connected
,09-08 16:32:05.874  3849  3849 D PbapServerProfile: Bluetooth service connected
,09-08 16:32:05.879  1348  1348 D BluetoothPbap: Proxy object connected
,09-08 16:32:05.879  1348  1348 D PbapServerProfile: Bluetooth service connected
09-08 16:32:05.879  4136  4136 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:32:05.879  4136  4136 D ObexServerSockets0: prepareForNewConnect()
,09-08 16:32:05.880  4136  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:32:05.892  4136  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:32:05.893  4136  4184 I BtOppRfcommListener: Accept thread started.
,09-08 16:32:05.933  1348  1368 D BluetoothHeadset: Proxy object connected
09-08 16:32:05.933   873   873 D BluetoothHeadset: Proxy object connected
09-08 16:32:05.933  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 16:32:05.933  1986  2002 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.934   873   873 D BluetoothHeadset: Proxy object connected
09-08 16:32:05.934   873   873 D BluetoothHeadset: Proxy object connected
09-08 16:32:05.934  3849  3860 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.934  3849  3849 D HeadsetProfile: Bluetooth service connected
09-08 16:32:05.936  1986  2004 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.941   873   890 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.941  3849  4130 D BluetoothHeadset: Proxy object connected
09-08 16:32:05.942  3849  3849 D HeadsetProfile: Bluetooth service connected
,09-08 16:32:05.943   873   890 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.945  1348  1695 D BluetoothHeadset: Proxy object connected
,09-08 16:32:05.945  1348  1348 D HeadsetProfile: Bluetooth service connected
,09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:32:09.084  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:32:09.092  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:32:09.093  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:09.093  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d157b7 removed from the list
09-08 16:32:09.093  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:32:09.093  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:09.094  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:09.096  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:32:09.097  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4664b24 added. We now have 4 listener(s)
,09-08 16:32:09.098  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:32:09.102   873  1683 D WifiService: setWifiEnabled: false pid=3750, uid=10000
09-08 16:32:09.102   873  1683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:32:14.115  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:14.116   873  3104 D WifiService: setWifiEnabled: true pid=3750, uid=10000
09-08 16:32:14.117   873  3104 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:32:14.128   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:32:14.148  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:32:14.154  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:32:14.160   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-08 16:32:14.161   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 16:32:14.162   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 16:32:14.162   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 16:32:14.163   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 16:32:14.163   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:32:14.163  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:32:14.163   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-08 16:32:14.167  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:32:14.177   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:32:14.177   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 16:32:14.178   372   871 D CommandListener: Setting iface cfg
,09-08 16:32:14.229   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 16:32:14.229   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 16:32:14.234   873  1303 E native  : do suspend true
,09-08 16:32:14.250   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 16:32:14.259   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 16:32:14.264   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:32:15.551   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:32:15.698   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=14.94 delta 1000 -> 994
,09-08 16:32:15.700   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 16:32:15.701   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:32:15.717   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 16:32:15.770   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 16:32:15.772  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 16:32:16.204  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 16:32:16.246  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 16:32:16.246  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 16:32:16.253   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:32:16.268   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:32:16.268   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 16:32:16.268   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:32:16.291   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:32:16.321   372   871 D CommandListener: Setting iface cfg
,09-08 16:32:16.325   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 16:32:16.339   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 16:32:16.364   873  4194 D DhcpClient: Receive thread started
,09-08 16:32:16.462   873  1303 E native  : do suspend false
,09-08 16:32:16.488   873  2093 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 16:32:16.496  1892  1952 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-08 16:32:16.497  1892  1952 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 16:32:16.503   873  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-08 16:32:16.504   873  2093 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-08 16:32:16.508   873  2093 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 16:32:16.521   873  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 16:32:16.522   873  2093 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 16:32:16.527   372   871 D CommandListener: Setting iface cfg
,09-08 16:32:16.538   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-08 16:32:16.539   873  2093 D DhcpClient: Scheduling renewal in 86399s
,09-08 16:32:16.541   873  1303 E native  : do suspend true
,09-08 16:32:16.551  1507  1507 I ConfigService: onCreate
,09-08 16:32:16.559   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-08 16:32:16.562   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-08 16:32:16.563   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-08 16:32:16.565   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
09-08 16:32:16.573   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 16:32:16.622   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 16:32:16.622   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 16:32:16.624   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 16:32:16.625   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 16:32:16.626   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 16:32:16.638   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 16:32:16.642   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 16:32:16.642   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 16:32:16.642   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 16:32:16.642   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 16:32:16.642   873  1305 D ConnectivityService:    accepting network in place of null
09-08 16:32:16.643   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 16:32:16.643   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:32:16.649   873  4193 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210646, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:32:16.663   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:32:16.683   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:32:16.690   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 16:32:16.690   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:32:16.698   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 16:32:16.701   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:16.707  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:32:16.708  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:16.717  3750  3750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:32:16.719   873  4192 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:815::200e
09-08 16:32:16.719  3750  3750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:32:16.725  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 16:32:16.729  1699  1699 D SystemUpdateService: onCreate
,09-08 16:32:16.732  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:32:16.745  1699  4204 I SystemUpdateService: active receiver: enabled
,09-08 16:32:16.750  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 16:32:16.756  1699  2518 I iu.UploadsManager: num queued entries: 0
,09-08 16:32:16.757  1699  2518 I iu.UploadsManager: num updated entries: 0
09-08 16:32:16.757  1699  4204 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:32:16.759  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 16:32:16.760  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:32:16.761  3905  3905 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:32:16.772  1699  4204 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 16:32:16.772  1699  4204 I SystemUpdateService: now status is 0 (complete)
09-08 16:32:16.772  1699  4204 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 16:32:16.772  1699  4204 I SystemUpdateService: file has been verified
,09-08 16:32:16.772  1699  4204 I SystemUpdateService: OTA package size = 12249756
09-08 16:32:16.773  1699  4207 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 16:32:16.773  1699  4207 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 16:32:16.775  1699  4207 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 16:32:16.776  3905  3905 D SprintDMHelper: simOperator: 
09-08 16:32:16.776  3905  3905 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:32:16.787   873  4192 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 14:32:16 GMT], X-Android-Received-Millis=[1473345136785], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473345136760]}
,09-08 16:32:16.789  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:32:16.789   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 16:32:16.790   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 16:32:16.791   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 16:32:16.791  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 16:32:16.805  1699  2518 I iu.SyncManager: NEXT; no task
,09-08 16:32:16.817   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 16:32:16.819  1699  4204 I SystemUpdateService: showing system update notification
,09-08 16:32:16.842  1507  1945 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 16:32:16.843  1507  1945 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 16:32:16.843  1507  1945 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:32:16.844  1507  1945 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:32:16.850  1699  1699 D SystemUpdateService: onDestroy,
,09-08 16:32:16.869  1699  4207 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-08 16:32:16.902  2130  4209 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 16:32:17.690   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:19.142  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:19.150  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:32:19.152  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:32:19.153  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4664b24 removed from the list
,09-08 16:32:19.153  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:32:19.154  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:32:19.154  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:19.172  3750  4218 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 16:32:19.172  3750  4218 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 16:32:21.645  1507  1507 I ConfigService: onDestroy
,09-08 16:32:22.178  3750  4220 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 16:32:22.179  3750  4218 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 16:32:22.181  3750  4220 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:32:22.182  3750  4218 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:32:22.183  3750  4218 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:32:22.183  3750  4220 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:32:22.184  3750  4218 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:32:22.184  3750  4220 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:32:22.190  3750  4218 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 16:32:22.190  3750  4220 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 16:32:22.194  3750  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 414, name: OutgoingSocketThread/Sender)
,09-08 16:32:22.200  3750  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 413, name: IncomingSocketThread/Sender)
,09-08 16:32:22.203  3750  4224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 415, name: OutgoingSocketThread/Receiver)
,09-08 16:32:22.204  3750  4224 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 415, thread name: OutgoingSocketThread/Receiver)
09-08 16:32:22.204  3750  4224 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 16:32:22.205  3750  4224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 415, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 16:32:22.205  3750  4225 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 416, name: IncomingSocketThread/Receiver)
,09-08 16:32:22.207  3750  4225 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 416, thread name: IncomingSocketThread/Receiver)
,09-08 16:32:22.207  3750  4225 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 16:32:22.207  3750  4225 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 416, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 16:32:24.649   873  1305 D ConnectivityService: handlePromptUnvalidated 102
,09-08 16:32:25.178  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 16:32:25.181  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 16:32:25.188  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dbaa3f2 Bundle[{}]
,09-08 16:32:25.188  3750  3799 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 16:32:25.188  3750  3799 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 16:32:25.189  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 16:32:25.189  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 16:32:25.190  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 16:32:25.190  3750  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 16:32:25.194  3750  3799 I System.out: Running OutgoingSocketThread
09-08 16:32:25.198  3750  4226 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 16:32:25.198  3750  4226 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 16:32:28.207  3750  4227 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 16:32:28.207  3750  4227 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:32:28.208  3750  4227 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:32:28.208  3750  4226 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 16:32:28.208  3750  4226 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 16:32:28.209  3750  4227 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:32:28.209  3750  4226 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:32:28.212  3750  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
09-08 16:32:28.212  3750  4226 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:32:28.215  3750  4226 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 16:32:28.220  3750  4227 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 16:32:28.223  3750  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-08 16:32:28.226  3750  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
,09-08 16:32:28.228  3750  4231 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
,09-08 16:32:28.229  3750  4231 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 16:32:28.229  3750  4232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
,09-08 16:32:28.229  3750  4231 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 16:32:28.231  3750  4232 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
09-08 16:32:28.232  3750  4232 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 16:32:28.232  3750  4232 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 16:32:31.209  3750  3799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
09-08 16:32:31.211  3750  3799 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 16:32:31.212  3750  3799 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,09-08 16:32:31.218  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:32:31.218  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4b268d added. We now have 3 listener(s)
,09-08 16:32:31.220  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:31.220  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:32:31.220  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:32:31.221  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:32:31.221  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcc9042 added. We now have 4 listener(s)
09-08 16:32:31.221  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:32:31.222  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:32:31.229  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:31.238  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:31.243  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:32:31.244  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:32:31.244  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:32:31.244  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:32:31.244  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:32:31.245  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:31.245  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:32:31.245  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:31.245  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:32:31.245  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4b268d removed from the list
,09-08 16:32:31.245  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:31.245  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcc9042 removed from the list
09-08 16:32:31.249  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:31.250  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:32:31.250  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:31.251  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:32:31.251  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:31.252  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:32:31.253  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:31.253  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:31.253  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcc9042 not in the list
09-08 16:32:31.253  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:31.253  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:31.256  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:31.256  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:31.256  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:31.257  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcc9042 not in the list
09-08 16:32:31.257  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:31.257  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:31.257  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:31.258  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:31.258  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4b268d not in the list
09-08 16:32:31.260  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:32:31.260  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ef590 added. We now have 3 listener(s)
,09-08 16:32:31.266  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:31.267  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:32:31.267  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:32:31.267  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:32:31.268  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd09e89 added. We now have 4 listener(s)
09-08 16:32:31.268  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:32:31.270  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:32:31.276  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:31.288  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:31.294  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:32:31.295  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:32:31.296  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:32:31.296  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 16:32:31.296  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:32:31.297  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:32:31.297  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 16:32:31.302  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:31.306  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:32:31.306  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:32:31.308  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:31.320  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:32:31.323  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:32:31.324  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:32:31.336  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 16:32:31.337  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:32:31.337  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:32:31.340  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:32:31.349  4136  4172 D BtGatt.GattService: registerClient() - UUID=7a63b174-9fbe-41de-8ec9-84ff2e201f02
,09-08 16:32:31.351  4136  4152 D BtGatt.GattService: onClientRegistered() - UUID=7a63b174-9fbe-41de-8ec9-84ff2e201f02, clientIf=5
,09-08 16:32:31.352  3750  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:32:31.355  4136  4176 D BtGatt.GattService: start scan with filters
,09-08 16:32:31.366  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 16:32:31.367  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 16:32:31.367  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 16:32:31.368  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 16:32:31.368  4136  4155 D BtGatt.ScanManager: handling starting scan
,09-08 16:32:31.373  4136  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ea6b54
,09-08 16:32:31.379  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:32:31.381  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:32:31.381  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:32:31.390  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:32:31.390  4136  4152 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 16:32:31.390  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.392  4136  4155 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:32:31.401  3750  3799 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 16:32:31.401  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:32:31.402  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:32:31.402  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:31.402  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:32:31.402  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:32:31.402  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:32:31.403  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:32:31.403  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:32:31.409  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 16:32:31.409  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 16:32:31.410  4136  4152 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:32:31.410  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.411  3750  3799 D BluetoothAdapter: STATE_ON
09-08 16:32:31.412  4136  4155 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:32:31.412  4136  4155 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 16:32:31.413  4136  4164 D BtGatt.GattService: stopScan() - queue size =1
,09-08 16:32:31.415  4136  4172 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:32:31.416  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 16:32:31.416  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 16:32:31.416  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 16:32:31.417  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:32:31.417  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:32:31.420  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:32:31.420  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:32:31.420  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-08 16:32:31.421  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:32:31.422  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:31.426  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:32:31.426  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:32:31.427  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:32:31.435  4136  4152 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 16:32:31.435  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.453  4136  4152 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 16:32:31.454  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.476  4136  4152 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 16:32:31.477  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.478  4136  4155 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:32:31.500  4136  4152 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:32:31.501  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.502  4136  4155 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:32:31.524  4136  4152 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:32:31.524  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:31.928  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 16:32:31.929  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:32:31.929  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:32:34.428  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:32:34.429  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:32:34.429  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:32:34.429  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:34.430  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:34.430  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:34.430  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 16:32:34.431  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ef590 removed from the list
09-08 16:32:34.431  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:34.431  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd09e89 removed from the list
09-08 16:32:34.432  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:32:34.432  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:34.434  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:34.434  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:34.437  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:32:34.437  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:34.438  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:34.438  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd09e89 not in the list
09-08 16:32:34.439  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:34.439  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:34.442  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:34.442  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:34.442  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:34.443  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd09e89 not in the list
09-08 16:32:34.443  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:34.443  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:34.444  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:34.444  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4ef590 not in the list
,09-08 16:32:34.447  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-08 16:32:34.447  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1fe59a added. We now have 3 listener(s)
,09-08 16:32:34.452  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:34.453  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:32:34.453  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 16:32:34.453  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:32:34.454  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5decb added. We now have 4 listener(s)
,09-08 16:32:34.454  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:32:34.455  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:32:34.462  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:34.474  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:34.479  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:34.480  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:32:34.481  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 16:32:34.482  3750  3799 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 16:32:34.483  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 16:32:34.483  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 16:32:34.484  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 16:32:34.484  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 16:32:34.484  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:34.486  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 16:32:34.489  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:34.491  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 16:32:34.491  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 16:32:34.492  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 16:32:34.492  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 16:32:34.492  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:32:34.492  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:32:34.499  3750  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:32:34.501  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:34.502  3750  3750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
09-08 16:32:34.506  3750  4233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 16:32:34.507  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 16:32:34.507  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:32:34.515  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:32:34.516  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:32:34.516  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:32:34.519  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 16:32:34.519  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:34.520  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-08 16:32:34.521  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 16:32:34.521  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 16:32:34.521  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 16:32:34.523  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:32:34.526  4136  4146 D BtGatt.GattService: registerClient() - UUID=11ce23f3-0770-4ebd-a0a9-026023c574f4
,09-08 16:32:34.526  4136  4152 D BtGatt.GattService: onClientRegistered() - UUID=11ce23f3-0770-4ebd-a0a9-026023c574f4, clientIf=5
09-08 16:32:34.527  3750  3761 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 16:32:34.532  4136  4154 D BtGatt.AdvertiseManager: message : 0
,09-08 16:32:34.536  4136  4154 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 16:32:34.548  4136  4152 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 16:32:34.556  4136  4152 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 16:32:34.557  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 16:32:34.558  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:32:34.563  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:32:34.566  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 16:32:34.567  3750  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 16:32:34.567  3750  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 16:32:34.567  3750  3750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 16:32:34.568  3750  3750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 16:32:34.568  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 16:32:34.573  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 16:32:34.574  3750  3750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 16:32:34.574  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 16:32:35.075  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 16:32:35.075  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 16:32:35.076  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:32:37.084  3872  4234 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 16:32:37.579  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:32:37.579  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 16:32:37.580  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:32:37.580  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 16:32:37.580  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 16:32:37.580  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 16:32:37.583  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:32:37.583  3750  4233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 16:32:37.583  3750  4233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 16:32:37.583  3750  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 16:32:37.583  3750  4233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 16:32:37.584  3750  3750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 16:32:37.584  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:32:37.585  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:32:37.585  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:32:37.585  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:32:37.585  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:32:37.587  3750  3799 D BluetoothAdapter: STATE_ON
09-08 16:32:37.587  3750  3799 D BluetoothLeScanner: could not find callback wrapper
09-08 16:32:37.588  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 16:32:37.588  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 16:32:37.590  4136  4154 D BtGatt.AdvertiseManager: message : 1
,09-08 16:32:37.592  4136  4154 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 16:32:37.601  4136  4152 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 16:32:37.601  4136  4152 D BtGatt.GattService: Client app is not null!
,09-08 16:32:37.604  4136  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:32:37.605  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:32:37.606  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 16:32:37.606  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 16:32:37.606  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 16:32:37.606  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 16:32:37.609  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:32:37.609  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:32:37.610  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:32:37.618  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:32:37.621  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:32:37.621  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:37.621  3750  3750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 16:32:37.621  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:37.621  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:32:37.621  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1fe59a removed from the list
09-08 16:32:37.621  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:32:37.621  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:32:37.621  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5decb removed from the list
09-08 16:32:37.621  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:32:37.622  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:37.622  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:32:37.622  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:32:37.625  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:32:37.625  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:37.632  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:37.632  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:37.632  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:37.632  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5decb not in the list
09-08 16:32:37.633  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:37.633  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:37.635  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:37.635  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:37.635  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:37.635  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5decb not in the list
,09-08 16:32:37.635  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:37.636  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:37.636  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:37.636  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1fe59a not in the list
09-08 16:32:37.637  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 16:32:37.637  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d84c554 added. We now have 3 listener(s)
,09-08 16:32:37.642  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:37.642  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:32:37.642  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:32:37.643  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:32:37.643  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89fccfd added. We now have 4 listener(s)
09-08 16:32:37.643  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:32:37.644  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:32:37.647  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:37.652  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:37.655  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:32:37.655  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:32:37.656  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:32:37.656  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 16:32:37.656  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:32:37.656  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:32:37.656  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 16:32:37.658  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:37.659  3750  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:32:37.659  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:32:37.660  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:37.662  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:32:37.663  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:32:37.663  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:32:37.666  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 16:32:37.666  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:32:37.666  3750  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 16:32:37.666  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:32:37.668  4136  4176 D BtGatt.GattService: registerClient() - UUID=77c6b1c4-66d8-412d-ba40-524a799aad73
,09-08 16:32:37.668  4136  4152 D BtGatt.GattService: onClientRegistered() - UUID=77c6b1c4-66d8-412d-ba40-524a799aad73, clientIf=5
09-08 16:32:37.668  3750  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 16:32:37.669  4136  4164 D BtGatt.GattService: start scan with filters
,09-08 16:32:37.671  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 16:32:37.671  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 16:32:37.671  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:32:37.671  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 16:32:37.671  4136  4155 D BtGatt.ScanManager: handling starting scan
,09-08 16:32:37.673  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:32:37.674  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:32:37.674  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:32:37.675  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:32:37.682  4136  4152 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 16:32:37.682  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:37.682  4136  4155 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:32:37.688  4136  4152 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 16:32:37.688  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:37.688  4136  4155 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:32:37.689  4136  4155 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:32:37.699  4136  4152 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 16:32:37.699  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:37.704  4136  4152 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 16:32:37.704  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:37.711  1507  4239 V NQFileLogger: [137] e.a: about to write to file
,09-08 16:32:37.720  1507  4239 V ProcessReports: [137] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,09-08 16:32:38.123  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:32:38.174  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:32:38.174  3750  3750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:32:38.175  3750  3750 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:32:38.209  4136  4136 D BtGatt.ScanManager: awakened up at time 232207
,09-08 16:32:38.211  4136  4155 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:32:38.268  4136  4152 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 16:32:38.269  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:32:38.269  4136  4152 D BtGatt.GattService: current time is 232267697156
,09-08 16:32:38.271  4136  4152 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -95, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -118, -49, 13, -43, 68, 112, 1, -128, -36, 5, 0, 0, 0, -118, -49, 13, -43, 68, 112, 1, -128, -35, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 16:32:38.275  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:32:38.278  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:32:38.279  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 16:32:38.280  4136  4152 D BtGatt.GattService: ScanRecord : []
09-08 16:32:38.280  4136  4152 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-08 16:32:38.282  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:32:38.283  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:32:38.283  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 16:32:38.289  3750  3750 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,09-08 16:32:38.292  3750  3750 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-08 16:32:39.771  4136  4136 D BtGatt.ScanManager: awakened up at time 233769
,09-08 16:32:39.773  4136  4155 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:32:39.844  4136  4152 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 16:32:39.844  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:39.845  4136  4152 D BtGatt.GattService: current time is 233843622982
,09-08 16:32:39.846  4136  4152 D BtGatt.GattService: Batch record : [-118, -49, 13, -43, 68, 112, 1, -128, -36, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 35, 97, 126, -92, 22, -56, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -94, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -75, 112, 8, 38, 113, -28, 1, 0, -106, 16, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 5, -112, -6, 2, 2, -29, 23, 62, -17, -44, -78, 28, 6, 8, 116, 105, 115, 55, 52, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:32:39.847  4136  4152 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-08 16:32:39.849  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:32:39.850  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:32:39.851  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:32:39.852  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 16:32:39.853  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 5, -112, -6, 2, 2, -29, 23, 62, -17, -44, -78, 6, 8, 116, 105, 115, 55, 52, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-08 16:32:39.854  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:32:39.855  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 16:32:39.860  3750  3750 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 1] updated - the peer count is 1
,09-08 16:32:40.686  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:32:40.686  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:32:40.687  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:32:40.687  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:32:40.687  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 16:32:40.688  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:32:40.688  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:32:40.688  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:32:40.689  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:32:40.690  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:32:40.690  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 16:32:40.692  3750  3799 D BluetoothAdapter: STATE_ON
,09-08 16:32:40.694  4136  4175 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:32:40.697  4136  4176 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 16:32:40.698  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:32:40.698  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 16:32:40.699  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 16:32:40.699  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:32:40.699  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:32:40.703  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:32:40.704  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 16:32:40.704  3750  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:32:40.704  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 16:32:40.707  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:40.707  3750  3799 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-08 16:32:40.708  4136  4136 D BtGatt.ScanManager: awakened up at time 234707
,09-08 16:32:40.715  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:40.715  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:32:40.715  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.716  3750  3750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:32:40.716  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:32:40.716  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:32:40.716  3750  3750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:32:40.716  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d84c554 removed from the list
09-08 16:32:40.717  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:40.717  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89fccfd removed from the list
09-08 16:32:40.717  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:32:40.717  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.720  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.721  4136  4152 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:32:40.721  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.721  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:40.721  4136  4155 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:32:40.724  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:40.724  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:32:40.724  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:40.725  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89fccfd not in the list
09-08 16:32:40.725  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.725  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:40.729  4136  4152 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:32:40.729  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:40.729  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:40.729  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:40.729  4136  4155 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 16:32:40.729  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:32:40.730  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89fccfd not in the list
09-08 16:32:40.730  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:40.730  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.731  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.731  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d84c554 not in the list
,09-08 16:32:40.733  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:32:40.733  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a36aec added. We now have 3 listener(s)
,09-08 16:32:40.739  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:32:40.739  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:32:40.740  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:32:40.740  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:32:40.740  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b09eb5 added. We now have 4 listener(s)
09-08 16:32:40.741  3750  3799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:32:40.741  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:32:40.746  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:32:40.750  3750  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:32:40.752  4136  4152 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 16:32:40.752  4136  4152 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:32:40.753  4136  4152 D BtGatt.GattService: current time is 234751262404
09-08 16:32:40.753  4136  4152 D BtGatt.GattService: Batch record : [-118, -49, 13, -43, 68, 112, 1, -128, -38, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:32:40.753  4136  4152 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-08 16:32:40.753  4136  4152 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:32:40.755  3750  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:32:40.755  3750  3799 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:32:40.756  3750  3799 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:32:40.756  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:32:40.756  3750  3799 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:32:40.756  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:32:40.757  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.757  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:32:40.757  3750  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 16:32:40.757  3750  3799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a36aec removed from the list
09-08 16:32:40.757  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:40.758  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:32:40.758  3750  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b09eb5 removed from the list
,09-08 16:32:40.760  3750  3750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:32:40.760  3750  3799 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:32:40.761  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.761  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.761  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:32:40.762  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:40.762  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:40.762  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:40.762  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b09eb5 not in the list
,09-08 16:32:40.762  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.762  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.763  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:32:40.763  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:32:40.763  3750  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:32:40.763  3750  3799 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b09eb5 not in the list
09-08 16:32:40.763  3750  3799 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:32:40.764  3750  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:32:40.764  3750  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:32:40.764  3750  3799 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a36aec not in the list
09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 16:32:40.765  3750  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:32:41.217  3750  3750 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:32:42.775  3750  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,09-08 16:32:44.773  3750  3799 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 447
,09-08 16:32:44.773  3750  3799 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 447, name: My test thread name)
,09-08 16:32:44.780  3750  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
,09-08 16:32:44.781  3750  4242 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
09-08 16:32:44.781  3750  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 16:32:44.785  3750  3799 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:32:44.794  3750  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,09-08 16:32:44.795  3750  4243 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 452, thread name: My test thread name): Test exception.
09-08 16:32:44.795  3750  4243 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 16:32:44.803  3750  3799 I jxcore-log: Total number of executed tests:  82
09-08 16:32:44.803  3750  3799 I jxcore-log: 
,09-08 16:32:44.804  3750  3799 I jxcore-log: Number of passed tests:  82
09-08 16:32:44.804  3750  3799 I jxcore-log: 
09-08 16:32:44.805  3750  3799 I jxcore-log: Number of failed tests:  0
09-08 16:32:44.805  3750  3799 I jxcore-log: 
,09-08 16:32:44.805  3750  3799 I jxcore-log: Number of ignored tests:  0
09-08 16:32:44.805  3750  3799 I jxcore-log: 
09-08 16:32:44.806  3750  3799 I jxcore-log: Total duration:  101455
09-08 16:32:44.806  3750  3799 I jxcore-log: 
,09-08 16:32:44.816  3750  3799 I jxcore-log: Unit Test app is loaded
09-08 16:32:44.816  3750  3799 I jxcore-log: 
,09-08 16:32:44.835  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.835  3750  3799 I jxcore-log: 
,09-08 16:32:44.840  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.840  3750  3799 I jxcore-log: 
09-08 16:32:44.841  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.841  3750  3799 I jxcore-log: 
09-08 16:32:44.842  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.842  3750  3799 I jxcore-log: 
09-08 16:32:44.844  3750  3750 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 16:32:44.844  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:32:44.844  3750  3799 I jxcore-log: 
,09-08 16:32:44.846  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.846  3750  3799 I jxcore-log: 
,09-08 16:32:44.849  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.849  3750  3799 I jxcore-log: 
,09-08 16:32:44.851  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.851  3750  3799 I jxcore-log: 
,09-08 16:32:44.852  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:32:44.852  3750  3799 I jxcore-log: 
09-08 16:32:44.853  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.853  3750  3799 I jxcore-log: 
,09-08 16:32:44.854  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.854  3750  3799 I jxcore-log: 
09-08 16:32:44.854  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.854  3750  3799 I jxcore-log: 
,09-08 16:32:44.855  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.855  3750  3799 I jxcore-log: 
09-08 16:32:44.856  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.856  3750  3799 I jxcore-log: 
,09-08 16:32:44.857  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.857  3750  3799 I jxcore-log: 
,09-08 16:32:44.858  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.858  3750  3799 I jxcore-log: 
09-08 16:32:44.859  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.859  3750  3799 I jxcore-log: 
,09-08 16:32:44.860  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.860  3750  3799 I jxcore-log: 
09-08 16:32:44.860  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.860  3750  3799 I jxcore-log: 
,09-08 16:32:44.861  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.861  3750  3799 I jxcore-log: 
09-08 16:32:44.862  3750  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-08 16:32:44.862  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.862  3750  3799 I jxcore-log: 
09-08 16:32:44.863  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.863  3750  3799 I jxcore-log: 
,09-08 16:32:44.864  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.864  3750  3799 I jxcore-log: 
09-08 16:32:44.865  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.865  3750  3799 I jxcore-log: 
,09-08 16:32:44.865  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.865  3750  3799 I jxcore-log: 
09-08 16:32:44.866  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.866  3750  3799 I jxcore-log: 
,09-08 16:32:44.867  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.867  3750  3799 I jxcore-log: 
09-08 16:32:44.868  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.868  3750  3799 I jxcore-log: 
,09-08 16:32:44.869  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.869  3750  3799 I jxcore-log: 
09-08 16:32:44.869  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.869  3750  3799 I jxcore-log: 
,09-08 16:32:44.870  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.870  3750  3799 I jxcore-log: 
09-08 16:32:44.871  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.871  3750  3799 I jxcore-log: 
,09-08 16:32:44.873  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.873  3750  3799 I jxcore-log: 
,09-08 16:32:44.873  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.873  3750  3799 I jxcore-log: 
09-08 16:32:44.874  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.874  3750  3799 I jxcore-log: 
,09-08 16:32:44.874  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.874  3750  3799 I jxcore-log: 
,09-08 16:32:44.875  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.875  3750  3799 I jxcore-log: 
09-08 16:32:44.875  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.875  3750  3799 I jxcore-log: 
09-08 16:32:44.876  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.876  3750  3799 I jxcore-log: 
,09-08 16:32:44.876  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.876  3750  3799 I jxcore-log: 
09-08 16:32:44.877  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:32:44.877  3750  3799 I jxcore-log: 
,09-08 16:32:44.877  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.877  3750  3799 I jxcore-log: 
09-08 16:32:44.878  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 16:32:44.878  3750  3799 I jxcore-log: 
,09-08 16:32:44.878  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.878  3750  3799 I jxcore-log: 
09-08 16:32:44.879  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.879  3750  3799 I jxcore-log: 
,09-08 16:32:44.879  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.879  3750  3799 I jxcore-log: 
09-08 16:32:44.880  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.880  3750  3799 I jxcore-log: 
,09-08 16:32:44.880  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.880  3750  3799 I jxcore-log: 
09-08 16:32:44.881  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.881  3750  3799 I jxcore-log: 
,09-08 16:32:44.881  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.881  3750  3799 I jxcore-log: 
09-08 16:32:44.882  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 16:32:44.882  3750  3799 I jxcore-log: 
,09-08 16:32:44.882  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.882  3750  3799 I jxcore-log: 
,09-08 16:32:44.883  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.883  3750  3799 I jxcore-log: 
09-08 16:32:44.883  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:32:44.883  3750  3799 I jxcore-log: 
,09-08 16:32:44.884  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 16:32:44.884  3750  3799 I jxcore-log: 
,09-08 16:32:44.885  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:32:44.885  3750  3799 I jxcore-log: 
09-08 16:32:44.885  3750  3799 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:32:44.885  3750  3799 I jxcore-log: 
,09-08 16:32:44.888  3750  3799 I jxcore-log: My device name is: motorola-Nexus 6
09-08 16:32:44.888  3750  3799 I jxcore-log: 
,09-08 16:32:44.889  3750  3799 I jxcore-log: Running for WIFI network type
09-08 16:32:44.889  3750  3799 I jxcore-log: 
,09-08 16:32:47.397  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 16:32:47.397  3750  3799 I jxcore-log: 
,09-08 16:32:47.893  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 16:32:47.893  3750  3799 I jxcore-log: 
,09-08 16:32:47.923  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 16:32:47.923  3750  3799 I jxcore-log: 
,09-08 16:32:49.343  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 16:32:49.343  3750  3799 I jxcore-log: 
,09-08 16:32:49.596  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 16:32:49.596  3750  3799 I jxcore-log: 
,09-08 16:32:49.602  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 16:32:49.602  3750  3799 I jxcore-log: 
,09-08 16:32:49.609  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 16:32:49.609  3750  3799 I jxcore-log: 
,09-08 16:32:49.881  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 16:32:49.881  3750  3799 I jxcore-log: 
,09-08 16:32:49.899  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 16:32:49.899  3750  3799 I jxcore-log: 
,09-08 16:32:49.903  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 16:32:49.903  3750  3799 I jxcore-log: 
,09-08 16:32:50.646  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 16:32:50.646  3750  3799 I jxcore-log: 
,09-08 16:32:50.820  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 16:32:50.820  3750  3799 I jxcore-log: 
,09-08 16:32:51.171  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 16:32:51.171  3750  3799 I jxcore-log: 
,09-08 16:32:51.181  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 16:32:51.181  3750  3799 I jxcore-log: 
,09-08 16:32:51.195  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 16:32:51.195  3750  3799 I jxcore-log: 
,09-08 16:32:51.210  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 16:32:51.210  3750  3799 I jxcore-log: 
,09-08 16:32:51.275  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 16:32:51.275  3750  3799 I jxcore-log: 
,09-08 16:32:51.326  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 16:32:51.326  3750  3799 I jxcore-log: 
,09-08 16:32:51.333  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 16:32:51.333  3750  3799 I jxcore-log: 
,09-08 16:32:51.342  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 16:32:51.342  3750  3799 I jxcore-log: 
,09-08 16:32:51.363  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 16:32:51.363  3750  3799 I jxcore-log: 
,09-08 16:32:51.368  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 16:32:51.368  3750  3799 I jxcore-log: 
,09-08 16:32:51.375  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 16:32:51.375  3750  3799 I jxcore-log: 
,09-08 16:32:51.392  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 16:32:51.392  3750  3799 I jxcore-log: 
,09-08 16:32:51.420  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 16:32:51.420  3750  3799 I jxcore-log: 
,09-08 16:32:51.431  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 16:32:51.431  3750  3799 I jxcore-log: 
,09-08 16:32:51.445  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 16:32:51.445  3750  3799 I jxcore-log: 
,09-08 16:32:51.457  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 16:32:51.457  3750  3799 I jxcore-log: 
,09-08 16:32:51.474  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 16:32:51.474  3750  3799 I jxcore-log: 
,09-08 16:32:51.485  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 16:32:51.485  3750  3799 I jxcore-log: 
,09-08 16:32:51.491  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 16:32:51.491  3750  3799 I jxcore-log: 
,09-08 16:32:51.523  3750  3799 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 16:32:51.523  3750  3799 I jxcore-log: 
,09-08 16:32:51.534  3750  3799 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 16:32:51.536  3750  3799 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 16:32:51.536  3750  3799 I jxcore-log: 
,09-08 16:32:51.538  3750  3799 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 16:32:51.538  3750  3799 I jxcore-log: 
,09-08 16:32:51.539  3750  3799 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 16:32:51.539  3750  3799 I jxcore-log: 
,09-08 16:32:51.544  3750  3799 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 16:32:51.544  3750  3799 I jxcore-log: 
,09-08 16:32:51.616  3750  3799 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 16:32:51.616  3750  3799 I jxcore-log: 
,09-08 16:32:51.618  3750  3799 E jxcore  : Error!: testUtils.logMessageToScreen0 is not a function
09-08 16:32:51.618  3750  3799 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js","_functionName":"thaliTape.begin/<","_lineNumber":"254","_columnNumber":"1","_msg":"    at thaliTape.begin/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:254:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"129","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:129:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"75","_columnNumber":"5","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:75:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"222","_columnNumber":"5","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:222:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"644","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:644:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.setTransport/<","_lineNumber":"251","_columnNumber":"5","_msg":"    at Socket.prototype.setTransport/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:251:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:134:7"}]
,09-08 16:32:51.631  3750  3799 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _functionName: 'thaliTape.begin/<',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _lineNumber: '254',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _columnNumber: '1',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _msg: '    at thaliTape.begin/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js:254:1' },
09-08 16:32:51.631  3750  3799 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _functionName: 'Emitter.prototype.emit',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _lineNumber: '134',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _columnNumber: '7',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _msg: '    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:134:7' },
09-08 16:32:51.631  3750  3799 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _functionName: 'Socket.prototype.emit',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _lineNumber: '129',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _columnNumber: '5',
09-08 16:32:51.631  3750  3799 I jxcore-log:     _msg: '    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:129:5' },
09-08 16:32:51.631  3750  3799 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/no
,09-08 16:32:51.632  3750  3799 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-08 16:32:51.632  3750  3799 I jxcore-log: 
09-08 16:32:51.632  3750  3799 E jxcore-log: TypeError: 
,09-08 16:32:51.632  3750  3799 E jxcore-log: testUtils.logMessageToScreen0 is not a function
09-08 16:32:51.632  3750  3799 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/thaliTape.js 254:0)
09-08 16:32:51.632  3750  3799 E jxcore-log: 
,09-08 16:32:52.284  4245  4245 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-08 16:32:52.291  4245  4245 D AndroidRuntime: CheckJNI is OFF
,09-08 16:32:52.335  4245  4245 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-08 16:32:52.384  4245  4245 I Radio-JNI: register_android_hardware_Radio DONE
,09-08 16:32:52.409  4245  4245 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 16:32:52.419   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-08 16:32:52.420   873   886 I ActivityManager: Killing 3750:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-08 16:32:52.532   873   896 W PackageSettings: Skipping PackageSetting{f3e7ad1 com.example.hello/10273} due to missing metadata
,09-08 16:32:52.560   873  1995 I WindowState: WIN DEATH: Window{d8454d7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-08 16:32:52.560   873  1304 D WifiService: Client connection lost with reason: 4
09-08 16:32:52.560   873  1681 D GraphicsStats: Buffer count: 2
,09-08 16:32:52.570   873   896 I art     : Starting a blocking GC Explicit
,09-08 16:32:52.586   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-08 16:32:52.586   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-08 16:32:52.587   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-08 16:32:52.587   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 16:32:52.587   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:52.587   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.587   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:32:52.587   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-08 16:32:52.588   873   886 I ActivityManager:   Force finishing activity ActivityRecord{fa5b4cc u0 com.test.thalitest/.MainActivity t4}
,09-08 16:32:52.606   873  1996 W ActivityManager: Spurious death for ProcessRecord{19c39f4 0:com.test.thalitest/u0a0}, curProc for 3750: null
,09-08 16:32:52.627   873   896 I art     : Explicit concurrent mark sweep GC freed 23020(1450KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 794us total 56.053ms
,09-08 16:32:52.647   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-08 16:32:52.649  4245  4245 I art     : System.exit called, status: 0
,09-08 16:32:52.649  4245  4245 I AndroidRuntime: VM exiting with result code 0.
,09-08 16:32:52.652   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-08 16:32:52.666   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-08 16:32:52.671  4136  4136 D BluetoothMapAppObserver: onReceive
09-08 16:32:52.671  4136  4136 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 16:32:52.671  1859  2167 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 16:32:52.672   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 16:32:52.673  3619  3619 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-08 16:32:52.683  1892  1892 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-08 16:32:52.710  1892  4257 I Keyboard.Facilitator.DecoderInitializer: run()
,09-08 16:32:52.725  1986  1986 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-08 16:32:52.727   873  1995 I ActivityManager: Start proc 4259:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-08 16:32:52.744  1892  4257 I Decoder : createOrResetDecoder
,09-08 16:32:52.752   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 16:32:52.760  1507  1507 I ConfigService: onCreate
,09-08 16:32:52.773  4259  4259 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-08 16:32:52.784  1892  4257 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-08 16:32:52.789   873  1683 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3750 uid 10000
09-08 16:32:52.790  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-08 16:32:52.803   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-08 16:32:52.803  2008  2083 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-08 16:32:52.804   873   885 E PackageManager: Failed to write settings, restoring backup
09-08 16:32:52.804   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 16:32:52.804   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 16:32:52.804   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 16:32:52.804   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 16:32:52.804   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 16:32:52.804   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:52.804   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.804   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 16:32:52.808   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-08 16:32:52.808   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 16:32:52.808   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:32:52.808   873   886 E DropBoxManagerService: 	... 13 more
,09-08 16:32:52.818   873  1389 I ActivityManager: Start proc 4275:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-08 16:32:52.819  2008  2083 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 16:32:52.819  2008  2083 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2008
09-08 16:32:52.819  2008  2083 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.819  2008  2083 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 16:32:52.821   873  4281 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:32:52.821   873  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:32:52.821   873  4281 E DropBoxManagerService: 	... 5 more
09-08 16:32:52.821   873  2057 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 16:32:52.827  2008  2083 I Process : Sending signal. PID: 2008 SIG: 9
,09-08 16:32:52.850  4259  4259 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-08 16:32:52.866  1892  4257 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-08 16:32:52.868  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 16:32:52.868  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-08 16:32:52.871  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-08 16:32:52.871  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 16:32:52.872  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 16:32:52.872  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 16:32:52.872  1892  4257 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 16:32:52.872  1892  4257 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 16:32:52.873  1892  4257 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 16:32:52.873  1892  4257 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 16:32:52.873  1892  4257 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 16:32:52.873  1892  4257 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-08 16:32:52.882   873  1996 I ActivityManager: Start proc 4292:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-08 16:32:52.885  4259  4290 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-08 16:32:52.900   279   279 E lowmemorykiller: Error writing /proc/2008/oom_score_adj; errno=22
,09-08 16:32:52.913  4259  4290 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.913  4259  4290 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 16:32:52.913  4259  4290 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 16:32:52.913  4259  4290 E AndroidRuntime: Process: android.process.acore, PID: 4259
09-08 16:32:52.913  4259  4290 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.913  4259  4290 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:32:52.915   873  4305 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerServ,ice.java:211)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:32:52.915   873  4305 E DropBoxManagerService: 	... 5 more
,09-08 16:32:52.920   873   883 D GraphicsStats: Buffer count: 1
09-08 16:32:52.920   873  1683 I WindowState: WIN DEATH: Window{848a362 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 16:32:52.931   873  1995 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2008) has died
09-08 16:32:52.933   873  1995 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 16:32:52.935  4259  4290 I Process : Sending signal. PID: 4259 SIG: 9
09-08 16:32:52.937   873  1995 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 16:32:52.942   279   279 E lowmemorykiller: Error writing /proc/4259/oom_score_adj; errno=22
,09-08 16:32:52.948  4292  4292 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-08 16:32:52.963   873   886 I ActivityManager: Start proc 4307:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 16:32:52.965   279   279 E lowmemorykiller: Error writing /proc/4259/oom_score_adj; errno=22
,09-08 16:32:52.967   279   279 E lowmemorykiller: Error writing /proc/4259/oom_score_adj; errno=22
,09-08 16:32:52.984  1699  4306 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-08 16:32:52.985  1699  4306 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-08 16:32:52.989   873  2065 I ActivityManager: Process android.process.acore (pid 4259) has died
,09-08 16:32:52.989   873  2065 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-08 16:32:52.997  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 16:32:52.997  1507  1507 D AndroidRuntime: Shutting down VM
09-08 16:32:52.998  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
09-08 16:32:52.998  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
09-08 16:32:52.998  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 16:32:52.998  1507  1507 E AndroidRuntime: 	... 8 more
,09-08 16:32:53.004  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,09-08 16:32:53.004   873  4322 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:32:53.004   873  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:32:53.004   873  4322 E DropBoxManagerService: 	... 5 more
,09-08 16:32:53.020   873   884 I ActivityManager: Killing 3671:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-08 16:32:53.033  4307  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:32:53.033  4307  4307 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:32:53.033  4307  4307 D AndroidRuntime: Shutting down VM
,09-08 16:32:53.063   873  1304 D WifiService: Client connection lost with reason: 4
,09-08 16:32:53.080   873  2063 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,09-08 16:32:53.082   873  2063 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-08 16:32:53.082   873  2063 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,09-08 16:32:53.082   873  2063 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.herrevad.services.LightweightNetworkQualityAndroidService in 21000ms
,09-08 16:32:53.082   873  2063 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,09-08 16:32:53.091  4307  4307 E AndroidRuntime: FATAL EXCEPTION: main
09-08 16:32:53.091  4307  4307 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4307
09-08 16:32:53.091  4307  4307 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:32:53.091  4307  4307 E AndroidRuntime: 	... 10 more
09-08 16:32:53.093   873  2031 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 16:32:53.094  4307  4307 I Process : Sending signal. PID: 4307 SIG: 9
,09-08 16:32:53.096  1699  1699 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-08 16:32:53.106   873  4323 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:32:53.106   873  4323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:32:53.106   873  4323 E DropBoxManagerService: 	... 5 more
,09-08 16:32:53.119   873  2057 I ActivityManager: Start proc 4324:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-08 16:32:53.125   873  1520 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4307) has died
,09-08 16:32:53.127   873  1520 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-08 16:32:53.150   873   886 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
