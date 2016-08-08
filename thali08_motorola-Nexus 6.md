#### Test 79689775603fe2e_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-08 15:42:03.221   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-08 15:42:03.900  3574  3574 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 15:42:03.905  3574  3574 D AndroidRuntime: CheckJNI is OFF
08-08 15:42:03.949  3574  3574 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 15:42:04.000  3574  3574 I Radio-JNI: register_android_hardware_Radio DONE
08-08 15:42:04.023  3574  3574 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 15:42:04.027   872  1690 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 15:42:04.057  1802  1813 W SearchService: Abort, client detached.
08-08 15:42:04.065  1802  1802 I HotwordDetector: Closing mic
08-08 15:42:04.066  1802  2153 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@530cba6
08-08 15:42:04.067  1802  2161 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-08 15:42:04.074  3574  3574 D AndroidRuntime: Shutting down VM
08-08 15:42:04.113   872  1828 I ActivityManager: Start proc 3584:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-08 15:42:04.136   375  2163 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-08 15:42:04.138   375  2163 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-08 15:42:04.143   375  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-08 15:42:04.145  1802  2157 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-08 15:42:04.145  1802  2160 I MicroRecognitionRnrImpl: Detection finished
08-08 15:42:04.182  3584  3584 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-08 15:42:04.202  3584  3584 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-08 15:42:04.208  3584  3584 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3382-3384)
08-08 15:42:04.208  3584  3584 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 15:42:04.219  3584  3584 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f96f571}
08-08 15:42:04.220  3584  3584 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 15:42:04.220  3584  3584 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 15:42:04.226  3584  3584 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 15:42:04.227  3584  3584 E SysUtils: ApplicationContext is null in ApplicationStatus
08-08 15:42:04.246  3584  3584 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-08 15:42:04.256  3584  3584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 15:42:04.256  3584  3584 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 15:42:04.256  3584  3584 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 15:42:04.256  3584  3584 I Adreno  : Build Date                       : 10/20/15
08-08 15:42:04.256  3584  3584 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 15:42:04.256  3584  3584 I Adreno  : Local Branch                     : M14
08-08 15:42:04.256  3584  3584 I Adreno  : Remote Branch                    : 
08-08 15:42:04.256  3584  3584 I Adreno  : Remote Branch                    : 
08-08 15:42:04.256  3584  3584 I Adreno  : Reconstruct Branch               : 
08-08 15:42:04.287   872  1999 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-08 15:42:04.311   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@240b31a:true
,08-08 15:42:04.386  3584  3584 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-08 15:42:04.399  3584  3584 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-08 15:42:04.481  3584  3622 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-08 15:42:04.495  3584  3609 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-08 15:42:04.537  3584  3622 I OpenGLRenderer: Initialized EGL, version 1.4
,08-08 15:42:04.605   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms
,08-08 15:42:04.618  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-08 15:42:04.688  3584  3584 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3584
,08-08 15:42:04.842  3584  3584 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-08 15:42:04.923   872   882 I ActivityManager: Killing 3043:com.google.android.gm/u0a78 (adj 15): empty #17
,08-08 15:42:04.976   872   882 I ActivityManager: Killing 2810:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-08 15:42:05.079  3584  3624 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1694566096
,08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-08 15:42:05.089  3584  3624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b800925 added. We now have 1 listener(s)
,08-08 15:42:05.093  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-08 15:42:05.097  3584  3624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:05.097  3584  3624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 15:42:05.097  3584  3624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
,08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 15:42:05.104  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 15:42:05.105  3584  3624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@652cb08 added. We now have 1 listener(s)
08-08 15:42:05.105  3584  3624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:05.107   872  1308 D WifiService: New client listening to asynchronous messages
,08-08 15:42:05.108  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-08 15:42:05.108  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 15:42:05.108  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
08-08 15:42:05.109  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 15:42:05.109  3584  3624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-08 15:42:05.112  3584  3624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:05.112  3584  3624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-08 15:42:05.115  3584  3624 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:05.115  3584  3624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:05.115  3584  3624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-08 15:42:05.115  3584  3624 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:05.115  3584  3624 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-08 15:42:05.206  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:05.208  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:05.210  3584  3584 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 15:42:06.050  3584  3633 W jxcore-log: Initializing JXcore engine
,08-08 15:42:06.051  3584  3633 W jxcore-log: JXcore engine is ready
,08-08 15:42:06.085  3633  3633 W Thread-318: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-08 15:42:06.085  3633  3633 W Thread-318: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9580]" dev="sockfs" ino=9580 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-08 15:42:06.085  3633  3633 W Thread-318: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-08 15:42:06.085  3633  3633 W Thread-318: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24679]" dev="sockfs" ino=24679 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-08 15:42:06.101  3584  3633 W jxcore-log: Starting JXcore engine
,08-08 15:42:06.256  3584  3633 W jxcore-log: Platform android
08-08 15:42:06.256  3584  3633 W jxcore-log: 
,08-08 15:42:06.256  3584  3633 W jxcore-log: Process ARCH arm
08-08 15:42:06.256  3584  3633 W jxcore-log: 
,08-08 15:42:06.512  3584  3633 I jxcore-log: JXcore Cordova bridge is ready!
08-08 15:42:06.512  3584  3633 I jxcore-log: 
,08-08 15:42:06.513  3584  3633 W jxcore-log: JXcore engine is started
,08-08 15:42:06.520  3584  3624 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 15:42:06.525  3584  3584 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 15:42:06.890  2866  3636 V KeepSync: Connecting to GoogleApiClient
,08-08 15:42:06.893   872  1757 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-08 15:42:06.995  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:06.998  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:07.031  1506  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-08 15:42:07.031  1506  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-08 15:42:07.031  1506  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 15:42:07.031  1506  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:07.059  1829  3637 V BaseAuthAsyncOperation: access token request failed
,08-08 15:42:07.060  2866  3636 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-08 15:42:07.123  1506  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-08 15:42:07.123  1506  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-08 15:42:07.123  1506  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:07.123  1506  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:07.138  2866  3636 E KeepSync: IOException
08-08 15:42:07.138  2866  3636 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-08 15:42:07.138  2866  3636 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 15:42:07.138  2866  3636 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-08 15:42:07.138  2866  3636 E KeepSync: 	... 10 more
,08-08 15:42:07.138  2866  3636 W KeepSync: Sync result 2
,08-08 15:42:07.143   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125919, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 15:42:09.369  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:09.410  1506  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 15:42:09.411  1506  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 15:42:09.411  1506  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 15:42:09.411  1506  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:09.441  3320  3320 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 15:42:09.442  3320  3320 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 15:42:09.442  3320  3320 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-08 15:42:22.777  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-08 15:42:22.777  3584  3633 I jxcore-log: 
,08-08 15:42:22.780  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-08 15:42:22.780  3584  3633 I jxcore-log: 
,08-08 15:42:22.782  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:22.782  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:22.783  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:22.783  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:22.785  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-08 15:42:22.785  3584  3633 I jxcore-log: 
,08-08 15:42:22.787  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-08 15:42:22.787  3584  3633 I jxcore-log: 
,08-08 15:42:23.130  3584  3633 D ExecuteNativeTests: Running unit tests
,08-08 15:42:23.189  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:23.190  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba added. We now have 2 listener(s)
,08-08 15:42:23.191  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-08 15:42:23.191  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 15:42:23.191  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:23.191  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:23.191  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b added. We now have 2 listener(s)
,08-08 15:42:23.191  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:23.192  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 15:42:23.194  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:23.200  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:23.200  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:23.201  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.201  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:23.201  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:23.204  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:23.209  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:23.209  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-08 15:42:23.209  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-08 15:42:23.209  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 15:42:23.214  3584  3633 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-08 15:42:23.215  3584  3633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-08 15:42:23.215  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 15:42:23.216  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 15:42:23.216  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-08 15:42:23.217  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.218  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 15:42:23.218  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 15:42:23.219  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.221  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.221  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 15:42:23.221  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-08 15:42:23.222  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba removed from the list
,08-08 15:42:23.222  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.222  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b removed from the list
08-08 15:42:23.222  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.222  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.224  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.225  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.226  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.226  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.226  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.226  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.228  3584  3633 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-08 15:42:23.229  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.229  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 15:42:23.229  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 15:42:23.231  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.231  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.231  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.232  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.232  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.232  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.232  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 15:42:23.232  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:23.232  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.232  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.232  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.233  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.234  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.234  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.234  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.244  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 15:42:23.245  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 15:42:23.246  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 15:42:23.247  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-08 15:42:23.248  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 15:42:23.248  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.249  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.249  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.249  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.249  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:23.249  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.249  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.249  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.249  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.249  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.250  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.250  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.250  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.250  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.251  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 15:42:23.251  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.251  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.251  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.251  3584  3633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 15:42:23.253  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:23.255  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:23.255  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:23.255  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.255  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.255  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:23.256  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:23.256  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:23.256  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 15:42:23.257  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 15:42:23.257  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:23.257  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 15:42:23.258  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:23.260  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-08 15:42:23.261  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 15:42:23.261  3584  3633 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 15:42:23.261  3584  3633 I io.jxcore.node.ConnectionHelper: start: OK
,08-08 15:42:23.261  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 15:42:23.262  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.262  3584  3633 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-08 15:42:23.264  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.264  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.264  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 15:42:23.264  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.264  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 15:42:23.264  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 15:42:23.264  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 15:42:23.264  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 15:42:23.264  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 15:42:23.265  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-08 15:42:23.265  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:23.266  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.266  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-08 15:42:23.266  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:23.266  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.266  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.266  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.266  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:23.266  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.266  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.266  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.266  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.267  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.267  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.267  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.267  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.267  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.267  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.267  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.268  3584  3633 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-08 15:42:23.270  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:23.272  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:23.272  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:23.272  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.272  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:23.272  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:23.273  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:23.273  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 15:42:23.273  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 15:42:23.273  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:23.273  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-08 15:42:23.274  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:23.276  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 15:42:23.276  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:23.276  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 15:42:23.276  3584  3633 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 15:42:23.276  3584  3633 I io.jxcore.node.ConnectionHelper: start: OK
08-08 15:42:23.276  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.276  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 15:42:23.276  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.276  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-08 15:42:23.277  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.277  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 15:42:23.277  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 15:42:23.277  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 15:42:23.277  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 15:42:23.277  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 15:42:23.277  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 15:42:23.277  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:23.278  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.278  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-08 15:42:23.278  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.278  3584  3633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-08 15:42:23.278  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:23.278  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.278  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.278  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.278  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.278  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.278  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:23.278  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.278  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.279  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.279  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.279  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.279  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.279  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.280  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.280  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.280  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.280  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.281  3584  3633 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-08 15:42:23.281  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.281  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.281  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.281  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.281  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.281  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.282  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.282  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.282  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.282  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.282  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.282  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.282  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.282  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.282  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.282  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.282  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.282  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.283  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 15:42:23.283  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 15:42:23.284  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.284  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.284  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.284  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.284  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.284  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.284  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:23.284  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.284  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.284  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.284  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.284  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.284  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.285  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.285  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:23.285  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.285  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.285  3584  3633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-08 15:42:23.285  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.286  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.286  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.286  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.286  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.286  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.286  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
,08-08 15:42:23.286  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.286  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.286  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.286  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.286  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.286  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.286  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.287  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 15:42:23.287  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:23.287  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.287  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.288  3584  3633 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-08 15:42:23.288  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 15:42:23.288  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.288  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.288  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:23.288  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.288  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.288  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
,08-08 15:42:23.288  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.288  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.288  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 15:42:23.288  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.288  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.288  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:23.289  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.289  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.289  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.289  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.289  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.289  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 15:42:23.292  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 15:42:23.292  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 15:42:23.292  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 15:42:23.294  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 15:42:23.294  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 15:42:23.294  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.294  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.294  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.294  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.294  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.295  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.295  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
,08-08 15:42:23.295  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.295  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.295  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.297  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.297  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.297  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.297  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.298  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.298  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.298  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.298  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.299  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 15:42:23.299  3584  3633 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-08 15:42:23.300  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-08 15:42:23.305  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-08 15:42:23.305  3584  3633 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 15:42:23.306  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 15:42:23.307  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 15:42:23.308  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 15:42:23.308  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-08 15:42:23.309  3584  3633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 15:42:23.309  3584  3633 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-08 15:42:23.309  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-08 15:42:23.309  3584  3633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 15:42:23.309  3584  3633 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-08 15:42:23.309  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 15:42:23.309  3584  3633 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 15:42:23.309  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-08 15:42:23.311  3584  3633 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
,08-08 15:42:23.311  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-08 15:42:23.312  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-08 15:42:23.312  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-08 15:42:23.312  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-08 15:42:23.312  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-08 15:42:23.312  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-08 15:42:23.313  3584  3633 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 15:42:23.313  3584  3633 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-08 15:42:23.314  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 15:42:23.314  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.314  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.314  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.314  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.314  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.314  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-08 15:42:23.314  3584  3648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
,08-08 15:42:23.315  3584  3648 E BluetoothDevice: Bluetooth is not enabled
08-08 15:42:23.315  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.315  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.315  3584  3648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 382)
08-08 15:42:23.315  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.315  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.315  3584  3648 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 382)
08-08 15:42:23.315  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.315  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.315  3584  3648 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 382)
08-08 15:42:23.315  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:23.315  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.315  3584  3649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
08-08 15:42:23.316  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.316  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.316  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.317  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
,08-08 15:42:23.317  3584  3584 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-08 15:42:23.317  3584  3648 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 382
08-08 15:42:23.318  3584  3584 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-08 15:42:23.318  3584  3584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 15:42:23.318  3584  3584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 15:42:23.318  3584  3648 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
08-08 15:42:23.318  3584  3633 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-08 15:42:23.319  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.319  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.319  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 15:42:23.319  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.319  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.320  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.320  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.320  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.320  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.320  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.320  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.321  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.321  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.321  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.322  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.322  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:23.322  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.322  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.323  3584  3633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-08 15:42:23.323  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.323  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.323  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.323  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.323  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.323  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.324  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.324  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.324  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.324  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.324  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.324  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.324  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.324  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:23.325  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.325  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.325  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.325  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.325  3584  3633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-08 15:42:23.326  3584  3633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-08 15:42:23.326  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 15:42:23.326  3584  3633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-08 15:42:23.326  3584  3633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 15:42:23.326  3584  3633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-08 15:42:23.326  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 15:42:23.326  3584  3633 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-08 15:42:23.326  3584  3633 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 15:42:23.326  3584  3633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 15:42:23.326  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 15:42:23.326  3584  3633 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-08 15:42:23.327  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.327  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.327  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.327  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:23.327  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.327  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.327  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.327  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.327  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.327  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.327  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.327  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.327  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.327  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.328  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 15:42:23.328  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.328  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.328  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.328  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.328  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.328  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.329  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.329  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.329  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.329  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 15:42:23.329  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.329  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.329  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.329  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.329  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.329  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.329  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.329  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.329  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.329  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.330  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.330  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.330  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.330  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.330  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.330  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.330  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.330  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 15:42:23.330  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.330  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.330  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.330  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.331  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.331  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.331  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.331  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.332  3584  3633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-08 15:42:23.332  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:23.332  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-08 15:42:23.332  3584  3633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 15:42:23.333  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 15:42:23.333  3584  3584 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 15:42:23.333  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.333  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-08 15:42:23.333  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.333  3584  3633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-08 15:42:23.333  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.333  3584  3584 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-08 15:42:23.333  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.333  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 15:42:23.333  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 15:42:23.333  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 15:42:23.334  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.334  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.334  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.334  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.334  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:23.334  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:23.334  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.334  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.334  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:23.334  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.334  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.335  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.335  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.335  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.335  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.335  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.335  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.335  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.335  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.335  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.335  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.335  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.335  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.335  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.336  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.336  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 15:42:23.338  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 15:42:23.338  3584  3633 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-08 15:42:23.338  3584  3633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 15:42:23.338  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 15:42:23.338  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 15:42:23.338  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.338  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.339  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.339  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.339  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.339  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.339  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.339  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.339  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.339  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.339  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.339  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.339  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.340  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.340  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.340  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.340  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.340  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.341  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.342  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.342  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.342  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.342  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.342  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.342  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.342  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.342  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.342  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.342  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.342  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.342  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.342  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.342  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.342  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.342  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.343  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.343  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:23.344  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:23.344  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:23.344  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:23.344  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.344  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.344  3584  3633 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d654cba not in the list
08-08 15:42:23.344  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.344  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.344  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:23.344  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.344  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.344  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:23.344  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:23.345  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:23.345  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:23.345  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:23.345  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e876b not in the list
08-08 15:42:23.346  3584  3633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-08 15:42:23.346  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 15:42:23.346  3584  3633 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-08 15:42:23.346  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 15:42:23.347  3584  3633 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-08 15:42:23.347  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 15:42:23.348  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 15:42:23.348  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-08 15:42:23.349  3584  3633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-08 15:42:23.349  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 15:42:23.349  3584  3633 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-08 15:42:23.349  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 15:42:23.349  3584  3633 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-08 15:42:23.349  3584  3633 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-08 15:42:23.350  3584  3633 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-08 15:42:23.351  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:23.351  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0a309d added. We now have 2 listener(s)
08-08 15:42:23.351  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:23.352   872  1692 D WifiService: setWifiEnabled: true pid=3584, uid=10000
08-08 15:42:23.352   872  1692 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 15:42:23.353  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:23.353  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@794b912 added. We now have 3 listener(s)
08-08 15:42:23.353  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:23.354  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.354  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.354  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:23.354  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a278e3 added. We now have 4 listener(s)
08-08 15:42:23.354  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:23.355  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:23.355  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@894d2e0 added. We now have 5 listener(s)
08-08 15:42:23.355  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:23.356   872  1757 D WifiService: setWifiEnabled: false pid=3584, uid=10000
08-08 15:42:23.356   872  1757 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 15:42:23.370   872   889 I ActivityManager: Start proc 3651:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-08 15:42:23.372  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:23.373  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-08 15:42:23.374  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:23.374  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:23.374  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.374  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:23.374  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:23.375  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:23.377  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:23.378   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-08 15:42:23.378   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-08 15:42:23.378   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 15:42:23.378   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 15:42:23.386   872  2011 D DhcpClient: Clearing IP address
08-08 15:42:23.386   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-08 15:42:23.390   371   870 D CommandListener: Setting iface cfg
08-08 15:42:23.392  1506  2292 V NativeCrypto: Read error: ssl=0x9aee5800: I/O error during system call, Connection timed out
08-08 15:42:23.393   872  2012 D DhcpClient: Receive thread stopped
08-08 15:42:23.394  1506  2292 V NativeCrypto: SSL shutdown failed: ssl=0x9aee5800: I/O error during system call, Broken pipe
,08-08 15:42:23.395   872  1677 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-08 15:42:23.396   872  1997 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-08 15:42:23.396   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-08 15:42:23.396   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-08 15:42:23.398   872  1997 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-08 15:42:23.398   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-08 15:42:23.399   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 15:42:23.399   399   399 E Parcel  : Reading a NULL string not supported here.
08-08 15:42:23.403   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-08 15:42:23.408   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-08 15:42:23.410  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:23.410  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.410  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:23.410  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.410  1847  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:23.410  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:23.411  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.411  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:23.411   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-08 15:42:23.434   872  1757 I ActivityManager: Start proc 3666:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-08 15:42:23.440   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-08 15:42:23.444   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:23.470  3666  3666 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-08 15:42:23.477   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:23.478   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-08 15:42:23.478   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:23.482   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-08 15:42:23.483  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:23.483  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:23.483  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:23.484  1802  1802 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-08 15:42:23.485  3221  3221 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4c1633 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-08 15:42:23.528  3666  3666 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-08 15:42:23.532   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-08 15:42:23.533   872  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-08 15:42:23.533   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 15:42:23.539  1829  1829 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 15:42:23.543  1829  1829 D SystemUpdateService: onCreate
,08-08 15:42:23.545  1829  1829 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 15:42:23.553  1829  3696 I SystemUpdateService: active receiver: enabled
,08-08 15:42:23.553  1829  1829 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-08 15:42:23.559  1829  2346 I iu.UploadsManager: num queued entries: 0
,08-08 15:42:23.560  1829  3696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 15:42:23.562  1829  1829 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 15:42:23.563  1829  2346 I iu.UploadsManager: num updated entries: 0
08-08 15:42:23.563  1829  1829 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 15:42:23.566  1829  3696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-08 15:42:23.566  1829  3696 I SystemUpdateService: now status is 0 (complete)
08-08 15:42:23.566  1829  3696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 15:42:23.566  1829  3696 I SystemUpdateService: file has been verified
,08-08 15:42:23.567  1829  3696 I SystemUpdateService: OTA package size = 12249756
08-08 15:42:23.568  1829  2346 I iu.SyncManager: NEXT; no task
,08-08 15:42:23.571  1829  3696 I SystemUpdateService: showing system update notification
,08-08 15:42:23.580   872  1757 I ActivityManager: Start proc 3698:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-08 15:42:23.583  3651  3651 D AdapterServiceConfig: Adding HeadsetService
,08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding A2dpService
08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding HidService
08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding HealthService
08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding PanService
08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding GattService
08-08 15:42:23.584  3651  3651 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 15:42:23.602  1829  1829 D SystemUpdateService: onDestroy
,08-08 15:42:23.606   872  1677 I ActivityManager: Killing 3221:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-08 15:42:23.618  3698  3698 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-08 15:42:23.620   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85e18d5:true
08-08 15:42:23.620  3651  3651 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 15:42:23.621  3698  3698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:23.623  3651  3651 I bt_bluedroid: init
,08-08 15:42:23.623  3651  3710 I BluetoothAdapterState: Entering OffState
,08-08 15:42:23.626  3651  3711 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 15:42:23.627  3651  3711 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 15:42:23.627  3651  3711 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 15:42:23.627  3698  3698 D SprintDMHelper: simOperator: 
08-08 15:42:23.627  3698  3698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-08 15:42:23.627  3651  3711 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 15:42:23.628  3651  3651 I bt_bluedroid: get_profile_interface socket
,08-08 15:42:23.630  3651  3714 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-08 15:42:23.630  3651  3651 I bt_bluedroid: get_profile_interface sdp
,08-08 15:42:23.668   872  1677 I ActivityManager: Start proc 3715:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-08 15:42:23.669   872  1677 I ActivityManager: Killing 3362:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-08 15:42:23.699  3651  3714 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 15:42:23.704  3651  3661 I bt_bluedroid: config_hci_snoop_log
08-08 15:42:23.705   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-08 15:42:23.718  3651  3710 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 15:42:23.718  3651  3710 D BluetoothAdapterProperties: Setting state to 14
08-08 15:42:23.719  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 15:42:23.719  3651  3710 D BluetoothBondStateMachine: make
08-08 15:42:23.727  3651  3710 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:23.729  3651  3651 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 15:42:23.723  3651  3727 I BluetoothBondStateMachine: StableState(): Entering Off State
08-08 15:42:23.731  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:23.744  3651  3651 D BtGatt.DebugUtils: handleDebugAction() action=null
08-08 15:42:23.744  3651  3651 D BtGatt.GattService: Received start request. Starting profile...
08-08 15:42:23.744  3651  3651 D BtGatt.GattService: start()
08-08 15:42:23.744  3651  3651 I bt_bluedroid: get_profile_interface gatt
08-08 15:42:23.745  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:23.745  3651  3651 D BtGatt.AdvertiseManager: advertise manager created
08-08 15:42:23.753  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:23.753  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:23.753  3651  3651 V BluetoothAdapterState: isBleTurningOn()=true
08-08 15:42:23.753  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:23.753  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 15:42:23.753  3651  3710 I bt_bluedroid: enable
08-08 15:42:23.753  3651  3711 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-08 15:42:23.754  3651  3711 I bt_hci  : start_up
,08-08 15:42:23.762  3651  3711 I bt_vendor: alloc value 0xb3a88189
08-08 15:42:23.762  3651  3711 I bt_vendor: init
08-08 15:42:23.762  3651  3711 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 15:42:23.762  3651  3711 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 15:42:23.806  2372  3733 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-08 15:42:23.809   872  1691 I ActivityManager: Start proc 3734:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-08 15:42:23.811   872  1828 I ActivityManager: Killing 2610:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-08 15:42:23.835  3584  3584 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 15:42:23.866  3651  3711 D bt_hci  : start_up starting async portion
08-08 15:42:23.867  3651  3730 I bt_hci  : event_finish_startup
08-08 15:42:23.867  3651  3730 I bt_hci_h4: hal_open
08-08 15:42:23.867  3651  3730 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 15:42:23.871  3651  3730 I bt_userial_vendor: device fd = 51 open
,08-08 15:42:23.878  3734  3734 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-08 15:42:23.911  3651  3730 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 15:42:23.930  3734  3734 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-08 15:42:23.930  3734  3734 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-08 15:42:23.930  3734  3734 I GAv4    :   adb logcat -s GAv4
,08-08 15:42:23.942  3651  3730 D bt_hwcfg: Chipset BCM4354A2
08-08 15:42:23.943  3651  3730 D bt_hwcfg: Target name = [BCM4354A2]
08-08 15:42:23.943  3651  3730 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 15:42:23.945  3734  3734 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-08 15:42:23.953  3734  3734 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-08 15:42:23.983  3734  3752 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-08 15:42:24.125  3734  3734 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-08 15:42:24.159  3734  3734 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-08 15:42:24.175  3734  3734 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 3341-3351)
,08-08 15:42:24.175  3734  3734 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 15:42:24.183  3734  3734 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4fe8595}
,08-08 15:42:24.184  3734  3734 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 15:42:24.184  3734  3734 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-08 15:42:24.191  3734  3734 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-08 15:42:24.193  3734  3734 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 15:42:24.211  3734  3734 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-08 15:42:24.223  3734  3734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
08-08 15:42:24.224  3734  3734 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-08 15:42:24.224  3734  3734 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 15:42:24.224  3734  3734 I Adreno  : Build Date                       : 10/20/15
08-08 15:42:24.224  3734  3734 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 15:42:24.224  3734  3734 I Adreno  : Local Branch                     : M14
08-08 15:42:24.224  3734  3734 I Adreno  : Remote Branch                    : 
08-08 15:42:24.224  3734  3734 I Adreno  : Remote Branch                    : 
08-08 15:42:24.224  3734  3734 I Adreno  : Reconstruct Branch               : 
,08-08 15:42:24.286  3734  3734 I NSApplication: Starting up...
,08-08 15:42:24.296  3734  3781 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-08 15:42:24.328   872  1692 I ActivityManager: Start proc 3786:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-08 15:42:24.329   872  1692 I ActivityManager: Killing 3302:android.process.acore/u0a5 (adj 15): empty #17
,08-08 15:42:24.405  3786  3786 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-08 15:42:24.512  3651  3730 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 15:42:24.513  3651  3730 D bt_hwcfg: Settlement delay -- 100 ms
08-08 15:42:24.513  3651  3730 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 15:42:24.606   872   882 I ActivityManager: Killing 3439:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-08 15:42:24.629  3651  3730 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-08 15:42:24.630  3651  3730 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 15:42:24.662  3651  3730 I bt_hwcfg: vendor lib fwcfg completed
08-08 15:42:24.662  3651  3730 I bt_vendor: firmware callback
08-08 15:42:24.663  3651  3730 I bt_hci  : firmware_config_callback
,08-08 15:42:24.680  3651  3800 I bt_btu  : btu_task pending for preload complete event
,08-08 15:42:24.680  3651  3800 I bt_btu_task: Bluetooth chip preload is complete
08-08 15:42:24.681  3651  3800 I bt_btu  : btu_task received preload complete event
,08-08 15:42:24.690  3651  3800 I         : BTE_InitTraceLevels -- TRC_HCI
08-08 15:42:24.690  3651  3800 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-08 15:42:24.691  3651  3800 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-08 15:42:24.691  3651  3800 I         : BTE_InitTraceLevels -- TRC_AVDT
08-08 15:42:24.691  3651  3800 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 15:42:24.691  3651  3800 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 15:42:24.691  3651  3800 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 15:42:24.692  3651  3800 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 15:42:24.692  3651  3800 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 15:42:24.692  3651  3800 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 15:42:24.692  3651  3800 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 15:42:24.692  3651  3800 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 15:42:24.693  3651  3800 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 15:42:24.693  3651  3800 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 15:42:24.693  3651  3800 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 15:42:24.831  3651  3800 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a05d9d
,08-08 15:42:24.831  3651  3800 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a05d9d 
,08-08 15:42:24.843  3651  3714 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 15:42:24.846  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 15:42:24.847  3651  3714 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 15:42:24.851  3651  3714 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 15:42:24.857  3651  3714 D BluetoothAdapterProperties: Scan Mode:20
,08-08 15:42:24.858  3651  3714 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 15:42:24.859  3651  3714 D bt_hci  : do_postload posting postload work item
08-08 15:42:24.860  3651  3730 I bt_hci  : event_postload
08-08 15:42:24.860  3651  3730 I bt_vendor: sco_config_cb
,08-08 15:42:24.860  3651  3730 I bt_hci  : sco_config_callback postload finished.
08-08 15:42:24.860  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:24.863  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:24.865  3651  3730 I bt_vendor: low_power_mode_cb
,08-08 15:42:24.872  3651  3714 D bt_bte_conf: Device ID record 1 : primary
,08-08 15:42:24.872  3651  3714 D bt_bte_conf:   vendorId            = 000f
08-08 15:42:24.872  3651  3714 D bt_bte_conf:   vendorIdSource      = 0001
08-08 15:42:24.873  3651  3714 D bt_bte_conf:   product             = 1200
08-08 15:42:24.873  3651  3714 D bt_bte_conf:   version             = 1436
08-08 15:42:24.873  3651  3714 D bt_bte_conf:   clientExecutableURL = 
,08-08 15:42:24.873  3651  3714 D bt_bte_conf:   serviceDescription  = 
08-08 15:42:24.874  3651  3714 D bt_bte_conf:   documentationURL    = 
08-08 15:42:24.874  3651  3714 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 15:42:24.874  3651  3711 D bt_stack_manager: event_start_up_stack finished
08-08 15:42:24.874  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 15:42:24.875  3651  3710 D BluetoothAdapterProperties: Setting state to 15
08-08 15:42:24.875  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 15:42:24.876  3651  3710 I BluetoothAdapterState: Entering BleOnState
,08-08 15:42:24.883  3651  3710 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-08 15:42:24.883  3651  3710 D BluetoothAdapterProperties: Setting state to 11
08-08 15:42:24.883  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 15:42:24.888  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:24.889  3651  3651 D HeadsetService: Received start request. Starting profile...
,08-08 15:42:24.892  3651  3651 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 15:42:24.893  3651  3651 D HeadsetStateMachine: make
,08-08 15:42:24.895  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:24.897  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:24.912   872   885 I ActivityManager: Start proc 3813:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-08 15:42:24.915  3651  3651 D HeadsetStateMachine: max_hf_connections = 1
,08-08 15:42:24.916  3651  3651 I bt_bluedroid: get_profile_interface handsfree
,08-08 15:42:24.916  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-08 15:42:24.916  3651  3714 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 15:42:24.925  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:24.926   872   872 D BluetoothA2dp: Proxy object connected
,08-08 15:42:24.928  3651  3710 I BluetoothAdapterState: Entering PendingCommandState
08-08 15:42:24.929  3651  3651 D A2dpService: Received start request. Starting profile...
,08-08 15:42:24.930  3651  3651 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 15:42:24.930  3651  3651 I bt_bluedroid: get_profile_interface avrcp
,08-08 15:42:24.942  3651  3651 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 15:42:24.942  3651  3651 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 15:42:24.942  3651  3651 D A2dpStateMachine: make
,08-08 15:42:24.945  3651  3651 I bt_bluedroid: get_profile_interface a2dp
,08-08 15:42:24.945  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 15:42:24.947  3651  3827 D A2dpStateMachine: Enter Disconnected: -2
08-08 15:42:24.949  3651  3651 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 15:42:24.950  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:24.952  1364  1364 D BluetoothInputDevice: Proxy object connected
08-08 15:42:24.952  3651  3651 D HidService: Received start request. Starting profile...
08-08 15:42:24.953  1364  1364 D HidProfile: Bluetooth service connected
08-08 15:42:24.953  3651  3651 I bt_bluedroid: get_profile_interface hidhost
08-08 15:42:24.953  3651  3651 D HidService: setHidService(): set to: null
08-08 15:42:24.953  3651  3714 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e73e5
08-08 15:42:24.953  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-08 15:42:24.954  3651  3651 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 15:42:24.955  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:24.956  3651  3651 D HealthService: Received start request. Starting profile...
,08-08 15:42:24.957  3651  3651 I bt_bluedroid: get_profile_interface health
,08-08 15:42:24.957  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.957  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.957  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.957  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:24.959  3651  3812 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 15:42:24.959  3651  3651 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 15:42:24.960  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:24.961  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:24.961  3651  3651 D PanService: Received start request. Starting profile...
08-08 15:42:24.961  3651  3651 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-08 15:42:24.961  3651  3651 I bt_bluedroid: get_profile_interface pan
08-08 15:42:24.961  1364  1364 D PanProfile: Bluetooth service connected
,08-08 15:42:24.962  3651  3714 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 15:42:24.966  3651  3651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:24.967  1364  1364 D BluetoothMap: Proxy object connected
08-08 15:42:24.967  3651  3651 D BluetoothMapService: Received start request. Starting profile...
08-08 15:42:24.967  3651  3651 D BluetoothMapService: start()
08-08 15:42:24.967  1364  1364 D MapProfile: Bluetooth service connected
08-08 15:42:24.967  1364  1364 D BluetoothMap: getConnectedDevices()
08-08 15:42:24.968  1364  1364 D BluetoothMap: Bluetooth is Not enabled
,08-08 15:42:24.969  3651  3651 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-08 15:42:24.969  3651  3651 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 15:42:24.969  3651  3651 D BluetoothMapAppObserver: createReceiver()
08-08 15:42:24.970  3651  3651 D BluetoothMapAppObserver: initObservers()
08-08 15:42:24.970  3651  3651 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 15:42:24.975  3813  3813 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.976  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:24.977  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:24.978  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-08 15:42:24.978  3651  3710 D BluetoothAdapterProperties: ScanMode =  20
08-08 15:42:24.978  3651  3710 D BluetoothAdapterProperties: State =  11
,08-08 15:42:24.978  3651  3710 D BluetoothAdapterProperties: Setting state to 12
08-08 15:42:24.978  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 15:42:24.979  1364  3583 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 15:42:24.979  3651  3714 D BluetoothAdapterProperties: Scan Mode:21
,08-08 15:42:24.979  3651  3714 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 15:42:24.981  1364  1375 D BluetoothPan: onBluetoothStateChange on: true
,08-08 15:42:24.981   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 15:42:24.981  3584  3584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-08 15:42:24.981   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:24.981  3651  3710 I BluetoothAdapterState: Entering OnState
,08-08 15:42:24.983  1364  1377 D BluetoothMap: onBluetoothStateChange: up=true
,08-08 15:42:24.984  1364  1823 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 15:42:24.984  3584  3584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-08 15:42:24.985  1735  1912 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 15:42:24.986  3584  3584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-08 15:42:24.987   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 15:42:24.987   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 15:42:24.989   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-08 15:42:24.990  3651  3651 D BluetoothMapService: onReceive
,08-08 15:42:24.990  3651  3651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:24.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:24.990  3651  3651 D BluetoothMapService: STATE_ON
08-08 15:42:24.992  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:24.994  1364  1668 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:24.995  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:24.996  3651  3651 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 15:42:24.997  3651  3651 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 15:42:24.997  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:24.998  1364  1364 D BluetoothA2dp: Proxy object connected
,08-08 15:42:24.999  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:25.000  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:25.001  3651  3651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 15:42:25.000  1364  1668 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-08 15:42:25.003  3651  3651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:25.004  3651  3651 D ObexServerSockets: Succeed to create listening sockets 
,08-08 15:42:25.004  3651  3651 D ObexServerSockets0: startAccept()
08-08 15:42:25.004  3651  3651 D ObexServerSockets0: prepareForNewConnect()
08-08 15:42:25.006  3651  3651 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-08 15:42:25.006  3651  3651 D BluetoothSdpJni: SDP Create record success - handle: 0
08-08 15:42:25.007  3651  3834 D ObexServerSockets0: Accepting socket connection...
,08-08 15:42:25.007  3651  3835 D ObexServerSockets0: Accepting socket connection...
,08-08 15:42:25.011  3651  3651 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 15:42:25.011  3651  3651 D ObexServerSockets0: prepareForNewConnect()
,08-08 15:42:25.032   872  1827 I ActivityManager: Killing 3456:com.android.musicfx/u0a18 (adj 15): empty #17
,08-08 15:42:25.076  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:25.083   872   889 D BluetoothHeadset: Proxy object connected
,08-08 15:42:25.087  1735  2111 D BluetoothHeadset: Proxy object connected
,08-08 15:42:25.088   872   889 D BluetoothHeadset: Proxy object connected
08-08 15:42:25.088   872   889 D BluetoothHeadset: Proxy object connected
08-08 15:42:25.089   872  1691 I ActivityManager: Start proc 3836:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-08 15:42:25.103  1364  3583 D BluetoothHeadset: Proxy object connected
,08-08 15:42:25.104  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:25.118  3836  3836 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.k.d(PG:583)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.242  3836  3836 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.242  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.243  3836  3836 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.243  3836  3836 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:42:25.243  3836  3836 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:42:25.270  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 15:42:25.275   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4665bd:true
,08-08 15:42:25.281  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 15:42:25.291  1364  1364 D BluetoothPbap: Proxy object connected
08-08 15:42:25.292  1364  1364 D PbapServerProfile: Bluetooth service connected
08-08 15:42:25.296  3651  3862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 15:42:25.308  3813  3813 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 15:42:25.319  3813  3813 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-08 15:42:25.337  3813  3813 D LocalBluetoothProfileManager: Adding local MAP profile
,08-08 15:42:25.338  3813  3813 D BluetoothMap: Create BluetoothMap proxy object
,08-08 15:42:25.343  3813  3813 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-08 15:42:25.346  3651  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:25.349  3651  3868 I BtOppRfcommListener: Accept thread started.
,08-08 15:42:25.358  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:25.358  3813  3813 D BluetoothA2dp: Proxy object connected
,08-08 15:42:25.361  3813  3813 D BluetoothInputDevice: Proxy object connected
,08-08 15:42:25.362  3813  3813 D HidProfile: Bluetooth service connected
,08-08 15:42:25.363  3813  3813 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:25.364  3813  3813 D PanProfile: Bluetooth service connected
,08-08 15:42:25.364  3813  3813 D BluetoothMap: Proxy object connected
08-08 15:42:25.365  3813  3813 D MapProfile: Bluetooth service connected
,08-08 15:42:25.365  3813  3813 D BluetoothMap: getConnectedDevices()
,08-08 15:42:25.367  3813  3813 D BluetoothPbap: Proxy object connected
,08-08 15:42:25.367  3813  3813 D PbapServerProfile: Bluetooth service connected
,08-08 15:42:25.369   872  1692 I ActivityManager: Killing 2030:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-08 15:42:25.426  3813  3826 D BluetoothHeadset: Proxy object connected
,08-08 15:42:25.427  3813  3813 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:25.510  3836  3852 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-08 15:42:25.533   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b40ef99:true
,08-08 15:42:26.379   872   883 D WifiService: setWifiEnabled: true pid=3584, uid=10000
,08-08 15:42:26.379   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 15:42:26.391   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:26.408  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:26.415  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:26.421   872  1307 D WifiConfigStore: loaded 0 passpoint configs
08-08 15:42:26.421   872  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 15:42:26.422   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 15:42:26.423   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-08 15:42:26.424   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-08 15:42:26.424   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:26.424  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:26.424   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 15:42:26.425   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 15:42:26.432  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:26.441   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-08 15:42:26.442   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.81 rxSuccessRate=8.44 delta 1000 -> 994
08-08 15:42:26.443   371   870 D CommandListener: Setting iface cfg
08-08 15:42:26.444   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
08-08 15:42:26.444   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 15:42:26.451   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-08 15:42:26.451   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-08 15:42:26.452   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-08 15:42:26.452   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:26.479   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-08 15:42:26.552   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-08 15:42:26.554  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-08 15:42:26.971  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 15:42:27.010  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-08 15:42:27.010  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-08 15:42:27.017   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 15:42:27.023   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 15:42:27.023   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 15:42:27.023   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-08 15:42:27.046   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:27.061   371   870 D CommandListener: Setting iface cfg,
08-08 15:42:27.063   872  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-08 15:42:27.076   872  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-08 15:42:27.078   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-08 15:42:27.094   872  3880 D DhcpClient: Receive thread started
,08-08 15:42:27.178   872  1307 E native  : do suspend false
,08-08 15:42:27.199   872  2011 D DhcpClient: Broadcasting DHCPDISCOVER
,08-08 15:42:27.213   872  3880 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172676, domain null
,08-08 15:42:27.214   872  2011 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172676 seconds
,08-08 15:42:27.220   872  2011 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-08 15:42:27.235   872  3880 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-08 15:42:27.236   872  2011 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-08 15:42:27.245   371   870 D CommandListener: Setting iface cfg
,08-08 15:42:27.259   872  2011 D DhcpClient: Scheduling renewal in 86399s
,08-08 15:42:27.260   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-08 15:42:27.274   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-08 15:42:27.277   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-08 15:42:27.278   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-08 15:42:27.279   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-08 15:42:27.288   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-08 15:42:27.297   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-08 15:42:27.343   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-08 15:42:27.343   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-08 15:42:27.344   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-08 15:42:27.346   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-08 15:42:27.347   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-08 15:42:27.356   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-08 15:42:27.362   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-08 15:42:27.362   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-08 15:42:27.362   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-08 15:42:27.362   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-08 15:42:27.362   872  1309 D ConnectivityService:    accepting network in place of null
08-08 15:42:27.363   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 15:42:27.363   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 15:42:27.372   872  3879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146548, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-08 15:42:27.415   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:27.444   872  3878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,08-08 15:42:27.453   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:27.460   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-08 15:42:27.461   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:27.468   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-08 15:42:27.473   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:27.491  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:27.493  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:27.502  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:27.504  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:27.506  1802  1802 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-08 15:42:27.511  1829  1829 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 15:42:27.514  1829  1829 D SystemUpdateService: onCreate
,08-08 15:42:27.519  1829  1829 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 15:42:27.521  1829  3892 I SystemUpdateService: active receiver: enabled
,08-08 15:42:27.524  1829  3892 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 15:42:27.527  1829  3892 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-08 15:42:27.527  1829  3892 I SystemUpdateService: now status is 0 (complete)
08-08 15:42:27.527  1829  3892 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 15:42:27.527  1829  3892 I SystemUpdateService: file has been verified
08-08 15:42:27.527  1829  3892 I SystemUpdateService: OTA package size = 12249756
,08-08 15:42:27.532  1829  3892 I SystemUpdateService: showing system update notification
,08-08 15:42:27.538  1829  1829 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-08 15:42:27.541  1829  2346 I iu.UploadsManager: num queued entries: 0
,08-08 15:42:27.541  1829  2346 I iu.UploadsManager: num updated entries: 0
,08-08 15:42:27.542  1829  2346 I iu.SyncManager: NEXT; no task
,08-08 15:42:27.548  1829  1829 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 15:42:27.549  1829  1829 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 15:42:27.549   872  3878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 13:42:27 GMT], X-Android-Received-Millis=[1470663747549], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470663747508]}
08-08 15:42:27.550  1829  3895 I MDM     : [209] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-08 15:42:27.550  1829  3895 W BaseAppContext: Using Auth Proxy for data requests.
,08-08 15:42:27.552   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 15:42:27.553   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-08 15:42:27.553   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-08 15:42:27.553  1829  3895 V GoogleAuthProtoRequest: [209] a.<init>: mAccountName set to: thalitester@gmail.com
08-08 15:42:27.553  1829  1829 D SystemUpdateService: onDestroy
08-08 15:42:27.554   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 15:42:27.558  3698  3698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:27.562  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:27.563  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:27.564  3698  3698 D SprintDMHelper: simOperator: 
08-08 15:42:27.564  3698  3698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 15:42:27.594  1506  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-08 15:42:27.594  1506  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-08 15:42:27.594  1506  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 15:42:27.595  1506  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:27.620  1829  3895 E MDM     : [209] SitrepService.a: Error sending sitrep.
,08-08 15:42:27.683  2372  3898 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-08 15:42:28.461   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-08 15:42:29.387   872  1828 D WifiService: setWifiEnabled: false pid=3584, uid=10000
,08-08 15:42:29.387   872  1828 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 15:42:29.424  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-08 15:42:29.430   872  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-08 15:42:29.430   872  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-08 15:42:29.431   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 15:42:29.432   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:29.461   872  2011 D DhcpClient: Clearing IP address
,08-08 15:42:29.462   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-08 15:42:29.466   371   870 D CommandListener: Setting iface cfg
,08-08 15:42:29.468  1506  3902 V NativeCrypto: Read error: ssl=0x9aee5800: I/O error during system call, Connection timed out
,08-08 15:42:29.472  1506  3902 V NativeCrypto: SSL shutdown failed: ssl=0x9aee5800: I/O error during system call, Broken pipe
,08-08 15:42:29.478   872  1690 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-08 15:42:29.478   872  3878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-08 15:42:29.484   872  3878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-08 15:42:29.486   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-08 15:42:29.486   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-08 15:42:29.498   872  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-08 15:42:29.499   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 15:42:29.501   399   399 E Parcel  : Reading a NULL string not supported here.
08-08 15:42:29.501   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-08 15:42:29.503   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 15:42:29.504   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-08 15:42:29.504   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-08 15:42:29.510   872  3880 D DhcpClient: Receive thread stopped
,08-08 15:42:29.511   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 15:42:29.511   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:29.518  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:29.521  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:29.524  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:29.525   872  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-08 15:42:29.527  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:29.529  1847  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 15:42:29.542   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:29.562   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:29.562   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-08 15:42:29.563   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:29.565   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-08 15:42:29.568  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:29.570  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:29.572  1802  1802 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-08 15:42:29.575  1829  1829 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 15:42:29.580  1829  1829 D SystemUpdateService: onCreate
,08-08 15:42:29.582  1829  1829 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 15:42:29.585  1829  3912 I SystemUpdateService: active receiver: enabled
08-08 15:42:29.587  1829  3912 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 15:42:29.588  1829  3912 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-08 15:42:29.588  1829  3912 I SystemUpdateService: now status is 0 (complete)
,08-08 15:42:29.589  1829  3912 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 15:42:29.589  1829  3912 I SystemUpdateService: file has been verified
08-08 15:42:29.589  1829  3912 I SystemUpdateService: OTA package size = 12249756
,08-08 15:42:29.591  1829  1829 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-08 15:42:29.592  1829  2346 I iu.UploadsManager: num queued entries: 0
08-08 15:42:29.592  1829  2346 I iu.UploadsManager: num updated entries: 0
08-08 15:42:29.593  1829  2346 I iu.SyncManager: NEXT; no task
,08-08 15:42:29.597  1829  3912 I SystemUpdateService: showing system update notification
,08-08 15:42:29.601  1829  1829 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 15:42:29.602  1829  1829 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 15:42:29.605  3698  3698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:29.608  3698  3698 D SprintDMHelper: simOperator: 
,08-08 15:42:29.608  3698  3698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 15:42:29.616  2372  3916 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-08 15:42:29.624  1829  1829 D SystemUpdateService: onDestroy
,08-08 15:42:29.641   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-08 15:42:29.642   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 15:42:30.952   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-08 15:42:30.962  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-08 15:42:30.978   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 15:42:30.978   872   892 I Adreno  : Build Date                       : 10/20/15
08-08 15:42:30.978   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 15:42:30.978   872   892 I Adreno  : Local Branch                     : M14
08-08 15:42:30.978   872   892 I Adreno  : Remote Branch                    : 
08-08 15:42:30.978   872   892 I Adreno  : Remote Branch                    : 
08-08 15:42:30.978   872   892 I Adreno  : Reconstruct Branch               : 
,08-08 15:42:31.021   280  2082 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (213 us)
,08-08 15:42:31.622  3584  3584 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-08 15:42:31.622  3584  3584 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-08 15:42:31.686  3584  3584 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e1f4ecf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@181545e, 16908290=android.view.AbsSavedState$1@181545e}, android:focusedViewId=100}]}]
,08-08 15:42:31.687  3584  3584 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-08 15:42:31.686   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-08 15:42:31.687  3584  3584 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-08 15:42:31.687  3584  3584 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-08 15:42:31.699   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-08 15:42:31.701   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-08 15:42:31.701   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-08 15:42:31.702   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-08 15:42:31.712   872   881 I art     : Background partial concurrent mark sweep GC freed 19590(1238KB) AllocSpace objects, 4(124KB) LOS objects, 33% free, 28MB/43MB, paused 3.557ms total 115.481ms
,08-08 15:42:31.938   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-08 15:42:31.943   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-08 15:42:31.949   872  1332 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,08-08 15:42:31.952   872   892 I DreamManagerService: Entering dreamland.
,08-08 15:42:31.953   872   892 I PowerManagerService: Dozing...
,08-08 15:42:31.955   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-08 15:42:32.009   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-08 15:42:32.010   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-08 15:42:32.015   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 15:42:32.019   872  1307 E native  : do suspend false
,08-08 15:42:32.022  1719  3923 D NfcService: Discovery configuration equal, not updating.
,08-08 15:42:32.044   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 15:42:32.047   872  1307 E native  : do suspend true
,08-08 15:42:32.152   375  1479 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-08 15:42:32.153   375  1479 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-08 15:42:32.400  3651  3710 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 15:42:32.401  3651  3710 D BluetoothAdapterProperties: Setting state to 13
,08-08 15:42:32.401  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 15:42:32.405  3651  3710 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 15:42:32.410  3651  3710 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:32.412  3651  3651 D BluetoothMapService: onReceive
08-08 15:42:32.412  3651  3651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 15:42:32.412  3651  3651 D BluetoothMapService: STATE_TURNING_OFF
,08-08 15:42:32.413  3651  3651 D BluetoothMapService: MAP Service closeService in
08-08 15:42:32.414  3651  3651 D BluetoothMapMasInstance0: MAP Service shutdown
08-08 15:42:32.414  3651  3651 D ObexServerSockets0: shutdown(block = true)
08-08 15:42:32.415  3651  3834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-08 15:42:32.426  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 15:42:32.429  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:32.429  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:32.430  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:32.429  3651  3714 D BluetoothAdapterProperties: Scan Mode:20
08-08 15:42:32.430  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:32.431  3651  3651 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-08 15:42:32.431  3651  3835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 15:42:32.432  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-08 15:42:32.433  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:32.433  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:32.434  3651  3809 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-08 15:42:32.434  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:32.434  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:32.435  3651  3651 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 15:42:32.435  3651  3651 D HeadsetService: Received stop request...Stopping profile...
08-08 15:42:32.437  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:32.439  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:32.439  1735  2111 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:32.439   872   872 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:32.439   872   872 D BluetoothHeadset: Proxy object disconnected
,08-08 15:42:32.439  3651  3651 I BtOppRfcommListener: stopping Accept Thread
08-08 15:42:32.440  3651  3868 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 15:42:32.440  1364  1823 D BluetoothHeadset: Proxy object disconnected
,08-08 15:42:32.440   872   872 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:32.440  3651  3868 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 15:42:32.441  3813  3826 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:32.442  3651  3651 D A2dpService: Received stop request...Stopping profile...
,08-08 15:42:32.442  3651  3827 D A2dpStateMachine: Exit Disconnected: -1
,08-08 15:42:32.443   872   872 D BluetoothA2dp: Proxy object disconnected
,08-08 15:42:32.444  3651  3651 D HidService: Received stop request...Stopping profile...
08-08 15:42:32.444  3651  3651 D HidService: Stopping Bluetooth HidService
,08-08 15:42:32.446  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,08-08 15:42:32.446  1364  1364 D BluetoothA2dp: Proxy object disconnected
,08-08 15:42:32.446  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-08 15:42:32.446  1364  1364 D HidProfile: Bluetooth service disconnected
08-08 15:42:32.447  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:32.447  3651  3651 D HealthService: Received stop request...Stopping profile...
,08-08 15:42:32.449  3651  3651 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:32.449  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:32.450  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:32.450  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:32.450  3651  3651 D PanService: Received stop request...Stopping profile...
08-08 15:42:32.451  3813  3813 D HeadsetProfile: Bluetooth service disconnected
,08-08 15:42:32.452  3813  3813 D BluetoothA2dp: Proxy object disconnected
,08-08 15:42:32.452  3813  3813 D BluetoothInputDevice: Proxy object disconnected
,08-08 15:42:32.452  3813  3813 D HidProfile: Bluetooth service disconnected
08-08 15:42:32.452  3813  3813 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 15:42:32.452  3813  3813 D PanProfile: Bluetooth service disconnected
08-08 15:42:32.453  3651  3651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-08 15:42:32.453  3651  3651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 15:42:32.453  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-08 15:42:32.453  3651  3651 D BluetoothMapService: Received stop request...Stopping profile...
08-08 15:42:32.453  3651  3651 D BluetoothMapService: stop()
08-08 15:42:32.454  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:32.454  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:32.454  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:32.454  3651  3714 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-08 15:42:32.456  3651  3651 D BluetoothMapAppObserver: deinitObservers()
08-08 15:42:32.456  3651  3651 D BluetoothMapAppObserver: removeReceiver()
,08-08 15:42:32.458  3813  3813 D BluetoothMap: Proxy object disconnected
08-08 15:42:32.458  3813  3813 D MapProfile: Bluetooth service disconnected
,08-08 15:42:32.461  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:32.462  3651  3651 V BluetoothAdapterState: isTurningOff()=true
,08-08 15:42:32.462  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:32.462  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:32.462  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:32.465  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 15:42:32.465  1364  1364 D PanProfile: Bluetooth service disconnected
,08-08 15:42:32.465  1364  1364 D BluetoothMap: Proxy object disconnected
08-08 15:42:32.465  1364  1364 D MapProfile: Bluetooth service disconnected
,08-08 15:42:32.466  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:32.466  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:32.466  3651  3800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 15:42:32.466  3651  3800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-08 15:42:32.467  3651  3800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-08 15:42:32.467  3651  3651 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:32.467  3651  3800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 15:42:32.467  3651  3651 V BluetoothAdapterState: isTurningOn()=false
,08-08 15:42:32.467  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-08 15:42:32.467  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:32.467  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:32.467  3651  3651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 15:42:32.467  3651  3651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 15:42:32.467  3651  3714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 15:42:32.468  3651  3651 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:32.468  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:32.468  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:32.468  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:32.468  3651  3651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 15:42:32.468  3651  3714 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 15:42:32.468  3651  3651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 15:42:32.469  3651  3651 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:32.469  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:32.469  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:32.469  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:32.469  3651  3651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-08 15:42:32.470  3651  3651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-08 15:42:32.471  3651  3651 D BluetoothMapService: MAP Service closeService in
,08-08 15:42:32.471  3651  3651 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:32.471  3651  3651 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:32.471  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:32.471  3651  3651 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:32.472  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 15:42:32.472  3651  3710 D BluetoothAdapterProperties: Setting state to 15
08-08 15:42:32.472  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 15:42:32.472  3651  3710 I BluetoothAdapterState: Entering BleOnState
,08-08 15:42:32.473  3813  3825 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-08 15:42:32.473  3651  3651 D BluetoothMapService: cleanup()
08-08 15:42:32.473  3651  3651 D BluetoothMapService: MAP Service closeService in
,08-08 15:42:32.474  3813  3826 D BluetoothMap: onBluetoothStateChange: up=false
08-08 15:42:32.475  3813  3825 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 15:42:32.475  1364  1364 D BluetoothPbap: Proxy object disconnected
08-08 15:42:32.475  1364  1364 D PbapServerProfile: Bluetooth service disconnected
08-08 15:42:32.475  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 15:42:32.476  3813  3813 D BluetoothPbap: Proxy object disconnected
08-08 15:42:32.476  1364  1823 D BluetoothPan: onBluetoothStateChange on: false
,08-08 15:42:32.476  3813  3813 D PbapServerProfile: Bluetooth service disconnected
,08-08 15:42:32.476  3813  3826 D BluetoothPan: onBluetoothStateChange on: false
,08-08 15:42:32.478  3813  3825 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 15:42:32.479   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 15:42:32.479   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:32.479  1364  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-08 15:42:32.480  1364  3583 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-08 15:42:32.481  1735  1912 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 15:42:32.481   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:32.481   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:32.481  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:32.482  3813  3930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:32.482  1364  1823 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 15:42:32.483  3651  3710 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-08 15:42:32.483  3651  3710 D BluetoothAdapterProperties: Setting state to 16
08-08 15:42:32.483  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 15:42:32.484  3651  3710 D BluetoothAdapterProperties: onBleDisable
08-08 15:42:32.485  3651  3710 I BluetoothAdapterState: Entering PendingCommandState
08-08 15:42:32.485  3651  3711 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-08 15:42:32.486  3651  3800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 15:42:32.486  3651  3800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:32.486  3651  3714 D BluetoothAdapterProperties: Scan Mode:20
08-08 15:42:32.487  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:32.489  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:32.489  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 15:42:32.490  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:32.491  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:32.494  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 15:42:32.503  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:32.693  3651  3714 I bt_hci  : shut_down
,08-08 15:42:32.694  3651  3730 D bt_hwcfg: hw_epilog_process
,08-08 15:42:32.696  3651  3730 I bt_vendor: low_power_mode_cb
,08-08 15:42:32.719  3651  3730 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-08 15:42:32.719  3651  3730 I bt_vendor: epilog_cb
,08-08 15:42:32.719  3651  3730 I bt_hci  : epilog_finished_callback
,08-08 15:42:32.728  3651  3714 I bt_hci_h4: hal_close
,08-08 15:42:32.730  3651  3714 I bt_userial_vendor: device fd = 51 close
,08-08 15:42:32.857  3651  3711 D bt_stack_manager: event_shut_down_stack finished.
,08-08 15:42:32.858  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 15:42:32.865  3651  3651 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 15:42:32.865  3651  3710 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-08 15:42:32.866  3651  3651 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 15:42:32.867  3651  3651 D BtGatt.GattService: stop()
08-08 15:42:32.867  3651  3651 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 15:42:32.872  3651  3651 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:32.872  3651  3651 V BluetoothAdapterState: isTurningOn()=false
,08-08 15:42:32.873  3651  3651 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:32.873  3651  3651 V BluetoothAdapterState: isBleTurningOff()=true
,08-08 15:42:32.874  3651  3710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-08 15:42:32.875  3651  3710 D BluetoothAdapterProperties: Setting state to 10
,08-08 15:42:32.875  3651  3710 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 15:42:32.876  3651  3710 I BluetoothAdapterState: Entering OffState
,08-08 15:42:32.880   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-08 15:42:32.912  3651  3651 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-08 15:42:32.912  3651  3651 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-08 15:42:32.913  3651  3711 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-08 15:42:32.922  3651  3711 D bt_stack_manager: event_clean_up_stack finished.
,08-08 15:42:32.922  3651  3651 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-08 15:42:32.924  3651  3651 I art     : System.exit called, status: 0
08-08 15:42:32.924  3651  3651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-08 15:42:32.990   872   882 I ActivityManager: Process com.android.bluetooth (pid 3651) has died
,08-08 15:42:35.367   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-08 15:42:35.436   872   889 I ActivityManager: Start proc 3933:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-08 15:42:35.561  3933  3933 D AdapterServiceConfig: Adding HeadsetService
,08-08 15:42:35.562  3933  3933 D AdapterServiceConfig: Adding A2dpService
,08-08 15:42:35.562  3933  3933 D AdapterServiceConfig: Adding HidService
08-08 15:42:35.562  3933  3933 D AdapterServiceConfig: Adding HealthService
08-08 15:42:35.562  3933  3933 D AdapterServiceConfig: Adding PanService
,08-08 15:42:35.563  3933  3933 D AdapterServiceConfig: Adding GattService
08-08 15:42:35.563  3933  3933 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 15:42:35.580   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7b0d1e:true
,08-08 15:42:35.581  3933  3933 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 15:42:35.587  3933  3933 I bt_bluedroid: init
,08-08 15:42:35.588  3933  3945 I BluetoothAdapterState: Entering OffState
,08-08 15:42:35.594  3933  3946 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 15:42:35.594  3933  3946 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 15:42:35.595  3933  3946 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 15:42:35.595  3933  3946 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 15:42:35.597  3933  3933 I bt_bluedroid: get_profile_interface socket
08-08 15:42:35.599  3933  3933 I bt_bluedroid: get_profile_interface sdp
,08-08 15:42:35.604  3933  3949 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 15:42:35.605  3933  3944 I bt_bluedroid: config_hci_snoop_log
,08-08 15:42:35.607  3933  3949 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 15:42:35.608   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-08 15:42:35.618  3933  3945 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 15:42:35.619  3933  3945 D BluetoothAdapterProperties: Setting state to 14
,08-08 15:42:35.621  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 15:42:35.628  3933  3945 D BluetoothBondStateMachine: make
,08-08 15:42:35.633  3933  3950 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 15:42:35.642  3933  3945 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:35.646  3933  3933 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 15:42:35.653  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:35.655  3933  3933 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 15:42:35.656  3933  3933 D BtGatt.GattService: Received start request. Starting profile...
,08-08 15:42:35.657  3933  3933 D BtGatt.GattService: start()
08-08 15:42:35.657  3933  3933 I bt_bluedroid: get_profile_interface gatt
,08-08 15:42:35.659  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:35.659  3933  3933 D BtGatt.AdvertiseManager: advertise manager created
,08-08 15:42:35.670  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:35.671  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:35.671  3933  3933 V BluetoothAdapterState: isBleTurningOn()=true
,08-08 15:42:35.671  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:35.671  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 15:42:35.672  3933  3945 I bt_bluedroid: enable
,08-08 15:42:35.672  3933  3946 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-08 15:42:35.673  3933  3946 I bt_hci  : start_up
,08-08 15:42:35.681  3933  3946 I bt_vendor: alloc value 0xb3a88189
,08-08 15:42:35.681  3933  3946 I bt_vendor: init
08-08 15:42:35.681  3933  3946 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 15:42:35.682  3933  3946 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 15:42:35.787  3933  3946 D bt_hci  : start_up starting async portion
08-08 15:42:35.787  3933  3953 I bt_hci  : event_finish_startup
,08-08 15:42:35.787  3933  3953 I bt_hci_h4: hal_open
08-08 15:42:35.787  3933  3953 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 15:42:35.793  3933  3953 I bt_userial_vendor: device fd = 51 open
,08-08 15:42:35.829  3933  3953 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 15:42:35.862  3933  3953 D bt_hwcfg: Chipset BCM4354A2
08-08 15:42:35.862  3933  3953 D bt_hwcfg: Target name = [BCM4354A2]
08-08 15:42:35.862  3933  3953 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 15:42:36.228  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:36.239  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:36.243  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:36.296  1506  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 15:42:36.297  1506  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 15:42:36.297  1506  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 15:42:36.297  1506  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:36.332  1847  2493 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 15:42:36.333  3320  3320 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 15:42:36.334  3320  3320 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 15:42:36.334  3320  3320 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-08 15:42:36.449  3933  3953 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-08 15:42:36.451  3933  3953 D bt_hwcfg: Settlement delay -- 100 ms
08-08 15:42:36.451  3933  3953 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 15:42:36.568  3933  3953 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 15:42:36.569  3933  3953 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 15:42:36.598  3933  3953 I bt_hwcfg: vendor lib fwcfg completed
,08-08 15:42:36.599  3933  3953 I bt_vendor: firmware callback
,08-08 15:42:36.599  3933  3953 I bt_hci  : firmware_config_callback
,08-08 15:42:36.610  3933  3956 I bt_btu  : btu_task pending for preload complete event
,08-08 15:42:36.611  3933  3956 I bt_btu_task: Bluetooth chip preload is complete
,08-08 15:42:36.611  3933  3956 I bt_btu  : btu_task received preload complete event
,08-08 15:42:36.624  3933  3956 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 15:42:36.625  3933  3956 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 15:42:36.625  3933  3956 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 15:42:36.625  3933  3956 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 15:42:36.626  3933  3956 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-08 15:42:36.626  3933  3956 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 15:42:36.626  3933  3956 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 15:42:36.627  3933  3956 I         : BTE_InitTraceLevels -- TRC_BTM
,08-08 15:42:36.628  3933  3956 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 15:42:36.628  3933  3956 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 15:42:36.629  3933  3956 I         : BTE_InitTraceLevels -- TRC_SDP
,08-08 15:42:36.629  3933  3956 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 15:42:36.630  3933  3956 I         : BTE_InitTraceLevels -- TRC_SMP
,08-08 15:42:36.630  3933  3956 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 15:42:36.631  3933  3956 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 15:42:36.764  3933  3956 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a05d9d
,08-08 15:42:36.764  3933  3956 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a05d9d 
,08-08 15:42:36.776  3933  3949 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 15:42:36.779  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 15:42:36.779  3933  3949 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-08 15:42:36.786  3933  3949 D BluetoothAdapterProperties: Name is: Nexus 6
08-08 15:42:36.788  3933  3949 D BluetoothAdapterProperties: Scan Mode:20
,08-08 15:42:36.789  3933  3949 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 15:42:36.789  3933  3949 D bt_hci  : do_postload posting postload work item
08-08 15:42:36.789  3933  3953 I bt_hci  : event_postload
08-08 15:42:36.789  3933  3953 I bt_vendor: sco_config_cb
,08-08 15:42:36.789  3933  3953 I bt_hci  : sco_config_callback postload finished.
08-08 15:42:36.791  3933  3949 D bt_bte_conf: Device ID record 1 : primary
08-08 15:42:36.792  3933  3949 D bt_bte_conf:   vendorId            = 000f
,08-08 15:42:36.792  3933  3949 D bt_bte_conf:   vendorIdSource      = 0001
08-08 15:42:36.792  3933  3949 D bt_bte_conf:   product             = 1200
08-08 15:42:36.792  3933  3949 D bt_bte_conf:   version             = 1436
,08-08 15:42:36.792  3933  3949 D bt_bte_conf:   clientExecutableURL = 
,08-08 15:42:36.793  3933  3949 D bt_bte_conf:   serviceDescription  = 
08-08 15:42:36.793  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:36.793  3933  3949 D bt_bte_conf:   documentationURL    = 
,08-08 15:42:36.794  3933  3949 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 15:42:36.794  3933  3946 D bt_stack_manager: event_start_up_stack finished
08-08 15:42:36.795  3933  3953 I bt_vendor: low_power_mode_cb
,08-08 15:42:36.796  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 15:42:36.796  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:36.796  3933  3945 D BluetoothAdapterProperties: Setting state to 15
08-08 15:42:36.797  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 15:42:36.798  3933  3945 I BluetoothAdapterState: Entering BleOnState
,08-08 15:42:36.803  3933  3945 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-08 15:42:36.803  3933  3945 D BluetoothAdapterProperties: Setting state to 11
08-08 15:42:36.804  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 15:42:36.812  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:36.816  3933  3933 D HeadsetService: Received start request. Starting profile...
,08-08 15:42:36.824  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:36.828  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:36.830  3933  3933 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 15:42:36.830  3933  3933 D HeadsetStateMachine: make
08-08 15:42:36.831  3933  3945 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:36.840  3933  3933 D HeadsetStateMachine: max_hf_connections = 1
,08-08 15:42:36.840  3933  3933 I bt_bluedroid: get_profile_interface handsfree
08-08 15:42:36.840  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-08 15:42:36.841  3933  3949 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 15:42:36.846  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:36.847  3933  3933 D A2dpService: Received start request. Starting profile...
,08-08 15:42:36.847  3933  3933 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 15:42:36.848  3933  3933 I bt_bluedroid: get_profile_interface avrcp
,08-08 15:42:36.859  3933  3933 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 15:42:36.860  3933  3933 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 15:42:36.860  3933  3933 D A2dpStateMachine: make
,08-08 15:42:36.862  3933  3933 I bt_bluedroid: get_profile_interface a2dp
,08-08 15:42:36.863  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 15:42:36.866  3933  3964 D A2dpStateMachine: Enter Disconnected: -2
,08-08 15:42:36.867  3933  3933 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 15:42:36.869  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:36.870  3933  3933 D HidService: Received start request. Starting profile...
,08-08 15:42:36.870  3933  3933 I bt_bluedroid: get_profile_interface hidhost
,08-08 15:42:36.871  3933  3949 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e73e5
08-08 15:42:36.871  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-08 15:42:36.871  3933  3933 D HidService: setHidService(): set to: null
08-08 15:42:36.872  3933  3933 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-08 15:42:36.873  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:36.877  3933  3933 D HealthService: Received start request. Starting profile...
,08-08 15:42:36.879  3933  3933 I bt_bluedroid: get_profile_interface health
,08-08 15:42:36.880  3933  3933 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-08 15:42:36.881  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:36.882  3933  3933 D PanService: Received start request. Starting profile...
,08-08 15:42:36.882  3933  3933 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-08 15:42:36.882  3933  3933 I bt_bluedroid: get_profile_interface pan
,08-08 15:42:36.882  3933  3949 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 15:42:36.886  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:36.886  3933  3933 D BluetoothMapService: Received start request. Starting profile...
08-08 15:42:36.886  3933  3933 D BluetoothMapService: start()
,08-08 15:42:36.889  3933  3933 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-08 15:42:36.890  3933  3933 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 15:42:36.890  3933  3933 D BluetoothMapAppObserver: createReceiver()
,08-08 15:42:36.891  3933  3933 D BluetoothMapAppObserver: initObservers()
,08-08 15:42:36.891  3933  3933 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 15:42:36.901  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:36.901  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:36.901  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.901  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:36.902  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:36.904  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:36.904  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.904  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:36.904  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.905  3933  3962 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:36.905  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:36.906  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:36.907  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-08 15:42:36.907  3933  3945 D BluetoothAdapterProperties: ScanMode =  20
08-08 15:42:36.907  3933  3945 D BluetoothAdapterProperties: State =  11
08-08 15:42:36.910  3933  3949 D BluetoothAdapterProperties: Scan Mode:21
08-08 15:42:36.910  3933  3945 D BluetoothAdapterProperties: Setting state to 12
08-08 15:42:36.910  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 15:42:36.911  3933  3949 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 15:42:36.911  3933  3945 I BluetoothAdapterState: Entering OnState
08-08 15:42:36.912  3813  3930 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 15:42:36.915  3813  3826 D BluetoothMap: onBluetoothStateChange: up=true
,08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:36.916  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:36.918  3813  3930 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 15:42:36.919  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:36.921  3813  3813 D BluetoothInputDevice: Proxy object connected
,08-08 15:42:36.922  3933  3933 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 15:42:36.922  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 15:42:36.921  3813  3813 D HidProfile: Bluetooth service connected
,08-08 15:42:36.923  3933  3933 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-08 15:42:36.924  1364  3583 D BluetoothPan: onBluetoothStateChange on: true
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:36.924  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:36.930  3813  3826 D BluetoothPan: onBluetoothStateChange on: true
,08-08 15:42:36.931  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:36.932  3933  3933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:36.933  3813  3825 D BluetoothPbap: onBluetoothStateChange: up=true
,08-08 15:42:36.934  3933  3933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:36.935   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 15:42:36.935  3933  3933 D ObexServerSockets: Succeed to create listening sockets 
,08-08 15:42:36.935  3933  3933 D ObexServerSockets0: startAccept()
08-08 15:42:36.935  3933  3933 D ObexServerSockets0: prepareForNewConnect()
08-08 15:42:36.936   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 15:42:36.936  1364  1375 D BluetoothMap: onBluetoothStateChange: up=true
08-08 15:42:36.938  3933  3933 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 15:42:36.938  3933  3933 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 15:42:36.938  1364  1823 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 15:42:36.939  3933  3972 D ObexServerSockets0: Accepting socket connection...
,08-08 15:42:36.939  3933  3971 D ObexServerSockets0: Accepting socket connection...
,08-08 15:42:36.939  1364  1364 D BluetoothMap: Proxy object connected
,08-08 15:42:36.939  1364  1364 D MapProfile: Bluetooth service connected
08-08 15:42:36.939  1364  1364 D BluetoothMap: getConnectedDevices()
08-08 15:42:36.940   872   872 D BluetoothA2dp: Proxy object connected
,08-08 15:42:36.941  1735  1750 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:36.942  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:36.942   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:36.942  1364  1364 D PanProfile: Bluetooth service connected
,08-08 15:42:36.942   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:36.942  1364  1364 D BluetoothInputDevice: Proxy object connected
08-08 15:42:36.942  1364  1364 D HidProfile: Bluetooth service connected
08-08 15:42:36.942  1364  3583 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:36.942  3813  3930 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:36.943  3813  3813 D BluetoothMap: Proxy object connected
08-08 15:42:36.943  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 15:42:36.943  3813  3813 D MapProfile: Bluetooth service connected
08-08 15:42:36.943  3813  3813 D BluetoothMap: getConnectedDevices()
08-08 15:42:36.944  1364  1364 D BluetoothA2dp: Proxy object connected
08-08 15:42:36.945  3813  3813 D BluetoothA2dp: Proxy object connected
08-08 15:42:36.946   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-08 15:42:36.946  3933  3933 D BluetoothMapService: onReceive
08-08 15:42:36.946  3933  3933 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 15:42:36.947  3933  3933 D BluetoothMapService: STATE_ON
08-08 15:42:36.949  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:36.949  3813  3813 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:36.949  3813  3813 D PanProfile: Bluetooth service connected
08-08 15:42:36.950  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:36.955  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 15:42:36.963  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:36.964  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:36.972  3813  3813 D BluetoothPbap: Proxy object connected
,08-08 15:42:36.972  3813  3813 D PbapServerProfile: Bluetooth service connected
08-08 15:42:36.972  3933  3933 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 15:42:36.972  3933  3933 D ObexServerSockets0: prepareForNewConnect()
08-08 15:42:36.972  1364  1364 D BluetoothPbap: Proxy object connected
,08-08 15:42:36.972  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-08 15:42:36.979  3933  3977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:36.995  3933  3981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:36.997  3933  3981 I BtOppRfcommListener: Accept thread started.
,08-08 15:42:37.038  1735  1747 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.038   872   872 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.038   872   872 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.038  1364  1375 D BluetoothHeadset: Proxy object connected
08-08 15:42:37.038   872   872 D BluetoothHeadset: Proxy object connected
08-08 15:42:37.038  1364  1364 D HeadsetProfile: Bluetooth service connected
08-08 15:42:37.039  3813  3930 D BluetoothHeadset: Proxy object connected
08-08 15:42:37.039  3813  3813 D HeadsetProfile: Bluetooth service connected
08-08 15:42:37.043  1735  2111 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.054   872   889 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.054   872   889 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.060  1364  1823 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.061  1364  1364 D HeadsetProfile: Bluetooth service connected
08-08 15:42:37.061  3813  3826 D BluetoothHeadset: Proxy object connected
,08-08 15:42:37.061  3813  3813 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:38.401  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:38.401  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:41.408  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:41.409  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a79c03f added. We now have 6 listener(s)
,08-08 15:42:41.409  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:41.415  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:41.415  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e243d0c added. We now have 7 listener(s)
,08-08 15:42:41.416  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:41.419  3584  3633 I System.out: IsBluetoothEnabled
,08-08 15:42:41.431  3933  3945 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 15:42:41.431  3933  3945 D BluetoothAdapterProperties: Setting state to 13
,08-08 15:42:41.431  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 15:42:41.434  3933  3945 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 15:42:41.437  3933  3945 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:41.448  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:41.448  3933  3933 D BluetoothMapService: onReceive
,08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:41.448  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:41.448  3933  3933 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 15:42:41.449  3933  3933 D BluetoothMapService: STATE_TURNING_OFF
08-08 15:42:41.449  3933  3933 D BluetoothMapService: MAP Service closeService in
,08-08 15:42:41.449  3933  3933 D BluetoothMapMasInstance0: MAP Service shutdown
08-08 15:42:41.449  3933  3933 D ObexServerSockets0: shutdown(block = true)
08-08 15:42:41.450  3933  3933 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 15:42:41.450  3933  3933 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 15:42:41.450  3584  3584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 15:42:41.451  3933  3958 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-08 15:42:41.451  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:41.451  3933  3972 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 15:42:41.452  3933  3971 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-08 15:42:41.453  3933  3933 I BtOppRfcommListener: stopping Accept Thread
08-08 15:42:41.453  3933  3981 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 15:42:41.455  3933  3949 D BluetoothAdapterProperties: Scan Mode:20
08-08 15:42:41.455  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-08 15:42:41.456  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 15:42:41.457  3933  3981 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 15:42:41.459  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:41.465  3933  3933 D HeadsetService: Received stop request...Stopping profile...
08-08 15:42:41.467  1735  1912 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.467  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:41.468   872   872 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.468  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.468  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:41.468   872   872 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.468  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:41.468  1364  1823 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.468  1364  1364 D HeadsetProfile: Bluetooth service disconnected
08-08 15:42:41.468   872   872 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.469  3813  3825 D BluetoothHeadset: Proxy object disconnected
08-08 15:42:41.470  3933  3933 D A2dpService: Received stop request...Stopping profile...
08-08 15:42:41.471  3933  3964 D A2dpStateMachine: Exit Disconnected: -1
08-08 15:42:41.472   872   872 D BluetoothA2dp: Proxy object disconnected
08-08 15:42:41.472  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-08 15:42:41.473  3933  3933 D HidService: Received stop request...Stopping profile...
08-08 15:42:41.473  3933  3933 D HidService: Stopping Bluetooth HidService
08-08 15:42:41.474  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-08 15:42:41.474  1364  1364 D HidProfile: Bluetooth service disconnected
,08-08 15:42:41.475  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:41.476  3933  3933 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-08 15:42:41.476  3933  3933 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 15:42:41.477  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-08 15:42:41.477  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:41.477  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:41.477  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:41.477  3933  3949 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 15:42:41.477  3933  3933 D HealthService: Received stop request...Stopping profile...
08-08 15:42:41.479  3933  3933 D PanService: Received stop request...Stopping profile...
08-08 15:42:41.481  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 15:42:41.481  1364  1364 D PanProfile: Bluetooth service disconnected
08-08 15:42:41.481  3933  3933 D BluetoothMapService: Received stop request...Stopping profile...
08-08 15:42:41.481  3933  3933 D BluetoothMapService: stop()
08-08 15:42:41.481  3813  3813 D DockEventReceiver: finishStartingService: stopping service
08-08 15:42:41.482  3933  3933 D BluetoothMapAppObserver: deinitObservers()
08-08 15:42:41.482  3933  3933 D BluetoothMapAppObserver: removeReceiver()
08-08 15:42:41.482  3813  3813 D HeadsetProfile: Bluetooth service disconnected
08-08 15:42:41.482  3813  3813 D BluetoothA2dp: Proxy object disconnected
08-08 15:42:41.483  3813  3813 D BluetoothInputDevice: Proxy object disconnected
08-08 15:42:41.483  3813  3813 D HidProfile: Bluetooth service disconnected
08-08 15:42:41.483  3813  3813 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 15:42:41.483  3813  3813 D PanProfile: Bluetooth service disconnected
08-08 15:42:41.483  1364  1364 D BluetoothMap: Proxy object disconnected
08-08 15:42:41.483  1364  1364 D MapProfile: Bluetooth service disconnected
08-08 15:42:41.484  3813  3813 D BluetoothMap: Proxy object disconnected
08-08 15:42:41.484  3813  3813 D MapProfile: Bluetooth service disconnected
08-08 15:42:41.486  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:41.486  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.486  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:41.486  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:41.486  1364  1364 D BluetoothPbap: Proxy object disconnected
08-08 15:42:41.486  1364  1364 D PbapServerProfile: Bluetooth service disconnected
08-08 15:42:41.487  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-08 15:42:41.487  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.487  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:41.487  3813  3813 D BluetoothPbap: Proxy object disconnected
08-08 15:42:41.487  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:41.487  3813  3813 D PbapServerProfile: Bluetooth service disconnected
08-08 15:42:41.488  3933  3933 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 15:42:41.488  3933  3933 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 15:42:41.488  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:41.488  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 15:42:41.488  3933  3956 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 15:42:41.488  3933  3956 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 15:42:41.489  3933  3956 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 15:42:41.489  3933  3956 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 15:42:41.489  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 15:42:41.489  3933  3949 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 15:42:41.491  3933  3933 V BluetoothAdapterState: isTurningOff()=true
,08-08 15:42:41.491  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.491  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:41.491  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:41.491  3933  3933 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-08 15:42:41.491  3933  3949 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 15:42:41.492  3933  3933 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 15:42:41.492  3933  3933 V BluetoothAdapterState: isTurningOff()=true
,08-08 15:42:41.492  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.492  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:41.492  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:41.492  3933  3933 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 15:42:41.492  3933  3933 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-08 15:42:41.493  3933  3933 D BluetoothMapService: MAP Service closeService in
08-08 15:42:41.493  3933  3933 V BluetoothAdapterState: isTurningOff()=true
,08-08 15:42:41.493  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.493  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:41.493  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:41.493  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 15:42:41.493  3933  3945 D BluetoothAdapterProperties: Setting state to 15
08-08 15:42:41.494  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-08 15:42:41.494  3933  3933 D BluetoothMapService: cleanup()
08-08 15:42:41.494  3933  3933 D BluetoothMapService: MAP Service closeService in
,08-08 15:42:41.495  3933  3945 I BluetoothAdapterState: Entering BleOnState
,08-08 15:42:41.495  3813  3930 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-08 15:42:41.496  3813  3826 D BluetoothMap: onBluetoothStateChange: up=false
,08-08 15:42:41.497  3813  3825 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-08 15:42:41.497  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=false
,08-08 15:42:41.498  1364  1823 D BluetoothPan: onBluetoothStateChange on: false
08-08 15:42:41.498  3813  3930 D BluetoothPan: onBluetoothStateChange on: false
,08-08 15:42:41.499  3813  3826 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 15:42:41.499   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 15:42:41.499   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 15:42:41.499  1364  3583 D BluetoothMap: onBluetoothStateChange: up=false
08-08 15:42:41.500  1364  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 15:42:41.500  1735  1750 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:41.501   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 15:42:41.501   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:41.501  1364  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:41.501  3813  3825 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 15:42:41.501  1364  1823 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-08 15:42:41.502  3933  3945 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-08 15:42:41.502  3933  3945 D BluetoothAdapterProperties: Setting state to 16
08-08 15:42:41.502  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16,
08-08 15:42:41.503  3933  3945 D BluetoothAdapterProperties: onBleDisable
08-08 15:42:41.504  3933  3945 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:41.504  3933  3946 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-08 15:42:41.505  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:41.505  3933  3949 D BluetoothAdapterProperties: Scan Mode:20
08-08 15:42:41.507  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:41.507  3933  3956 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 15:42:41.507  3933  3956 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 15:42:41.508  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 15:42:41.514  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 15:42:41.515  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:41.711  3933  3949 I bt_hci  : shut_down
,08-08 15:42:41.721  3933  3953 I bt_vendor: low_power_mode_cb
,08-08 15:42:41.726  3933  3953 D bt_hwcfg: hw_epilog_process
,08-08 15:42:41.742  3933  3953 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 15:42:41.742  3933  3953 I bt_vendor: epilog_cb
,08-08 15:42:41.743  3933  3953 I bt_hci  : epilog_finished_callback
,08-08 15:42:41.751  3933  3949 I bt_hci_h4: hal_close
,08-08 15:42:41.754  3933  3949 I bt_userial_vendor: device fd = 51 close
,08-08 15:42:41.875  3933  3946 D bt_stack_manager: event_shut_down_stack finished.
,08-08 15:42:41.877  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 15:42:41.884  3933  3933 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 15:42:41.884  3933  3945 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 15:42:41.886  3933  3933 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 15:42:41.886  3933  3933 D BtGatt.GattService: stop()
08-08 15:42:41.887  3933  3933 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 15:42:41.891  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:41.892  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-08 15:42:41.892  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:41.892  3933  3933 V BluetoothAdapterState: isBleTurningOff()=true
08-08 15:42:41.894  3933  3945 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-08 15:42:41.894  3933  3945 D BluetoothAdapterProperties: Setting state to 10
08-08 15:42:41.894  3933  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-08 15:42:41.896  3933  3945 I BluetoothAdapterState: Entering OffState
,08-08 15:42:41.898   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-08 15:42:41.919  3933  3933 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-08 15:42:41.919  3933  3933 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-08 15:42:41.920  3933  3946 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-08 15:42:41.922  3933  3946 D bt_stack_manager: event_clean_up_stack finished.
,08-08 15:42:41.923  3933  3933 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-08 15:42:41.925  3933  3933 I art     : System.exit called, status: 0
,08-08 15:42:41.925  3933  3933 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-08 15:42:41.988   872  1692 I ActivityManager: Process com.android.bluetooth (pid 3933) has died
,08-08 15:42:42.434  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:42.435  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:42.435  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 15:42:42.435  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:42.482   872   889 I ActivityManager: Start proc 3991:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-08 15:42:42.607  3991  3991 D AdapterServiceConfig: Adding HeadsetService
,08-08 15:42:42.607  3991  3991 D AdapterServiceConfig: Adding A2dpService
,08-08 15:42:42.607  3991  3991 D AdapterServiceConfig: Adding HidService
,08-08 15:42:42.607  3991  3991 D AdapterServiceConfig: Adding HealthService
,08-08 15:42:42.608  3991  3991 D AdapterServiceConfig: Adding PanService
,08-08 15:42:42.608  3991  3991 D AdapterServiceConfig: Adding GattService
,08-08 15:42:42.608  3991  3991 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 15:42:42.623   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33280bc:true
,08-08 15:42:42.624  3991  3991 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 15:42:42.629  3991  3991 I bt_bluedroid: init
,08-08 15:42:42.629  3991  4003 I BluetoothAdapterState: Entering OffState
,08-08 15:42:42.634  3991  4004 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 15:42:42.635  3991  4004 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 15:42:42.635  3991  4004 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 15:42:42.635  3991  4004 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 15:42:42.637  3991  3991 I bt_bluedroid: get_profile_interface socket
,08-08 15:42:42.639  3991  3991 I bt_bluedroid: get_profile_interface sdp
,08-08 15:42:42.642  3991  4007 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 15:42:42.644  3991  4002 I bt_bluedroid: config_hci_snoop_log
,08-08 15:42:42.647  3991  4007 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 15:42:42.648   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-08 15:42:42.656  3991  4003 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 15:42:42.657  3991  4003 D BluetoothAdapterProperties: Setting state to 14
08-08 15:42:42.657  3991  4003 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 15:42:42.661  3991  4003 D BluetoothBondStateMachine: make
,08-08 15:42:42.667  3991  4008 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 15:42:42.674  3991  4003 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:42.677  3991  3991 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 15:42:42.687  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:42.688  3991  3991 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 15:42:42.690  3991  3991 D BtGatt.GattService: Received start request. Starting profile...
,08-08 15:42:42.691  3991  3991 D BtGatt.GattService: start()
08-08 15:42:42.691  3991  3991 I bt_bluedroid: get_profile_interface gatt
,08-08 15:42:42.695  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:42.695  3991  3991 D BtGatt.AdvertiseManager: advertise manager created
,08-08 15:42:42.709  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:42.710  3991  3991 V BluetoothAdapterState: isTurningOn()=false
,08-08 15:42:42.710  3991  3991 V BluetoothAdapterState: isBleTurningOn()=true
,08-08 15:42:42.710  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:42.711  3991  4003 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 15:42:42.712  3991  4003 I bt_bluedroid: enable
08-08 15:42:42.713  3991  4004 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-08 15:42:42.714  3991  4004 I bt_hci  : start_up
,08-08 15:42:42.729  3991  4004 I bt_vendor: alloc value 0xb3a88189
,08-08 15:42:42.729  3991  4004 I bt_vendor: init
08-08 15:42:42.729  3991  4004 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 15:42:42.729  3991  4004 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 15:42:42.838  3991  4004 D bt_hci  : start_up starting async portion
,08-08 15:42:42.839  3991  4011 I bt_hci  : event_finish_startup
08-08 15:42:42.839  3991  4011 I bt_hci_h4: hal_open
,08-08 15:42:42.839  3991  4011 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 15:42:42.848  3991  4011 I bt_userial_vendor: device fd = 51 open
,08-08 15:42:42.881  3991  4011 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 15:42:42.912  3991  4011 D bt_hwcfg: Chipset BCM4354A2
,08-08 15:42:42.913  3991  4011 D bt_hwcfg: Target name = [BCM4354A2]
,08-08 15:42:42.914  3991  4011 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 15:42:43.541  3991  4011 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 15:42:43.542  3991  4011 D bt_hwcfg: Settlement delay -- 100 ms
08-08 15:42:43.543  3991  4011 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 15:42:43.659  3991  4011 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 15:42:43.660  3991  4011 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 15:42:43.690  3991  4011 I bt_hwcfg: vendor lib fwcfg completed
,08-08 15:42:43.690  3991  4011 I bt_vendor: firmware callback
08-08 15:42:43.690  3991  4011 I bt_hci  : firmware_config_callback
,08-08 15:42:43.701  3991  4013 I bt_btu  : btu_task pending for preload complete event
,08-08 15:42:43.702  3991  4013 I bt_btu_task: Bluetooth chip preload is complete
08-08 15:42:43.702  3991  4013 I bt_btu  : btu_task received preload complete event
,08-08 15:42:43.712  3991  4013 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 15:42:43.712  3991  4013 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-08 15:42:43.712  3991  4013 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 15:42:43.713  3991  4013 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 15:42:43.713  3991  4013 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-08 15:42:43.713  3991  4013 I         : BTE_InitTraceLevels -- TRC_A2D
,08-08 15:42:43.714  3991  4013 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 15:42:43.714  3991  4013 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 15:42:43.714  3991  4013 I         : BTE_InitTraceLevels -- TRC_GAP
,08-08 15:42:43.714  3991  4013 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 15:42:43.715  3991  4013 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 15:42:43.715  3991  4013 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 15:42:43.715  3991  4013 I         : BTE_InitTraceLevels -- TRC_SMP
,08-08 15:42:43.715  3991  4013 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 15:42:43.716  3991  4013 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 15:42:43.850  3991  4013 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a05d9d
,08-08 15:42:43.850  3991  4013 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a05d9d 
,08-08 15:42:43.856  3991  4007 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 15:42:43.858  3991  4007 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 15:42:43.860  3991  4007 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 15:42:43.863  3991  4007 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 15:42:43.866  3991  4007 D BluetoothAdapterProperties: Scan Mode:20
08-08 15:42:43.868  3991  4007 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 15:42:43.868  3991  4007 D bt_hci  : do_postload posting postload work item
,08-08 15:42:43.869  3991  4011 I bt_hci  : event_postload
,08-08 15:42:43.869  3991  4011 I bt_vendor: sco_config_cb
,08-08 15:42:43.869  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:43.869  3991  4011 I bt_hci  : sco_config_callback postload finished.
,08-08 15:42:43.874  3991  4007 D bt_bte_conf: Device ID record 1 : primary
,08-08 15:42:43.874  3991  4007 D bt_bte_conf:   vendorId            = 000f
08-08 15:42:43.875  3991  4007 D bt_bte_conf:   vendorIdSource      = 0001
,08-08 15:42:43.875  3991  4007 D bt_bte_conf:   product             = 1200
,08-08 15:42:43.875  3991  4007 D bt_bte_conf:   version             = 1436
08-08 15:42:43.875  3991  4007 D bt_bte_conf:   clientExecutableURL = 
,08-08 15:42:43.877  3991  4007 D bt_bte_conf:   serviceDescription  = 
,08-08 15:42:43.877  3991  4007 D bt_bte_conf:   documentationURL    = 
08-08 15:42:43.879  3991  4011 I bt_vendor: low_power_mode_cb
,08-08 15:42:43.879  3991  4007 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-08 15:42:43.880  3991  4004 D bt_stack_manager: event_start_up_stack finished
08-08 15:42:43.881  3991  4003 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-08 15:42:43.884  3991  4003 D BluetoothAdapterProperties: Setting state to 15
,08-08 15:42:43.884  3991  4003 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 15:42:43.885  3991  4003 I BluetoothAdapterState: Entering BleOnState
,08-08 15:42:43.893  3991  4003 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-08 15:42:43.894  3991  4003 D BluetoothAdapterProperties: Setting state to 11
,08-08 15:42:43.894  3991  4003 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 15:42:43.900  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:43.907  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.909  3991  3991 D HeadsetService: Received start request. Starting profile...
,08-08 15:42:43.913  3991  3991 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 15:42:43.913  3991  3991 D HeadsetStateMachine: make
,08-08 15:42:43.921  3991  4003 I BluetoothAdapterState: Entering PendingCommandState
,08-08 15:42:43.928  3991  3991 D HeadsetStateMachine: max_hf_connections = 1
08-08 15:42:43.928  3991  3991 I bt_bluedroid: get_profile_interface handsfree
08-08 15:42:43.928  3991  4007 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-08 15:42:43.929  3991  4007 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-08 15:42:43.933  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.934  3991  3991 D A2dpService: Received start request. Starting profile...
08-08 15:42:43.935  3991  3991 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-08 15:42:43.935  3991  3991 I bt_bluedroid: get_profile_interface avrcp
08-08 15:42:43.941  3991  3991 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-08 15:42:43.942  3991  3991 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 15:42:43.942  3991  3991 D A2dpStateMachine: make
08-08 15:42:43.943  3991  3991 I bt_bluedroid: get_profile_interface a2dp
08-08 15:42:43.944  3991  4007 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-08 15:42:43.946  3991  4022 D A2dpStateMachine: Enter Disconnected: -2
08-08 15:42:43.948  3991  3991 I BluetoothHidServiceJni: classInitNative: succeeds
08-08 15:42:43.949  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.949  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 15:42:43.952  3991  3991 D HidService: Received start request. Starting profile...
08-08 15:42:43.952  3991  3991 I bt_bluedroid: get_profile_interface hidhost
08-08 15:42:43.952  3991  4007 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e73e5
08-08 15:42:43.952  3991  4007 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-08 15:42:43.952  3991  3991 D HidService: setHidService(): set to: null
08-08 15:42:43.953  3991  3991 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 15:42:43.954  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.955  3991  3991 D HealthService: Received start request. Starting profile...
08-08 15:42:43.957  3991  3991 I bt_bluedroid: get_profile_interface health
08-08 15:42:43.958  3991  3991 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 15:42:43.959  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.960  3991  3991 D PanService: Received start request. Starting profile...
08-08 15:42:43.960  3991  3991 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 15:42:43.960  3991  3991 I bt_bluedroid: get_profile_interface pan
08-08 15:42:43.964  3991  4007 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-08 15:42:43.971  3991  3991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
08-08 15:42:43.972  3991  3991 D BluetoothMapService: Received start request. Starting profile...
08-08 15:42:43.972  3991  3991 D BluetoothMapService: start()
08-08 15:42:43.974  3991  3991 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-08 15:42:43.974  3991  3991 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 15:42:43.975  3991  3991 D BluetoothMapAppObserver: createReceiver()
08-08 15:42:43.975  3991  3991 D BluetoothMapAppObserver: initObservers()
08-08 15:42:43.975  3991  3991 D BluetoothMapAppObserver: getEnabledAccountItems()
08-08 15:42:43.981  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:43.981  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:43.981  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:43.981  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:43.982  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:43.982  3991  3991 V BluetoothAdapterState: isTurningOn()=true
08-08 15:42:43.982  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:43.982  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:43.982  3991  4020 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOn()=true
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOn()=true,
08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOff()=false
08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isTurningOn()=true
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 15:42:43.983  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 15:42:43.984  3991  3991 V BluetoothAdapterState: isTurningOff()=false
,08-08 15:42:43.984  3991  3991 V BluetoothAdapterState: isTurningOn()=true
,08-08 15:42:43.984  3991  3991 V BluetoothAdapterState: isBleTurningOn()=false
08-08 15:42:43.984  3991  3991 V BluetoothAdapterState: isBleTurningOff()=false
08-08 15:42:43.984  3991  4003 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-08 15:42:43.984  3991  4003 D BluetoothAdapterProperties: ScanMode =  20
08-08 15:42:43.984  3991  4003 D BluetoothAdapterProperties: State =  11
08-08 15:42:43.985  3991  4003 D BluetoothAdapterProperties: Setting state to 12
,08-08 15:42:43.985  3991  4003 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-08 15:42:43.985  3991  4003 I BluetoothAdapterState: Entering OnState
08-08 15:42:43.986  3813  3826 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 15:42:43.986  3991  4007 D BluetoothAdapterProperties: Scan Mode:21
08-08 15:42:43.986  3991  4007 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 15:42:43.988  3813  3930 D BluetoothMap: onBluetoothStateChange: up=true
08-08 15:42:43.990  3813  3825 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:43.990  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 15:42:43.991  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-08 15:42:43.992  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 15:42:43.994  1364  1823 D BluetoothPan: onBluetoothStateChange on: true
08-08 15:42:43.994  3813  3813 D BluetoothInputDevice: Proxy object connected
08-08 15:42:43.994  3813  3813 D HidProfile: Bluetooth service connected
,08-08 15:42:43.995  3813  3826 D BluetoothPan: onBluetoothStateChange on: true
08-08 15:42:43.995  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:43.995  1364  1364 D PanProfile: Bluetooth service connected
08-08 15:42:43.997  3813  3930 D BluetoothPbap: onBluetoothStateChange: up=true
,08-08 15:42:43.999   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 15:42:43.999   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.000  1364  1377 D BluetoothMap: onBluetoothStateChange: up=true
,08-08 15:42:44.000  3813  3813 D BluetoothMap: Proxy object connected
,08-08 15:42:44.000  3813  3813 D MapProfile: Bluetooth service connected
08-08 15:42:44.000  3813  3813 D BluetoothMap: getConnectedDevices()
08-08 15:42:44.000   872   872 D BluetoothA2dp: Proxy object connected
08-08 15:42:44.000  3991  3991 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener,
08-08 15:42:44.001  3991  3991 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 15:42:44.002  1364  1364 D BluetoothMap: Proxy object connected
08-08 15:42:44.002  1364  1364 D MapProfile: Bluetooth service connected
08-08 15:42:44.002  1364  1823 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-08 15:42:44.002  1364  1364 D BluetoothMap: getConnectedDevices()
08-08 15:42:44.003  3991  3991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 15:42:44.003  1735  1750 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.004  3813  3813 D BluetoothA2dp: Proxy object connected
,08-08 15:42:44.004   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.004   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.004  1364  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.004  1364  1364 D BluetoothInputDevice: Proxy object connected
,08-08 15:42:44.004  1364  1364 D HidProfile: Bluetooth service connected
08-08 15:42:44.004  3813  4027 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 15:42:44.006  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 15:42:44.006  3991  3991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 15:42:44.007  1364  1364 D BluetoothA2dp: Proxy object connected
08-08 15:42:44.008  3813  3813 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 15:42:44.008  3813  3813 D PanProfile: Bluetooth service connected
08-08 15:42:44.008  3991  3991 D ObexServerSockets: Succeed to create listening sockets 
,08-08 15:42:44.008  3991  3991 D ObexServerSockets0: startAccept()
08-08 15:42:44.008  3991  3991 D ObexServerSockets0: prepareForNewConnect()
,08-08 15:42:44.009   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-08 15:42:44.011  3991  3991 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 15:42:44.011  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:44.011  3991  3991 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 15:42:44.012  3991  3991 D BluetoothMapService: onReceive
08-08 15:42:44.012  3991  3991 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 15:42:44.012  3991  3991 D BluetoothMapService: STATE_ON
,08-08 15:42:44.014  3991  4030 D ObexServerSockets0: Accepting socket connection...
08-08 15:42:44.014  3991  4029 D ObexServerSockets0: Accepting socket connection...
,08-08 15:42:44.017  3813  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 15:42:44.023  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 15:42:44.026  3813  3813 D DockEventReceiver: finishStartingService: stopping service
,08-08 15:42:44.033  3813  3813 D BluetoothPbap: Proxy object connected
08-08 15:42:44.033  3813  3813 D PbapServerProfile: Bluetooth service connected
,08-08 15:42:44.036  1364  1364 D BluetoothPbap: Proxy object connected
,08-08 15:42:44.036  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-08 15:42:44.039  3991  3991 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 15:42:44.039  3991  3991 D ObexServerSockets0: prepareForNewConnect()
08-08 15:42:44.040  3991  4034 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:44.059  3991  4038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 15:42:44.060  3991  4038 I BtOppRfcommListener: Accept thread started.
,08-08 15:42:44.102  1735  1747 D BluetoothHeadset: Proxy object connected
,08-08 15:42:44.102   872   872 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.102   872   872 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.103  1364  1377 D BluetoothHeadset: Proxy object connected
,08-08 15:42:44.103  1364  1364 D HeadsetProfile: Bluetooth service connected
08-08 15:42:44.103   872   872 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.104  1735  2111 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.104   872   889 D BluetoothHeadset: Proxy object connected
,08-08 15:42:44.104   872   889 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.105  1364  1823 D BluetoothHeadset: Proxy object connected
08-08 15:42:44.106  3813  4027 D BluetoothHeadset: Proxy object connected
,08-08 15:42:44.112  3813  3825 D BluetoothHeadset: Proxy object connected
,08-08 15:42:44.114  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:44.116  3813  3813 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:44.120  3813  3813 D HeadsetProfile: Bluetooth service connected
,08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:44.458  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:44.465  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:44.468  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:44.469  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34fd655 added. We now have 8 listener(s)
08-08 15:42:44.469  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:44.474   872  1757 D WifiService: setWifiEnabled: false pid=3584, uid=10000
,08-08 15:42:44.475   872  1757 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 15:42:44.485  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:44.486   872  1677 D WifiService: setWifiEnabled: true pid=3584, uid=10000
08-08 15:42:44.487   872  1677 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 15:42:44.502   872  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:44.526  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:44.529  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 15:42:44.530  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 15:42:44.534  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 15:42:44.539  3584  4042 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-08 15:42:44.539  3584  4042 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-08 15:42:44.541   872  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-08 15:42:44.542   872  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 15:42:44.542   872  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 15:42:44.543   872  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-08 15:42:44.544   872  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 15:42:44.544   872  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 15:42:44.544   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 15:42:44.545   872  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 15:42:44.556   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-08 15:42:44.557   872  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.12 rxSuccessRate=0.16 delta 1000 -> 1000
08-08 15:42:44.558   371   870 D CommandListener: Setting iface cfg
08-08 15:42:44.558   872  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-08 15:42:44.558   872  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-08 15:42:44.559   872  1307 E native  : do suspend true
,08-08 15:42:44.566   872  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-08 15:42:44.571   872  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 15:42:44.571   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-08 15:42:44.571   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:44.580   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-08 15:42:44.639   872  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-08 15:42:44.641  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-08 15:42:44.723   872  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-08 15:42:44.727  1456  1456 E wpa_supplicant: PNO: In assoc process
,08-08 15:42:44.728   872  1307 E WifiStateMachine:  Fail to set up pno, want true now false
,08-08 15:42:45.103  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 15:42:45.128  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-08 15:42:45.128  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-08 15:42:45.132   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 15:42:45.141   872  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 15:42:45.142   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-08 15:42:45.142   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:45.160   872  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 15:42:45.172   371   870 D CommandListener: Setting iface cfg
,08-08 15:42:45.175   872  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-08 15:42:45.183   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-08 15:42:45.223   872  4047 D DhcpClient: Receive thread started
,08-08 15:42:45.312   872  1307 E native  : do suspend false
,08-08 15:42:45.335   872  2011 D DhcpClient: Broadcasting DHCPDISCOVER
,08-08 15:42:45.348   872  4047 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-08 15:42:45.349   872  2011 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-08 15:42:45.352   872  2011 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-08 15:42:45.365   872  4047 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-08 15:42:45.366   872  2011 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-08 15:42:45.371   371   870 D CommandListener: Setting iface cfg
,08-08 15:42:45.382   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-08 15:42:45.383   872  2011 D DhcpClient: Scheduling renewal in 86399s
08-08 15:42:45.385   872  1307 E native  : do suspend true
,08-08 15:42:45.398   872  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-08 15:42:45.399   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-08 15:42:45.399   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-08 15:42:45.405   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-08 15:42:45.407   872  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-08 15:42:45.461   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-08 15:42:45.461   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-08 15:42:45.465   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-08 15:42:45.467   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-08 15:42:45.470   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-08 15:42:45.489   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-08 15:42:45.500   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-08 15:42:45.500   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-08 15:42:45.500   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-08 15:42:45.500   872  1309 D ConnectivityService:    accepting network in place of null,
,08-08 15:42:45.500   872  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-08 15:42:45.501   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-08 15:42:45.502   872  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 15:42:45.509   872  4046 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164685, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-08 15:42:45.559   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:45.585   872  4045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:810::200e
,08-08 15:42:45.595   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 15:42:45.600   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-08 15:42:45.601   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-08 15:42:45.602   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-08 15:42:45.604   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:45.626  3584  3584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:45.629  3584  3584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:45.642  1829  1829 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 15:42:45.647  1802  1802 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-08 15:42:45.648  1829  1829 D SystemUpdateService: onCreate
,08-08 15:42:45.653  1829  1829 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 15:42:45.665  3535  4058 I BooksSync: Starting books sync for 61035162, extras: ade
,08-08 15:42:45.671  1829  4056 I SystemUpdateService: active receiver: enabled
,08-08 15:42:45.685   872  4045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 13:42:45 GMT], X-Android-Received-Millis=[1470663765684], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470663765644]}
,08-08 15:42:45.685   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 15:42:45.686   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-08 15:42:45.686   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-08 15:42:45.688   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 15:42:45.766  1829  4056 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 15:42:45.782  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:45.788  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:45.788  1829  1829 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-08 15:42:45.797  1829  2346 I iu.UploadsManager: num queued entries: 0
,08-08 15:42:45.799  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 15:42:45.828  1829  2346 I iu.UploadsManager: num updated entries: 0
,08-08 15:42:45.829  1829  2346 I iu.SyncManager: NEXT; no task
,08-08 15:42:45.832  1829  4056 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-08 15:42:45.832  1829  4056 I SystemUpdateService: now status is 0 (complete)
,08-08 15:42:45.832  1829  4056 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-08 15:42:45.832  1829  4056 I SystemUpdateService: file has been verified
08-08 15:42:45.832  1829  4056 I SystemUpdateService: OTA package size = 12249756
,08-08 15:42:45.853  1829  1829 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 15:42:45.854  1829  1829 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 15:42:45.856  3698  3698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 15:42:45.862  1829  4063 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-08 15:42:45.863  1829  4063 W BaseAppContext: Using Auth Proxy for data requests.
,08-08 15:42:45.864  1829  4063 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 15:42:45.866  3698  3698 D SprintDMHelper: simOperator: 
08-08 15:42:45.866  3698  3698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 15:42:45.905  1506  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 15:42:45.905  1506  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-08 15:42:45.905  1506  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 15:42:45.905  1506  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:45.972  3535  4069 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-08 15:42:45.977  1829  4056 I SystemUpdateService: showing system update notification
,08-08 15:42:46.016  1829  1829 D SystemUpdateService: onDestroy
,08-08 15:42:46.052  1506  4072 I VacuumService: Vacuum at: now=1470663766052 tag=VacuumService
,08-08 15:42:46.064  2372  4066 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-08 15:42:46.070  2825  4059 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-08 15:42:46.070  2825  4059 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jdm.a(PG:82)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jcs.o(PG:406)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jcn.a(PG:1379)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jcs.i(PG:143)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at blb.a(PG:3937)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at czp.a(PG:18188)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at czp.a(PG:9081)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at czq.run(PG:1686)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 15:42:46.070  2825  4059 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jdj.a(PG:4091)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jdj.a(PG:1125)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jdm.a(PG:77)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	... 12 more
08-08 15:42:46.070  2825  4059 E HttpOperation: Caused by: faj: BadAuthentication
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at fal.a(PG:38)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	at jdj.a(PG:4089)
08-08 15:42:46.070  2825  4059 E HttpOperation: 	... 14 more
,08-08 15:42:46.115  1506  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-08 15:42:46.115  1506  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 15:42:46.115  1506  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:46.115  1506  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:46.163  1506  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-08 15:42:46.163  1506  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-08 15:42:46.163  1506  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:46.163  1506  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:46.200  3535  4069 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-08 15:42:46.200  3535  4058 E BooksSync: Soft error
08-08 15:42:46.200  3535  4058 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 15:42:46.200  3535  4058 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 15:42:46.201  3535  4058 E BooksSync: Sync error
08-08 15:42:46.201  3535  4058 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 15:42:46.201  3535  4058 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 15:42:46.201  3535  4058 I BooksSync: Finished books sync
,08-08 15:42:46.214   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161000, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 15:42:46.224  1506  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 15:42:46.224  1506  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-08 15:42:46.224  1506  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:46.224  1506  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:46.243  2825  4059 E HttpOperation: [getmobileexperiments] Unexpected exception
08-08 15:42:46.243  2825  4059 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jdm.a(PG:82)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jcs.o(PG:406)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jcn.a(PG:1379)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jcs.i(PG:143)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at hec.a(PG:42)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at hee.a(PG:102)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at czr.a(PG:65)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at kka.a(PG:108)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at czp.a(PG:19176)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at czp.a(PG:9081)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at czq.run(PG:1686)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 15:42:46.243  2825  4059 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jdj.a(PG:4091)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jdj.a(PG:1125)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jdm.a(PG:77)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	... 15 more
08-08 15:42:46.243  2825  4059 E HttpOperation: Caused by: faj: BadAuthentication
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at fal.a(PG:38)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	at jdj.a(PG:4089)
08-08 15:42:46.243  2825  4059 E HttpOperation: 	... 17 more
,08-08 15:42:46.244  2825  4059 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-08 15:42:46.244  2825  4059 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jdm.a(PG:82)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jcs.o(PG:406)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jcn.a(PG:1379)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jcs.i(PG:143)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at hec.a(PG:42)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at hee.a(PG:102)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at czr.a(PG:65)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at kka.a(PG:108)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at czp.a(PG:19176)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at czp.a(PG:9081)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at czq.run(PG:1686)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jdj.a(PG:4091)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jdj.a(PG:1125)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jdm.a(PG:77)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	... 15 more
08-08 15:42:46.244  2825  4059 E ExperimentLoader: Caused by: faj: BadAuthentication
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at fal.a(PG:38)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	at jdj.a(PG:4089)
08-08 15:42:46.244  2825  4059 E ExperimentLoader: 	... 17 more
,08-08 15:42:46.271  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-08 15:42:46.271  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-08 15:42:46.271  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:46.271  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:46.359  1829  4063 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-08 15:42:46.378  1506  4073 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-08 15:42:46.383  1506  4073 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-08 15:42:46.410   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 159194, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-08 15:42:46.602   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-08 15:42:46.824  1506  4073 W Uploader:  no longer exists, so no auth token.
,08-08 15:42:47.347   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-08 15:42:47.418  1506  4073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-08 15:42:47.418  1506  4073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-08 15:42:47.418  1506  4073 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:47.418  1506  4073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:47.434  1506  4073 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 15:42:47.434  1506  4073 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-08 15:42:47.434  1506  4073 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-08 15:42:47.550  3584  4085 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-08 15:42:47.551  3584  4042 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-08 15:42:47.551  3584  4042 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-08 15:42:47.551  3584  4085 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-08 15:42:47.553  3584  4042 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-08 15:42:47.553  3584  4085 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-08 15:42:47.555  3584  4042 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-08 15:42:47.555  3584  4085 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:47.559  3584  4087 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 411, name: OutgoingSocketThread/Sender)
,08-08 15:42:47.559  3584  4085 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-08 15:42:47.560  3584  4042 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-08 15:42:47.564  3584  4088 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 412, name: IncomingSocketThread/Sender)
,08-08 15:42:47.567  3584  4090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 413, name: OutgoingSocketThread/Receiver)
,08-08 15:42:47.568  3584  4089 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 414, name: IncomingSocketThread/Receiver)
,08-08 15:42:47.569  3584  4090 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 413, thread name: OutgoingSocketThread/Receiver)
,08-08 15:42:47.569  3584  4090 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-08 15:42:47.569  3584  4090 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 413, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-08 15:42:47.570  3584  4089 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 414, thread name: IncomingSocketThread/Receiver)
,08-08 15:42:47.570  3584  4089 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-08 15:42:47.571  3584  4089 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 414, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-08 15:42:47.741  1506  4073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-08 15:42:47.741  1506  4073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-08 15:42:47.741  1506  4073 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:47.742  1506  4073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:47.759  1506  4073 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 15:42:47.759  1506  4073 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-08 15:42:47.759  1506  4073 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-08 15:42:48.237  1506  4073 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-08 15:42:48.238  1506  4073 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-08 15:42:48.238  1506  4073 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 15:42:48.238  1506  4073 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 15:42:48.259  1506  4073 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 15:42:48.259  1506  4073 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-08 15:42:48.259  1506  4073 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-08 15:42:50.549  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-08 15:42:50.551  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-08 15:42:50.558  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e1f4ecf Bundle[{}]
,08-08 15:42:50.558  3584  3633 I io.jxcore.node.LifeCycleMonitor: start: OK
08-08 15:42:50.558  3584  3633 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-08 15:42:50.559  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-08 15:42:50.559  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-08 15:42:50.560  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-08 15:42:50.560  3584  3633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-08 15:42:50.565  3584  3633 I System.out: Running OutgoingSocketThread
,08-08 15:42:50.568  3584  4093 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-08 15:42:50.569  3584  4093 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-08 15:42:53.507   872  1309 D ConnectivityService: handlePromptUnvalidated 102,
,08-08 15:42:53.577  3584  4094 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-08 15:42:53.577  3584  4094 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-08 15:42:53.578  3584  4094 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:53.578  3584  4093 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-08 15:42:53.578  3584  4093 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-08 15:42:53.579  3584  4094 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:53.579  3584  4093 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:53.581  3584  4096 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Sender)
,08-08 15:42:53.582  3584  4094 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-08 15:42:53.584  3584  4093 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:53.588  3584  4097 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Receiver)
,08-08 15:42:53.590  3584  4093 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-08 15:42:53.591  3584  4097 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 424, thread name: IncomingSocketThread/Receiver)
,08-08 15:42:53.591  3584  4097 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-08 15:42:53.592  3584  4097 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 424, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-08 15:42:53.596  3584  4098 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
,08-08 15:42:53.597  3584  4099 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
,08-08 15:42:53.598  3584  4099 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
08-08 15:42:53.599  3584  4099 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-08 15:42:53.599  3584  4099 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-08 15:42:56.580  3584  3633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-08 15:42:56.582  3584  3633 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-08 15:42:56.583  3584  3633 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 436)
,08-08 15:42:56.590  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:56.590  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70a586a added. We now have 2 listener(s)
,08-08 15:42:56.591  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-08 15:42:56.592  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.592  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:56.592  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:56.592  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254215b added. We now have 9 listener(s)
08-08 15:42:56.592  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:56.593  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-08 15:42:56.598  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:56.612  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:56.618  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:56.618  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:56.618  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 15:42:56.618  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60482d1 added. We now have 3 listener(s)
,08-08 15:42:56.620  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.620  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 15:42:56.620  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:56.621  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.621  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d9136 added. We now have 10 listener(s)
08-08 15:42:56.621  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:56.621  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:56.621  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:56.621  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:56.621  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:56.621  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.621  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:56.621  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:56.622  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70a586a removed from the list
08-08 15:42:56.622  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:56.622  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254215b removed from the list
,08-08 15:42:56.626  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:56.626  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:56.627  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.628  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.628  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:56.631  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:56.631  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:56.631  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:56.631  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254215b not in the list
08-08 15:42:56.631  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.632  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:56.634  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:56.634  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:56.634  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:56.634  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6d9136 removed from the list
08-08 15:42:56.635  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:56.635  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.635  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.635  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:56.635  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60482d1 removed from the list
08-08 15:42:56.635  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:56.637  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:56.637  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca97837 added. We now have 2 listener(s)
08-08 15:42:56.640  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.641  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.641  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:56.641  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.641  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85321a4 added. We now have 9 listener(s)
,08-08 15:42:56.641  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:56.642  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-08 15:42:56.649  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:56.659  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:56.664  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:56.665  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 15:42:56.666  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:56.667  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f98ac2 added. We now have 3 listener(s)
,08-08 15:42:56.671  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:56.674  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.674  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.674  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:56.675  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.675  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39360d3 added. We now have 10 listener(s)
08-08 15:42:56.675  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:56.676  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:56.676  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 15:42:56.677  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 15:42:56.677  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:56.677  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 15:42:56.679  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:56.685  3584  3633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-08 15:42:56.686  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-08 15:42:56.700  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-08 15:42:56.703  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-08 15:42:56.703  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-08 15:42:56.712  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-08 15:42:56.713  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-08 15:42:56.713  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-08 15:42:56.715  3584  3633 D BluetoothAdapter: STATE_ON
,08-08 15:42:56.724  3991  4028 D BtGatt.GattService: registerClient() - UUID=78671768-ce33-4f22-9d41-d680c61b97e9
,08-08 15:42:56.725  3991  4007 D BtGatt.GattService: onClientRegistered() - UUID=78671768-ce33-4f22-9d41-d680c61b97e9, clientIf=5
,08-08 15:42:56.727  3584  3595 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-08 15:42:56.728  3991  4002 D BtGatt.GattService: start scan with filters
,08-08 15:42:56.736  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-08 15:42:56.736  3991  4010 D BtGatt.ScanManager: handling starting scan
,08-08 15:42:56.737  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-08 15:42:56.738  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-08 15:42:56.738  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-08 15:42:56.741  3991  4010 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9793e73
,08-08 15:42:56.744  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-08 15:42:56.744  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-08 15:42:56.744  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-08 15:42:56.748  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-08 15:42:56.755  3991  4007 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-08 15:42:56.755  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.757  3991  4010 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-08 15:42:56.760  3584  3633 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-08 15:42:56.760  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:56.760  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 15:42:56.761  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.762  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-08 15:42:56.762  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 15:42:56.763  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-08 15:42:56.764  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 15:42:56.764  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-08 15:42:56.766  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-08 15:42:56.767  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-08 15:42:56.769  3584  3633 D BluetoothAdapter: STATE_ON
,08-08 15:42:56.770  3991  4002 D BtGatt.GattService: stopScan() - queue size =1
08-08 15:42:56.771  3991  4001 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-08 15:42:56.772  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-08 15:42:56.772  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-08 15:42:56.772  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-08 15:42:56.772  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-08 15:42:56.773  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-08 15:42:56.774  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-08 15:42:56.774  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.775  3991  4010 D BtGatt.ScanManager: Starting BLE batch scan
08-08 15:42:56.775  3991  4010 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-08 15:42:56.777  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-08 15:42:56.777  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-08 15:42:56.777  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-08 15:42:56.778  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 15:42:56.779  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:56.781  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:56.781  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:56.781  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-08 15:42:56.786  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 15:42:56.786  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:56.786  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:56.787  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:56.787  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.787  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 15:42:56.787  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:56.787  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca97837 removed from the list
,08-08 15:42:56.787  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:56.787  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85321a4 removed from the list
,08-08 15:42:56.788  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:56.788  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.788  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.789  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.790  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:56.790  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:56.790  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:56.791  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85321a4 not in the list
08-08 15:42:56.791  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.791  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.793  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:56.793  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:56.793  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:56.793  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39360d3 removed from the list
,08-08 15:42:56.794  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:56.794  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.794  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:56.794  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:56.794  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f98ac2 removed from the list
,08-08 15:42:56.795  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 15:42:56.795  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f29372f added. We now have 2 listener(s)
08-08 15:42:56.798  3991  4007 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-08 15:42:56.798  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.799  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.799  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.799  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:56.799  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.800  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7013c added. We now have 9 listener(s)
08-08 15:42:56.800  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:56.800  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 15:42:56.807  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:56.812  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-08 15:42:56.812  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:56.817  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 15:42:56.820  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 15:42:56.820  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:56.821  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 15:42:56.821  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a1b01a added. We now have 3 listener(s)
,08-08 15:42:56.824  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-08 15:42:56.824  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.824  3991  4010 D BtGatt.ScanManager: stopping BLe Batch
08-08 15:42:56.825  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.825  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.825  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:56.825  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:56.826  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79c174b added. We now have 10 listener(s)
08-08 15:42:56.827  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:56.827  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:56.830  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:56.831  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:56.832  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:56.832  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-08 15:42:56.833  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-08 15:42:56.834  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 15:42:56.833  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.834  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:56.834  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 15:42:56.835  3991  4010 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-08 15:42:56.839  3584  3633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-08 15:42:56.839  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-08 15:42:56.844  3991  4007 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-08 15:42:56.844  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.848  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-08 15:42:56.849  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-08 15:42:56.849  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-08 15:42:56.856  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-08 15:42:56.856  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-08 15:42:56.856  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-08 15:42:56.857  3584  3633 D BluetoothAdapter: STATE_ON
,08-08 15:42:56.863  3991  4001 D BtGatt.GattService: registerClient() - UUID=70b3121f-6cd5-4d07-96fd-53392ede736a
,08-08 15:42:56.864  3991  4007 D BtGatt.GattService: onClientRegistered() - UUID=70b3121f-6cd5-4d07-96fd-53392ede736a, clientIf=5
,08-08 15:42:56.865  3584  3629 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-08 15:42:56.866  3991  4019 D BtGatt.GattService: start scan with filters
,08-08 15:42:56.873  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-08 15:42:56.873  3991  4010 D BtGatt.ScanManager: handling starting scan
08-08 15:42:56.873  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-08 15:42:56.874  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-08 15:42:56.874  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-08 15:42:56.879  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-08 15:42:56.879  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-08 15:42:56.879  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-08 15:42:56.883  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-08 15:42:56.887  3991  4007 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-08 15:42:56.887  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.888  3991  4010 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-08 15:42:56.891  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-08 15:42:56.891  3584  3633 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-08 15:42:56.891  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:56.891  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 15:42:56.892  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 15:42:56.892  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:56.892  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.892  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-08 15:42:56.892  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-08 15:42:56.892  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f29372f removed from the list
,08-08 15:42:56.893  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:56.893  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7013c removed from the list
,08-08 15:42:56.893  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:56.893  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:56.894  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.894  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-08 15:42:56.895  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.895  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:56.897  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 15:42:56.898  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:56.898  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:56.898  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7013c not in the list
08-08 15:42:56.898  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-08 15:42:56.898  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-08 15:42:56.899  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 15:42:56.899  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-08 15:42:56.899  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-08 15:42:56.900  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-08 15:42:56.900  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.901  3584  3633 D BluetoothAdapter: STATE_ON
08-08 15:42:56.901  3991  4010 D BtGatt.ScanManager: Starting BLE batch scan
08-08 15:42:56.901  3991  4010 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-08 15:42:56.902  3991  4028 D BtGatt.GattService: stopScan() - queue size =1
,08-08 15:42:56.903  3991  4002 D BtGatt.GattService: unregisterClient() - clientIf=5
08-08 15:42:56.904  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-08 15:42:56.904  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-08 15:42:56.904  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-08 15:42:56.905  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-08 15:42:56.905  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-08 15:42:56.908  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:56.908  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-08 15:42:56.908  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-08 15:42:56.909  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 15:42:56.910  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.913  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:56.914  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:56.914  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:56.914  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:56.914  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79c174b removed from the list
,08-08 15:42:56.914  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:56.914  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:56.914  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:56.914  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:56.915  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:56.915  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:56.915  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a1b01a removed from the list
,08-08 15:42:56.917  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:56.917  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d12dd27 added. We now have 2 listener(s)
08-08 15:42:56.919  3991  4007 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-08 15:42:56.920  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.921  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.921  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.922  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:56.922  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.922  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3943bd4 added. We now have 9 listener(s)
08-08 15:42:56.922  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:56.923  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 15:42:56.927  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-08 15:42:56.927  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.927  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:56.933  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:56.935  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-08 15:42:56.935  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.935  3991  4010 D BtGatt.ScanManager: stopping BLe Batch
,08-08 15:42:56.935  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:56.936  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 15:42:56.937  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:56.937  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bce2872 added. We now have 3 listener(s)
08-08 15:42:56.939  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:56.939  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:56.939  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:56.939  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 15:42:56.940  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:56.940  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14624c3 added. We now have 10 listener(s)
08-08 15:42:56.940  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:56.940  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:56.940  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 15:42:56.940  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 15:42:56.940  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 15:42:56.940  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 15:42:56.943  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-08 15:42:56.943  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.943  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 15:42:56.943  3991  4010 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-08 15:42:56.944  3584  3633 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-08 15:42:56.945  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-08 15:42:56.950  3991  4007 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-08 15:42:56.950  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:56.950  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-08 15:42:56.952  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-08 15:42:56.952  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-08 15:42:56.958  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-08 15:42:56.958  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-08 15:42:56.958  3584  3633 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-08 15:42:56.959  3584  3633 D BluetoothAdapter: STATE_ON
,08-08 15:42:56.964  3991  4001 D BtGatt.GattService: registerClient() - UUID=3def63c6-cb7e-42d0-b946-a14df404342a
,08-08 15:42:56.965  3991  4007 D BtGatt.GattService: onClientRegistered() - UUID=3def63c6-cb7e-42d0-b946-a14df404342a, clientIf=5
,08-08 15:42:56.965  3584  3596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-08 15:42:56.966  3991  4019 D BtGatt.GattService: start scan with filters
,08-08 15:42:56.971  3991  4010 D BtGatt.ScanManager: handling starting scan
08-08 15:42:56.971  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-08 15:42:56.971  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-08 15:42:56.971  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-08 15:42:56.971  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-08 15:42:56.975  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-08 15:42:56.976  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-08 15:42:56.976  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-08 15:42:56.978  3991  4007 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-08 15:42:56.978  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.978  3991  4010 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-08 15:42:56.980  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-08 15:42:56.986  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-08 15:42:56.987  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:56.987  3991  4010 D BtGatt.ScanManager: Starting BLE batch scan
08-08 15:42:56.987  3991  4010 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-08 15:42:56.995  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 15:42:56.996  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 15:42:56.996  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 15:42:56.996  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:56.997  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:56.997  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-08 15:42:56.997  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-08 15:42:56.997  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d12dd27 removed from the list
,08-08 15:42:56.998  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:56.998  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3943bd4 removed from the list
,08-08 15:42:56.998  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 15:42:56.998  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 15:42:57.000  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:57.000  3991  4007 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-08 15:42:57.000  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:57.000  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-08 15:42:57.000  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:57.000  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:57.003  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:57.003  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:57.003  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:57.004  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3943bd4 not in the list
08-08 15:42:57.004  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-08 15:42:57.004  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 15:42:57.004  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-08 15:42:57.005  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-08 15:42:57.005  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-08 15:42:57.007  3584  3633 D BluetoothAdapter: STATE_ON
,08-08 15:42:57.007  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-08 15:42:57.007  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-08 15:42:57.008  3991  4028 D BtGatt.GattService: stopScan() - queue size =1
,08-08 15:42:57.010  3991  4001 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-08 15:42:57.011  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-08 15:42:57.011  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-08 15:42:57.011  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-08 15:42:57.012  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-08 15:42:57.012  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-08 15:42:57.015  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:57.015  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-08 15:42:57.015  3584  3633 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-08 15:42:57.015  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-08 15:42:57.015  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:57.017  3991  4007 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-08 15:42:57.017  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 15:42:57.017  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:57.017  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:57.017  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 15:42:57.017  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14624c3 removed from the list
08-08 15:42:57.017  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:57.017  3584  3584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-08 15:42:57.017  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:57.017  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:57.017  3584  3584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 15:42:57.017  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:57.017  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bce2872 removed from the list
08-08 15:42:57.017  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:57.018  3991  4010 D BtGatt.ScanManager: stopping BLe Batch
08-08 15:42:57.018  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 15:42:57.018  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc4a1f added. We now have 2 listener(s)
08-08 15:42:57.020  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:57.020  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:57.020  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:57.020  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 15:42:57.020  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55b316c added. We now have 9 listener(s)
08-08 15:42:57.020  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 15:42:57.021  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 15:42:57.024  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 15:42:57.026  3991  4007 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-08 15:42:57.026  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:57.027  3991  4010 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 15:42:57.029  3584  3633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 15:42:57.032  3584  3633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 15:42:57.033  3991  4007 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-08 15:42:57.033  3991  4007 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-08 15:42:57.033  3584  3633 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 15:42:57.034  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 15:42:57.034  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5653ca added. We now have 3 listener(s)
08-08 15:42:57.036  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:57.037  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 15:42:57.037  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 15:42:57.038  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 15:42:57.038  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 15:42:57.038  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a85693b added. We now have 10 listener(s)
08-08 15:42:57.038  3584  3633 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 15:42:57.039  3584  3584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 15:42:57.039  3584  3633 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 15:42:57.039  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:57.039  3584  3633 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 15:42:57.039  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 15:42:57.039  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:57.039  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 15:42:57.039  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:57.039  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc4a1f removed from the list
08-08 15:42:57.040  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 15:42:57.040  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55b316c removed from the list
08-08 15:42:57.040  3584  3633 D io.jxcore.node.ConnectivityMonitor: stop
08-08 15:42:57.040  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:57.040  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 15:42:57.041  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 15:42:57.042  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 15:42:57.042  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:57.042  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:57.042  3584  3633 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55b316c not in the list
08-08 15:42:57.042  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:57.042  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:57.044  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 15:42:57.044  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 15:42:57.044  3584  3633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 15:42:57.044  3584  3633 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a85693b removed from the list
08-08 15:42:57.044  3584  3633 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 15:42:57.044  3584  3633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 15:42:57.044  3584  3633 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 15:42:57.045  3584  3633 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 15:42:57.045  3584  3633 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5653ca removed from the list
08-08 15:42:57.046  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-08 15:42:57.046  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-08 15:42:57.046  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-08 15:42:57.046  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 15:42:57.046  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-08 15:42:57.047  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-08 15:42:57.055  3584  4101 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
,08-08 15:42:57.282  3584  3584 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 15:42:57.416  3584  3584 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 15:42:57.518  3584  3584 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 15:42:59.054  3584  3633 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 444
,08-08 15:42:59.055  3584  3633 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 444, name: My test thread name)
,08-08 15:42:59.062  3584  4102 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: My test thread name)
,08-08 15:42:59.062  3584  4102 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: My test thread name)
08-08 15:42:59.062  3584  4102 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-08 15:42:59.066  3584  3633 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-08 15:42:59.075  3584  4103 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: My test thread name)
,08-08 15:42:59.076  3584  4103 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 449, thread name: My test thread name): Test exception.
,08-08 15:42:59.076  3584  4103 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 449, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-08 15:42:59.079  3584  3633 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true
08-08 15:42:59.079  3584  3633 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-08 15:42:59.079  3584  3633 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,08-08 15:42:59.079  3584  3633 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
,08-08 15:42:59.080  3584  3633 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 81
,08-08 15:42:59.080  3584  3633 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
,08-08 15:42:59.080  3584  3633 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-08 15:42:59.081  3584  3633 D com.test.thalitest.ThaliTestRunner: Total duration: 35891 ms
08-08 15:42:59.086  3584  3633 I jxcore-log: Total number of executed tests:  82
08-08 15:42:59.086  3584  3633 I jxcore-log: 
08-08 15:42:59.087  3584  3633 I jxcore-log: Number of passed tests:  81
08-08 15:42:59.087  3584  3633 I jxcore-log: 
08-08 15:42:59.088  3584  3633 I jxcore-log: Number of failed tests:  1
08-08 15:42:59.088  3584  3633 I jxcore-log: 
,08-08 15:42:59.088  3584  3633 I jxcore-log: Number of ignored tests:  0
08-08 15:42:59.088  3584  3633 I jxcore-log: 
08-08 15:42:59.089  3584  3633 I jxcore-log: Total duration:  35891
08-08 15:42:59.089  3584  3633 I jxcore-log: 
,08-08 15:42:59.091  3584  3633 I jxcore-log: Failed to execute UT.
08-08 15:42:59.091  3584  3633 I jxcore-log: 
,08-08 15:42:59.092  3584  3633 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-08 15:42:59.092  3584  3633 I jxcore-log: 
,08-08 15:42:59.100  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.100  3584  3633 I jxcore-log: 
08-08 15:42:59.103  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.103  3584  3633 I jxcore-log: 
08-08 15:42:59.104  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.104  3584  3633 I jxcore-log: 
08-08 15:42:59.106  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.106  3584  3633 I jxcore-log: 
,08-08 15:42:59.107  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.107  3584  3633 I jxcore-log: 
08-08 15:42:59.108  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.108  3584  3633 I jxcore-log: 
08-08 15:42:59.112  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.112  3584  3633 I jxcore-log: 
,08-08 15:42:59.115  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-08 15:42:59.115  3584  3633 I jxcore-log: 
,08-08 15:42:59.116  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.116  3584  3633 I jxcore-log: 
,08-08 15:42:59.117  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.117  3584  3633 I jxcore-log: 
,08-08 15:42:59.118  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-08 15:42:59.118  3584  3633 I jxcore-log: 
08-08 15:42:59.119  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-08 15:42:59.119  3584  3633 I jxcore-log: 
,08-08 15:42:59.120  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.120  3584  3633 I jxcore-log: 
,08-08 15:42:59.121  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.121  3584  3633 I jxcore-log: 
,08-08 15:42:59.122  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.122  3584  3633 I jxcore-log: 
08-08 15:42:59.122  3584  3584 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-08 15:42:59.123  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.123  3584  3633 I jxcore-log: 
08-08 15:42:59.124  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.124  3584  3633 I jxcore-log: 
08-08 15:42:59.125  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.125  3584  3633 I jxcore-log: 
08-08 15:42:59.126  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.126  3584  3633 I jxcore-log: 
08-08 15:42:59.127  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.127  3584  3633 I jxcore-log: 
,08-08 15:42:59.127  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.127  3584  3633 I jxcore-log: 
08-08 15:42:59.128  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.128  3584  3633 I jxcore-log: 
,08-08 15:42:59.129  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.129  3584  3633 I jxcore-log: 
08-08 15:42:59.129  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-08 15:42:59.129  3584  3633 I jxcore-log: 
,08-08 15:42:59.130  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-08 15:42:59.130  3584  3633 I jxcore-log: 
,08-08 15:42:59.131  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-08 15:42:59.131  3584  3633 I jxcore-log: 
08-08 15:42:59.132  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.132  3584  3633 I jxcore-log: 
08-08 15:42:59.133  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.133  3584  3633 I jxcore-log: 
08-08 15:42:59.133  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.133  3584  3633 I jxcore-log: 
08-08 15:42:59.134  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.134  3584  3633 I jxcore-log: 
08-08 15:42:59.135  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.135  3584  3633 I jxcore-log: 
,08-08 15:42:59.136  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-08 15:42:59.136  3584  3633 I jxcore-log: 
,08-08 15:42:59.137  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-08 15:42:59.137  3584  3633 I jxcore-log: 
,08-08 15:42:59.138  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-08 15:42:59.138  3584  3633 I jxcore-log: 
08-08 15:42:59.138  3584  3633 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-08 15:42:59.138  3584  3633 I jxcore-log: 
,08-08 15:42:59.261  3584  4101 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-08 15:42:59.756  4104  4104 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-08 15:42:59.761  4104  4104 D AndroidRuntime: CheckJNI is OFF
,08-08 15:42:59.782  3584  3633 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 15:42:59.782  3584  3633 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-08 15:42:59.805  4104  4104 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-08 15:42:59.852  4104  4104 I Radio-JNI: register_android_hardware_Radio DONE
,08-08 15:42:59.877  4104  4104 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-08 15:42:59.888   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-08 15:42:59.889   872   885 I ActivityManager: Killing 3584:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-08 15:42:59.998   872   883 D GraphicsStats: Buffer count: 2
08-08 15:42:59.999   872  1308 D WifiService: Client connection lost with reason: 4
08-08 15:42:59.999   872  1691 I WindowState: WIN DEATH: Window{2de9cb1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 15:43:00.000   872   895 W PackageSettings: Skipping PackageSetting{6b1f14 com.example.hello/10273} due to missing metadata
,08-08 15:43:00.054   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-08 15:43:00.054   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-08 15:43:00.055   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-08 15:43:00.055   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-08 15:43:00.055   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.055   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.055   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 15:43:00.055   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-08 15:43:00.055   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4fb675e u0 com.test.thalitest/.MainActivity t4}
,08-08 15:43:00.059   872  1828 W ActivityManager: Spurious death for ProcessRecord{cff1afc 0:com.test.thalitest/u0a0}, curProc for 3584: null
,08-08 15:43:00.060   872   895 I art     : Starting a blocking GC Explicit
,08-08 15:43:00.101   872   895 I art     : Explicit concurrent mark sweep GC freed 17694(1142KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 790us total 40.881ms
,08-08 15:43:00.122   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-08 15:43:00.124  4104  4104 I art     : System.exit called, status: 0
08-08 15:43:00.124  4104  4104 I AndroidRuntime: VM exiting with result code 0.
,08-08 15:43:00.128   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-08 15:43:00.143   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-08 15:43:00.148  3991  3991 D BluetoothMapAppObserver: onReceive
08-08 15:43:00.148  3991  3991 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-08 15:43:00.150  1655  1655 I Keyboard.Facilitator: resetDictionaries() : en_US
08-08 15:43:00.151   872  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-08 15:43:00.151  1847  2021 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-08 15:43:00.154  3425  3425 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-08 15:43:00.159  1655  4115 I Keyboard.Facilitator.DecoderInitializer: run()
,08-08 15:43:00.179  1655  4115 I Decoder : createOrResetDecoder
,08-08 15:43:00.187  1735  1735 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-08 15:43:00.203   872  1828 I ActivityManager: Start proc 4118:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-08 15:43:00.210  1506  1506 I ConfigService: onCreate
,08-08 15:43:00.240   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-08 15:43:00.248  1506  4128 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-08 15:43:00.252  4118  4118 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-08 15:43:00.262  1655  4115 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-08 15:43:00.270   872  1828 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3584 uid 10000
,08-08 15:43:00.271  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-08 15:43:00.293  1655  4115 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-08 15:43:00.295  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-08 15:43:00.295  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-08 15:43:00.297  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-08 15:43:00.297  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-08 15:43:00.298  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-08 15:43:00.298  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-08 15:43:00.299  1655  4115 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-08 15:43:00.299  1655  4115 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-08 15:43:00.299  1655  4115 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-08 15:43:00.299  1655  4115 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-08 15:43:00.299  1655  4115 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-08 15:43:00.299  1655  4115 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-08 15:43:00.315  4118  4118 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-08 15:43:00.324  4118  4135 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-08 15:43:00.328  4118  4133 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.328  4118  4133 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.328  4118  4133 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-08 15:43:00.333   872   882 I ActivityManager: Start proc 4136:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-08 15:43:00.341  1752  1861 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-08 15:43:00.342   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-08 15:43:00.343   872   884 E PackageManager: Failed to write settings, restoring backup
08-08 15:43:00.343   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-08 15:43:00.343   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-08 15:43:00.343   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-08 15:43:00.343   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-08 15:43:00.343   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-08 15:43:00.343   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.343   872   884 E PackageManager: ,	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.343   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61),
,08-08 15:43:00.350   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-08 15:43:00.350   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 15:43:00.350   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:43:00.350   872   885 E DropBoxManagerService: 	... 13 more
,08-08 15:43:00.355   872  1691 I ActivityManager: Start proc 4148:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
,08-08 15:43:00.356  1752  1861 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-08 15:43:00.356  1752  1861 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1752
08-08 15:43:00.356  1752  1861 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.356  1752  1861 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-08 15:43:00.360   872  1828 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-08 15:43:00.362   872  4156 E DropBoxManagerService: Can't write: system_app_crash
08-08 15:43:00.362   872  4156 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:43:00.362   872  4156 E DropBoxManagerService: 	... 5 more
,08-08 15:43:00.364  1752  1861 I Process : Sending signal. PID: 1752 SIG: 9
,08-08 15:43:00.376  4136  4136 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-08 15:43:00.405  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-08 15:43:00.405  1506  1506 D AndroidRuntime: Shutting down VM
,08-08 15:43:00.412   872   882 I ActivityManager: Killing 3477:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-08 15:43:00.406  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
08-08 15:43:00.406  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
08-08 15:43:00.406  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-08 15:43:00.406  1506  1506 E AndroidRuntime: 	... 8 more
,08-08 15:43:00.439  4118  4133 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-08 15:43:00.448  4118  4135 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.448  4118  4135 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-08 15:43:00.449  4118  4135 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-08 15:43:00.449  4118  4135 E AndroidRuntime: Process: android.process.acore, PID: 4118
08-08 15:43:00.449  4118  4135 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.449  4118  4135 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-08 15:43:00.450  4118  4133 I Process : Sending signal. PID: 4118 SIG: 9
,08-08 15:43:00.465   872  1757 D GraphicsStats: Buffer count: 1
,08-08 15:43:00.465   872  1690 I WindowState: WIN DEATH: Window{650ca2e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-08 15:43:00.481   872  1828 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1752) has died
,08-08 15:43:00.482   872  1828 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-08 15:43:00.484   872  1828 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-08 15:43:00.495   872  1677 I ActivityManager: Process android.process.acore (pid 4118) has died
,08-08 15:43:00.496   872  1677 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms,
08-08 15:43:00.497   872  1691 W ActivityManager: Can't find mystery application for Crash from pid=4118 uid=10005: android.os.BinderProxy@5061631
,08-08 15:43:00.498   872  1691 E DropBoxManagerService: Can't write: system_server_crash
08-08 15:43:00.498   872  1691 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop73.tmp: open failed: EROFS (Read-only file system)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:43:00.498   872  1691 E DropBoxManagerService: 	... 11 more
,08-08 15:43:00.507   872  4164 E DropBoxManagerService: Can't write: system_app_crash
08-08 15:43:00.507   872  4164 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:43:00.507   872  4164 E DropBoxManagerService: 	... 5 more
,08-08 15:43:00.513   872   885 I ActivityManager: Start proc 4165:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 15:43:00.514  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
,08-08 15:43:00.562  4165  4165 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:43:00.562  4165  4165 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 15:43:00.562  4165  4165 D AndroidRuntime: Shutting down VM
08-08 15:43:00.569  4165  4165 E AndroidRuntime: FATAL EXCEPTION: main
08-08 15:43:00.569  4165  4165 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4165
08-08 15:43:00.569  4165  4165 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-08 15:43:00.569  4165  4165 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-08 15:43:00.569  4165  4165 E AndroidRuntime: 	... 10 more
,08-08 15:43:00.571   872  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-08 15:43:00.572   872  4179 E DropBoxManagerService: Can't write: system_app_crash
08-08 15:43:00.572   872  4179 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 15:43:00.572   872  4179 E DropBoxManagerService: 	... 5 more
08-08 15:43:00.572  4165  4165 I Process : Sending signal. PID: 4165 SIG: 9
,08-08 15:43:00.578   872  1308 D WifiService: Client connection lost with reason: 4
,08-08 15:43:00.583   872  1691 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
,08-08 15:43:00.584   872  1691 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-08 15:43:00.584   872  1691 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
,08-08 15:43:00.585   872  1691 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
,08-08 15:43:00.596  1829  1829 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-08 15:43:00.606   872  1691 I ActivityManager: Start proc 4181:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-08 15:43:00.610   872  1828 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4165) has died
,08-08 15:43:00.612   872  1828 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
