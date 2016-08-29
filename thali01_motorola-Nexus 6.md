#### Test 82912030d0e406f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 16:09:05.531   876  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 16:09:06.206  3827  3827 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 16:09:06.211  3827  3827 D AndroidRuntime: CheckJNI is OFF
08-29 16:09:06.254  3827  3827 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 16:09:06.306  3827  3827 I Radio-JNI: register_android_hardware_Radio DONE
08-29 16:09:06.329  3827  3827 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 16:09:06.333   876  1383 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 16:09:06.368  2064  2082 W SearchService: Abort, client detached.
08-29 16:09:06.373  2064  2064 I HotwordDetector: Closing mic
08-29 16:09:06.374  2064  2327 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@89434cc
08-29 16:09:06.375  2064  2336 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 16:09:06.382  3827  3827 D AndroidRuntime: Shutting down VM
08-29 16:09:06.404   876  1691 I ActivityManager: Start proc 3836:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 16:09:06.431   376  2338 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 16:09:06.434   376  2338 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 16:09:06.443   376  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 16:09:06.447  2064  2335 I MicroRecognitionRnrImpl: Detection finished
08-29 16:09:06.447  2064  2331 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 16:09:06.498  3836  3836 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 16:09:06.530  3836  3836 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 16:09:06.539  3836  3836 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3743-3746)
08-29 16:09:06.539  3836  3836 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 16:09:06.574  3836  3836 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dd9e50f}
08-29 16:09:06.575  3836  3836 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 16:09:06.575  3836  3836 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 16:09:06.583  3836  3836 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 16:09:06.585  3836  3836 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 16:09:06.610  3836  3836 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 16:09:06.624  3836  3836 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:09:06.624  3836  3836 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:09:06.624  3836  3836 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:09:06.624  3836  3836 I Adreno  : Build Date                       : 10/20/15
08-29 16:09:06.624  3836  3836 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:09:06.624  3836  3836 I Adreno  : Local Branch                     : M14
08-29 16:09:06.624  3836  3836 I Adreno  : Remote Branch                    : 
08-29 16:09:06.624  3836  3836 I Adreno  : Remote Branch                    : 
08-29 16:09:06.624  3836  3836 I Adreno  : Reconstruct Branch               : 
,08-29 16:09:06.710   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dcc6722:true
,08-29 16:09:06.772  3836  3836 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 16:09:06.785  3836  3836 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 16:09:06.850  3836  3876 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 16:09:06.862  3836  3862 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 16:09:06.899  3836  3876 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 16:09:06.978   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +598ms
,08-29 16:09:06.984  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 16:09:07.036  3836  3836 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3836
,08-29 16:09:07.146  3836  3836 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 16:09:07.234   876  1968 I ActivityManager: Killing 3396:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 16:09:07.323   876  1968 I ActivityManager: Killing 2977:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 16:09:07.418  3836  3878 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1696728784
,08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 16:09:07.426  3836  3878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@615f463 added. We now have 1 listener(s)
,08-29 16:09:07.430  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 16:09:07.431  3836  3878 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:09:07.431  3836  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:09:07.431  3836  3878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 16:09:07.445  3836  3878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@859a5de added. We now have 1 listener(s)
08-29 16:09:07.446  3836  3878 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:09:07.449   876  1309 D WifiService: New client listening to asynchronous messages
,08-29 16:09:07.450  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:09:07.450  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 16:09:07.450  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 16:09:07.450  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 16:09:07.450  3836  3878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 16:09:07.453  3836  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:07.453  3836  3878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 16:09:07.464  3836  3878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:07.465  3836  3878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:07.465  3836  3878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 16:09:07.465  3836  3878 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:09:07.465  3836  3878 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 16:09:07.488  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:07.491  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:07.493  3836  3836 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 16:09:08.297  3836  3887 W jxcore-log: Initializing JXcore engine
,08-29 16:09:08.297  3836  3887 W jxcore-log: JXcore engine is ready
,08-29 16:09:08.322   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:09:08.337  3887  3887 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9010 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 16:09:08.337  3887  3887 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11249]" dev="sockfs" ino=11249 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 16:09:08.337  3887  3887 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 16:09:08.337  3887  3887 W Thread-333: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[28714]" dev="sockfs" ino=28714 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 16:09:08.353  3836  3887 W jxcore-log: Starting JXcore engine
,08-29 16:09:08.430  3836  3887 W jxcore-log: Platform android
08-29 16:09:08.430  3836  3887 W jxcore-log: 
08-29 16:09:08.430  3836  3887 W jxcore-log: Process ARCH arm
08-29 16:09:08.430  3836  3887 W jxcore-log: 
,08-29 16:09:08.781  3836  3887 I jxcore-log: JXcore Cordova bridge is ready!
08-29 16:09:08.781  3836  3887 I jxcore-log: 
,08-29 16:09:08.781  3836  3887 W jxcore-log: JXcore engine is started
,08-29 16:09:08.788  3836  3878 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 16:09:08.794  3836  3836 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 16:09:10.660  3037  3889 V KeepSync: Connecting to GoogleApiClient
,08-29 16:09:10.661   876  1691 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:09:10.707  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:10.709  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:10.733  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 16:09:10.734  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 16:09:10.734  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:10.734  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:10.752  1716  3890 V BaseAuthAsyncOperation: access token request failed
,08-29 16:09:10.753  3037  3889 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:09:10.817  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 16:09:10.818  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:09:10.818  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:10.818  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:10.844  3037  3889 E KeepSync: IOException
08-29 16:09:10.844  3037  3889 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:09:10.844  3037  3889 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:09:10.844  3037  3889 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:09:10.844  3037  3889 E KeepSync: 	... 10 more
,08-29 16:09:10.844  3037  3889 W KeepSync: Sync result 2
,08-29 16:09:10.855   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:09:11.350   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:09:11.606  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:11.659  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 16:09:11.660  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 16:09:11.660  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:09:11.660  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:11.701  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:09:11.702  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:09:11.702  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 16:09:17.670   876  1902 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:09:20.446   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:09:21.834  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:21.836  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:21.852  3780  3900 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:09:21.876  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 16:09:21.876  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-29 16:09:21.876  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:21.876  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:21.896  3780  3900 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:09:21.897  3780  3900 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:09:22.685  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 16:09:22.685  3836  3887 I jxcore-log: 
,08-29 16:09:22.688  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 16:09:22.688  3836  3887 I jxcore-log: 
,08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:22.701  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:22.708  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:22.710  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 16:09:22.710  3836  3887 I jxcore-log: 
,08-29 16:09:22.712  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 16:09:22.712  3836  3887 I jxcore-log: 
,08-29 16:09:23.150  3836  3887 I jxcore-log: Running unit tests
08-29 16:09:23.150  3836  3887 I jxcore-log: 
,08-29 16:09:23.151  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:09:23.151  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9700ea3 added. We now have 2 listener(s)
,08-29 16:09:23.152  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:09:23.153  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:09:23.153  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:09:23.153  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:09:23.153  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3e15a0 added. We now have 2 listener(s)
08-29 16:09:23.153  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:09:23.153  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:09:23.155  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:23.165  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:23.168  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:23.168  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:09:23.170  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:23.171  3836  3887 D executeNativeTests: Running unit tests
,08-29 16:09:23.173  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:23.232  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:09:23.232  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce added. We now have 3 listener(s)
,08-29 16:09:23.234  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:09:23.234  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:09:23.234  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:09:23.234  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:09:23.234  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef added. We now have 3 listener(s)
,08-29 16:09:23.234  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:09:23.234  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:09:23.245  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:23.256  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:23.261  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:23.261  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:09:23.263  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 16:09:23.265  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:23.265  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:23.265  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:23.266  3836  3887 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 16:09:23.266  3836  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 16:09:23.266  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 16:09:23.267  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:09:23.267  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:09:23.267  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:09:23.267  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:23.267  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:23.267  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:23.268  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:23.268  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.268  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:09:23.268  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 16:09:23.268  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce removed from the list
08-29 16:09:23.268  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.268  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef removed from the list
08-29 16:09:23.268  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:23.269  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:23.269  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.269  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.269  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.270  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:23.270  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:23.270  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.270  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:23.271  3836  3887 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 16:09:23.272  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:23.272  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:23.272  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:23.272  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:23.272  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.272  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.272  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:23.272  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.272  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:23.272  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:23.272  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.272  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.273  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.273  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.274  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:23.274  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:23.274  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.274  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:23.278  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 16:09:23.279  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 16:09:23.280  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 16:09:23.280  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:23.280  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:23.280  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:23.281  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:23.281  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.281  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.281  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:23.281  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.281  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:23.281  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:23.281  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.281  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.282  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:23.282  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:23.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:23.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:23.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:23.284  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:23.286  3836  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 16:09:23.289  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:23.296  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:23.297  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:23.297  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:09:23.298  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:09:23.298  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:09:23.299  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:09:23.299  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:09:23.299  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:09:23.302  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:23.306  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:23.308  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:09:23.308  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 16:09:23.315  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 16:09:23.318  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:09:23.318  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 16:09:23.321  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 16:09:23.327  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 16:09:23.327  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 16:09:23.327  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:09:23.328  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 16:09:23.329  3836  3887 D BluetoothAdapter: STATE_ON
08-29 16:09:23.334  2663  2821 D BtGatt.GattService: registerClient() - UUID=7889ee7a-b4a8-4a12-bb98-5f9cf6f7d531
08-29 16:09:23.335  2663  2685 D BtGatt.GattService: onClientRegistered() - UUID=7889ee7a-b4a8-4a12-bb98-5f9cf6f7d531, clientIf=5
08-29 16:09:23.337  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 16:09:23.338  2663  2675 D BtGatt.GattService: start scan with filters
08-29 16:09:23.340  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 16:09:23.341  2663  2688 D BtGatt.ScanManager: handling starting scan
08-29 16:09:23.341  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:09:23.341  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:09:23.341  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:09:23.344  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:09:23.344  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:09:23.345  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 16:09:23.345  2663  2688 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:09:23.346  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:09:23.349  3836  3887 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:09:23.354  2663  2685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 16:09:23.354  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:23.356  2663  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:09:23.362  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 16:09:23.362  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:23.364  2663  2688 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:09:23.364  2663  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 16:09:23.372  2663  2685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 16:09:23.372  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:23.376  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 16:09:23.376  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:23.477   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 16:09:23.846  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 16:09:23.847  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 16:09:23.847  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:09:24.885  2663  2663 D BtGatt.ScanManager: awakened up at time 142093
,08-29 16:09:24.888  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:24.922  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 16:09:24.923  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:24.923  2663  2685 D BtGatt.GattService: current time is 142131021986
,08-29 16:09:24.923  2663  2685 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -68, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -67, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -100, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:09:24.925  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-29 16:09:24.926  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 16:09:24.926  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:09:24.926  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 16:09:24.927  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 16:09:24.927  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 16:09:26.426  2663  2663 D BtGatt.ScanManager: awakened up at time 143634
,08-29 16:09:26.429  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:26.442  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 16:09:26.442  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:27.944  2663  2663 D BtGatt.ScanManager: awakened up at time 145151
,08-29 16:09:27.946  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:27.974  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-29 16:09:27.974  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:27.974  2663  2685 D BtGatt.GattService: current time is 145182449870
08-29 16:09:27.975  2663  2685 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-29 16:09:27.975  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-29 16:09:28.359  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:28.360  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:28.360  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:09:28.360  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:28.361  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:09:28.361  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:09:28.361  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:09:28.362  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 16:09:28.362  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:09:28.364  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:09:28.365  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 16:09:28.368  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:09:28.371  2663  2675 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:09:28.373  2663  2799 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:09:28.374  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:09:28.374  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:09:28.374  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 16:09:28.374  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 16:09:28.375  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 16:09:28.377  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:09:28.378  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:09:28.379  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-29 16:09:28.379  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:09:28.381  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:09:28.383  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:28.384  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:28.384  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:09:28.385  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:28.385  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:28.385  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:09:28.386  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:28.386  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:28.386  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:28.386  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:28.387  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:28.394  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 16:09:28.395  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:28.395  2663  2688 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:09:28.412  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 16:09:28.412  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:28.412  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:28.442  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-29 16:09:28.442  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:28.443  2663  2685 D BtGatt.GattService: current time is 145650950091
,08-29 16:09:28.443  2663  2685 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -100, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-29 16:09:28.453  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 16:09:28.454  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 16:09:28.455  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-29 16:09:28.886  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:09:32.043  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:32.056  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:32.061  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:32.123  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 16:09:32.123  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 16:09:32.124  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:32.124  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:32.173  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:09:32.174  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 16:09:32.177  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 16:09:32.776   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 16:09:32.785  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 16:09:32.792   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:09:32.792   876   896 I Adreno  : Build Date                       : 10/20/15
08-29 16:09:32.792   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:09:32.792   876   896 I Adreno  : Local Branch                     : M14
08-29 16:09:32.792   876   896 I Adreno  : Remote Branch                    : 
08-29 16:09:32.792   876   896 I Adreno  : Remote Branch                    : 
08-29 16:09:32.792   876   896 I Adreno  : Reconstruct Branch               : 
,08-29 16:09:32.832   282   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (306 us)
,08-29 16:09:33.389  3836  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 16:09:33.455  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 16:09:33.455  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 16:09:33.493  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:33.496   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:33.503  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:33.509   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 16:09:33.513   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 16:09:33.516   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-29 16:09:33.516   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 16:09:33.528  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:33.529  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:09:33.529  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:09:33.530  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:09:33.530  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:09:33.530  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:09:33.530  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:09:33.530  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:33.533  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:33.534  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b358e5d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@45e76e7, 16908290=android.view.AbsSavedState$1@45e76e7}, android:focusedViewId=100}]}]
,08-29 16:09:33.534  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 16:09:33.534  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 16:09:33.534  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-29 16:09:33.534  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:09:33.535  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:09:33.539  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:09:33.539  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:09:33.539  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:09:33.542  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 16:09:33.542  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:09:33.542  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 16:09:33.543  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:09:33.545  2663  2799 D BtGatt.GattService: registerClient() - UUID=61e2c140-1b48-49fc-8f36-10acc7b5a5ff
08-29 16:09:33.545  2663  2685 D BtGatt.GattService: onClientRegistered() - UUID=61e2c140-1b48-49fc-8f36-10acc7b5a5ff, clientIf=5
08-29 16:09:33.545  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 16:09:33.546  2663  2821 D BtGatt.GattService: start scan with filters
,08-29 16:09:33.549  2663  2688 D BtGatt.ScanManager: handling starting scan
,08-29 16:09:33.550  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 16:09:33.550  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:09:33.550  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:09:33.550  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:09:33.553  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:09:33.554  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:09:33.554  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 16:09:33.555  2663  2685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 16:09:33.555  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.555  2663  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:09:33.556  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:09:33.560  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 16:09:33.560  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.560  2663  2688 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 16:09:33.560  2663  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 16:09:33.561  3836  3887 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:09:33.564  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:33.564  3836  3887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 16:09:33.564  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:09:33.564  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 16:09:33.565  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:33.565  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:09:33.565  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:09:33.565  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:09:33.565  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:09:33.565  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:09:33.565  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:09:33.566  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 16:09:33.566  3836  3887 D BluetoothAdapter: STATE_ON
08-29 16:09:33.567  2663  2821 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:09:33.568  2663  2799 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 16:09:33.569  2663  2685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 16:09:33.569  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.568  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:09:33.569  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:09:33.569  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 16:09:33.569  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 16:09:33.570  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:09:33.571  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:09:33.571  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 16:09:33.571  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:09:33.571  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:09:33.572  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:09:33.573  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 16:09:33.573  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.574  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-29 16:09:33.574  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:33.574  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:09:33.574  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:33.575  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:33.575  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:09:33.575  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:33.575  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:33.575  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:33.575  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:33.575  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:33.576  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:33.576  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:33.577  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:33.577  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:33.577  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:33.577  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:33.578  3836  3887 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 16:09:33.579  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 16:09:33.579  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.579  2663  2688 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:09:33.580  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:33.584  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 16:09:33.584  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.585  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:33.586  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:33.589  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 16:09:33.589  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:33.589  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.589  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:09:33.590  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:09:33.590  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:09:33.590  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:09:33.590  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:09:33.591  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:09:33.592  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:33.594  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 16:09:33.594  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:09:33.598  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:33.600  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:09:33.601  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 16:09:33.601  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:09:33.607  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 16:09:33.607  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:09:33.607  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 16:09:33.608  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:09:33.612  2663  2821 D BtGatt.GattService: registerClient() - UUID=1936330b-201e-43c1-a070-fa67a312405f
08-29 16:09:33.613  2663  2685 D BtGatt.GattService: onClientRegistered() - UUID=1936330b-201e-43c1-a070-fa67a312405f, clientIf=5
08-29 16:09:33.613  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:09:33.614  2663  2799 D BtGatt.GattService: start scan with filters
,08-29 16:09:33.617  2663  2688 D BtGatt.ScanManager: handling starting scan
08-29 16:09:33.617  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 16:09:33.617  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 16:09:33.617  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:09:33.617  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:09:33.622  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:09:33.622  2663  2685 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 16:09:33.622  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:33.622  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 16:09:33.622  2663  2688 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 16:09:33.622  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:09:33.624  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:09:33.627  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 16:09:33.627  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:33.627  2663  2688 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:09:33.627  2663  2688 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 16:09:33.628  3836  3887 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 16:09:33.638  2663  2685 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 16:09:33.638  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:33.645  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 16:09:33.645  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:33.765   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 16:09:33.769   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 16:09:33.775   876  1333 D SurfaceControl: Excessive delay in setPowerMode(): 261ms
08-29 16:09:33.783   876   896 I DreamManagerService: Entering dreamland.
,08-29 16:09:33.786   876   896 I PowerManagerService: Dozing...
,08-29 16:09:33.787   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 16:09:33.845   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 16:09:33.846   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 16:09:33.859   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:09:33.869  1946  3908 D NfcService: Discovery configuration equal, not updating.
,08-29 16:09:33.884   876  1308 E native  : do suspend false
,08-29 16:09:33.914   876  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 16:09:33.938   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:09:33.950   876  1308 E native  : do suspend true
,08-29 16:09:33.984   376  1461 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 16:09:33.984   376  1461 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 16:09:34.124  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 16:09:34.124  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:09:34.124  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:09:34.149  2663  2663 D BtGatt.ScanManager: awakened up at time 151356
,08-29 16:09:34.151  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:34.200  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-29 16:09:34.200  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:34.201  2663  2685 D BtGatt.GattService: current time is 151409018321
,08-29 16:09:34.202  2663  2685 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-29 16:09:34.202  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 16:09:34.203  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 16:09:34.204  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-29 16:09:34.367   876  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-29 16:09:35.707  2663  2663 D BtGatt.ScanManager: awakened up at time 152914
,08-29 16:09:35.709  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:35.759  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 16:09:35.759  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:35.760  2663  2685 D BtGatt.GattService: current time is 152968209570
,08-29 16:09:35.761  2663  2685 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -52, 11, 57, -70, 107, -17, 1, 0, -105, 23, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 81, 34, 97, 112, -14, -5, 1, -128, -85, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -86, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:09:35.762  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 16:09:35.762  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,08-29 16:09:35.763  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 16:09:35.764  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-29 16:09:35.765  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-29 16:09:35.765  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 16:09:37.262  2663  2663 D BtGatt.ScanManager: awakened up at time 154470
,08-29 16:09:37.266  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:37.277  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 16:09:37.277  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:09:38.629  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:38.629  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:38.630  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:09:38.630  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:38.630  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:09:38.631  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:09:38.631  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 16:09:38.631  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:09:38.631  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:09:38.632  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:09:38.632  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 16:09:38.635  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:09:38.637  2663  2821 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:09:38.641  2663  2799 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:09:38.642  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:09:38.643  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 16:09:38.643  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 16:09:38.643  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 16:09:38.644  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:09:38.650  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:09:38.650  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 16:09:38.650  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:09:38.651  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:09:38.652  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:09:38.656  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:38.657  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:09:38.657  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:09:38.655  2663  2663 D BtGatt.ScanManager: awakened up at time 155862
,08-29 16:09:38.662  2663  2685 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 16:09:38.662  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:38.663  2663  2688 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:09:38.679  2663  2685 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 16:09:38.680  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:38.680  2663  2688 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:09:38.728  2663  2685 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-29 16:09:38.728  2663  2685 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:09:38.728  2663  2685 D BtGatt.GattService: current time is 155936566898
,08-29 16:09:38.729  2663  2685 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:09:38.730  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 16:09:38.731  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 16:09:38.733  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 16:09:38.733  2663  2685 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 16:09:38.972  1889  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 16:09:39.158  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 16:09:39.159  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:39.159  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:09:41.237  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:41.243  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:41.320  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:09:41.321  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 16:09:41.321  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:41.321  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:41.377  3550  3914 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:09:41.377  3550  3914 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:09:41.377  3550  3914 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	... 12 more
08-29 16:09:41.377  3550  3914 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at fal.a(PG:38)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:09:41.377  3550  3914 E HttpOperation: 	... 14 more
,08-29 16:09:41.455  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 16:09:41.456  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 16:09:41.456  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:41.456  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:41.484  3550  3914 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:09:41.484  3550  3914 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at hec.a(PG:42)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at hee.a(PG:102)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at czr.a(PG:65)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at kka.a(PG:108)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:09:41.484  3550  3914 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	... 15 more
08-29 16:09:41.484  3550  3914 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:09:41.484  3550  3914 E HttpOperation: 	,at fal.a(PG:38)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:09:41.484  3550  3914 E HttpOperation: 	... 17 more
08-29 16:09:41.486  3550  3914 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:09:41.486  3550  3914 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	... 15 more
08-29 16:09:41.486  3550  3914 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:09:41.486  3550  3914 E ExperimentLoader: 	... 17 more
,08-29 16:09:41.616   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129245, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:09:43.657  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:43.658  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.658  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:09:43.658  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:43.659  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.659  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:09:43.660  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.660  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:43.660  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.661  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.661  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.663  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.663  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.666  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.667  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.667  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:43.667  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:43.669  3836  3887 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 16:09:43.671  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:43.672  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.672  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:09:43.673  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.673  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.673  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.673  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:43.674  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.674  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.674  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.675  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.675  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.675  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.676  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.677  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.678  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:09:43.678  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.678  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:43.679  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 16:09:43.679  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:43.679  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:09:43.679  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:43.679  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.679  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.679  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.679  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.680  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.680  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.680  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:43.680  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.680  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.680  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.680  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.682  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:09:43.682  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.682  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:43.682  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.683  3836  3887 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 16:09:43.683  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:43.683  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:09:43.683  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:09:43.683  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.683  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.684  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.684  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.684  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.684  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.684  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:43.684  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.684  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.684  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.684  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.685  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:09:43.686  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:09:43.686  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.686  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.686  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 16:09:43.686  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:43.687  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.687  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:43.687  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.687  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.687  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.687  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.687  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.687  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.687  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.687  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.687  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.688  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.688  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.689  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.689  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.689  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.689  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.690  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 16:09:43.690  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:43.690  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:43.690  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 16:09:43.691  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 16:09:43.691  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:09:43.691  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 16:09:43.691  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 16:09:43.691  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-29 16:09:43.691  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:43.691  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.691  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:09:43.691  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:43.692  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.692  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.692  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:43.692  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:43.692  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:43.692  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:43.692  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.692  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.692  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.692  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.693  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.693  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.694  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.694  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.695  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:09:43.695  3836  3887 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 16:09:43.695  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 16:09:43.699  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:09:43.699  3836  3887 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 16:09:43.699  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 16:09:43.699  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 16:09:43.699  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 16:09:43.699  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 16:09:43.699  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 16:09:43.700  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:,1510:1510]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
,08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 16:09:43.701  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 16:09:43.702  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-29 16:09:43.702  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 16:09:43.702  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-29 16:09:43.702  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 16:09:43.702  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-29 16:09:43.702  3836  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 16:09:43.703  3836  3887 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 16:09:43.703  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 16:09:43.703  3836  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 16:09:43.703  3836  3887 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-29 16:09:43.703  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 16:09:43.703  3836  3887 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 16:09:43.703  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 16:09:43.706  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 16:09:43.707  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 16:09:43.707  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 16:09:43.708  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 16:09:43.708  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-29 16:09:43.708  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 16:09:43.708  3836  3887 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 16:09:43.708  3836  3887 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 16:09:43.709  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:43.709  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.709  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:09:43.709  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.709  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.710  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.710  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 16:09:43.710  3836  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-29 16:09:43.710  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.710  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.711  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.711  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:43.711  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.711  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.711  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.711  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.712  3836  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-29 16:09:43.714  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.714  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:09:43.714  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.714  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.715  3836  3887 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 16:09:43.716  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:43.716  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.716  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:43.716  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:43.716  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.716  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.716  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.717  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.717  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.717  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.717  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.717  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.717  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.717  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.717  3836  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:09:43.724  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.724  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.725  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.725  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.727  3836  3887 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-29 16:09:43.728  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:43.728  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.729  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:43.729  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.730  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.730  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.730  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:43.730  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.731  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.731  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.731  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.731  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.732  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.732  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.733  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.733  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.734  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.734  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.736  3836  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 16:09:43.736  3836  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 16:09:43.736  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 16:09:43.737  3836  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 16:09:43.737  3836  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 16:09:43.737  3836  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 16:09:43.738  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 16:09:43.738  3836  3887 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 16:09:43.738  3836  3887 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 16:09:43.738  3836  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-29 16:09:43.739  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 16:09:43.739  3836  3887 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 16:09:43.740  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:43.740  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:43.740  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:43.741  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:43.741  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:43.741  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.742  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.742  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.743  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.743  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:43.743  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.743  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:43.743  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.743  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.744  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:43.744  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:43.744  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.744  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.745  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:43.745  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.745  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:43.745  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:43.746  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:43.746  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:43.746  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:43.746  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:43.746  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:45.546   876  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-29 16:09:46.721  1503  2091 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 16:09:48.747  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.747  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.748  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:48.748  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.748  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:48.749  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:48.749  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:48.750  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:09:48.750  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:48.751  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:48.751  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.751  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:48.751  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
,08-29 16:09:48.752  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:48.752  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.752  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:48.753  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:48.753  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.753  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.753  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.757  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:48.757  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:48.758  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.758  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.765  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 16:09:48.766  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:48.769  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 16:09:48.770  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 16:09:48.771  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 16:09:48.771  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:09:48.771  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 16:09:48.771  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 16:09:48.771  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:48.772  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 16:09:48.772  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:09:48.772  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 16:09:48.772  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.772  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 16:09:48.772  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:48.772  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.772  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:09:48.772  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 16:09:48.779  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:09:48.779  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 16:09:48.772  3836  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:09:48.779  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.779  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.779  3836  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 16:09:48.781  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:09:48.781  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.781  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:48.781  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:48.781  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:09:48.782  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:48.782  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:48.782  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.782  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:09:48.782  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.782  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:48.782  3836  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:09:48.783  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.783  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.783  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:48.784  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:48.783  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:09:48.784  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.784  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.784  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.786  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:48.786  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:48.787  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.787  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.790  3836  3887 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 16:09:48.791  3836  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 16:09:48.791  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 16:09:48.794  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 16:09:48.794  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 16:09:48.795  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:09:48.795  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:48.795  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 16:09:48.795  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:48.795  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.795  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.796  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:48.796  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.796  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:48.796  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:48.796  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.796  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.796  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.796  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:48.799  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:09:48.800  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:48.800  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.800  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.804  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-29 16:09:48.804  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:48.804  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:48.805  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:09:48.805  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.805  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.805  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:48.805  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.805  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
08-29 16:09:48.805  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:48.805  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.806  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:48.806  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.806  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.808  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:09:48.808  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:48.808  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.809  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:48.811  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:09:48.811  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:09:48.812  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:09:48.812  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:09:48.812  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:48.813  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.813  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68721ce not in the list
08-29 16:09:48.813  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.813  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:48.814  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:48.814  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.814  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:09:48.814  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:48.815  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:48.817  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:09:48.817  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:09:48.818  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:09:48.818  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a58ef not in the list
,08-29 16:09:48.821  3836  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-29 16:09:48.821  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 16:09:48.822  3836  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-29 16:09:48.822  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 16:09:48.822  3836  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 16:09:48.823  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 16:09:48.828  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 16:09:48.828  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 16:09:48.829  3836  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 16:09:48.829  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-29 16:09:48.829  3836  3887 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 16:09:48.829  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-29 16:09:48.829  3836  3887 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 16:09:48.829  3836  3887 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 16:09:48.830  3836  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 16:09:48.830  3836  3887 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 16:09:48.831  3836  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-29 16:09:48.831  3836  3887 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 16:09:48.831  3836  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-29 16:09:48.831  3836  3887 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 16:09:48.832  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:09:48.832  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe59a7e added. We now have 3 listener(s)
,08-29 16:09:48.832  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:09:48.834  3836  3887 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 16:09:48.835   876  1402 D WifiService: setWifiEnabled: true pid=3836, uid=10000
,08-29 16:09:48.835   876  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:09:48.846  2663  2765 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 16:09:48.846  2663  2784 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-29 16:09:48.846  3836  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
,08-29 16:09:49.284  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:09:53.844  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:09:53.845  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5495bdf added. We now have 4 listener(s)
,08-29 16:09:53.845  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:09:53.862  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:53.863  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5495bdf removed from the list
08-29 16:09:53.863  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:09:53.863  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:09:53.864  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:53.866  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:09:53.866  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b4402c added. We now have 4 listener(s)
,08-29 16:09:53.867  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:09:53.872  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:09:53.873  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b4402c removed from the list
08-29 16:09:53.873  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:09:53.873  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:09:53.874  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:09:53.876  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:09:53.876  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@154eaf5 added. We now have 4 listener(s)
08-29 16:09:53.877  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:09:53.883   876  2001 D WifiService: setWifiEnabled: false pid=3836, uid=10000
,08-29 16:09:53.884   876  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:09:53.891  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:09:53.893  2663  2681 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 16:09:53.893  2663  2681 D BluetoothAdapterProperties: Setting state to 13
08-29 16:09:53.894  2663  2681 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 16:09:53.896  2663  2681 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 16:09:53.896  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:53.896  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:09:53.898  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:53.898  2663  2685 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:09:53.898  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:53.898  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:09:53.899  2663  2681 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:09:53.899  2663  2681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 16:09:53.902  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:53.904  2663  2663 D BluetoothMapService: onReceive
08-29 16:09:53.904  2663  2663 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 16:09:53.904  2663  2663 D BluetoothMapService: STATE_TURNING_OFF
08-29 16:09:53.905  2663  2663 D BluetoothMapService: MAP Service closeService in
08-29 16:09:53.905  2663  2663 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 16:09:53.905  2663  2663 D ObexServerSockets0: shutdown(block = true)
,08-29 16:09:53.906  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 16:09:53.906  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 16:09:53.906  2663  2784 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 16:09:53.906  2663  2822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 16:09:53.906  2663  2823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 16:09:53.907  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:53.910  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:53.910  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.911  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:53.911  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:09:53.912  2663  2663 I BtOppRfcommListener: stopping Accept Thread
,08-29 16:09:53.913  2663  3408 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 16:09:53.913  2663  3408 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 16:09:53.915  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:53.915  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.916  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.916  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:09:53.918   876   889 I ActivityManager: Start proc 3922:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 16:09:53.919  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:53.921  2663  2663 D HeadsetService: Received stop request...Stopping profile...
08-29 16:09:53.924   876   876 D BluetoothHeadset: Proxy object disconnected
08-29 16:09:53.924  1353  2351 D BluetoothHeadset: Proxy object disconnected
,08-29 16:09:53.924   876   876 D BluetoothHeadset: Proxy object disconnected
08-29 16:09:53.925  1961  1979 D BluetoothHeadset: Proxy object disconnected
08-29 16:09:53.925   876   876 D BluetoothHeadset: Proxy object disconnected
08-29 16:09:53.926  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:53.927  2663  2663 D A2dpService: Received stop request...Stopping profile...
08-29 16:09:53.927  2663  2802 D A2dpStateMachine: Exit Disconnected: -1
08-29 16:09:53.929   876   876 D BluetoothA2dp: Proxy object disconnected
08-29 16:09:53.929  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:53.929  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 16:09:53.930  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-29 16:09:53.930  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-29 16:09:53.930  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:09:53.930  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:09:53.930   876  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 16:09:53.930   876  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 16:09:53.930   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:09:53.931   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:09:53.931  2663  2663 D HidService: Received stop request...Stopping profile...
08-29 16:09:53.931  2663  2663 D HidService: Stopping Bluetooth HidService
08-29 16:09:53.933  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:09:53.935  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 16:09:53.936  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 16:09:53.936  2663  2685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 16:09:53.936  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.936  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.936  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.936  2663  2685 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 16:09:53.937  2663  2663 D HealthService: Received stop request...Stopping profile...
,08-29 16:09:53.941  2663  2663 D PanService: Received stop request...Stopping profile...
,08-29 16:09:53.946   876  1308 E native  : do suspend true
,08-29 16:09:53.946  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-29 16:09:53.946  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-29 16:09:53.947  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:09:53.947  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:09:53.947  2663  2663 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 16:09:53.947  2663  2663 D BluetoothMapService: stop()
,08-29 16:09:53.945  1353  1353 D HeadsetProfile: Bluetooth service disconnected
,08-29 16:09:53.948  2663  2663 D BluetoothMapAppObserver: deinitObservers()
08-29 16:09:53.948  2663  2663 D BluetoothMapAppObserver: removeReceiver()
08-29 16:09:53.948  1353  1353 D BluetoothA2dp: Proxy object disconnected
08-29 16:09:53.948  1353  1353 D BluetoothInputDevice: Proxy object disconnected
,08-29 16:09:53.948  1353  1353 D HidProfile: Bluetooth service disconnected
08-29 16:09:53.949  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 16:09:53.949  1353  1353 D PanProfile: Bluetooth service disconnected
,08-29 16:09:53.949  1353  1353 D BluetoothMap: Proxy object disconnected
08-29 16:09:53.949  1353  1353 D MapProfile: Bluetooth service disconnected
08-29 16:09:53.950  2663  2685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 16:09:53.950  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.950  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.950  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-29 16:09:53.950  2663  2765 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 16:09:53.950  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-29 16:09:53.950  2663  2765 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:09:53.950  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:09:53.950  2663  2765 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 16:09:53.950  2663  2765 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:09:53.950  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:09:53.951  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 16:09:53.951  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 16:09:53.951  2663  2685 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 16:09:53.951  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-29 16:09:53.951  2663  2663 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:09:53.951  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:09:53.951  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:09:53.951  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 16:09:53.951  2663  2685 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 16:09:53.952  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 16:09:53.953  2663  2663 V BluetoothAdapterState: isTurningOff()=true
08-29 16:09:53.953  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-29 16:09:53.953  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:09:53.953  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:09:53.953  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 16:09:53.953  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 16:09:53.955  2663  2663 D BluetoothMapService: MAP Service closeService in
,08-29 16:09:53.955  2663  2663 V BluetoothAdapterState: isTurningOff()=true
,08-29 16:09:53.955  2663  2663 V BluetoothAdapterState: isTurningOn()=false
08-29 16:09:53.955  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:09:53.955  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:09:53.956  2663  2681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 16:09:53.956  2663  2681 D BluetoothAdapterProperties: Setting state to 15
08-29 16:09:53.956  2663  2681 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 16:09:53.957  2663  2681 I BluetoothAdapterState: Entering BleOnState
08-29 16:09:53.957  2663  2663 D BluetoothMapService: cleanup()
08-29 16:09:53.957  2663  2663 D BluetoothMapService: MAP Service closeService in
08-29 16:09:53.959   876  1903 D DhcpClient: Clearing IP address
08-29 16:09:53.959   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:09:53.960  1961  2280 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:09:53.960  1353  1367 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:09:53.961  1353  1364 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 16:09:53.961   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:09:53.962   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:09:53.963   372   874 D CommandListener: Setting iface cfg
08-29 16:09:53.962  1353  2099 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:09:53.964  1353  2351 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:09:53.964   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:09:53.964   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:09:53.964  1353  1367 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 16:09:53.966   876  1906 D DhcpClient: Receive thread stopped
08-29 16:09:53.966  1353  1364 D BluetoothPan: onBluetoothStateChange on: false
,08-29 16:09:53.967  2663  2681 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 16:09:53.967  2663  2681 D BluetoothAdapterProperties: Setting state to 16
08-29 16:09:53.967  2663  2681 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 16:09:53.967  2663  2681 D BluetoothAdapterProperties: onBleDisable
08-29 16:09:53.967  2663  2681 I BluetoothAdapterState: Entering PendingCommandState
08-29 16:09:53.968  2663  2682 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 16:09:53.969   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 16:09:53.969  2663  2685 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:09:53.969   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 16:09:53.970  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:09:53.970  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.971  2663  2765 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 16:09:53.971  2663  2765 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:09:53.971  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.971  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:09:53.971   395   395 E Parcel  : Reading a NULL string not supported here.
08-29 16:09:53.972  1503  2493 V NativeCrypto: Read error: ssl=0x9ae83000: I/O error during system call, Connection timed out
08-29 16:09:53.974  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:53.974  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.975  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.975  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:53.975   876  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 16:09:53.975   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:09:53.976   876  1308 E native  : do suspend true
,08-29 16:09:53.976  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:53.976  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.977  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.977  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:53.978  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:53.978  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:09:53.978  1503  2493 V NativeCrypto: SSL shutdown failed: ssl=0x9ae83000: I/O error during system call, Broken pipe
08-29 16:09:53.979   876  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 16:09:53.979  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:53.980  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:09:54.004   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:09:54.004  3922  3922 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 16:09:54.013  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:09:54.019  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:09:54.019   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@535936f:true
,08-29 16:09:54.026   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 16:09:54.026   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:09:54.027   876  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 16:09:54.027   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:09:54.031   876  1691 I ActivityManager: Start proc 3938:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 16:09:54.032   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:09:54.035   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:09:54.038  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.038  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:54.039  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.039  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:54.041  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:09:54.050   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:09:54.052  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.052  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:54.053  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:54.053   876  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 16:09:54.053  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:54.055  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.055  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:54.055  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:54.055  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:54.055  3922  3922 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 16:09:54.057  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:54.057  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:54.057  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:54.057  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:54.058  1889  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:09:54.063  3922  3922 D BluetoothMap: Create BluetoothMap proxy object
,08-29 16:09:54.070  3922  3922 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 16:09:54.076  3938  3938 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 16:09:54.084  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:09:54.093   876  1383 I ActivityManager: Killing 2274:com.google.android.talk/u0a61 (adj 15): empty #17
,08-29 16:09:54.096   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-29 16:09:54.097   876  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 16:09:54.173  2663  2685 I bt_hci  : shut_down
,08-29 16:09:54.177  2663  2695 D bt_hwcfg: hw_epilog_process
08-29 16:09:54.177  2663  2695 I bt_vendor: low_power_mode_cb
,08-29 16:09:54.195  2663  2695 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 16:09:54.196  2663  2695 I bt_vendor: epilog_cb
08-29 16:09:54.196  2663  2695 I bt_hci  : epilog_finished_callback
,08-29 16:09:54.200  2663  2685 I bt_hci_h4: hal_close
,08-29 16:09:54.201  2663  2685 I bt_userial_vendor: device fd = 51 close
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.262  3938  3938 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.262  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 16:09:54.263  3938  3938 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:09:54.263  3938  3938 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:09:54.263  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:09:54.267  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 16:09:54.280  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:09:54.286  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:09:54.307   876  1968 I ActivityManager: Start proc 3972:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-29 16:09:54.310   876  1968 I ActivityManager: Killing 3565:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 16:09:54.383  2663  2682 D bt_stack_manager: event_shut_down_stack finished.
08-29 16:09:54.383  2663  2681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 16:09:54.387  2663  2681 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 16:09:54.387  2663  2663 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:09:54.389  2663  2663 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 16:09:54.389  2663  2663 D BtGatt.GattService: stop()
08-29 16:09:54.389  2663  2663 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 16:09:54.393  2663  2663 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:09:54.393  2663  2663 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:09:54.393  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:09:54.394  2663  2663 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 16:09:54.394  2663  2681 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 16:09:54.394  2663  2681 D BluetoothAdapterProperties: Setting state to 10
,08-29 16:09:54.395  2663  2681 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 16:09:54.396  2663  2681 I BluetoothAdapterState: Entering OffState
,08-29 16:09:54.397   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 16:09:54.400  3972  3972 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-29 16:09:54.415  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 16:09:54.415  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 16:09:54.415  2663  2682 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 16:09:54.418  2663  2682 D bt_stack_manager: event_clean_up_stack finished.
,08-29 16:09:54.418  2663  2663 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 16:09:54.426  2663  2663 I art     : System.exit called, status: 0
,08-29 16:09:54.426  2663  2663 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 16:09:54.506   876  2011 I ActivityManager: Process com.android.bluetooth (pid 2663) has died
,08-29 16:09:54.663  3972  3993 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 16:09:54.663  3972  3993 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 16:09:54.673  3972  3993 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 16:09:54.673  3972  3993 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 16:09:54.697  3972  3993 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 16:09:54.697  3972  3993 I Babel_SMS: MmsConfig.loadFromResources
,08-29 16:09:54.709  3972  3993 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 16:09:54.710  3972  3993 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 16:09:54.745  3972  3972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 16:09:54.748  3972  3972 I Babel_Crash: startup - clean
,08-29 16:09:54.774  3972  3972 I Babel_telephony: TeleModule.launchCompleted
,08-29 16:09:54.785   876  2001 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 16:09:54.796  3938  3968 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 16:09:54.799  3972  3972 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 16:09:54.807  3972  3972 W Babel   : BAM#gBA: invalid account id: -1
,08-29 16:09:54.807  3972  3972 W Babel   : BAM#gBA: invalid account id: -1
,08-29 16:09:54.807  3972  3972 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-29 16:09:54.813  3972  3998 I Babel   : deleted: false for 0
,08-29 16:09:54.820   876  2000 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 16:09:54.837  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:09:54.841  1716  1716 D SystemUpdateService: onCreate
,08-29 16:09:54.856  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:09:54.876  1716  4000 I SystemUpdateService: active receiver: enabled
,08-29 16:09:54.884  1716  4000 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:09:54.886  1716  4000 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 16:09:54.886  1716  4000 I SystemUpdateService: now status is 0 (complete)
08-29 16:09:54.886  1716  4000 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:09:54.886  1716  4000 I SystemUpdateService: file has been verified
08-29 16:09:54.887  1716  4000 I SystemUpdateService: OTA package size = 12249756
,08-29 16:09:54.889  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 16:09:54.895  1716  2457 I iu.UploadsManager: num queued entries: 0
,08-29 16:09:54.896  1716  2457 I iu.UploadsManager: num updated entries: 0
,08-29 16:09:54.896  1716  4000 I SystemUpdateService: showing system update notification
08-29 16:09:54.896  1716  2457 I iu.SyncManager: NEXT; no task
,08-29 16:09:54.911  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:09:54.915  1716  1716 D SystemUpdateService: onDestroy
,08-29 16:09:54.916  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:09:54.919  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:09:54.940   876  2011 I ActivityManager: Start proc 4002:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 16:09:54.968  3972  3972 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 16:09:54.978  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:09:54.988  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:09:54.993  4002  4002 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 16:09:55.004  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:09:55.010  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:09:55.014  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 16:09:55.032   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ae4999:true
,08-29 16:09:55.033  3972  3972 I vclib   : onServiceConnected
,08-29 16:09:55.036  4002  4002 D SprintDMHelper: simOperator: 
08-29 16:09:55.036  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:09:55.074   876  2024 I ActivityManager: Start proc 4014:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 16:09:55.075   876  2024 I ActivityManager: Killing 3449:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 16:09:55.243   876  2024 I ActivityManager: Start proc 4029:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 16:09:55.262  3972  4028 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 16:09:55.278   876  1967 I ActivityManager: Killing 3489:android.process.acore/u0a5 (adj 15): empty #17
,08-29 16:09:55.296  4029  4029 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 16:09:55.376  4029  4029 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 16:09:55.376  4029  4029 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 16:09:55.376  4029  4029 I GAv4    :   adb logcat -s GAv4
,08-29 16:09:55.390  4029  4029 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:09:55.399  4029  4029 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:09:55.429  4029  4046 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 16:09:55.536  4029  4029 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 16:09:55.580  4029  4029 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 16:09:55.592  4029  4029 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 2793-2799)
08-29 16:09:55.592  4029  4029 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 16:09:55.601  4029  4029 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9cbc53}
,08-29 16:09:55.601  4029  4029 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 16:09:55.602  4029  4029 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 16:09:55.611  4029  4029 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 16:09:55.612  4029  4029 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 16:09:55.630  4029  4029 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 16:09:55.644  4029  4029 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:09:55.644  4029  4029 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 16:09:55.645  4029  4029 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 16:09:55.645  4029  4029 I Adreno  : Build Date                       : 10/20/15
08-29 16:09:55.645  4029  4029 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 16:09:55.645  4029  4029 I Adreno  : Local Branch                     : M14
08-29 16:09:55.645  4029  4029 I Adreno  : Remote Branch                    : 
08-29 16:09:55.645  4029  4029 I Adreno  : Remote Branch                    : 
08-29 16:09:55.645  4029  4029 I Adreno  : Reconstruct Branch               : 
,08-29 16:09:55.704  4029  4029 I NSApplication: Starting up...
,08-29 16:09:55.715  4029  4075 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 16:09:55.745   876  1402 I ActivityManager: Start proc 4080:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-29 16:09:55.746   876  1402 I ActivityManager: Killing 3654:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 16:09:55.819  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 16:09:56.047   876  1383 I ActivityManager: Killing 3669:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 16:09:58.831  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:58.847  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:58.852  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:09:58.900   876   887 D WifiService: setWifiEnabled: true pid=3836, uid=10000
,08-29 16:09:58.900   876   887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:09:58.909   876  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 16:09:58.917  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:58.917  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:09:58.917  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:58.918  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:09:58.921  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:58.921  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:09:58.921  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:58.921  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:09:58.924  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:09:58.925  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:09:58.925  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:09:58.926  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:09:58.927  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 16:09:58.928  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 16:09:58.928  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:09:58.928  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:09:58.956  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:09:58.957  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:09:58.957  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-29 16:09:58.964   876  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-29 16:09:58.965   876  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 16:09:58.966   876  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 16:09:58.967   876  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 16:09:58.967   876  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 16:09:58.967   876  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK,
08-29 16:09:58.967   876  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 16:09:59.000   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 16:09:59.002   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:09:59.002   372   874 D CommandListener: Setting iface cfg
,08-29 16:09:59.003   876  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-29 16:09:59.004   876  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 16:09:59.012   876  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-29 16:09:59.013   876  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 16:09:59.014   876  1308 E native  : do suspend true
,08-29 16:09:59.047   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:09:59.679   876  2011 I ActivityManager: Killing 2113:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 16:10:00.402   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:10:00.460   876  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.31 rxSuccessRate=5.00 delta 1000 -> 994
,08-29 16:10:00.462   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 16:10:00.463   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:00.480   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 16:10:00.526   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 16:10:00.528  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 16:10:00.948  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 16:10:00.985  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 16:10:00.986  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-29 16:10:00.989   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:10:00.996   876  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 16:10:00.997   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:00.997   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 16:10:01.013   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:01.023   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:01.024   876  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 16:10:01.031   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 16:10:01.052   876  4106 D DhcpClient: Receive thread started
,08-29 16:10:01.136   876  1308 E native  : do suspend false
,08-29 16:10:01.156   876  1903 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 16:10:01.171   876  4106 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172644, domain null
,08-29 16:10:01.173   876  1903 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172644 seconds
,08-29 16:10:01.176   876  1903 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 16:10:01.196   876  4106 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 16:10:01.197   876  1903 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 16:10:01.203   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:01.216   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 16:10:01.216   876  1903 D DhcpClient: Scheduling renewal in 86399s
,08-29 16:10:01.220   876  1308 E native  : do suspend true
,08-29 16:10:01.243   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-29 16:10:01.244   876  1308 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 16:10:01.245   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 16:10:01.247   876  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 16:10:01.247   876  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 16:10:01.318   876  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 16:10:01.318   876  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 16:10:01.320   876  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 16:10:01.321   876  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 16:10:01.323   876  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 16:10:01.334   876  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:10:01.340   876  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 16:10:01.340   876  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 16:10:01.340   876  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 16:10:01.341   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 16:10:01.341   876  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 16:10:01.341   876  1310 D ConnectivityService:    accepting network in place of null
,08-29 16:10:01.343   876  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:10:01.379   876  4105 D NetlinkSocketObserver: NeighborEvent{elapsedMs=178586, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:10:01.393   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:01.426   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:01.435   876  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 16:10:01.438   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:01.445   876  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 16:10:01.448   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:10:01.472  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:01.472  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:01.472  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:01.472  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:01.476  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:01.476  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:10:01.477  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:01.477  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:01.477   876  4104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:815::200e
08-29 16:10:01.483  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:01.483  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:10:01.483  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 16:10:01.483  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:01.498  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:10:01.501  1716  1716 D SystemUpdateService: onCreate
,08-29 16:10:01.504  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:10:01.514  3753  4115 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:10:01.524  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:10:01.526  1716  2457 I iu.UploadsManager: num queued entries: 0
,08-29 16:10:01.526  1716  2457 I iu.UploadsManager: num updated entries: 0
,08-29 16:10:01.527  1716  2457 I iu.SyncManager: NEXT; no task
08-29 16:10:01.532  1716  4117 I SystemUpdateService: active receiver: enabled
,08-29 16:10:01.538  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 16:10:01.539  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:10:01.540  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:01.546  1716  4119 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 16:10:01.546  1716  4119 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 16:10:01.547  1716  4119 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:10:01.548  4002  4002 D SprintDMHelper: simOperator: 
08-29 16:10:01.548  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:10:01.566   876  4104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:10:01 GMT], X-Android-Received-Millis=[1472479801565], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472479801524]}
,08-29 16:10:01.568   876  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 16:10:01.568   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 16:10:01.568   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 16:10:01.569   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 16:10:01.589  1716  4117 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:10:01.610  1716  4117 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 16:10:01.610  1716  4117 I SystemUpdateService: now status is 0 (complete)
,08-29 16:10:01.610  1716  4117 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 16:10:01.610  1716  4117 I SystemUpdateService: file has been verified
08-29 16:10:01.610  1716  4117 I SystemUpdateService: OTA package size = 12249756
,08-29 16:10:01.636  1716  4117 I SystemUpdateService: showing system update notification
,08-29 16:10:01.648  3753  4129 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:10:01.670  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:10:01.670  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:10:01.670  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:01.670  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:01.670  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 16:10:01.670  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 16:10:01.670  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:01.670  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:01.711  1716  1716 D SystemUpdateService: onDestroy
,08-29 16:10:01.723  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:10:01.723  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:10:01.723  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:01.723  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:01.734  3753  4129 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:10:01.735  3753  4115 E BooksSync: Soft error
08-29 16:10:01.735  3753  4115 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:10:01.735  3753  4115 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:10:01.735  3753  4115 E BooksSync: Sync error
08-29 16:10:01.735  3753  4115 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:10:01.735  3753  4115 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:10:01.735  3753  4115 I BooksSync: Finished books sync,
,08-29 16:10:01.742  1716  4119 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-29 16:10:01.746   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161827, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:10:01.850  3972  4124 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:10:02.436   876  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 16:10:03.908   876  1383 D WifiService: setWifiEnabled: false pid=3836, uid=10000
,08-29 16:10:03.908   876  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:10:03.948  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 16:10:03.957   876  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 16:10:03.957   876  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 16:10:03.958   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 16:10:03.958   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:03.993   876  1308 E native  : do suspend true
,08-29 16:10:04.005   876  1903 D DhcpClient: Clearing IP address
,08-29 16:10:04.005   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-29 16:10:04.010   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:04.019  1503  4130 V NativeCrypto: Read error: ssl=0x9a682800: I/O error during system call, Connection timed out
,08-29 16:10:04.021  1503  4130 V NativeCrypto: SSL shutdown failed: ssl=0x9a682800: I/O error during system call, Broken pipe
,08-29 16:10:04.024   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 16:10:04.024   876  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 16:10:04.025   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 16:10:04.026   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 16:10:04.026   876  1308 E native  : do suspend true
08-29 16:10:04.032   395   395 E Parcel  : Reading a NULL string not supported here.
,08-29 16:10:04.040   876  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 16:10:04.046   876  4106 D DhcpClient: Receive thread stopped
,08-29 16:10:04.071   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:04.099   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:04.100   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-29 16:10:04.101   876  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 16:10:04.102   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:04.106   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:10:04.117  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:04.118   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.118  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.118  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.118  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:04.122  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.125  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.125  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.126  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:04.129  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.129  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.129  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:04.129  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:04.140   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:10:04.143  1889  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 16:10:04.144   876  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 16:10:04.150  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:10:04.154  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.155  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.155  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:04.155  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:04.156  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.156  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.156  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.156  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:04.157  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.157  1716  1716 D SystemUpdateService: onCreate
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:04.157  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:04.157  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:04.157  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:04.161  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:10:04.173  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 16:10:04.177  1716  2457 I iu.UploadsManager: num queued entries: 0
,08-29 16:10:04.180  1716  4142 I SystemUpdateService: active receiver: enabled
,08-29 16:10:04.182  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:10:04.183  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:10:04.185  1716  2457 I iu.UploadsManager: num updated entries: 0
,08-29 16:10:04.186  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:04.189  1716  4142 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:10:04.191  1716  4142 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 16:10:04.191  1716  4142 I SystemUpdateService: now status is 0 (complete)
08-29 16:10:04.192  4002  4002 D SprintDMHelper: simOperator: 
08-29 16:10:04.192  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 16:10:04.193   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-29 16:10:04.192  1716  4142 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:10:04.194  1716  4142 I SystemUpdateService: file has been verified
08-29 16:10:04.195  1716  4142 I SystemUpdateService: OTA package size = 12249756
,08-29 16:10:04.196  1716  2457 I iu.SyncManager: NEXT; no task
,08-29 16:10:04.200  1716  4142 I SystemUpdateService: showing system update notification
,08-29 16:10:04.206  3972  4145 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 16:10:04.255  1716  1716 D SystemUpdateService: onDestroy
,08-29 16:10:08.967   876   893 I ActivityManager: Start proc 4149:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 16:10:09.096  4149  4149 D AdapterServiceConfig: Adding HeadsetService
,08-29 16:10:09.097  4149  4149 D AdapterServiceConfig: Adding A2dpService
08-29 16:10:09.097  4149  4149 D AdapterServiceConfig: Adding HidService
,08-29 16:10:09.097  4149  4149 D AdapterServiceConfig: Adding HealthService
,08-29 16:10:09.097  4149  4149 D AdapterServiceConfig: Adding PanService
,08-29 16:10:09.097  4149  4149 D AdapterServiceConfig: Adding GattService
08-29 16:10:09.098  4149  4149 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 16:10:09.116   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3616c7:true
,08-29 16:10:09.116  4149  4149 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 16:10:09.122  4149  4149 I bt_bluedroid: init
08-29 16:10:09.123  4149  4161 I BluetoothAdapterState: Entering OffState
,08-29 16:10:09.128  4149  4162 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 16:10:09.129  4149  4162 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 16:10:09.129  4149  4162 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 16:10:09.130  4149  4162 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 16:10:09.131  4149  4149 I bt_bluedroid: get_profile_interface socket
08-29 16:10:09.134  4149  4149 I bt_bluedroid: get_profile_interface sdp
,08-29 16:10:09.139  4149  4160 I bt_bluedroid: config_hci_snoop_log
,08-29 16:10:09.139  4149  4165 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:10:09.142   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 16:10:09.146  4149  4165 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:10:09.153  4149  4161 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 16:10:09.154  4149  4161 D BluetoothAdapterProperties: Setting state to 14
,08-29 16:10:09.154  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 16:10:09.159  4149  4161 D BluetoothBondStateMachine: make
,08-29 16:10:09.164  4149  4166 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 16:10:09.173  4149  4161 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:10:09.174  4149  4149 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 16:10:09.180  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:09.181  4149  4149 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:10:09.183  4149  4149 D BtGatt.GattService: Received start request. Starting profile...
08-29 16:10:09.183  4149  4149 D BtGatt.GattService: start()
08-29 16:10:09.183  4149  4149 I bt_bluedroid: get_profile_interface gatt
,08-29 16:10:09.185  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:09.185  4149  4149 D BtGatt.AdvertiseManager: advertise manager created
,08-29 16:10:09.199  4149  4149 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:09.199  4149  4149 V BluetoothAdapterState: isTurningOn()=false
08-29 16:10:09.199  4149  4149 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 16:10:09.199  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:09.200  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 16:10:09.201  4149  4161 I bt_bluedroid: enable
08-29 16:10:09.201  4149  4162 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 16:10:09.202  4149  4162 I bt_hci  : start_up
,08-29 16:10:09.224  4149  4162 I bt_vendor: alloc value 0xb3a4a189
,08-29 16:10:09.224  4149  4162 I bt_vendor: init
08-29 16:10:09.224  4149  4162 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 16:10:09.224  4149  4162 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 16:10:09.334  4149  4162 D bt_hci  : start_up starting async portion
,08-29 16:10:09.335  4149  4169 I bt_hci  : event_finish_startup
,08-29 16:10:09.335  4149  4169 I bt_hci_h4: hal_open
08-29 16:10:09.335  4149  4169 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 16:10:09.346   876  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-29 16:10:09.349  4149  4169 I bt_userial_vendor: device fd = 51 open
,08-29 16:10:09.373  4149  4169 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:10:09.405  4149  4169 D bt_hwcfg: Chipset BCM4354A2
08-29 16:10:09.405  4149  4169 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 16:10:09.406  4149  4169 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 16:10:10.063  4149  4169 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 16:10:10.065  4149  4169 D bt_hwcfg: Settlement delay -- 100 ms
08-29 16:10:10.065  4149  4169 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 16:10:10.182  4149  4169 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:10:10.183  4149  4169 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 16:10:10.212  4149  4169 I bt_hwcfg: vendor lib fwcfg completed
08-29 16:10:10.212  4149  4169 I bt_vendor: firmware callback
08-29 16:10:10.213  4149  4169 I bt_hci  : firmware_config_callback
,08-29 16:10:10.224  4149  4171 I bt_btu  : btu_task pending for preload complete event
,08-29 16:10:10.224  4149  4171 I bt_btu_task: Bluetooth chip preload is complete
,08-29 16:10:10.224  4149  4171 I bt_btu  : btu_task received preload complete event
,08-29 16:10:10.237  4149  4171 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 16:10:10.237  4149  4171 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 16:10:10.237  4149  4171 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 16:10:10.238  4149  4171 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 16:10:10.238  4149  4171 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 16:10:10.238  4149  4171 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 16:10:10.238  4149  4171 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 16:10:10.239  4149  4171 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 16:10:10.239  4149  4171 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 16:10:10.239  4149  4171 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 16:10:10.239  4149  4171 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 16:10:10.240  4149  4171 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 16:10:10.240  4149  4171 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 16:10:10.240  4149  4171 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 16:10:10.241  4149  4171 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 16:10:10.380  4149  4171 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,08-29 16:10:10.380  4149  4171 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,08-29 16:10:10.411  4149  4165 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 16:10:10.415  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-29 16:10:10.416  4149  4165 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:10:10.418  4149  4165 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:10:10.419  4149  4165 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:10:10.419  4149  4165 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 16:10:10.420  4149  4165 D bt_hci  : do_postload posting postload work item
,08-29 16:10:10.420  4149  4169 I bt_hci  : event_postload
,08-29 16:10:10.420  4149  4169 I bt_vendor: sco_config_cb
08-29 16:10:10.421  4149  4169 I bt_hci  : sco_config_callback postload finished.
,08-29 16:10:10.422  4149  4165 D bt_bte_conf: Device ID record 1 : primary
08-29 16:10:10.422  4149  4165 D bt_bte_conf:   vendorId            = 000f
08-29 16:10:10.422  4149  4165 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 16:10:10.422  4149  4165 D bt_bte_conf:   product             = 1200
08-29 16:10:10.422  4149  4165 D bt_bte_conf:   version             = 1436
,08-29 16:10:10.422  4149  4165 D bt_bte_conf:   clientExecutableURL = 
08-29 16:10:10.422  4149  4165 D bt_bte_conf:   serviceDescription  = 
08-29 16:10:10.422  4149  4165 D bt_bte_conf:   documentationURL    = 
08-29 16:10:10.423  4149  4165 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 16:10:10.423  4149  4162 D bt_stack_manager: event_start_up_stack finished
,08-29 16:10:10.424  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 16:10:10.424  4149  4161 D BluetoothAdapterProperties: Setting state to 15
,08-29 16:10:10.424  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 16:10:10.426  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.426  4149  4161 I BluetoothAdapterState: Entering BleOnState
,08-29 16:10:10.429  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:10.429  4149  4161 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 16:10:10.430  4149  4161 D BluetoothAdapterProperties: Setting state to 11
,08-29 16:10:10.430  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 16:10:10.430  4149  4169 I bt_vendor: low_power_mode_cb
08-29 16:10:10.433  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.447  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.448  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:10.449  4149  4149 D HeadsetService: Received start request. Starting profile...
08-29 16:10:10.451  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.453  4149  4149 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 16:10:10.453  4149  4149 D HeadsetStateMachine: make
08-29 16:10:10.455  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:10.460  4149  4161 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:10:10.462  4149  4149 D HeadsetStateMachine: max_hf_connections = 1
,08-29 16:10:10.462  4149  4149 I bt_bluedroid: get_profile_interface handsfree
08-29 16:10:10.462  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 16:10:10.462  4149  4165 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 16:10:10.467  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:10:10.467  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:10.468  4149  4149 D A2dpService: Received start request. Starting profile...
,08-29 16:10:10.469  4149  4149 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 16:10:10.470  4149  4149 I bt_bluedroid: get_profile_interface avrcp
,08-29 16:10:10.475  4149  4149 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 16:10:10.475  4149  4149 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 16:10:10.475  4149  4149 D A2dpStateMachine: make
08-29 16:10:10.476  4149  4149 I bt_bluedroid: get_profile_interface a2dp
,08-29 16:10:10.477  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 16:10:10.478  4149  4149 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 16:10:10.479  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:10.479  4149  4180 D A2dpStateMachine: Enter Disconnected: -2
,08-29 16:10:10.480  3922  3922 D BluetoothInputDevice: Proxy object connected
08-29 16:10:10.480  4149  4149 D HidService: Received start request. Starting profile...
08-29 16:10:10.481  4149  4149 I bt_bluedroid: get_profile_interface hidhost
08-29 16:10:10.481  4149  4149 D HidService: setHidService(): set to: null
,08-29 16:10:10.481  4149  4165 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
,08-29 16:10:10.481  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 16:10:10.481  3922  3922 D HidProfile: Bluetooth service connected
08-29 16:10:10.481  4149  4149 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 16:10:10.482  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:10.483  4149  4149 D HealthService: Received start request. Starting profile...
,08-29 16:10:10.484  4149  4149 I bt_bluedroid: get_profile_interface health
08-29 16:10:10.484  4149  4149 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 16:10:10.485  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:10.486  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:10:10.486  4149  4149 D PanService: Received start request. Starting profile...
08-29 16:10:10.486  4149  4149 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 16:10:10.486  4149  4149 I bt_bluedroid: get_profile_interface pan
08-29 16:10:10.486  3922  3922 D PanProfile: Bluetooth service connected
,08-29 16:10:10.487  4149  4165 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 16:10:10.489  4149  4149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:10.490  4149  4149 D BluetoothMapService: Received start request. Starting profile...
08-29 16:10:10.490  4149  4149 D BluetoothMapService: start()
,08-29 16:10:10.492  4149  4149 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 16:10:10.492  4149  4149 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 16:10:10.492  4149  4149 D BluetoothMapAppObserver: createReceiver()
08-29 16:10:10.493  4149  4149 D BluetoothMapAppObserver: initObservers(),
08-29 16:10:10.493  4149  4149 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 16:10:10.501  4149  4178 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 16:10:10.501  4149  4149 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:10.501  4149  4149 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:10.501  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.501  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false,
,08-29 16:10:10.504  4149  4149 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:10.504  4149  4149 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:10.504  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.504  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOn()=true
,08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.505  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:10.506  4149  4149 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:10.506  4149  4149 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:10.506  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:10.506  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:10.506  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-29 16:10:10.506  4149  4161 D BluetoothAdapterProperties: ScanMode =  20
08-29 16:10:10.506  4149  4161 D BluetoothAdapterProperties: State =  11
08-29 16:10:10.507  4149  4161 D BluetoothAdapterProperties: Setting state to 12
08-29 16:10:10.507  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 16:10:10.507  1961  1988 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:10.507  4149  4161 I BluetoothAdapterState: Entering OnState
08-29 16:10:10.508  3922  3933 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:10:10.508  4149  4165 D BluetoothAdapterProperties: Scan Mode:21
,08-29 16:10:10.508  4149  4165 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 16:10:10.509  3922  3922 D BluetoothMap: Proxy object connected
08-29 16:10:10.509  3922  3922 D MapProfile: Bluetooth service connected
08-29 16:10:10.509  3922  3922 D BluetoothMap: getConnectedDevices()
08-29 16:10:10.510  1353  1367 D BluetoothMap: onBluetoothStateChange: up=true
08-29 16:10:10.512  1353  1353 D BluetoothMap: Proxy object connected
,08-29 16:10:10.512  1353  1353 D MapProfile: Bluetooth service connected
08-29 16:10:10.512  1353  1353 D BluetoothMap: getConnectedDevices()
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:10.512  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:10.512  1353  2351 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 16:10:10.514  1353  1353 D BluetoothInputDevice: Proxy object connected
08-29 16:10:10.514  1353  1353 D HidProfile: Bluetooth service connected
08-29 16:10:10.514   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:10.514   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 16:10:10.515  1353  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:10:10.516   876   876 D BluetoothA2dp: Proxy object connected
,08-29 16:10:10.516  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:10.519  1353  1353 D BluetoothA2dp: Proxy object connected
08-29 16:10:10.519  1353  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:10.519  4149  4149 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:10:10.520  4149  4149 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:10.520  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:10.521  3922  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 16:10:10.521   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:10.521   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:10.521  3922  3933 D BluetoothMap: onBluetoothStateChange: up=true
08-29 16:10:10.521  3922  3932 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:10:10.522  4149  4149 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:10.522  1353  2351 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:10:10.523  1353  2099 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:10:10.524  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:10.524  4149  4149 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 16:10:10.525  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:10:10.525  1353  1353 D PanProfile: Bluetooth service connected
08-29 16:10:10.526   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 16:10:10.527  4149  4149 D ObexServerSockets: Succeed to create listening sockets 
,08-29 16:10:10.528  4149  4149 D ObexServerSockets0: startAccept()
08-29 16:10:10.528  4149  4149 D ObexServerSockets0: prepareForNewConnect()
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:10.528  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:10.529  4149  4149 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 16:10:10.530  4149  4149 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 16:10:10.530  4149  4149 D BluetoothMapService: onReceive
08-29 16:10:10.530  4149  4149 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 16:10:10.530  4149  4149 D BluetoothMapService: STATE_ON
08-29 16:10:10.530  3922  3922 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 16:10:10.531  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:10.531  4149  4188 D ObexServerSockets0: Accepting socket connection...
,08-29 16:10:10.531  4149  4187 D ObexServerSockets0: Accepting socket connection...
08-29 16:10:10.532  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.533  3922  3922 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 16:10:10.533  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:10.534  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:10.551  4149  4149 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 16:10:10.551  4149  4149 D ObexServerSockets0: prepareForNewConnect()
,08-29 16:10:10.555  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:10:10.558  3922  3922 D BluetoothA2dp: Proxy object connected
,08-29 16:10:10.562  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:10:10.566  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:10:10.568  1353  1353 D BluetoothPbap: Proxy object connected
,08-29 16:10:10.568  1353  1353 D PbapServerProfile: Bluetooth service connected
08-29 16:10:10.569  3922  3922 D BluetoothPbap: Proxy object connected
08-29 16:10:10.569  3922  3922 D PbapServerProfile: Bluetooth service connected
,08-29 16:10:10.577  4149  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:10.590  4149  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:10.590  4149  4196 I BtOppRfcommListener: Accept thread started.
,08-29 16:10:10.609   876   876 D BluetoothHeadset: Proxy object connected
,08-29 16:10:10.609  1353  2099 D BluetoothHeadset: Proxy object connected
08-29 16:10:10.609  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:10.609   876   876 D BluetoothHeadset: Proxy object connected
08-29 16:10:10.609  1961  2152 D BluetoothHeadset: Proxy object connected
08-29 16:10:10.609   876   876 D BluetoothHeadset: Proxy object connected
,08-29 16:10:10.614   876   893 D BluetoothHeadset: Proxy object connected
,08-29 16:10:10.621  1353  1364 D BluetoothHeadset: Proxy object connected
08-29 16:10:10.621  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:10.622   876   893 D BluetoothHeadset: Proxy object connected
,08-29 16:10:10.622   876   893 D BluetoothHeadset: Proxy object connected
,08-29 16:10:10.643  3922  3933 D BluetoothHeadset: Proxy object connected
08-29 16:10:10.643  3922  3922 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:13.927  4149  4161 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 16:10:13.928  4149  4161 D BluetoothAdapterProperties: Setting state to 13
,08-29 16:10:13.928  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 16:10:13.930  4149  4161 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 16:10:13.939  4149  4149 D BluetoothMapService: onReceive
,08-29 16:10:13.939  4149  4149 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 16:10:13.940  4149  4149 D BluetoothMapService: STATE_TURNING_OFF
,08-29 16:10:13.941  4149  4149 D BluetoothMapService: MAP Service closeService in
,08-29 16:10:13.941  4149  4149 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 16:10:13.941  4149  4149 D ObexServerSockets0: shutdown(block = true)
08-29 16:10:13.942  4149  4187 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 16:10:13.947  4149  4149 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 16:10:13.948  4149  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 16:10:13.948  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:13.949  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:13.949  4149  4173 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 16:10:13.950  4149  4149 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 16:10:13.951  4149  4149 I BtOppRfcommListener: stopping Accept Thread
08-29 16:10:13.951  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:13.951  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:13.952  4149  4196 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 16:10:13.958  4149  4165 D BluetoothAdapterProperties: Scan Mode:20
08-29 16:10:13.958  4149  4161 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:10:13.958  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 16:10:13.959  4149  4196 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 16:10:13.960  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:13.960  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:13.961  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 16:10:13.961  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:13.964  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:13.964  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:13.964  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:13.965  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 16:10:13.965  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:13.967  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:13.970  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:13.969  4149  4149 D HeadsetService: Received stop request...Stopping profile...
,08-29 16:10:13.971  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:13.972   876   876 D BluetoothHeadset: Proxy object disconnected
,08-29 16:10:13.972  1353  2351 D BluetoothHeadset: Proxy object disconnected
,08-29 16:10:13.972   876   876 D BluetoothHeadset: Proxy object disconnected
08-29 16:10:13.973  3922  3922 D DockEventReceiver: finishStartingService: stopping service
08-29 16:10:13.973  1961  2280 D BluetoothHeadset: Proxy object disconnected
,08-29 16:10:13.973  4149  4149 D A2dpService: Received stop request...Stopping profile...
08-29 16:10:13.973   876   876 D BluetoothHeadset: Proxy object disconnected
08-29 16:10:13.973  1353  1353 D HeadsetProfile: Bluetooth service disconnected
,08-29 16:10:13.974  4149  4180 D A2dpStateMachine: Exit Disconnected: -1
08-29 16:10:13.974  3922  3933 D BluetoothHeadset: Proxy object disconnected
08-29 16:10:13.977  3922  3922 D HeadsetProfile: Bluetooth service disconnected
,08-29 16:10:13.977  1353  1353 D BluetoothA2dp: Proxy object disconnected
08-29 16:10:13.978   876   876 D BluetoothA2dp: Proxy object disconnected
08-29 16:10:13.978  3922  3922 D BluetoothA2dp: Proxy object disconnected
08-29 16:10:13.978  4149  4149 D HidService: Received stop request...Stopping profile...
,08-29 16:10:13.978  4149  4149 D HidService: Stopping Bluetooth HidService
08-29 16:10:13.979  1353  1353 D BluetoothInputDevice: Proxy object disconnected
08-29 16:10:13.979  1353  1353 D HidProfile: Bluetooth service disconnected
08-29 16:10:13.979  3922  3922 D BluetoothInputDevice: Proxy object disconnected
,08-29 16:10:13.979  3922  3922 D HidProfile: Bluetooth service disconnected
08-29 16:10:13.981  4149  4149 D HealthService: Received stop request...Stopping profile...
,08-29 16:10:13.984  4149  4149 D PanService: Received stop request...Stopping profile...
,08-29 16:10:13.984  3922  3922 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 16:10:13.984  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 16:10:13.984  3922  3922 D PanProfile: Bluetooth service disconnected
08-29 16:10:13.985  1353  1353 D PanProfile: Bluetooth service disconnected
08-29 16:10:13.985  4149  4149 D BluetoothMapService: Received stop request...Stopping profile...
08-29 16:10:13.985  4149  4149 D BluetoothMapService: stop()
,08-29 16:10:13.985  4149  4149 D BluetoothMapAppObserver: deinitObservers()
,08-29 16:10:13.985  4149  4149 D BluetoothMapAppObserver: removeReceiver()
08-29 16:10:13.986  1353  1353 D BluetoothMap: Proxy object disconnected
08-29 16:10:13.986  3922  3922 D BluetoothMap: Proxy object disconnected
08-29 16:10:13.986  1353  1353 D MapProfile: Bluetooth service disconnected
,08-29 16:10:13.987  3922  3922 D MapProfile: Bluetooth service disconnected
,08-29 16:10:13.988  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.988  4149  4149 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:10:13.988  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:13.988  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:13.990  4149  4149 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 16:10:13.991  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:10:13.991  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:10:13.991  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 16:10:13.991  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:10:13.991  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 16:10:13.991  4149  4165 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 16:10:13.991  4149  4149 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
08-29 16:10:13.991  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.991  4149  4149 V BluetoothAdapterState: isTurningOn()=false
08-29 16:10:13.992  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:13.992  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:13.993  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 16:10:13.993  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:10:13.993  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.993  4149  4149 V BluetoothAdapterState: isTurningOn()=false
08-29 16:10:13.994  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:10:13.994  4149  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 16:10:13.994  4149  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 16:10:13.994  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false,
08-29 16:10:13.994  4149  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 16:10:13.994  4149  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 16:10:13.994  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 16:10:13.994  4149  4149 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 16:10:13.994  4149  4149 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 16:10:13.994  4149  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 16:10:13.994  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.994  4149  4149 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:10:13.994  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:13.995  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:13.995  4149  4149 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 16:10:13.995  4149  4165 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 16:10:13.995  4149  4149 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 16:10:13.996  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.996  4149  4149 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:10:13.996  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:13.996  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:13.996  4149  4149 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 16:10:13.996  4149  4149 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 16:10:13.997  4149  4149 D BluetoothMapService: MAP Service closeService in
08-29 16:10:13.997  4149  4149 V BluetoothAdapterState: isTurningOff()=true
08-29 16:10:13.997  4149  4149 V BluetoothAdapterState: isTurningOn()=false
,08-29 16:10:13.997  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:10:13.998  4149  4149 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:13.998  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 16:10:13.998  4149  4149 D BluetoothMapService: cleanup()
08-29 16:10:13.998  4149  4149 D BluetoothMapService: MAP Service closeService in,
,08-29 16:10:13.998  4149  4161 D BluetoothAdapterProperties: Setting state to 15
,08-29 16:10:13.998  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 16:10:13.999  4149  4161 I BluetoothAdapterState: Entering BleOnState
08-29 16:10:14.001  3922  3922 D BluetoothPbap: Proxy object disconnected
,08-29 16:10:14.001  3922  3922 D PbapServerProfile: Bluetooth service disconnected
,08-29 16:10:14.001  1961  1988 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:10:14.002  1353  1353 D BluetoothPbap: Proxy object disconnected
08-29 16:10:14.002  1353  1353 D PbapServerProfile: Bluetooth service disconnected
,08-29 16:10:14.003  3922  3933 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 16:10:14.004  1353  1364 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:10:14.004  3922  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:10:14.006  1353  2351 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 16:10:14.007   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:10:14.007   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:10:14.007  1353  2099 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 16:10:14.008  1353  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:10:14.008  3922  4202 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 16:10:14.009   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 16:10:14.009   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 16:10:14.009  3922  3933 D BluetoothMap: onBluetoothStateChange: up=false
08-29 16:10:14.010  3922  3932 D BluetoothPan: onBluetoothStateChange on: false
,08-29 16:10:14.010  3922  4202 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 16:10:14.011  1353  1364 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 16:10:14.011  1353  2351 D BluetoothPan: onBluetoothStateChange on: false
08-29 16:10:14.012  4149  4161 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 16:10:14.012  4149  4161 D BluetoothAdapterProperties: Setting state to 16
,08-29 16:10:14.012  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 16:10:14.013  4149  4161 D BluetoothAdapterProperties: onBleDisable
,08-29 16:10:14.014  4149  4162 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 16:10:14.014  4149  4161 I BluetoothAdapterState: Entering PendingCommandState
08-29 16:10:14.014  4149  4171 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 16:10:14.014  4149  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 16:10:14.015  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:14.017  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:14.018  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:10:14.020  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:14.021  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:14.021  4149  4165 D BluetoothAdapterProperties: Scan Mode:20
08-29 16:10:14.022  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:14.023  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:14.027  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 16:10:14.032  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:10:14.218  4149  4165 I bt_hci  : shut_down
,08-29 16:10:14.238  4149  4169 D bt_hwcfg: hw_epilog_process
,08-29 16:10:14.239  4149  4169 I bt_vendor: low_power_mode_cb
,08-29 16:10:14.255  4149  4169 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 16:10:14.256  4149  4169 I bt_vendor: epilog_cb
,08-29 16:10:14.256  4149  4169 I bt_hci  : epilog_finished_callback
,08-29 16:10:14.264  4149  4165 I bt_hci_h4: hal_close
,08-29 16:10:14.266  4149  4165 I bt_userial_vendor: device fd = 51 close
,08-29 16:10:14.397  4149  4162 D bt_stack_manager: event_shut_down_stack finished.
,08-29 16:10:14.398  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 16:10:14.404  4149  4149 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 16:10:14.404  4149  4161 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 16:10:14.406  4149  4149 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 16:10:14.406  4149  4149 D BtGatt.GattService: stop()
08-29 16:10:14.407  4149  4149 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 16:10:14.412  4149  4149 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:14.412  4149  4149 V BluetoothAdapterState: isTurningOn()=false
08-29 16:10:14.413  4149  4149 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:14.413  4149  4149 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 16:10:14.414  4149  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 16:10:14.414  4149  4161 D BluetoothAdapterProperties: Setting state to 10
08-29 16:10:14.415  4149  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 16:10:14.416  4149  4161 I BluetoothAdapterState: Entering OffState
,08-29 16:10:14.418   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 16:10:14.464  4149  4149 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 16:10:14.464  4149  4149 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 16:10:14.465  4149  4162 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 16:10:14.465  4149  4149 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 16:10:14.470  4149  4162 D bt_stack_manager: event_clean_up_stack finished.
,08-29 16:10:14.472  4149  4149 I art     : System.exit called, status: 0
,08-29 16:10:14.472  4149  4149 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 16:10:14.530   876  1383 I ActivityManager: Process com.android.bluetooth (pid 4149) has died
,08-29 16:10:18.925  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:10:18.926  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:18.931  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:18.931  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@154eaf5 removed from the list
08-29 16:10:18.932  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:18.932  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:18.932  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:18.935  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:18.936  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e11d6fb added. We now have 4 listener(s)
08-29 16:10:18.936  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:10:18.937  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:18.938  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e11d6fb removed from the list
08-29 16:10:18.938  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:18.938  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:18.939  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:18.941  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:18.941  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3b3318 added. We now have 4 listener(s)
08-29 16:10:18.942  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:10:23.955  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:24.006   876   893 I ActivityManager: Start proc 4207:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 16:10:24.139  4207  4207 D AdapterServiceConfig: Adding HeadsetService
,08-29 16:10:24.139  4207  4207 D AdapterServiceConfig: Adding A2dpService
08-29 16:10:24.140  4207  4207 D AdapterServiceConfig: Adding HidService
,08-29 16:10:24.141  4207  4207 D AdapterServiceConfig: Adding HealthService
08-29 16:10:24.142  4207  4207 D AdapterServiceConfig: Adding PanService
,08-29 16:10:24.142  4207  4207 D AdapterServiceConfig: Adding GattService
,08-29 16:10:24.143  4207  4207 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 16:10:24.180   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4462108:true
08-29 16:10:24.181  4207  4207 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 16:10:24.186  4207  4207 I bt_bluedroid: init
,08-29 16:10:24.187  4207  4219 I BluetoothAdapterState: Entering OffState
,08-29 16:10:24.192  4207  4220 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 16:10:24.192  4207  4220 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 16:10:24.192  4207  4220 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 16:10:24.192  4207  4220 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 16:10:24.194  4207  4207 I bt_bluedroid: get_profile_interface socket
,08-29 16:10:24.197  4207  4223 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 16:10:24.198  4207  4223 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:10:24.201  4207  4207 I bt_bluedroid: get_profile_interface sdp
,08-29 16:10:24.208  4207  4218 I bt_bluedroid: config_hci_snoop_log
,08-29 16:10:24.212   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 16:10:24.225  4207  4219 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 16:10:24.226  4207  4219 D BluetoothAdapterProperties: Setting state to 14
,08-29 16:10:24.226  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 16:10:24.231  4207  4219 D BluetoothBondStateMachine: make
,08-29 16:10:24.239  4207  4224 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 16:10:24.249  4207  4219 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:10:24.249  4207  4207 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 16:10:24.258  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:24.259  4207  4207 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 16:10:24.260  4207  4207 D BtGatt.GattService: Received start request. Starting profile...
,08-29 16:10:24.260  4207  4207 D BtGatt.GattService: start()
,08-29 16:10:24.260  4207  4207 I bt_bluedroid: get_profile_interface gatt
08-29 16:10:24.261  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:24.261  4207  4207 D BtGatt.AdvertiseManager: advertise manager created
,08-29 16:10:24.272  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:24.272  4207  4207 V BluetoothAdapterState: isTurningOn()=false
08-29 16:10:24.272  4207  4207 V BluetoothAdapterState: isBleTurningOn()=true
08-29 16:10:24.272  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:24.273  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 16:10:24.273  4207  4219 I bt_bluedroid: enable
08-29 16:10:24.274  4207  4220 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 16:10:24.275  4207  4220 I bt_hci  : start_up
,08-29 16:10:24.298  4207  4220 I bt_vendor: alloc value 0xb3a4a189
,08-29 16:10:24.298  4207  4220 I bt_vendor: init
08-29 16:10:24.299  4207  4220 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 16:10:24.299  4207  4220 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 16:10:24.408  4207  4220 D bt_hci  : start_up starting async portion
,08-29 16:10:24.409  4207  4227 I bt_hci  : event_finish_startup
08-29 16:10:24.409  4207  4227 I bt_hci_h4: hal_open
08-29 16:10:24.409  4207  4227 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 16:10:24.421  4207  4227 I bt_userial_vendor: device fd = 51 open
,08-29 16:10:24.450  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:10:24.482  4207  4227 D bt_hwcfg: Chipset BCM4354A2
08-29 16:10:24.483  4207  4227 D bt_hwcfg: Target name = [BCM4354A2]
08-29 16:10:24.483  4207  4227 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 16:10:25.150  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 16:10:25.151  4207  4227 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 16:10:25.152  4207  4227 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 16:10:25.268  4207  4227 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 16:10:25.270  4207  4227 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 16:10:25.299  4207  4227 I bt_hwcfg: vendor lib fwcfg completed
,08-29 16:10:25.300  4207  4227 I bt_vendor: firmware callback
,08-29 16:10:25.300  4207  4227 I bt_hci  : firmware_config_callback
,08-29 16:10:25.311  4207  4229 I bt_btu  : btu_task pending for preload complete event
08-29 16:10:25.311  4207  4229 I bt_btu_task: Bluetooth chip preload is complete
08-29 16:10:25.311  4207  4229 I bt_btu  : btu_task received preload complete event
,08-29 16:10:25.321  4207  4229 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 16:10:25.322  4207  4229 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 16:10:25.322  4207  4229 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 16:10:25.322  4207  4229 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 16:10:25.323  4207  4229 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 16:10:25.323  4207  4229 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 16:10:25.323  4207  4229 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 16:10:25.323  4207  4229 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 16:10:25.323  4207  4229 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 16:10:25.324  4207  4229 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 16:10:25.324  4207  4229 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 16:10:25.324  4207  4229 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 16:10:25.324  4207  4229 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 16:10:25.325  4207  4229 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 16:10:25.325  4207  4229 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 16:10:25.458  4207  4229 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,08-29 16:10:25.459  4207  4229 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,08-29 16:10:25.469  4207  4223 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 16:10:25.471  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 16:10:25.472  4207  4223 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 16:10:25.474  4207  4223 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 16:10:25.477  4207  4223 D BluetoothAdapterProperties: Scan Mode:20
,08-29 16:10:25.478  4207  4223 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 16:10:25.478  4207  4223 D bt_hci  : do_postload posting postload work item
,08-29 16:10:25.479  4207  4227 I bt_hci  : event_postload
,08-29 16:10:25.479  4207  4227 I bt_vendor: sco_config_cb
,08-29 16:10:25.480  4207  4227 I bt_hci  : sco_config_callback postload finished.
08-29 16:10:25.481  4207  4223 D bt_bte_conf: Device ID record 1 : primary
08-29 16:10:25.481  4207  4223 D bt_bte_conf:   vendorId            = 000f
08-29 16:10:25.481  4207  4223 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 16:10:25.482  4207  4223 D bt_bte_conf:   product             = 1200
,08-29 16:10:25.482  4207  4223 D bt_bte_conf:   version             = 1436
,08-29 16:10:25.482  4207  4223 D bt_bte_conf:   clientExecutableURL = 
08-29 16:10:25.482  4207  4223 D bt_bte_conf:   serviceDescription  = ,
08-29 16:10:25.482  4207  4223 D bt_bte_conf:   documentationURL    = 
08-29 16:10:25.483  4207  4223 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 16:10:25.483  4207  4220 D bt_stack_manager: event_start_up_stack finished
,08-29 16:10:25.485  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:25.486  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 16:10:25.487  4207  4219 D BluetoothAdapterProperties: Setting state to 15
08-29 16:10:25.487  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 16:10:25.488  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:25.490  4207  4219 I BluetoothAdapterState: Entering BleOnState
08-29 16:10:25.492  4207  4227 I bt_vendor: low_power_mode_cb
08-29 16:10:25.494  4207  4219 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 16:10:25.494  4207  4219 D BluetoothAdapterProperties: Setting state to 11
,08-29 16:10:25.496  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 16:10:25.512  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:25.513  4207  4207 D HeadsetService: Received start request. Starting profile...
08-29 16:10:25.516  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:25.518  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:25.520  4207  4207 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 16:10:25.520  4207  4207 D HeadsetStateMachine: make
,08-29 16:10:25.524  4207  4219 I BluetoothAdapterState: Entering PendingCommandState
,08-29 16:10:25.531  4207  4207 D HeadsetStateMachine: max_hf_connections = 1
,08-29 16:10:25.531  4207  4207 I bt_bluedroid: get_profile_interface handsfree
,08-29 16:10:25.532  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 16:10:25.532  4207  4223 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 16:10:25.537  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:25.537  4207  4207 D A2dpService: Received start request. Starting profile...
,08-29 16:10:25.538  4207  4207 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 16:10:25.538  4207  4207 I bt_bluedroid: get_profile_interface avrcp
,08-29 16:10:25.543  4207  4207 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 16:10:25.543  4207  4207 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 16:10:25.543  4207  4207 D A2dpStateMachine: make
,08-29 16:10:25.544  4207  4207 I bt_bluedroid: get_profile_interface a2dp
,08-29 16:10:25.545  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 16:10:25.546  4207  4207 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 16:10:25.547  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:25.547  4207  4238 D A2dpStateMachine: Enter Disconnected: -2
,08-29 16:10:25.548  4207  4207 D HidService: Received start request. Starting profile...
,08-29 16:10:25.548  4207  4207 I bt_bluedroid: get_profile_interface hidhost
08-29 16:10:25.548  4207  4207 D HidService: setHidService(): set to: null
,08-29 16:10:25.548  4207  4223 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
08-29 16:10:25.548  4207  4223 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 16:10:25.548  4207  4207 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 16:10:25.549  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:25.550  4207  4207 D HealthService: Received start request. Starting profile...
08-29 16:10:25.551  4207  4207 I bt_bluedroid: get_profile_interface health
08-29 16:10:25.552  4207  4207 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
08-29 16:10:25.553  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:25.554  4207  4207 D PanService: Received start request. Starting profile...
08-29 16:10:25.554  4207  4207 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 16:10:25.554  4207  4207 I bt_bluedroid: get_profile_interface pan
08-29 16:10:25.554  4207  4223 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 16:10:25.554  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 16:10:25.556  4207  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
08-29 16:10:25.557  4207  4207 D BluetoothMapService: Received start request. Starting profile...
,08-29 16:10:25.557  4207  4207 D BluetoothMapService: start()
08-29 16:10:25.559  4207  4207 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 16:10:25.560  4207  4207 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 16:10:25.560  4207  4207 D BluetoothMapAppObserver: createReceiver()
,08-29 16:10:25.562  4207  4207 D BluetoothMapAppObserver: initObservers()
,08-29 16:10:25.562  4207  4207 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 16:10:25.569  4207  4207 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:25.569  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.569  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:25.569  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:25.572  4207  4236 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:25.572  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isTurningOff()=false
,08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
08-29 16:10:25.573  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:25.574  4207  4207 V BluetoothAdapterState: isTurningOff()=false
08-29 16:10:25.574  4207  4207 V BluetoothAdapterState: isTurningOn()=true
08-29 16:10:25.574  4207  4207 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 16:10:25.574  4207  4207 V BluetoothAdapterState: isBleTurningOff()=false
08-29 16:10:25.574  4207  4219 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 16:10:25.574  4207  4219 D BluetoothAdapterProperties: ScanMode =  20
08-29 16:10:25.574  4207  4219 D BluetoothAdapterProperties: State =  11
08-29 16:10:25.576  4207  4223 D BluetoothAdapterProperties: Scan Mode:21,
08-29 16:10:25.576  4207  4219 D BluetoothAdapterProperties: Setting state to 12
08-29 16:10:25.576  4207  4219 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 16:10:25.576  4207  4223 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 16:10:25.576  1961  1979 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:25.576  4207  4219 I BluetoothAdapterState: Entering OnState
08-29 16:10:25.577  3922  3932 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:10:25.579  1353  1364 D BluetoothMap: onBluetoothStateChange: up=true
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:25.579  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:25.580  3922  4202 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 16:10:25.581  1353  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 16:10:25.581  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:25.581  1353  1353 D BluetoothMap: Proxy object connected
08-29 16:10:25.581  1353  1353 D MapProfile: Bluetooth service connected
08-29 16:10:25.581  1353  1353 D BluetoothMap: getConnectedDevices()
08-29 16:10:25.584   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 16:10:25.584   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:25.584  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 16:10:25.585  1353  2351 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 16:10:25.585  1353  1353 D BluetoothInputDevice: Proxy object connected
08-29 16:10:25.585  1353  1353 D HidProfile: Bluetooth service connected
,08-29 16:10:25.585   876   876 D BluetoothA2dp: Proxy object connected
08-29 16:10:25.586  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 16:10:25.587  1353  1353 D BluetoothA2dp: Proxy object connected
08-29 16:10:25.587  1353  2099 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:25.587  3922  3933 D BluetoothInputDevice: onBluetoothStateChange: up=true,
08-29 16:10:25.588  4207  4207 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:10:25.589  4207  4207 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 16:10:25.589   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:25.589   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 16:10:25.589  3922  4202 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 16:10:25.590  4207  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:25.591  3922  3933 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:10:25.592  4207  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:25.592  3922  3932 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 16:10:25.593  4207  4207 D ObexServerSockets: Succeed to create listening sockets 
,08-29 16:10:25.593  4207  4207 D ObexServerSockets0: startAccept()
,08-29 16:10:25.594  4207  4207 D ObexServerSockets0: prepareForNewConnect()
08-29 16:10:25.594  1353  1364 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 16:10:25.595  4207  4207 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 16:10:25.596  4207  4207 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 16:10:25.596  4207  4245 D ObexServerSockets0: Accepting socket connection...
,08-29 16:10:25.596  1353  1367 D BluetoothPan: onBluetoothStateChange on: true
08-29 16:10:25.597  4207  4246 D ObexServerSockets0: Accepting socket connection...
08-29 16:10:25.598  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 16:10:25.598  1353  1353 D PanProfile: Bluetooth service connected
08-29 16:10:25.600  4207  4207 D BluetoothMapService: onReceive
08-29 16:10:25.600  4207  4207 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 16:10:25.600  4207  4207 D BluetoothMapService: STATE_ON
08-29 16:10:25.600   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 16:10:25.601  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:25.599  3922  3922 D BluetoothInputDevice: Proxy object connected
08-29 16:10:25.601  3922  3922 D HidProfile: Bluetooth service connected
08-29 16:10:25.602  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:25.606  3922  3922 D BluetoothMap: Proxy object connected
,08-29 16:10:25.606  3922  3922 D MapProfile: Bluetooth service connected
08-29 16:10:25.606  3922  3922 D BluetoothMap: getConnectedDevices()
08-29 16:10:25.607  3922  3922 D BluetoothA2dp: Proxy object connected
,08-29 16:10:25.609  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 16:10:25.609  3922  3922 D PanProfile: Bluetooth service connected
,08-29 16:10:25.612  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 16:10:25.619  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 16:10:25.620  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,08-29 16:10:25.626  3922  3922 D BluetoothPbap: Proxy object connected
,08-29 16:10:25.626  3922  3922 D PbapServerProfile: Bluetooth service connected
08-29 16:10:25.626  4207  4207 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 16:10:25.626  4207  4207 D ObexServerSockets0: prepareForNewConnect()
,08-29 16:10:25.628  1353  1353 D BluetoothPbap: Proxy object connected
,08-29 16:10:25.628  1353  1353 D PbapServerProfile: Bluetooth service connected
,08-29 16:10:25.636  4207  4250 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:25.650  4207  4254 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:25.652  4207  4254 I BtOppRfcommListener: Accept thread started.
,08-29 16:10:25.677   876   876 D BluetoothHeadset: Proxy object connected
,08-29 16:10:25.678  1353  1367 D BluetoothHeadset: Proxy object connected
08-29 16:10:25.678  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:25.678   876   876 D BluetoothHeadset: Proxy object connected
08-29 16:10:25.679  1961  2280 D BluetoothHeadset: Proxy object connected
,08-29 16:10:25.679   876   876 D BluetoothHeadset: Proxy object connected
,08-29 16:10:25.679  3922  3932 D BluetoothHeadset: Proxy object connected
08-29 16:10:25.680  3922  3922 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:25.681  3922  3933 D BluetoothHeadset: Proxy object connected
08-29 16:10:25.683  3922  3922 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:25.685   876   893 D BluetoothHeadset: Proxy object connected
,08-29 16:10:25.688  1353  2099 D BluetoothHeadset: Proxy object connected
,08-29 16:10:25.688  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-29 16:10:25.689   876   893 D BluetoothHeadset: Proxy object connected
08-29 16:10:25.690   876   893 D BluetoothHeadset: Proxy object connected
,08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:28.975  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:28.982  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:28.983  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:10:28.983  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3b3318 removed from the list
08-29 16:10:28.984  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:28.984  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:28.984  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:28.987  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:28.987  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5564171 added. We now have 4 listener(s)
08-29 16:10:28.987  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:10:28.991   876  1967 D WifiService: setWifiEnabled: false pid=3836, uid=10000,
08-29 16:10:28.992   876  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:10:31.323  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:10:31.331  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:10:31.334  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:10:31.378  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 16:10:31.378  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 16:10:31.379  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:10:31.379  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:31.415  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 16:10:31.416  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 16:10:31.416  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-29 16:10:32.826  1876  1927 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-29 16:10:32.826  1876  1927 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 16:10:32.857  1503  1503 I ConfigService: onCreate
,08-29 16:10:34.005  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:34.006   876  2011 D WifiService: setWifiEnabled: true pid=3836, uid=10000
,08-29 16:10:34.006   876  2011 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 16:10:34.023   876  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:34.041  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:34.046  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 16:10:34.051  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 16:10:34.054  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 16:10:34.069   876  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-29 16:10:34.070   876  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 16:10:34.071   876  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 16:10:34.071   876  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 16:10:34.072   876  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 16:10:34.072   876  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 16:10:34.072   876  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 16:10:34.090   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:10:34.090   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 16:10:34.093   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:34.143   876  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-29 16:10:34.143   876  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 16:10:34.149   876  1308 E native  : do suspend true
,08-29 16:10:34.165   876  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 16:10:34.166   876  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 16:10:34.179   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:10:35.592   876  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 16:10:35.741   876  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.12 rxSuccessRate=6.44 delta 1000 -> 994
,08-29 16:10:35.742   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 16:10:35.743   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:35.762   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 16:10:35.835   876  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 16:10:35.838  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 16:10:36.281  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 16:10:36.323  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 16:10:36.324  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 16:10:36.334   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 16:10:36.351   876  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:10:36.352   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 16:10:36.354   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:36.383   876  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 16:10:36.408   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:36.410   876  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 16:10:36.424   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 16:10:36.465   876  4266 D DhcpClient: Receive thread started
,08-29 16:10:36.548   876  1308 E native  : do suspend false
,08-29 16:10:36.562   876  1903 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 16:10:36.574   876  4266 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-29 16:10:36.575   876  1903 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-29 16:10:36.578   876  1903 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 16:10:36.593   876  4266 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 16:10:36.594   876  1903 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 16:10:36.598   372   874 D CommandListener: Setting iface cfg
,08-29 16:10:36.601   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 16:10:36.606   876  1308 E native  : do suspend true
,08-29 16:10:36.607   876  1903 D DhcpClient: Scheduling renewal in 86399s
,08-29 16:10:36.618   876  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 16:10:36.619   876  1308 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 16:10:36.619   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 16:10:36.620   876  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 16:10:36.621   876  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 16:10:36.703   876  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 16:10:36.703   876  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 16:10:36.706   876  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 16:10:36.708   876  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 16:10:36.711   876  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 16:10:36.727   876  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 16:10:36.736   876  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 16:10:36.736   876  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 16:10:36.737   876  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 16:10:36.737   876  1310 D ConnectivityService:    accepting network in place of null,
,08-29 16:10:36.737   876  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 16:10:36.738   876  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 16:10:36.739   876  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 16:10:36.749   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213956, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:10:36.773   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:36.804   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 16:10:36.813   876  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 16:10:36.813   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:36.821   876  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 16:10:36.824   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:36.843  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:36.847  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:36.853  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:36.855  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:36.859  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 16:10:36.866  1716  1716 D SystemUpdateService: onCreate
,08-29 16:10:36.871  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 16:10:36.883  1716  4275 I SystemUpdateService: active receiver: enabled
,08-29 16:10:36.891  1716  4275 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 16:10:36.892  1716  4275 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 16:10:36.892  1716  4275 I SystemUpdateService: now status is 0 (complete)
08-29 16:10:36.893  1716  4275 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 16:10:36.893  1716  4275 I SystemUpdateService: file has been verified
08-29 16:10:36.893  1716  4275 I SystemUpdateService: OTA package size = 12249756
,08-29 16:10:36.902  3753  4276 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:10:36.903  1716  4275 I SystemUpdateService: showing system update notification
,08-29 16:10:36.922  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:10:36.925  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:10:36.933  3780  4277 V GoogleAuthProtoRequest: [320] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:10:36.949  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 16:10:36.951  1716  2457 I iu.UploadsManager: num queued entries: 0
,08-29 16:10:36.951  1716  2457 I iu.UploadsManager: num updated entries: 0
,08-29 16:10:36.951  1716  2457 I iu.SyncManager: NEXT; no task
,08-29 16:10:36.959  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 16:10:36.960  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 16:10:36.962  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 16:10:36.973  1716  4278 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 16:10:36.973  1716  4278 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 16:10:36.974  4002  4002 D SprintDMHelper: simOperator: 
,08-29 16:10:36.974  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 16:10:36.985  1716  4278 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:10:37.055  3753  4284 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:10:37.072  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:10:37.072  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:10:37.072  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:37.072  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:37.080  1716  1716 D SystemUpdateService: onDestroy
,08-29 16:10:37.107  1503  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 16:10:37.107  1503  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-29 16:10:37.107  1503  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:37.107  1503  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 16:10:37.108  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 16:10:37.108  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:10:37.108  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:10:37.108  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:37.119  3753  4284 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:10:37.120  3753  4276 E BooksSync: Soft error
08-29 16:10:37.120  3753  4276 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:10:37.120  3753  4276 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:10:37.120  3753  4276 E BooksSync: Sync error
08-29 16:10:37.120  3753  4276 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:10:37.120  3753  4276 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:10:37.120  3753  4276 I BooksSync: Finished books sync
,08-29 16:10:37.130   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 211440, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:10:37.139  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager,
08-29 16:10:37.140  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 16:10:37.140  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:10:37.140  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:10:37.153  3780  4277 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:10:37.171  1716  4278 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-29 16:10:37.813   876  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 16:10:37.931  1503  1503 I ConfigService: onDestroy
,08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:39.036  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:39.043  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:39.044  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:39.045  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5564171 removed from the list
08-29 16:10:39.045  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:39.045  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:39.045  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:39.057  3836  4289 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-29 16:10:39.058  3836  4289 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 16:10:41.817   876  4264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.142,2a00:1450:4001:802::200e
,08-29 16:10:41.961   876  4264 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 14:10:42 GMT], X-Android-Received-Millis=[1472479841959], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472479841869]}
,08-29 16:10:41.965   876  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 16:10:41.967   876  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 16:10:41.971   876  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 16:10:41.978   876  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 16:10:42.064  3836  4291 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-29 16:10:42.066  3836  4289 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 16:10:42.066  3836  4291 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:10:42.067  3836  4289 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:10:42.068  3836  4289 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:10:42.068  3836  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:10:42.069  3836  4291 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:10:42.069  3836  4289 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:10:42.072  3836  4289 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 16:10:42.072  3836  4291 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 16:10:42.076  3836  4294 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Sender)
,08-29 16:10:42.080  3836  4293 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Sender)
,08-29 16:10:42.084  3836  4295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
,08-29 16:10:42.085  3836  4295 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
,08-29 16:10:42.085  3836  4295 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-29 16:10:42.085  3836  4295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 16:10:42.086  3836  4296 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
08-29 16:10:42.088  3836  4296 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
,08-29 16:10:42.088  3836  4296 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 16:10:42.088  3836  4296 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 16:10:42.164  3972  4282 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 16:10:44.740   876  1310 D ConnectivityService: handlePromptUnvalidated 102
,08-29 16:10:45.065  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 16:10:45.067  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 16:10:45.075  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b358e5d Bundle[{}]
,08-29 16:10:45.075  3836  3887 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 16:10:45.076  3836  3887 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 16:10:45.076  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 16:10:45.076  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 16:10:45.077  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 16:10:45.077  3836  3887 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 16:10:45.081  3836  3887 I System.out: Running OutgoingSocketThread
,08-29 16:10:45.085  3836  4299 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 16:10:45.085  3836  4299 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 16:10:48.094  3836  4300 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-29 16:10:48.095  3836  4300 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:10:48.095  3836  4300 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:10:48.096  3836  4299 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-29 16:10:48.096  3836  4299 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 16:10:48.096  3836  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:10:48.098  3836  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:10:48.098  3836  4300 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 16:10:48.102  3836  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: OutgoingSocketThread/Sender)
08-29 16:10:48.102  3836  4299 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 16:10:48.108  3836  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: IncomingSocketThread/Sender)
,08-29 16:10:48.110  3836  4300 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 16:10:48.112  3836  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
,08-29 16:10:48.114  3836  4304 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
08-29 16:10:48.114  3836  4304 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-29 16:10:48.115  3836  4304 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-29 16:10:48.115  3836  4305 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Receiver)
08-29 16:10:48.117  3836  4305 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: IncomingSocketThread/Receiver)
08-29 16:10:48.117  3836  4305 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 16:10:48.117  3836  4305 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-29 16:10:51.097  3836  3887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-29 16:10:51.099  3836  3887 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 16:10:51.100  3836  3887 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 454)
,08-29 16:10:51.105  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:10:51.105  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c107b56 added. We now have 3 listener(s)
08-29 16:10:51.107  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:10:51.107  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:10:51.107  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:10:51.107  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:51.107  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ce7d7 added. We now have 4 listener(s)
,08-29 16:10:51.108  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:10:51.108  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 16:10:51.112  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:51.123  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:51.128  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:51.128  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:10:51.128  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:10:51.129  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:10:51.129  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:10:51.129  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:51.129  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:51.129  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:10:51.129  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:10:51.129  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c107b56 removed from the list
08-29 16:10:51.129  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:51.129  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ce7d7 removed from the list
08-29 16:10:51.134  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:51.137  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:51.137  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:51.138  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:51.140  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:51.140  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:51.144  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:10:51.144  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:51.145  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:51.145  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ce7d7 not in the list
,08-29 16:10:51.145  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:51.146  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:51.149  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:51.149  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:10:51.149  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:51.150  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ce7d7 not in the list
08-29 16:10:51.150  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:51.150  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:51.150  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:51.151  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c107b56 not in the list
,08-29 16:10:51.153  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:10:51.153  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c83ad added. We now have 3 listener(s)
,08-29 16:10:51.159  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:10:51.159  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:10:51.160  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:10:51.160  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 16:10:51.161  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b0f6e2 added. We now have 4 listener(s)
08-29 16:10:51.161  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:10:51.162  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:10:51.171  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:51.180  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:51.184  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:51.184  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:10:51.184  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 16:10:51.184  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:10:51.184  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:10:51.184  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:10:51.185  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:10:51.188  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:51.190  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 16:10:51.191  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:51.191  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 16:10:51.201  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:10:51.202  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:10:51.202  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:10:51.210  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 16:10:51.211  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:10:51.211  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 16:10:51.214  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:10:51.222  4207  4244 D BtGatt.GattService: registerClient() - UUID=b5036a30-5fd1-4702-96e7-82dbbe5d6e0b
,08-29 16:10:51.224  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=b5036a30-5fd1-4702-96e7-82dbbe5d6e0b, clientIf=5
,08-29 16:10:51.226  3836  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:10:51.228  4207  4217 D BtGatt.GattService: start scan with filters
,08-29 16:10:51.236  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 16:10:51.236  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 16:10:51.236  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:10:51.237  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:10:51.237  4207  4226 D BtGatt.ScanManager: handling starting scan
,08-29 16:10:51.241  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:10:51.241  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 16:10:51.242  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:10:51.243  4207  4226 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dcb0121
,08-29 16:10:51.245  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:10:51.249  3836  3887 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 16:10:51.250  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 16:10:51.250  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:10:51.250  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:51.250  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:10:51.250  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:10:51.250  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 16:10:51.250  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:10:51.250  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:10:51.251  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:10:51.251  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 16:10:51.252  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:10:51.253  4207  4217 D BtGatt.GattService: stopScan() - queue size =1
08-29 16:10:51.254  4207  4223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 16:10:51.254  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:51.255  4207  4226 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:10:51.260  4207  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:10:51.261  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:10:51.261  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:10:51.261  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 16:10:51.262  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 16:10:51.262  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:10:51.264  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:10:51.264  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 16:10:51.264  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:51.264  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 16:10:51.264  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:10:51.264  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:10:51.265  4207  4226 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:10:51.265  4207  4226 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 16:10:51.266  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:10:51.267  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:10:51.268  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:10:51.268  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:10:51.277  4207  4223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 16:10:51.277  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:51.287  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 16:10:51.287  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:51.300  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 16:10:51.300  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:10:51.300  4207  4226 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:10:51.308  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 16:10:51.308  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:10:51.308  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:10:51.318  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 16:10:51.318  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:51.769  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:10:51.769  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:10:51.770  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:10:54.269  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:10:54.270  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:10:54.270  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 16:10:54.271  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:54.271  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:10:54.272  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:10:54.272  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 16:10:54.272  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c83ad removed from the list
,08-29 16:10:54.273  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:10:54.273  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b0f6e2 removed from the list
,08-29 16:10:54.273  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 16:10:54.273  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:54.275  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:54.275  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:54.278  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:10:54.279  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:54.279  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:54.280  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b0f6e2 not in the list
08-29 16:10:54.280  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:10:54.280  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:54.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:54.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:10:54.284  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:10:54.285  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b0f6e2 not in the list
,08-29 16:10:54.285  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:54.286  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:54.286  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:54.286  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c83ad not in the list
,08-29 16:10:54.287  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 16:10:54.287  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f66facf added. We now have 3 listener(s)
,08-29 16:10:54.289  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:10:54.289  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:10:54.289  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 16:10:54.289  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:54.289  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5e0c5c added. We now have 4 listener(s)
08-29 16:10:54.290  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:10:54.290  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:10:54.293  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:54.299  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 16:10:54.302  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:54.302  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:10:54.304  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:10:54.305  3836  3887 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-29 16:10:54.305  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 16:10:54.306  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:54.308  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 16:10:54.308  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-29 16:10:54.308  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 16:10:54.308  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:10:54.309  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 16:10:54.309  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 16:10:54.309  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 16:10:54.310  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 16:10:54.310  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-29 16:10:54.310  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:10:54.310  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 16:10:54.312  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:10:54.313  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 16:10:54.317  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 16:10:54.317  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 16:10:54.318  3836  4307 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 16:10:54.320  3836  4307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 16:10:54.323  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:10:54.324  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:10:54.324  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:10:54.327  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 16:10:54.327  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:10:54.328  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-29 16:10:54.329  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 16:10:54.329  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 16:10:54.329  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 16:10:54.330  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:10:54.334  4207  4217 D BtGatt.GattService: registerClient() - UUID=a2cfafd9-a19e-4e3d-aaad-f67d954fd6fa
,08-29 16:10:54.335  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=a2cfafd9-a19e-4e3d-aaad-f67d954fd6fa, clientIf=5
,08-29 16:10:54.335  3836  3848 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 16:10:54.337  4207  4225 D BtGatt.AdvertiseManager: message : 0
,08-29 16:10:54.341  4207  4225 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 16:10:54.354  4207  4223 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 16:10:54.364  4207  4223 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 16:10:54.366  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 16:10:54.367  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:10:54.372  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:10:54.375  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 16:10:54.375  3836  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 16:10:54.375  3836  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 16:10:54.375  3836  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 16:10:54.376  3836  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-29 16:10:54.376  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 16:10:54.379  3836  3836 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 16:10:54.379  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 16:10:54.381  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 16:10:54.381  3836  3887 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:10:54.880  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 16:10:57.383  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:10:57.383  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 16:10:57.384  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:10:57.384  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 16:10:57.384  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 16:10:57.384  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 16:10:57.385  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 16:10:57.386  3836  3887 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 16:10:57.386  3836  4307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 16:10:57.386  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 16:10:57.386  3836  4307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 16:10:57.386  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:10:57.387  3836  4307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 16:10:57.387  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 16:10:57.387  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 16:10:57.387  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 16:10:57.389  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 16:10:57.390  3836  3887 D BluetoothAdapter: STATE_ON
08-29 16:10:57.390  3836  3887 D BluetoothLeScanner: could not find callback wrapper
08-29 16:10:57.390  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:10:57.391  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 16:10:57.393  4207  4225 D BtGatt.AdvertiseManager: message : 1
08-29 16:10:57.394  4207  4225 D BtGatt.AdvertiseManager: stop advertise for client 5
08-29 16:10:57.405  4207  4223 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 16:10:57.405  4207  4223 D BtGatt.GattService: Client app is not null!
08-29 16:10:57.406  4207  4244 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 16:10:57.407  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 16:10:57.407  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 16:10:57.408  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 16:10:57.408  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 16:10:57.408  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 16:10:57.411  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-29 16:10:57.411  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-29 16:10:57.412  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 16:10:57.413  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,08-29 16:10:57.416  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:10:57.416  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 16:10:57.416  3836  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 16:10:57.417  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 16:10:57.417  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:10:57.417  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 16:10:57.418  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:57.418  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:10:57.419  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:10:57.419  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:10:57.419  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f66facf removed from the list
08-29 16:10:57.419  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:57.420  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5e0c5c removed from the list
,08-29 16:10:57.420  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:10:57.421  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:57.421  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:57.422  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 16:10:57.424  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:10:57.424  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:57.425  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:10:57.425  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5e0c5c not in the list
08-29 16:10:57.425  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 16:10:57.425  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:10:57.426  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:10:57.427  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:10:57.427  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:10:57.427  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5e0c5c not in the list
,08-29 16:10:57.427  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:10:57.427  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:10:57.427  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:10:57.427  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f66facf not in the list
08-29 16:10:57.429  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:10:57.429  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36968e1 added. We now have 3 listener(s)
08-29 16:10:57.432  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 16:10:57.432  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 16:10:57.432  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:10:57.433  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 16:10:57.433  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc6606 added. We now have 4 listener(s)
08-29 16:10:57.434  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 16:10:57.435  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:10:57.439  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:10:57.444  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:10:57.446  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:10:57.447  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 16:10:57.447  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 16:10:57.447  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 16:10:57.447  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 16:10:57.447  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 16:10:57.447  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 16:10:57.450  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:57.451  3836  3887 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 16:10:57.452  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 16:10:57.452  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:10:57.459  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 16:10:57.460  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 16:10:57.460  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 16:10:57.464  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 16:10:57.464  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 16:10:57.464  3836  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 16:10:57.465  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:10:57.468  4207  4243 D BtGatt.GattService: registerClient() - UUID=ce26e30c-471c-432a-a90c-e64c06ce9740
,08-29 16:10:57.469  4207  4223 D BtGatt.GattService: onClientRegistered() - UUID=ce26e30c-471c-432a-a90c-e64c06ce9740, clientIf=5
,08-29 16:10:57.470  3836  3906 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 16:10:57.470  4207  4235 D BtGatt.GattService: start scan with filters
,08-29 16:10:57.474  4207  4226 D BtGatt.ScanManager: handling starting scan
,08-29 16:10:57.474  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 16:10:57.474  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 16:10:57.474  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 16:10:57.474  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 16:10:57.479  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:10:57.480  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 16:10:57.480  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 16:10:57.483  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 16:10:57.484  4207  4223 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 16:10:57.484  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:10:57.485  4207  4226 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 16:10:57.494  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 16:10:57.494  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:10:57.494  4207  4226 D BtGatt.ScanManager: Starting BLE batch scan
08-29 16:10:57.495  4207  4226 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-29 16:10:57.515  4207  4223 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 16:10:57.515  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:57.532  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 16:10:57.532  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:57.918  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:10:57.980  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 16:10:57.981  3836  3836 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 16:10:57.981  3836  3836 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 16:10:59.035  4207  4207 D BtGatt.ScanManager: awakened up at time 236243
,08-29 16:10:59.040  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 16:10:59.077  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-29 16:10:59.078  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:10:59.079  4207  4223 D BtGatt.GattService: current time is 236286789138
,08-29 16:10:59.079  4207  4223 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -122, 124, -58, -76, 103, 100, 1, -128, -59, 28, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -46, -4, -117, 6, 105, -37, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -98, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 16:10:59.081  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 16:10:59.082  4207  4223 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,08-29 16:10:59.082  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-29 16:10:59.082  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 16:10:59.082  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 16:10:59.083  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 16:10:59.083  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-29 16:10:59.090  3836  3836 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
08-29 16:10:59.091  3836  3836 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-29 16:11:00.496  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 16:11:00.497  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 16:11:00.497  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 16:11:00.498  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.499  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 16:11:00.499  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 16:11:00.500  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 16:11:00.500  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 16:11:00.501  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 16:11:00.502  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 16:11:00.503  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 16:11:00.506  3836  3887 D BluetoothAdapter: STATE_ON
,08-29 16:11:00.508  4207  4235 D BtGatt.GattService: stopScan() - queue size =1
,08-29 16:11:00.510  4207  4218 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 16:11:00.512  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 16:11:00.513  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 16:11:00.513  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 16:11:00.513  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 16:11:00.514  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 16:11:00.519  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:11:00.520  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-29 16:11:00.520  3836  3887 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 16:11:00.520  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 16:11:00.522  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:11:00.523  3836  3887 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-29 16:11:00.524  4207  4207 D BtGatt.ScanManager: awakened up at time 237732
08-29 16:11:00.529  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:11:00.529  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 16:11:00.530  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 16:11:00.530  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:11:00.532  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.533  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 16:11:00.533  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:11:00.533  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36968e1 removed from the list
08-29 16:11:00.533  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:11:00.534  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc6606 removed from the list
08-29 16:11:00.534  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:11:00.534  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:11:00.536  4207  4223 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 16:11:00.536  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:11:00.537  4207  4226 D BtGatt.ScanManager: stopping BLe Batch
,08-29 16:11:00.538  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.538  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:11:00.541  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:11:00.541  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 16:11:00.541  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:11:00.542  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc6606 not in the list
08-29 16:11:00.542  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.542  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:11:00.544  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:11:00.545  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 16:11:00.545  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:11:00.545  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc6606 not in the list
08-29 16:11:00.546  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 16:11:00.546  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.546  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:11:00.547  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36968e1 not in the list
,08-29 16:11:00.548  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 16:11:00.549  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e526260 added. We now have 3 listener(s)
,08-29 16:11:00.550  4207  4223 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 16:11:00.550  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 16:11:00.551  4207  4226 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 16:11:00.551  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 16:11:00.551  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 16:11:00.552  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 16:11:00.552  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 16:11:00.552  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94d5319 added. We now have 4 listener(s)
08-29 16:11:00.552  3836  3887 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 16:11:00.552  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 16:11:00.555  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 16:11:00.560  3836  3887 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 16:11:00.562  3836  3887 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 16:11:00.562  3836  3887 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 16:11:00.563  3836  3887 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 16:11:00.563  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 16:11:00.563  3836  3887 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 16:11:00.563  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:11:00.564  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.564  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 16:11:00.564  3836  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 16:11:00.564  3836  3887 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e526260 removed from the list
08-29 16:11:00.564  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:11:00.564  3836  3887 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94d5319 removed from the list
,08-29 16:11:00.566  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 16:11:00.566  3836  3887 D io.jxcore.node.ConnectivityMonitor: stop
08-29 16:11:00.566  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:11:00.566  4207  4223 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-29 16:11:00.566  4207  4223 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 16:11:00.566  4207  4223 D BtGatt.GattService: current time is 237774525883
,08-29 16:11:00.567  4207  4223 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -105, 6, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 81, 34, 97, 112, -14, -5, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-29 16:11:00.567  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.567  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:11:00.567  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
08-29 16:11:00.567  4207  4223 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-29 16:11:00.568  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:11:00.568  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:11:00.568  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 16:11:00.568  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94d5319 not in the list
08-29 16:11:00.568  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.568  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 16:11:00.570  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 16:11:00.571  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 16:11:00.571  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 16:11:00.571  3836  3887 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 16:11:00.571  3836  3887 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94d5319 not in the list
,08-29 16:11:00.571  3836  3887 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 16:11:00.571  3836  3887 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 16:11:00.571  3836  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 16:11:00.571  3836  3887 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e526260 not in the list
08-29 16:11:00.572  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 16:11:00.573  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 16:11:00.573  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 16:11:00.573  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-29 16:11:00.573  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 16:11:00.573  3836  3887 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 16:11:01.031  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 16:11:02.590  3836  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-29 16:11:04.588  3836  3887 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 463
,08-29 16:11:04.588  3836  3887 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 463, name: My test thread name)
,08-29 16:11:04.595  3836  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,08-29 16:11:04.595  3836  4309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 464, thread name: My test thread name)
08-29 16:11:04.596  3836  4309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 16:11:04.600  3836  3887 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 16:11:04.608  3836  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: My test thread name)
,08-29 16:11:04.609  3836  4310 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 468, thread name: My test thread name): Test exception.
,08-29 16:11:04.609  3836  4310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 16:11:04.617  3836  3887 I jxcore-log: Total number of executed tests:  82
08-29 16:11:04.617  3836  3887 I jxcore-log: 
,08-29 16:11:04.618  3836  3887 I jxcore-log: Number of passed tests:  82
08-29 16:11:04.618  3836  3887 I jxcore-log: 
,08-29 16:11:04.619  3836  3887 I jxcore-log: Number of failed tests:  0
08-29 16:11:04.619  3836  3887 I jxcore-log: 
08-29 16:11:04.620  3836  3887 I jxcore-log: Number of ignored tests:  0
08-29 16:11:04.620  3836  3887 I jxcore-log: 
,08-29 16:11:04.620  3836  3887 I jxcore-log: Total duration:  101382
08-29 16:11:04.620  3836  3887 I jxcore-log: 
,08-29 16:11:04.630  3836  3887 I jxcore-log: Unit Test app is loaded
08-29 16:11:04.630  3836  3887 I jxcore-log: 
,08-29 16:11:04.651  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.651  3836  3887 I jxcore-log: 
,08-29 16:11:04.656  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.656  3836  3887 I jxcore-log: 
,08-29 16:11:04.657  3836  3836 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 16:11:04.658  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.658  3836  3887 I jxcore-log: 
08-29 16:11:04.659  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.659  3836  3887 I jxcore-log: 
,08-29 16:11:04.661  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 16:11:04.661  3836  3887 I jxcore-log: 
,08-29 16:11:04.662  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.662  3836  3887 I jxcore-log: 
,08-29 16:11:04.665  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.665  3836  3887 I jxcore-log: 
,08-29 16:11:04.667  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.667  3836  3887 I jxcore-log: 
,08-29 16:11:04.668  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 16:11:04.668  3836  3887 I jxcore-log: 
,08-29 16:11:04.669  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.669  3836  3887 I jxcore-log: 
08-29 16:11:04.669  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.669  3836  3887 I jxcore-log: 
,08-29 16:11:04.670  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.670  3836  3887 I jxcore-log: 
,08-29 16:11:04.671  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.671  3836  3887 I jxcore-log: 
,08-29 16:11:04.672  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.672  3836  3887 I jxcore-log: 
08-29 16:11:04.673  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.673  3836  3887 I jxcore-log: 
,08-29 16:11:04.674  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.674  3836  3887 I jxcore-log: 
08-29 16:11:04.675  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.675  3836  3887 I jxcore-log: 
,08-29 16:11:04.675  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.675  3836  3887 I jxcore-log: 
08-29 16:11:04.677  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.677  3836  3887 I jxcore-log: 
,08-29 16:11:04.678  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.678  3836  3887 I jxcore-log: 
08-29 16:11:04.679  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.679  3836  3887 I jxcore-log: 
,08-29 16:11:04.679  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.679  3836  3887 I jxcore-log: 
08-29 16:11:04.680  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.680  3836  3887 I jxcore-log: 
08-29 16:11:04.681  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.681  3836  3887 I jxcore-log: 
08-29 16:11:04.682  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.682  3836  3887 I jxcore-log: 
08-29 16:11:04.682  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.682  3836  3887 I jxcore-log: 
08-29 16:11:04.683  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.683  3836  3887 I jxcore-log: 
08-29 16:11:04.684  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.684  3836  3887 I jxcore-log: 
08-29 16:11:04.685  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.685  3836  3887 I jxcore-log: 
08-29 16:11:04.686  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.686  3836  3887 I jxcore-log: 
,08-29 16:11:04.687  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.687  3836  3887 I jxcore-log: 
08-29 16:11:04.687  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.687  3836  3887 I jxcore-log: 
,08-29 16:11:04.688  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.688  3836  3887 I jxcore-log: 
08-29 16:11:04.688  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.688  3836  3887 I jxcore-log: 
,08-29 16:11:04.689  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.689  3836  3887 I jxcore-log: 
08-29 16:11:04.689  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.689  3836  3887 I jxcore-log: 
,08-29 16:11:04.690  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.690  3836  3887 I jxcore-log: 
08-29 16:11:04.690  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.690  3836  3887 I jxcore-log: 
,08-29 16:11:04.691  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.691  3836  3887 I jxcore-log: 
08-29 16:11:04.691  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.691  3836  3887 I jxcore-log: 
,08-29 16:11:04.692  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 16:11:04.692  3836  3887 I jxcore-log: 
08-29 16:11:04.692  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.692  3836  3887 I jxcore-log: 
,08-29 16:11:04.693  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 16:11:04.693  3836  3887 I jxcore-log: 
08-29 16:11:04.693  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.693  3836  3887 I jxcore-log: 
,08-29 16:11:04.694  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.694  3836  3887 I jxcore-log: 
08-29 16:11:04.694  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.694  3836  3887 I jxcore-log: 
,08-29 16:11:04.695  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.695  3836  3887 I jxcore-log: 
08-29 16:11:04.695  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.695  3836  3887 I jxcore-log: 
,08-29 16:11:04.696  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.696  3836  3887 I jxcore-log: 
,08-29 16:11:04.696  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.696  3836  3887 I jxcore-log: 
08-29 16:11:04.697  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 16:11:04.697  3836  3887 I jxcore-log: 
08-29 16:11:04.697  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.697  3836  3887 I jxcore-log: 
08-29 16:11:04.698  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.698  3836  3887 I jxcore-log: 
08-29 16:11:04.698  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 16:11:04.698  3836  3887 I jxcore-log: 
,08-29 16:11:04.699  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-29 16:11:04.699  3836  3887 I jxcore-log: 
08-29 16:11:04.700  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 16:11:04.700  3836  3887 I jxcore-log: 
,08-29 16:11:04.700  3836  3887 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 16:11:04.700  3836  3887 I jxcore-log: 
,08-29 16:11:04.703  3836  3887 I jxcore-log: My device name is: motorola-Nexus 6
08-29 16:11:04.703  3836  3887 I jxcore-log: 
08-29 16:11:04.705  3836  3887 I jxcore-log: Running for NATIVE network type
08-29 16:11:04.705  3836  3887 I jxcore-log: 
,08-29 16:11:04.734  3836  4308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-29 16:11:05.132  3836  3887 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-29 16:11:05.206  4311  3887 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
08-29 16:11:05.206  4311  3887 W google-breakpad: O A arm 04 armv7l 3.10.40-geb6cc9d #1 SMP PREEMPT Wed Apr 20 00:05:01 UTC 2016
,08-29 16:11:05.206  4311  3887 W google-breakpad: S 0 9115B378 9115B000 00008000
,08-29 16:11:05.270  4311  3887 W google-breakpad: S 9115B000 0000000000000000000000000000000000000000000000000000000000DCAF8D00000000000000000100000002000000E0086F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF69170B01591ECB31591A8660492000000000000000090B4159100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 16:11:05.271  4311  3887 W google-breakpad: S 9115B180 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B690B21591C0EA829640B31591A0B21591A8D23290FCB21591E46A0492C0F0CB950020F19FC8F0CB9540B0C290A0B215910100000080BF1591F6FFFFFFCCEA829600000000C0EA829690B215910300000008000000603FC79088FFFFFF40B0C29088FFFFFF00454F8F85FFFFFFC8F0CB95A0D232900020F19FC0B315910CA3D6B6C0F0CB9594D5D5B6C8F0CB95A0D232905B02D4B600000000E4B2159101000000C0EA8296FCB215919401F5910CB6159124BF1591C0EA8296000000002CB315915C55F491
,08-29 16:11:05.271  4311  3887 W google-breakpad: S 9115B300 A0D2329048B3159140B0C2906909000030B5C9951070919654B315911044D59100000000C0B315912C00000070B3159148B315910700000058DB449274172F92C0EA82960000000085FFFFFF00F02E9DACB315912049D5910000000070B31591C0EA8296000000006C172F92C0B3159174172F92ACB3159107000000000000000000000090B8E0E630454F8F85FFFFFFE01DD190C0EA829630B41591DCB31591B4B3159185FFFFFFD4B31591202EF49100000000E01DD19022000000A0B41591DCB3159130B4159174172F9230454F8FFCB3159158D715922C09768F000000000000000082FFFFFF30B41591A0B4159120B41591C0EA829664B415911C6B0E92E4D82E9250DC2E9258DB4492220000002C09768F44CF7A8F0000000034B4159130454F8F85FFFFFFC0EA82960000000030454F8F85FFFFFFE8B41591B8B5159118C14592B0B415910000000001000000A0B4159190B4159122000000C0EA8296F4B515912894119290D2329000000000C0EA829680B4159102000000C8B41591
,08-29 16:11:05.271  4311  3887 W google-breakpad: S 9115B480 E0ACD98FE8B4159160414E8F88FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFFC0EA82960000000000000000C0EA82960100000018B6159128B615910100000090D23290070000000700000001000000A0434F8F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF0000000098D2329022000000A8434F8F0700000000000000010000001800D09050F9BB8E81FFFFFF54B51591E0AAFE9107000000A0434F8FC0EA8296000000001000D09060B5159194B51591E8ECFE910000000000000000000000000CB2868CC8B515910100000000000000E0454E8FE01BD190A0434F8F00000000FFFFFFFF50F9BB8E81FFFFFF30B61591B0B2868C88B61591A4B51591F0B51591000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFFA0434F8F85FFFFFF1000D09085FFFFFF000000006049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E81FFFFFF30B61591381FFC900000000004B61591
08-29 16:11:05.271  4311  3887 W google-breakpad: S 9115B600 8C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFFA0434F8F85FFFFFF8CB61591C0F9BB8E88FCB08E01050000A0434F8F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFFBCB61591D4B6159100000000B0B615918C29FC90820100008086C690010000000000000082FFFFFFA0434F8F85FFFFFF5CB71591C07E768F2CAC878C010A0000A0434F8F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFD84FF79E020000000000000088B715918C29FC9002020000C04CC69002000000A0C6C59088FFFFFFA0434F8F85FFFFFF
,08-29 16:11:05.271  4311  3887 W google-breakpad: S 9115B780 60096F8F88FFFFFFFCB715918046FB8DAC90F79E81060000F0D9D19085FFFFFFA0434F8F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E0B715910000000083FFFFFF680000004090BA8CA8434F8F01000000300000004090BA8C0000000020B815918C29FC9082010000009A458F010000000000000082FFFFFFA0434F8F85FFFFFFA4B81591701FF98DEC88F79E81070000A0434F8F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC0B81591B8B81591B0B8159124B91591780000004090BA8C000000001694DB9558DB4492C0EA829600000000C8B815918C29FC9082010000409A458F010000000000000082FFFFFFA0434F8F85FFFFFF34B915919815F98DCC7EF79E01060000A0434F8F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 16:11:05.272  4311  3887 W google-breakpad: S 9115B900 0000000082FFFFFF0000000040B9159158B9159104000000600000004090BA8CE005F98D81FFFFFFC4B91591F8DFFB900000000058B915918C29FC9082010000609A458F010000000000000082FFFFFFA0434F8F85FFFFFFC4B91591980FF98DD075F79E01060000A0434F8F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000080454E8F0000000010DF0A8E60000000B0454E8F04000000D84FF79ED4B915917804E19104000000E8B915918C29FC9082010000809A458F010000000000000082FFFFFF80454E8F88FFFFFF64BA15919004F98DE46CF79E0107000080454E8F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFFA0434F8F85FFFFFF0000000058BA159154BA159188FFFFFF7000000050454E8F3063468F84E1F39100000000000000000400000088BA15918C29FC9082010000009B458F01000000A053199088FFFFFF
08-29 16:11:05.272  4311  3887 W google-breakpad: S 9115BA80 C0414E8F88FFFFFFE4BA1591606AF48D5066F79E01050000C0414E8F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFF3063468F0100000014BB15912CBB159150000000C0340E8F020000007063178F04BB1591C803E1910000000018BB1591DC7DE190820200002058E18F030000000000000082FFFFFFC0414E8F88FFFFFF0000000081FFFFFF3063468F88FFFFFFB4BB1591D0D66E8DE832848C010900003063468F88FFFFFF0000000081FFFFFFC0414E8F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00C2498E88FFFFFF0000000082FFFFFF0900000081FFFFFF3063468F88FFFFFF8063468F00000000E4BB1591C0D6C2909000000020C0C290D84FF79E020000007061F48D81FFFFFF00000000D8BB15918C29FC9082010000B002C390010000003063468F88FFFFFF2058E18F88FFFFFF5CBC15912866F48DC05FF79E810700002058E18F88FFFFFF3063468F88FFFFFFB002C39088FFFFFF
,08-29 16:11:05.272  4311  3887 W google-breakpad: S 9115BC00 8063468F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFF8063468F88FFFFFF0000000082FFFFFF80BC1591381FFC900000000044BC159178000000C0340E8F000000001456F79E42030000030000000000000088BC15918C29FC90020200004058E18F02000000106C089088FFFFFFE0ACD98F88FFFFFF3063468F88FFFFFFF4BC1591785BF48DE05AF79E010600003063468F88FFFFFFE0ACD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFB8BC1591A035C490D0444F8F4011D19060000000C0340E8F85FFFFFF2C44838B85FFFFFFF4BC1591000000000037C490384F838B800B00008058E18F020000000037C49088FFFFFFE0ACD98F88FFFFFF303D4C8F88FFFFFFE0444F8F85FFFFFFE062468F88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFE0424E8F303D4C8FA035C490D03F488F8A00000090444E8FE0444F8FE062468F303D4C8FA035C490D0444F8F8018D0904000408F
08-29 16:11:05.272  4311  3887 W google-breakpad: S 9115BD80 0900000000096F8FD0B0C290D0B0C290303D4C8F88FFFFFF090000004011D190090000000037C490E0ACD98F90414E8F00096F8F88FFFFFF000000007CEBE09020EDE090000400008036C490010000000037C49088FFFFFFE0ACD98F88FFFFFF0000000082FFFFFFF02A4E92E0ACD98F60414E8F30414E8F0000000087FFFFFFA00FC39000414E8F30414E8FE0086F8FE0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFF00414E8F88FFFFFF70BE159100414E8FA0404E8FD0404E8FFCDE868C800200000037C49000000000A0404E8F88FFFFFF503B4A8F8A00000007000000603B4A8FC0EA829640B0C290C03F488F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFFC03F488F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B648C015910100000081FFFFFFA0BF1591
08-29 16:11:05.273  4311  3887 W google-breakpad: S 9115BF00 0CC0159114C4E691603FC790000000000000000070BF159124BF15913857FB9058DB4492C0EA82960049DF958CD015910000000000000000000000000100000074C71591C0EA82960001000000000000B0DD868C00000000603FC79000C41591020000000100000000000000000000000100000081FFFFFF0000000000000000D8C31591F6FFFFFFCCEA829601000000C0EA8296A0BF159100000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000048C01591C0EA8296783B4E920082CA900000000088D232900CC0159137DCE1F800000000C0EA829648C0159110C01591603FC7900082CA900000000088D2329034C015912C650492000000000000000000000000C01ED6B601000000C0EA829608C4159140C01591BCC315912466049252E4AF8DFBE5AF8D08C4159101000000E80C4492010000000082CA9040C015910000000000E6AF8D0200000002000000010000000000000080BA43925C0000000600000000000000
,08-29 16:11:05.273  4311  3887 W google-breakpad: S 9115C080 78CF15910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D0000000000000000010000000200000040086F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF691D8C1159154C51591A86604920000000000000000F8C51591000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.273  4311  3887 W google-breakpad: S 9115C200 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 16:11:05.273  4311  3887 W google-breakpad: S 9115C380 0000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B6F8C31591C0EA8296A8C4159108C4159188D2329064C41591E46A0492C0F0CB950020F19FC8F0CB9540B0C29008C4159101000000E8D01591F6FFFFFFCCEA829600000000C0EA8296F8C315910300000008000000603FC79088FFFFFF40B0C29088FFFFFFC03F488F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000037DCE1F804000000C0EA8296B8C41591A8C41591B0C41591A4C4159182FFFFFF80D2329094C415913855F49180D23290B0C4159140B0C29088FFFFFF18C5159128C5159108C6159101000000C0C4159100000000F4C4159120EB1592B0C41591000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF0100000080D232900000000082FFFFFFC0EA8296000000006C172F9228C5159118C5159100665C9998685C99C0EA829608C615916C172F9264C51591B8FA0C9228C515917CC51591
08-29 16:11:05.273  4311  3887 W google-breakpad: S 9115C500 070000004F0000002C97FC8EDC08768F00000000D008768F40B0C29088FFFFFFC0EA829600000000C03F488F85FFFFFFC0EA82960000000078C5159118703092FD08768F98C5159108C6159188C51591C0EA82967CC515912200000000665C99CCC51591EC6A0E92E4D82E9250DC2E9258DB449222000000DC08768F14CF7A8F000000009CC51591220000000000000020C7159100000000B4C515911435CC9150C6159120C7159118C1459218C61591000000000100000008C61591F8C5159122000000C0EA82965CC715912894119270D2329000000000C0EA8296E8C515910200000030C6159190ACD98F50C61591E0EB688F88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000C0EA82960100000080C7159190C715910100000070D23290070000000700000001000000603E488F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF0000000078D2329022000000683E488F
,08-29 16:11:05.274  4311  3887 W google-breakpad: S 9115C680 0700000000000000010000001800D09050F9BB8E81FFFFFFBCC61591E0AAFE9107000000603E488FC0EA8296000000001000D090C8C61591FCC61591E8ECFE910000000000000000000000000CB2868C30C71591010000000000000070404E8FE01BD190603E488F00000000FFFFFFFF50F9BB8E81FFFFFF98C71591B0B2868CF0C715910CC7159158C71591000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFF603E488F85FFFFFF1000D09085FFFFFF000000006049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E81FFFFFF98C71591381FFC90000000006CC715918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFF603E488F85FFFFFFF4C71591C0F9BB8E88FCB08E01050000603E488F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFF24C815913CC815910000000018C815918C29FC9082010000
,08-29 16:11:05.274  4311  3887 W google-breakpad: S 9115C800 8086C690010000000000000082FFFFFF603E488F85FFFFFFC4C81591C07E768F2CAC878C010A0000603E488F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFD84FF79E0200000000000000F0C815918C29FC9002020000C04CC69002000000A0C6C59088FFFFFF603E488F85FFFFFFC0086F8F88FFFFFF64C915918046FB8DAC90F79E81060000F0D9D19085FFFFFF603E488F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000048C915910000000083FFFFFF680000004090BA8C683E488F01000000300000004090BA8C0000000088C915918C29FC9082010000009A458F010000000000000082FFFFFF
08-29 16:11:05.274  4311  3887 W google-breakpad: S 9115C980 603E488F85FFFFFF0CCA1591701FF98DEC88F79E81070000603E488F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF28CA159120CA159118CA15918CCA1591780000004090BA8C000000001694DB9558DB4492C0EA82960000000030CA15918C29FC9082010000409A458F010000000000000082FFFFFF603E488F85FFFFFF9CCA15919815F98DCC7EF79E01060000603E488F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A8CA1591C0CA159104000000600000004090BA8CE005F98D81FFFFFF2CCB1591F8DFFB9000000000C0CA15918C29FC9082010000609A458F010000000000000082FFFFFF603E488F85FFFFFF2CCB1591980FF98DD075F79E01060000603E488F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
,08-29 16:11:05.274  4311  3887 W google-breakpad: S 9115CB00 0000000010404E8F0000000010DF0A8E6000000040404E8F04000000D84FF79E3CCB15917804E1910400000050CB15918C29FC9082010000809A458F010000000000000082FFFFFF10404E8F88FFFFFFCCCB15919004F98DE46CF79E0107000010404E8F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFF603E488F85FFFFFF00000000C0CB1591BCCB159188FFFFFF70000000D0EF688F903C4C8F84E1F391000000000000000004000000F0CB15918C29FC9082010000009B458F01000000A053199088FFFFFF40EC688F88FFFFFF4CCC1591606AF48D5066F79E0105000040EC688F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFF903C4C8F010000007CCC159194CC159150000000C0340E8F020000007063178F6CCC1591C803E1910000000080CC1591DC7DE190820200002058E18F030000000000000082FFFFFF40EC688F88FFFFFF0000000081FFFFFF903C4C8F88FFFFFF
08-29 16:11:05.275  4311  3887 W google-breakpad: S 9115CC80 1CCD1591D0D66E8DE832848C01090000903C4C8F88FFFFFF0000000081FFFFFF40EC688F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF90C1498E88FFFFFF0000000082FFFFFF0900000081FFFFFF903C4C8F88FFFFFFE03C4C8F000000004CCD1591C0D6C2909000000020C0C290D84FF79E020000007061F48D81FFFFFF0000000040CD15918C29FC9082010000B002C39001000000903C4C8F88FFFFFF2058E18F88FFFFFFC4CD15912866F48DC05FF79E810700002058E18F88FFFFFF903C4C8F88FFFFFFB002C39088FFFFFFE03C4C8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFFE03C4C8F88FFFFFF0000000082FFFFFFE8CD1591381FFC9000000000ACCD159178000000C0340E8F000000001456F79E420300000300000000000000F0CD15918C29FC90020200004058E18F02000000106C089088FFFFFF90ACD98F88FFFFFF903C4C8F88FFFFFF5CCE1591785BF48DE05AF79E01060000
,08-29 16:11:05.275  4311  3887 W google-breakpad: S 9115CE00 903C4C8F88FFFFFF90ACD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFF20CE1591A035C490903F488F4011D19060000000C0340E8F85FFFFFF2C44838B85FFFFFF5CCE1591000000000037C490384F838B800B00008058E18F020000000037C49088FFFFFF90ACD98F88FFFFFFA0364C8F88FFFFFFA03F488F85FFFFFF403C4C8F88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF60ED688FA0364C8FA035C490503B4A8F8A00000010EF688FA03F488F403C4C8FA0364C8FA035C490903F488F8018D090B03B4A8F0900000060086F8FD0B0C290D0B0C290A0364C8F88FFFFFF090000004011D190090000000037C49090ACD98F10EC688F60086F8F88FFFFFF000000007CEBE09020EDE090000400008036C490010000000037C49088FFFFFF90ACD98F88FFFFFF0000000082FFFFFFF02A4E9290ACD98FE0EB688FB0EB688F0000000087FFFFFFA00FC39080EB688FB0EB688F40086F8FE0BB868C80020000
08-29 16:11:05.275  4311  3887 W google-breakpad: S 9115CF80 C036C490020000000000000082FFFFFFA00FC39088FFFFFF80EB688F88FFFFFFD8CF159180EB688F20EB688F50EB688FFCDE868C800200000037C4900000000020EB688F88FFFFFF8017488F8A000000070000009017488FC0EA829640B0C290403B4A8F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFF403B4A8F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B6B0D115910100000081FFFFFF08D1159174D1159114C4E691603FC7900000000000000000D8D015918CD015913857FB9058DB4492C0EA82960049DF95F4E1159100000000000000000000000001000000DCD81591C0EA82960001000000000000B0DD868C00000000603FC79068D51591020000000100000000000000000000000100000081FFFFFF000000000000000040D51591F6FFFFFFCCEA829601000000C0EA829608D11591
,08-29 16:11:05.275  4311  3887 W google-breakpad: S 9115D100 000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B0D11591C0EA8296783B4E920082CA900000000068D2329074D1159137DCE1F800000000C0EA8296B0D1159178D11591603FC7900082CA900000000068D232909CD115912C650492000000000000000000000000C01ED6B601000000C0EA829670D51591A8D1159124D515912466049252E4AF8DFBE5AF8D70D5159101000000E80C4492010000000082CA90A8D115910000000000E6AF8D0200000002000000010000000000000080BA43925C0000000600000000000000E0E0159100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.275  4311  3887 W google-breakpad: S 9115D280 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D00000000000000000100000002000000A0076F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF69140D31591BCD61591A8660492000000000000000060D715910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-29 16:11:05.276  4311  3887 W google-breakpad: S 9115D400 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B660D51591C0EA829610D6159170D5159168D23290CCD51591E46A0492C0F0CB950020F19FC8F0CB9540B0C29070D515910100000050E21591F6FFFFFFCCEA829600000000C0EA829660D515910300000008000000603FC79088FFFFFF40B0C29088FFFFFF403B4A8F85FFFFFF0000000000000000
08-29 16:11:05.276  4311  3887 W google-breakpad: S 9115D580 00000000000000000000000000000000000000000000000000000000000000000400000037DCE1F804000000C0EA829620D6159110D6159118D615910CD6159182FFFFFF60D23290FCD515913855F49160D2329018D6159140B0C29088FFFFFF80D6159190D6159170D715910100000028D61591000000005CD6159120EB159218D61591000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF0100000060D232900000000082FFFFFFC0EA8296000000006C172F9290D6159180D6159100665C9998685C99C0EA829670D715916C172F92CCD61591B8FA0C9290D61591E4D61591070000004F0000002C97FC8E8C08768F000000008008768F40B0C29088FFFFFFC0EA829600000000403B4A8F85FFFFFFC0EA829600000000E0D6159118703092AD08768F00D7159170D71591F0D61591C0EA8296E4D615912200000000665C9934D71591EC6A0E92E4D82E9250DC2E9258DB4492220000008C08768FE4CE7A8F0000000004D71591220000000000000088D8159100000000
08-29 16:11:05.276  4311  3887 W google-breakpad: S 9115D700 1CD715911435CC91B8D7159188D8159118C1459280D71591000000000100000070D7159160D7159122000000C0EA8296C4D815912894119250D2329000000000C0EA829650D715910200000098D7159140ACD98FB8D7159170E6688F88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000C0EA829601000000E8D81591F8D815910100000050D23290070000000700000001000000E0394A8F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF0000000058D2329022000000E8394A8F0700000000000000010000001800D09050F9BB8E81FFFFFF24D81591E0AAFE9107000000E0394A8FC0EA8296000000001000D09030D8159164D81591E8ECFE910000000000000000000000000CB2868C98D815910100000000000000F0EA688FE01BD190E0394A8F00000000FFFFFFFF50F9BB8E81FFFFFF00D91591B0B2868C58D9159174D81591C0D81591000000000000000078B2868C
08-29 16:11:05.276  4311  3887 W google-breakpad: S 9115D880 4003000001000000FFFFFFFF81FFFFFFE0394A8F85FFFFFF1000D09085FFFFFF000000006049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E81FFFFFF00D91591381FFC9000000000D4D815918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFFE0394A8F85FFFFFF5CD91591C0F9BB8E88FCB08E01050000E0394A8F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFF8CD91591A4D915910000000080D915918C29FC90820100008086C690010000000000000082FFFFFFE0394A8F85FFFFFF2CDA1591C07E768F2CAC878C010A0000E0394A8F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF
08-29 16:11:05.277  4311  3887 W google-breakpad: S 9115DA00 82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFD84FF79E020000000000000058DA15918C29FC9002020000C04CC69002000000A0C6C59088FFFFFFE0394A8F85FFFFFF20086F8F88FFFFFFCCDA15918046FB8DAC90F79E81060000F0D9D19085FFFFFFE0394A8F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B0DA15910000000083FFFFFF680000004090BA8CE8394A8F01000000300000004090BA8C00000000F0DA15918C29FC9082010000009A458F010000000000000082FFFFFFE0394A8F85FFFFFF74DB1591701FF98DEC88F79E81070000E0394A8F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF90DB159188DB159180DB1591F4DB1591780000004090BA8C000000001694DB9558DB4492C0EA82960000000098DB15918C29FC9082010000
08-29 16:11:05.277  4311  3887 W google-breakpad: S 9115DB80 409A458F010000000000000082FFFFFFE0394A8F85FFFFFF04DC15919815F98DCC7EF79E01060000E0394A8F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000010DC159128DC159104000000600000004090BA8CE005F98D81FFFFFF94DC1591F8DFFB900000000028DC15918C29FC9082010000609A458F010000000000000082FFFFFFE0394A8F85FFFFFF94DC1591980FF98DD075F79E01060000E0394A8F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000090EA688F0000000010DF0A8E60000000C0EA688F04000000D84FF79EA4DC15917804E19104000000B8DC15918C29FC9082010000809A458F010000000000000082FFFFFF90EA688F88FFFFFF34DD15919004F98DE46CF79E0107000090EA688F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFF
08-29 16:11:05.277  4311  3887 W google-breakpad: S 9115DD00 E0394A8F85FFFFFF0000000028DD159124DD159188FFFFFF7000000060EA688F00364C8F84E1F39100000000000000000400000058DD15918C29FC9082010000009B458F01000000A053199088FFFFFFD0E6688F88FFFFFFB4DD1591606AF48D5066F79E01050000D0E6688F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFF00364C8F01000000E4DD1591FCDD159150000000C0340E8F020000007063178FD4DD1591C803E19100000000E8DD1591DC7DE190820200002058E18F030000000000000082FFFFFFD0E6688F88FFFFFF0000000081FFFFFF00364C8F88FFFFFF84DE1591D0D66E8DE832848C0109000000364C8F88FFFFFF0000000081FFFFFFD0E6688F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF20C1498E88FFFFFF0000000082FFFFFF0900000081FFFFFF00364C8F88FFFFFF50364C8F00000000B4DE1591C0D6C2909000000020C0C290D84FF79E020000007061F48D81FFFFFF
08-29 16:11:05.277  4311  3887 W google-breakpad: S 9115DE80 00000000A8DE15918C29FC9082010000B002C3900100000000364C8F88FFFFFF2058E18F88FFFFFF2CDF15912866F48DC05FF79E810700002058E18F88FFFFFF00364C8F88FFFFFFB002C39088FFFFFF50364C8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFF50364C8F88FFFFFF0000000082FFFFFF50DF1591381FFC900000000014DF159178000000C0340E8F000000001456F79E42030000030000000000000058DF15918C29FC90020200004058E18F02000000106C089088FFFFFF40ACD98F88FFFFFF00364C8F88FFFFFFC4DF1591785BF48DE05AF79E0106000000364C8F88FFFFFF40ACD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFF88DF1591A035C490103B4A8F4011D19060000000C0340E8F85FFFFFF2C44838B85FFFFFFC4DF1591000000000037C490384F838B800B00008058E18F020000000037C49088FFFFFF40ACD98F88FFFFFF10304C8F88FFFFFF203B4A8F85FFFFFFB0354C8F88FFFFFF
08-29 16:11:05.277  4311  3887 W google-breakpad: S 9115E000 0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFF0E7688F10304C8FA035C4908017488F8A000000A0E9688F203B4A8FB0354C8F10304C8FA035C490103B4A8F8018D090E017488F09000000C0076F8FD0B0C290D0B0C29010304C8F88FFFFFF090000004011D190090000000037C49040ACD98FA0E6688FC0076F8F88FFFFFF000000007CEBE09020EDE090000400008036C490010000000037C49088FFFFFF40ACD98F88FFFFFF0000000082FFFFFFF02A4E9240ACD98F70E6688F40E6688F0000000087FFFFFFA00FC39010E6688F40E6688FA0076F8FE0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFF10E6688F88FFFFFF40E1159110E6688FB0E5688FE0E5688FFCDE868C800200000037C49000000000B0E5688F88FFFFFF60346E8F8A0000000700000070346E8FC0EA829640B0C2907017488F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFF7017488F85FFFFFF00000000000000000000000000000000
08-29 16:11:05.278  4311  3887 W google-breakpad: S 9115E180 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B618E315910100000081FFFFFF70E21591DCE2159114C4E691603FC790000000000000000040E21591F4E115913857FB9058DB4492C0EA82960049DF955CF315910000000000000000000000000100000044EA1591C0EA82960001159100000000B0DD868C00000000603FC790D0E61591020000000100000064E21591000000000100000081FFFFFF00E5159100000005A8E61591F6FFFFFFCCEA829601000000C0EA829670E21591000000000800000094E2159114A40A92000080002000000018E51591F87BCA900000100000000000E4E215910100000018E31591C0EA8296783B4E920082CA900000000048D23290DCE2159137DCE1F800000000C0EA829618E31591E0E21591603FC7900082CA900000000048D2329004E315912C65049200000000B4080C9202000000C01ED6B601000000C0EA8296D8E6159110E31591
08-29 16:11:05.278  4311  3887 W google-breakpad: S 9115E300 8CE61591246604921CE315910C090C92D8E6159101000000E80C4492010000000082CA9010E3159100000000009B0A920200000038000000C430FF8D2C9A0A9211E315913800000010E7159111E515913C000000000000E0C01ED6B618E51591B0E31591F87BCA90F0ABD98F000000009430FF8DF0B70A92D830FF8D8CE31591010000009CE315919CE31591FFFFFF0001000000ACE3159108000000DC30FF8DB030FF8D3C9CF79E489CF79E20800A92209CF79EF0FFFFFFFFFFFFFF000000000400000000001015C8F0CB950030FF8D0020F19F30E71591C8F0CB9530D232900020F19F18E515910CA3D6B6C0F0CB9594D5D5B6C8F0CB9530D232905B02D4B648E41591C4E4159100211D8C48E415913CE415914808EA913C9CF79E4C9CF79E78DDDD8D78DDDD8D4CE4159130E715910100000078DDDD8DC0EA829618E515910100000078DDDD8DC0EA8296F0ABD98FF0ABD98F000000006CE415912CC3D69148EC159118E515917CE41591246BE59100000000C01ED6B604F015915C3DEA91
08-29 16:11:05.278  4311  3887 W google-breakpad: S 9115E480 00D0DD8DBCC02F920D0000007CE4B68E03000000000000000000000000ABEA9100D0DD8D64C32F926862838B18E515910100000000D0DD8DD0E41591F87BCA90F0ABD98F28CB429241B0C290584E838B10000000280000001C0000002C0000000000000078DDDD8D0D0000007CE4B68E03000000000000000D000000CC7A0A92020000000100000018E5159100000000000000000000000028E51591000000000000000000000000000000000000000040E51591000000000000000000000000000000000000000058E51591000000000000000000000000000000000000000070E5159100000000000000000000000080E5159100000000010000000000000090E515910000000000000000000000000800000000000000A8E51591000000000800000000000000B8E51591000000000800000000000000C8E51591000000000800000000000000D8E51591000000000000000000000000E8E51591000000000000000005000000F8E515910000000000000000020000000200000000000000
08-29 16:11:05.278  4311  3887 W google-breakpad: S 9115E600 30D23290010000000100000000000000000000000000000028E61591000000000000000000000000200000000000000040E6159100000000200000000000000001E615910000000058E6159105000000010000000500000068E615910200000001000000D00000000400000037DCE1F8C01ED6B6C8E61591C0EA829678E71591D8E6159148D2329034E71591E46A0492C0F0CB950020F19FC8F0CB9540B0C290D8E6159101000000B8F31591F6FFFFFFCCEA829600000000C0EA8296C8E615910300000008000000603FC79088FFFFFF40B0C29088FFFFFF7017488F85FFFFFF200000000000000001E6159100000000702A4292B030FF8D0134FF8D0000FF8D702A4292B030FF8D0134FF8D37DCE1F804000000C0EA829688E7159178E7159180E7159174E7159182FFFFFF40D2329064E715913855F49140D2329080E7159140B0C29088FFFFFFE8E71591F8E71591D8E815910100000090E7159100000000C4E7159120EB159280E71591080000001800000040B0C290603FC79088FFFFFF
08-29 16:11:05.279  4311  3887 W google-breakpad: S 9115E780 0000000082FFFFFF0100000040D232900000000082FFFFFFC0EA8296000000006C172F92F8E71591E8E7159100665C9998685C99C0EA8296D8E815916C172F9234E81591B8FA0C92F8E715914CE81591070000004F0000002C97FC8E3C08768F000000003008768F40B0C29088FFFFFFC0EA8296000000007017488F85FFFFFFC0EA82960000000048E81591187030925D08768F68E81591D8E8159158E81591C0EA82964CE815912200000000665C999CE81591EC6A0E92E4D82E9250DC2E9258DB4492220000003C08768FB4CE7A8F000000006CE815912200000000000000F0E915910000000084E815911435CC9120E91591F0E9159118C14592E8E815910000000001000000D8E81591C8E8159122000000C0EA82962CEA15912894119230D232903015748C00000000001000003015748C00E9159118E9159120E915913015748CE401DCB40000000082FFFFFF000000000001000022000000000000000000000000000000000B348FC0EA82960100000050EA159160EA159101FFFFFF
08-29 16:11:05.279  4311  3887 W google-breakpad: S 9115E900 30D23290070000000700000001FFFFFF1016488F00FFFFFFC0EA829601000000E801DCB4060000003CC145923CC145920600000018C1459200000000FFFFFFFF0000000038D23290220000001816488F0700000000000000010000001800D09050F9BB8E81FFFFFF8CE91591E0AAFE91070000001016488FC0EA8296000000001000D09098E91591CCE91591E8ECFE91F4A2D6B6BB14D3B6A80C348F0CB2868C00EA159101000000080A289D80E5688FE01BD1901016488F00000000FFFFFFFF50F9BB8E81FFFFFF68EA1591B0B2868CC0EA1591DCE9159128EA1591000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFF1016488F85FFFFFF1000D09085FFFFFFE401DCB46049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E81FFFFFF68EA1591381FFC90000000003CEA15918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFF1016488F85FFFFFFC4EA1591C0F9BB8E88FCB08E010500001016488F85FFFFFF
08-29 16:11:05.279  4311  3887 W google-breakpad: S 9115EA80 00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFFF4EA15910CEB159100000000E8EA15918C29FC90820100008086C690010000000000000082FFFFFF1016488F85FFFFFF94EB1591C07E768F2CAC878C010A00001016488F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFD84FF79E0200000000000000C0EB15918C29FC9002020000C04CC69002000000A0C6C59088FFFFFF1016488F85FFFFFF80076F8F88FFFFFF34EC15918046FB8DAC90F79E81060000F0D9D19085FFFFFF1016488F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 16:11:05.279  4311  3887 W google-breakpad: S 9115EC00 0000000082FFFFFFC103000018EC15910000000083FFFFFF680000004090BA8C1816488F01000000300000004090BA8C0000000058EC15918C29FC9082010000009A458F010000000000000082FFFFFF1016488F85FFFFFFDCEC1591701FF98DEC88F79E810700001016488F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF8EC1591F0EC1591E8EC15915CED1591780000004090BA8C000000001694DB9558DB4492C0EA82960000000000ED15918C29FC9082010000409A458F010000000000000082FFFFFF1016488F85FFFFFF6CED15919815F98DCC7EF79E010600001016488F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000078ED159190ED159104000000600000004090BA8CE005F98D81FFFFFFFCED1591F8DFFB900000000090ED15918C29FC9082010000609A458F01000000
08-29 16:11:05.279  4311  3887 W google-breakpad: S 9115ED80 0000000082FFFFFF1016488F85FFFFFFFCED1591980FF98DD075F79E010600001016488F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000020E5688F0000000010DF0A8E6000000050E5688F04000000D84FF79E0CEE15917804E1910400000020EE15918C29FC9082010000809A458F010000000000000082FFFFFF20E5688F88FFFFFF9CEE15919004F98DE46CF79E0107000020E5688F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFF1016488F85FFFFFF0000000090EE15918CEE159188FFFFFF70000000F0E4688F609F6F8F84E1F391000000000000000004000000C0EE15918C29FC9082010000009B458F01000000A053199088FFFFFF60E1688F88FFFFFF1CEF1591606AF48D5066F79E0105000060E1688F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFF609F6F8F010000004CEF159164EF1591
08-29 16:11:05.280  4311  3887 W google-breakpad: S 9115EF00 50000000C0340E8F020000007063178F3CEF1591C803E1910000000050EF1591DC7DE190820200002058E18F030000000000000082FFFFFF60E1688F88FFFFFF0000000081FFFFFF609F6F8F88FFFFFFECEF1591D0D66E8DE832848C01090000609F6F8F88FFFFFF0000000081FFFFFF60E1688F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB0C0498E88FFFFFF0000000082FFFFFF0900000081FFFFFF609F6F8F88FFFFFFB09F6F8F000000001CF01591C0D6C2909000000020C0C290D84FF79E020000007061F48D81FFFFFF0000000010F015918C29FC9082010000B002C39001000000609F6F8F88FFFFFF2058E18F88FFFFFF94F015912866F48DC05FF79E810700002058E18F88FFFFFF609F6F8F88FFFFFFB002C39088FFFFFFB09F6F8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFFB09F6F8F88FFFFFF0000000082FFFFFFB8F01591381FFC90000000007CF0159178000000C0340E8F
08-29 16:11:05.280  4311  3887 W google-breakpad: S 9115F080 000000001456F79E420300000300000000000000C0F015918C29FC90020200004058E18F02000000106C089088FFFFFFF0ABD98F88FFFFFF609F6F8F88FFFFFF2CF11591785BF48DE05AF79E01060000609F6F8F88FFFFFFF0ABD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFF0F01591A035C4904017488F4011D19060000000C0340E8F85FFFFFF2C44838B85FFFFFF2CF11591000000000037C490384F838B800B00008058E18F020000000037C49088FFFFFFF0ABD98F88FFFFFF70996F8F88FFFFFF5017488F85FFFFFF109F6F8F88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF80E2688F70996F8FA035C49060346E8F8A00000030E4688F5017488F109F6F8F70996F8FA035C4904017488F8018D090C0346E8F0900000020076F8FD0B0C290D0B0C29070996F8F88FFFFFF090000004011D190090000000037C490F0ABD98F30E1688F20076F8F88FFFFFF000000007CEBE09020EDE09000040000
08-29 16:11:05.280  4311  3887 W google-breakpad: S 9115F200 8036C490010000000037C49088FFFFFFF0ABD98F88FFFFFF0000000082FFFFFFF02A4E92F0ABD98F00E1688FD0E0688F0000000087FFFFFFA00FC390A0E0688FD0E0688F00076F8FE0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFFA0E0688F88FFFFFF00000000A0E0688F40E0688F70E0688FFCDE868C800200000037C4900000000040E0688F88FFFFFF70FC159148000000B4F2159180FA15914800000040B0C29050346E8F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFF50346E8F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B680F415910100000081FFFFFFD8F3159144F4159114C4E691603FC7900000000000000000A8F315915CF315913857FB9058DB4492C0EA82960049DF95C404169100000000000000000000000001000000ACFB1591C0EA8296
08-29 16:11:05.280  4311  3887 W google-breakpad: S 9115F380 0001FD8E00000000B0DD868C00000000603FC79038F8159102000000010000007079BD8E000000000100000081FFFFFF0020F19F987C388E10F81591F6FFFFFFCCEA829601000000C0EA8296D8F3159100000000080000002000FD8E0000FD8EC079BD8E9A010000B06FBD8E0000FD8E7000FD8E1804000048A1E89F0100000080F41591C0EA8296783B4E920082CA900000000028D2329044F4159137DCE1F800000000C0EA829680F4159148F41591603FC7900082CA900000000028D232906CF415912C65049200000000F8EFB68E00000000C01ED6B601000000C0EA829640F8159178F41591F4F715912466049252E4AF8DFBE5AF8D40F8159101000000E80C4492010000000082CA9078F415910000000000E6AF8D0200000002000000010000000000000080BA43925C0000000600000000000000B00316910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.281  4311  3887 W google-breakpad: S 9115F500 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D0000000000000000010000000200000060066F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF69110F615918CF91591A8660492000000000000000030FA1591000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.281  4311  3887 W google-breakpad: S 9115F680 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000009C00248EF80D248E0000000000A00000F80D248E9713D3B688F7159170F71591BC00248ECC032C8E00000000002000009810248E9713D3B6C8F7159190F71591E401DCB49810248ECC032C8EE801DCB4F0A2D6B6BB14D3B6A80C348FFFFFFFFFA00E9890FFFFFFFF580B348FFFFFFFFFA00E2C8EFFFFFFFF9810888E01000000B409A48D010000006009208E01000000CC032C8EFFFFFFFF0400000037DCE1F8C01ED6B630F81591C0EA8296E0F8159140F8159128D232909CF81591E46A0492C0F0CB950020F19F
08-29 16:11:05.281  4311  3887 W google-breakpad: S 9115F800 C8F0CB9540B0C29040F815910100000020051691F6FFFFFFCCEA829600000000C0EA829630F815910300000008000000603FC79088FFFFFF40B0C29088FFFFFF50346E8F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000037DCE1F800000000C0EA8296F0F81591E0F81591E8F81591DCF8159182FFFFFF20D23290CCF815913855F49120D23290E8F8159140B0C29088FFFFFF50F9159160F9159140FA159101000000F8F81591000000002CF9159120EB1592E8F81591000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF0100000020D232900000000082FFFFFFC0EA8296000000006C172F9260F9159150F9159100665C9998685C99C0EA829640FA15916C172F929CF91591B8FA0C9260F91591B4F91591070000004F0000002C97FC8EEC07768F00000000E007768F40B0C29088FFFFFFC0EA82960000000050346E8F85FFFFFFC0EA829600000000B0F91591187030920D08768FD0F91591
08-29 16:11:05.281  4311  3887 W google-breakpad: S 9115F980 40FA1591C0F91591C0EA8296B4F915912200000000665C9904FA1591EC6A0E92E4D82E9250DC2E9258DB449222000000EC07768F6CCE7A8FC0A1A68FD4F91591220000000000000058FB159100000000ECF915911435CC9188FA159158FB159118C1459250FA1591000000000100000040FA159130FA159122000000C0EA829694FB15912894119210D232901CDCDE9500B02E9D64E20C924CFA159168FA159184FA159188FA1591A0FA1591000000000000000082FFFFFF0000000000010000220000000000000084FA1591D410F89100DCDE95C0EA829601000000B8FB1591C8FB159101DCDE9510D23290070000000700000001114492F0326E8F00E0688FC0EA8296A45EF991987C388E060000003CC145923CC145920600000018C1459200000000FFFFFFFF0000000008D2329022000000F8326E8F0700000000000000010000001800D09050F9BB8E01000000F4FA1591E0AAFE9107000000F0326E8FC0EA8296000000001000D09000FB159134FB1591E8ECFE9130BDC29085FFFFFF
08-29 16:11:05.281  4311  3887 W google-breakpad: S 9115FB00 F0326E8F0CB2868C68FB1591010000004C0E688E10E0688FE01BD190F0326E8F00000000FFFFFFFF50F9BB8E01000000D0FB1591B0B2868C28FC159144FB159190FB1591000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFFF0326E8F85FFFFFF1000D09085FFFFFFB052B88E6049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E01000000D0FB1591381FFC9000000000A4FB15918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFFF0326E8F85FFFFFF2CFC1591C0F9BB8E88FCB08E01050000F0326E8F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFF5CFC159174FC15910000000050FC15918C29FC90820100008086C690010000000000000082FFFFFFF0326E8F85FFFFFFFCFC1591C07E768F2CAC878C010A0000F0326E8F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF
08-29 16:11:05.282  4311  3887 W google-breakpad: S 9115FC80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFB0BE618F030200000000000028FD15918C29FC9002020000C04CC69002000000A0C6C59088FFFFFFF0326E8F85FFFFFFE0066F8F88FFFFFF9CFD15918046FB8DAC90F79E81060000F0D9D19085FFFFFFF0326E8F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000080FD15910000000083FFFFFF680000004090BA8CF8326E8F01000000300000004090BA8C00000000C0FD15918C29FC9082010000009A458F010000000000000082FFFFFFF0326E8F85FFFFFF44FE1591701FF98DEC88F79E81070000F0326E8F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 16:11:05.282  4311  3887 W google-breakpad: S 9115FE00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF60FE159158FE159150FE1591C4FE1591780000004090BA8C000000001694DB9558DB4492C0EA82960000000068FE15918C29FC9082010000409A458F010000000000000082FFFFFFF0326E8F85FFFFFFD4FE15919815F98DCC7EF79E01060000F0326E8F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E0FE1591F8FE159104000000600000004090BA8CE005F98D0100000064FF1591F8DFFB9000000000F8FE15918C29FC9082010000609A458F010000000000000082FFFFFFF0326E8F85FFFFFF64FF1591980FF98DD075F79E01060000F0326E8F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A0BF618F0000000010DF0A8E60000000D0BF618F04000000B0BE618F74FF15917804E1910400000088FF15918C29FC9082010000809A458F010000000000000082FFFFFF
08-29 16:11:05.282  4311  3887 W google-breakpad: S 9115FF80 A0BF618F88FFFFFF040016919004F98DE46CF79E01070000A0BF618F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFFF0326E8F85FFFFFF00000000F8FF1591F4FF159188FFFFFF7000000070BF618FD0986F8F84E1F391000000000000000004000000280016918C29FC9082010000009B458F01000000A053199088FFFFFFE0BB618F88FFFFFF84001691606AF48D5066F79E01050000E0BB618F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFFD0986F8F01000000B4001691CC00169150000000C0340E8F030200007063178FA4001691C803E19100000000B8001691DC7DE190820200002058E18F030000000000000082FFFFFFE0BB618F88FFFFFF0000000081FFFFFFD0986F8F88FFFFFF54011691D0D66E8DE832848C01090000D0986F8F88FFFFFF0000000081FFFFFFE0BB618F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF
08-29 16:11:05.282  4311  3887 W google-breakpad: S 91160100 0000000081FFFFFF40C0498E88FFFFFF0000000082FFFFFF0900000081FFFFFFD0986F8F88FFFFFF20996F8F0000000084011691C0D6C2909000000020C0C290B0BE618F030200007061F48D0100000000000000780116918C29FC9082010000B002C39001000000D0986F8F88FFFFFF2058E18F88FFFFFFFC0116912866F48DC05FF79E810700002058E18F88FFFFFFD0986F8F88FFFFFFB002C39088FFFFFF20996F8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFF20996F8F88FFFFFF0000000082FFFFFF20021691381FFC9000000000E401169178000000C0340E8F000000001456F79E420300000300000000000000280216918C29FC90020200004058E18F02000000106C089088FFFFFFA0ABD98F88FFFFFFD0986F8F88FFFFFF94021691785BF48DE05AF79E01060000D0986F8F88FFFFFFA0ABD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFCC41FC90DC021691E00216910000000060000000C0340E8F
08-29 16:11:05.283  4311  3887 W google-breakpad: S 91160280 C802169100000000B0BE618F0302000000000000C00216918C29FC90020200008058E18F020000000037C49088FFFFFFA0ABD98F88FFFFFFE0926F8F88FFFFFF5C03169158D2BF90FC34B08E01090000E0926F8F88FFFFFFA0ABD98F88FFFFFF0037C49088FFFFFF8058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFF30346E8F85FFFFFF80986F8F88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF80066F8F88FFFFFFB0BE618F88FFFFFF603FC7900100000090000000B0BB618F640316915403169108254E920000000004000000AC05169120EDE090000400008036C490010000000037C49088FFFFFFA0ABD98F88FFFFFF0000000082FFFFFFF02A4E92A0ABD98F80BB618F50BB618F0000000087FFFFFFA00FC39020BB618F50BB618F60066F8FE0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFF20BB618F88FFFFFF1004169120BB618FC0BA618FF0BA618FFCDE868C800200000037C49000000000C0BA618F88FFFFFF
08-29 16:11:05.283  4311  3887 W google-breakpad: S 91160400 30306C8F8A0000000700000040306C8FC0EA829640B0C290E0F1608F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFFE0F1608F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B6E80516910100000081FFFFFF40051691AC05169114C4E691603FC790000000000000000010051691C40416913857FB9058DB4492C0EA82960049DF952C16169100000000000000000000000001000000140D1691C0EA82960001000000000000B0DD868C00000000603FC790A0091691020000000100000000000000000000000100000081FFFFFF000000000000000078091691F6FFFFFFCCEA829601000000C0EA829640051691000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000E8051691C0EA8296783B4E920082CA900000000008D23290
08-29 16:11:05.283  4311  3887 W google-breakpad: S 91160580 AC05169137DCE1F800000000C0EA8296E8051691B0051691603FC7900082CA900000000008D23290D40516912C650492000000000000000000000000C01ED6B601000000C0EA8296A8091691E00516915C0916912466049252E4AF8DFBE5AF8DA809169101000000E80C4492010000000082CA90E00516910000000000E6AF8D0200000002000000010000000000000080BA43925C00000006000000000000001815169100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.283  4311  3887 W google-breakpad: S 91160700 00000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D00000000000000000100000002000000C0056F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF69178071691F40A1691A86604920000000000000000980B16910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.283  4311  3887 W google-breakpad: S 91160880 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B698091691C0EA8296480A1691A809169108D23290040A1691E46A0492C0F0CB950020F19FC8F0CB9540B0C290A80916910100000088161691F6FFFFFFCCEA829600000000C0EA8296980916910300000008000000603FC79088FFFFFF40B0C29088FFFFFFE0F1608F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000037DCE1F804000000C0EA8296580A1691480A1691500A1691440A169182FFFFFF00D23290
08-29 16:11:05.284  4311  3887 W google-breakpad: S 91160A00 340A16913855F49100D23290500A169140B0C29088FFFFFFB80A1691C80A1691A80B169101000000600A169100000000940A169120EB1592500A1691000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF0100000000D232900000000082FFFFFFC0EA8296000000006C172F92C80A1691B80A169100665C9998685C99C0EA8296A80B16916C172F92040B1691B8FA0C92C80A16911C0B1691070000004F0000002C97FC8E9C07768F000000009007768F40B0C29088FFFFFFC0EA829600000000E0F1608F85FFFFFFC0EA829600000000180B169118703092BD07768F380B1691A80B1691280B1691C0EA82961C0B16912200000000665C996C0B1691EC6A0E92E4D82E9250DC2E9258DB4492220000009C07768F3CCE7A8F000000003C0B16912200000000000000C00C169100000000540B16911435CC91F00B1691C00C169118C14592B80B16910000000001000000A80B1691980B169122000000C0EA8296FC0C169128941192F0D1329000000000C0EA8296880B1691
08-29 16:11:05.284  4311  3887 W google-breakpad: S 91160B80 02000000D00B169150ABD98FF00B169110B6618F88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000C0EA829601000000200D1691300D169101000000F0D1329007000000070000000100000080F0608F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF00000000F8D132902200000088F0608F0700000000000000010000001800D09050F9BB8E010000005C0C1691E0AAFE910700000080F0608FC0EA8296000000001000D090680C16919C0C1691E8ECFE91F4A2D6B6BB14D3B6A80C348F0CB2868CD00C169101000000080A289D90BA618FE01BD19080F0608F00000000FFFFFFFF50F9BB8E01000000380D1691B0B2868C900D1691AC0C1691F80C1691000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFF80F0608F85FFFFFF1000D09085FFFFFFE401DCB46049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E01000000380D1691381FFC90
08-29 16:11:05.284  4311  3887 W google-breakpad: S 91160D00 000000000C0D16918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFF80F0608F85FFFFFF940D1691C0F9BB8E88FCB08E0105000080F0608F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFFC40D1691DC0D169100000000B80D16918C29FC90820100008086C690010000000000000082FFFFFF80F0608F85FFFFFF640E1691C07E768F2CAC878C010A000080F0608F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFF40B9618F0302000000000000900E16918C29FC9002020000C04CC69002000000A0C6C59088FFFFFF
08-29 16:11:05.284  4311  3887 W google-breakpad: S 91160E80 80F0608F85FFFFFF40066F8F88FFFFFF040F16918046FB8DAC90F79E81060000F0D9D19085FFFFFF80F0608F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E80E16910000000083FFFFFF680000004090BA8C88F0608F01000000300000004090BA8C00000000280F16918C29FC9082010000009A458F010000000000000082FFFFFF80F0608F85FFFFFFAC0F1691701FF98DEC88F79E8107000080F0608F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC80F1691C00F1691B80F16912C101691780000004090BA8C000000001694DB9558DB4492C0EA829600000000D00F16918C29FC9082010000409A458F010000000000000082FFFFFF80F0608F85FFFFFF3C1016919815F98DCC7EF79E0106000080F0608F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF
08-29 16:11:05.285  4311  3887 W google-breakpad: S 91161000 0000000082FFFFFF0000000082FFFFFF00000000481016916010169104000000600000004090BA8CE005F98D01000000CC101691F8DFFB9000000000601016918C29FC9082010000609A458F010000000000000082FFFFFF80F0608F85FFFFFFCC101691980FF98DD075F79E0106000080F0608F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000030BA618F0000000010DF0A8E6000000060BA618F0400000040B9618FDC1016917804E19104000000F01016918C29FC9082010000809A458F010000000000000082FFFFFF30BA618F88FFFFFF6C1116919004F98DE46CF79E0107000030BA618F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFF80F0608F85FFFFFF00000000601116915C11169188FFFFFF7000000000BA618F40926F8F84E1F391000000000000000004000000901116918C29FC9082010000009B458F01000000
08-29 16:11:05.285  4311  3887 W google-breakpad: S 91161180 A053199088FFFFFF70B6618F88FFFFFFEC111691606AF48D5066F79E0105000070B6618F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFF40926F8F010000001C1216913412169150000000C0340E8F030200007063178F0C121691C803E1910000000020121691DC7DE190820200002058E18F030000000000000082FFFFFF70B6618F88FFFFFF0000000081FFFFFF40926F8F88FFFFFFBC121691D0D66E8DE832848C0109000040926F8F88FFFFFF0000000081FFFFFF70B6618F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF90EF548E88FFFFFF0000000082FFFFFF0900000081FFFFFF40926F8F88FFFFFF90926F8F00000000EC121691C0D6C2909000000020C0C29040B9618F030200007061F48D0100000000000000E01216918C29FC9082010000B002C3900100000040926F8F88FFFFFF2058E18F88FFFFFF641316912866F48DC05FF79E810700002058E18F88FFFFFF40926F8F88FFFFFF
08-29 16:11:05.285  4311  3887 W google-breakpad: S 91161300 B002C39088FFFFFF90926F8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFF90926F8F88FFFFFF0000000082FFFFFF88131691381FFC90000000004C13169178000000C0340E8F000000001456F79E420300000300000000000000901316918C29FC90020200004058E18F02000000106C089088FFFFFF50ABD98F88FFFFFF40926F8F88FFFFFFFC131691785BF48DE05AF79E0106000040926F8F88FFFFFF50ABD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFCC41FC9044141691481416910000000060000000C0340E8F301416910000000040B9618F0302000000000000281416918C29FC90020200008058E18F020000000037C49088FFFFFF50ABD98F88FFFFFF407C6F8F88FFFFFFC414169158D2BF90FC34B08E01090000407C6F8F88FFFFFF50ABD98F88FFFFFF0037C49088FFFFFF8058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFC0F1608F85FFFFFFF0916F8F88FFFFFF0900000081FFFFFF
08-29 16:11:05.285  4311  3887 W google-breakpad: S 91161480 0900000081FFFFFF0900000081FFFFFFE0056F8F88FFFFFF40B9618F88FFFFFF603FC790010000009000000040B6618FCC141691BC14169108254E9200000000040000001417169120EDE090000400008036C490010000000037C49088FFFFFF50ABD98F88FFFFFF0000000082FFFFFFF02A4E9250ABD98F10B6618FE0B5618F0000000087FFFFFFA00FC390B0B5618FE0B5618FC0056F8FE0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFFB0B5618F88FFFFFF78151691B0B5618F50B5618F80B5618FFCDE868C800200000037C4900000000050B5618F88FFFFFF106F608F8A00000007000000206F608FC0EA829640B0C29020306C8F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFF20306C8F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B65017169101000000
08-29 16:11:05.286  4311  3887 W google-breakpad: S 91161600 81FFFFFFA81616911417169114C4E691603FC7900000000000000000781616912C1616913857FB9058DB4492C0EA82960049DF9594271691000000000000000000000000010000007C1E1691C0EA82960001000000000000B0DD868C00000000603FC790081B1691020000000100000000000000000000000100000081FFFFFF0000000000000000E01A1691F6FFFFFFCCEA829601000000C0EA8296A816169100000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000050171691C0EA8296783B4E920082CA9000000000E8D132901417169137DCE1F800000000C0EA82965017169118171691603FC7900082CA9000000000E8D132903C1716912C650492000000000000000000000000C01ED6B601000000C0EA8296101B169148171691C41A16912466049252E4AF8DFBE5AF8D101B169101000000E80C4492010000000082CA90481716910000000000E6AF8D0200000002000000010000000000000080BA43925C000000
08-29 16:11:05.286  4311  3887 W google-breakpad: S 91161780 0600000000000000802616910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D0000000000000000010000000200000020056F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF691E01816915C1C1691A86604920000000000000000001D169100000000000000000000000000000000000000000000000000000000
08-29 16:11:05.286  4311  3887 W google-breakpad: S 91161900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.286  4311  3887 W google-breakpad: S 91161A80 00000000000000000000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B6001B1691C0EA8296B01B1691101B1691E8D132906C1B1691E46A0492C0F0CB950020F19FC8F0CB9540B0C290101B169101000000F0271691F6FFFFFFCCEA829600000000C0EA8296001B16910300000008000000603FC79088FFFFFF40B0C29088FFFFFF20306C8F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000400000037DCE1F804000000C0EA8296C01B1691B01B1691B81B1691AC1B169182FFFFFFE0D132909C1B16913855F491E0D13290B81B169140B0C29088FFFFFF201C1691301C1691101D169101000000C81B169100000000FC1B169120EB1592B81B1691000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF01000000E0D132900000000082FFFFFFC0EA8296000000006C172F92301C1691201C169100665C9998685C99C0EA8296101D16916C172F926C1C1691B8FA0C92
08-29 16:11:05.286  4311  3887 W google-breakpad: S 91161C00 301C1691841C1691070000004F0000002C97FC8E4C07768F000000004007768F40B0C29088FFFFFFC0EA82960000000020306C8F85FFFFFFC0EA829600000000801C1691187030926D07768FA01C1691101D1691901C1691C0EA8296841C16912200000000665C99D41C1691EC6A0E92E4D82E9250DC2E9258DB4492220000004C07768F0CCE7A8F00000000A41C16912200000000000000281E169100000000BC1C16911435CC91581D1691281E169118C14592201D16910000000001000000101D1691001D169122000000C0EA8296641E169128941192D0D1329000000000C0EA8296F01C169102000000381D169100ABD98F581D1691A0B0618F88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000C0EA829601000000881E1691981E169101000000D0D13290070000000700000001000000B0AE608F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF00000000D8D13290
08-29 16:11:05.287  4311  3887 W google-breakpad: S 91161D80 22000000B8AE608F0700000000000000010000001800D09050F9BB8E01000000C41D1691E0AAFE9107000000B0AE608FC0EA8296000000001000D090D01D1691041E1691E8ECFE91F4A2D6B6BB14D3B6A80C348F0CB2868C381E,169101000000540C848B20B5618FE01BD190B0AE608F00000000FFFFFFFF50F9BB8E01000000A01E1691B0B2868CF81E1691141E1691601E1691000000000000000078B2868C4003000001000000FFFFFFFF81FFFFFFB0AE608F85FFFFFF1000D09085FFFFFFE401DCB46049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E01000000A01E1691381FFC9000000000741E16918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFFB0AE608F85FFFFFFFC1E1691C0F9BB8E88FCB08E01050000B0AE608F85FFFFFF00EAC29088FFFFFF6049C69088FFFFFF0000000082FFFFFF000000002801838B40020000000000005000000030BDC290F0D9D19085FFFFFF2C1F1691441F169100000000201F1691
08-29 16:11:05.287  4311  3887 W google-breakpad: S 91161F00 8C29FC90820100008086C690010000000000000082FFFFFFB0AE608F85FFFFFFCC1F1691C07E768F2CAC878C010A0000B0AE608F85FFFFFF0000000082FFFFFF8086C69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007D09085FFFFFFF0D9D19085FFFFFF82FFFFFF58184E92F0FBD190DC4EF79EA000000030BDC2900000000083FFFFFFD0B3618F0302000000000000F81F16918C29FC9002020000C04CC69002000000A0C6C59088FFFFFFB0AE608F85FFFFFFA0056F8F88FFFFFF6C2016918046FB8DAC90F79E81060000F0D9D19085FFFFFFB0AE608F85FFFFFFA0C6C59088FFFFFFC04CC69088FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000502016910000000083FFFFFF680000004090BA8CB8AE608F01000000300000004090BA8C00000000902016918C29FC9082010000009A458F01000000
08-29 16:11:05.287  4311  3887 W google-breakpad: S 91162080 0000000082FFFFFFB0AE608F85FFFFFF14211691701FF98DEC88F79E81070000B0AE608F85FFFFFF0000000082FFFFFF009A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF30211691282116912021169194211691780000004090BA8C000000001694DB9558DB4492C0EA829600000000382116918C29FC9082010000409A458F010000000000000082FFFFFFB0AE608F85FFFFFFA42116919815F98DCC7EF79E01060000B0AE608F85FFFFFF0000000082FFFFFF409A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B0211691C821169104000000600000004090BA8CE005F98D0100000034221691F8DFFB9000000000C82116918C29FC9082010000609A458F010000000000000082FFFFFFB0AE608F85FFFFFF34221691980FF98DD075F79E01060000B0AE608F85FFFFFF0000000082FFFFFF609A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF
08-29 16:11:05.287  4311  3887 W google-breakpad: S 91162200 0000000082FFFFFF00000000C0B4618F0000000010DF0A8E60000000F0B4618F04000000D0B3618F442216917804E19104000000582216918C29FC9082010000809A458F010000000000000082FFFFFFC0B4618F88FFFFFFD42216919004F98DE46CF79E01070000C0B4618F88FFFFFF0000000082FFFFFF809A458F88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013D19085FFFFFFB0AE608F85FFFFFF00000000C8221691C422169188FFFFFF7000000090B4618FA07B6F8F84E1F391000000000000000004000000F82216918C29FC9082010000009B458F01000000A053199088FFFFFF00B1618F88FFFFFF54231691606AF48D5066F79E0105000000B1618F88FFFFFFA053199088FFFFFF009B458F88FFFFFFC0D3D19085FFFFFFA07B6F8F01000000842316919C23169150000000C0340E8F030200007063178F74231691C803E1910000000088231691DC7DE190820200002058E18F030000000000000082FFFFFF00B1618F88FFFFFF0000000081FFFFFF
08-29 16:11:05.288  4311  3887 W google-breakpad: S 91162380 A07B6F8F88FFFFFF24241691D0D66E8DE832848C01090000A07B6F8F88FFFFFF0000000081FFFFFF00B1618F88FFFFFF0000000082FFFFFF2058E18F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF20EF548E88FFFFFF0000000082FFFFFF0900000081FFFFFFA07B6F8F88FFFFFFF07B6F8F0000000054241691C0D6C2909000000020C0C290D0B3618F030200007061F48D0100000000000000482416918C29FC9082010000B002C39001000000A07B6F8F88FFFFFF2058E18F88FFFFFFCC2416912866F48DC05FF79E810700002058E18F88FFFFFFA07B6F8F88FFFFFFB002C39088FFFFFFF07B6F8F88FFFFFFC0D6C29088FFFFFFC0D0C29088FFFFFF0000000082FFFFFFF07B6F8F88FFFFFF0000000082FFFFFFF0241691381FFC9000000000B424169178000000C0340E8F000000001456F79E420300000300000000000000F82416918C29FC90020200004058E18F02000000106C089088FFFFFF00ABD98F88FFFFFFA07B6F8F88FFFFFF64251691785BF48D
08-29 16:11:05.288  4311  3887 W google-breakpad: S 91162500 E05AF79E01060000A07B6F8F88FFFFFF00ABD98F88FFFFFF106C089088FFFFFF4058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFCC41FC90AC251691B02516910000000060000000C0340E8F9825169100000000D0B3618F0302000000000000902516918C29FC90020200008058E18F020000000037C49088FFFFFF00ABD98F88FFFFFFB0756F8F88FFFFFF2C26169158D2BF90FC34B08E01090000B0756F8F88FFFFFF00ABD98F88FFFFFF0037C49088FFFFFF8058E18F88FFFFFF0000000082FFFFFF0000000082FFFFFFF0AF608F85FFFFFF507B6F8F88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF40056F8F88FFFFFFD0B3618F88FFFFFF603FC7900100000090000000D0B0618FC00900002426169108254E9200000000040000007C28169120EDE090000400008036C490010000000037C49088FFFFFF00ABD98F88FFFFFF0000000082FFFFFFF02A4E9200ABD98FA0B0618F70B0618F0000000087FFFFFFA00FC39040B0618F70B0618F20056F8F
08-29 16:11:05.288  4311  3887 W google-breakpad: S 91162680 E0BB868C80020000C036C490020000000000000082FFFFFFA00FC39088FFFFFF40B0618F88FFFFFFE026169140B0618FD08F678F10B0618FFCDE868C800200000037C49000000000D08F678F88FFFFFFB04E698F8A00000007000000C04E698FC0EA829640B0C290006F608F0037C4902058FB9003020000603FC7900100000040B0C29088FFFFFF006F608F85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C0EA8296C01ED6B6B82816910100000081FFFFFF102816917C28169114C4E691603FC7900000000000000000E0271691942716913857FB9058DB4492C0EA82960049DF95FC38169100000000000000000000000001000000E42F1691C0EA82960001000000000000B0DD868C00000000603FC790702C1691020000000100000000000000000000000100000081FFFFFF0000000000000000482C1691F6FFFFFFCCEA829601000000
08-29 16:11:05.288  4311  3887 W google-breakpad: S 91162800 C0EA829610281691000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B8281691C0EA8296783B4E920082CA9000000000C0D132907C28169137DCE1F800000000C0EA8296B828169180281691603FC7900082CA9000000000C0D13290A42816912C650492000000000000000000000000C01ED6B601000000C0EA8296782C1691B02816912C2C16912466049252E4AF8DFBE5AF8D782C169101000000E80C4492010000000082CA90B02816910000000000E6AF8D0200000002000000010000000000000080BA43925C0000000600000000000000E83716910000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.288  4311  3887 W google-breakpad: S 91162980 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DCAF8D0000000000000000010000000200000080046F8F0083CA90E57E289D000000000000000037DCE1F800000000C01ED6B600000000C0EA8296C8BAF691482A1691C42D1691A86604920000000000000000682E1691000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.289  4311  3887 W google-breakpad: S 91162B00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000400000037DCE1F8C01ED6B6682C1691C0EA8296182D1691782C1691C0D13290D42C1691E46A0492C0F0CB950020F19FC8F0CB9540B0C290782C16910100000058391691F6FFFFFFCCEA829600000000C0EA8296682C16910300000008000000603FC79088FFFFFF40B0C29088FFFFFF006F608F85FFFFFF
08-29 16:11:05.289  4311  3887 W google-breakpad: S 91162C80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000037DCE1F804000000C0EA8296282D1691182D1691202D1691142D169182FFFFFFB8D13290042D16913855F491B8D13290202D169140B0C29088FFFFFF882D1691982D1691782E169101000000302D169100000000642D169120EB1592202D1691000000001800000040B0C290603FC79088FFFFFF0000000082FFFFFF01000000B8D132900000000082FFFFFFC0EA8296000000006C172F92982D1691882D169100665C9998685C99C0EA8296782E16916C172F92D42D1691B8FA0C92982D1691EC2D1691070000004F0000002C97FC8EFC06768F00000000F006768F40B0C29088FFFFFFC0EA829600000000006F608F85FFFFFFC0EA829600000000E82D1691187030921D07768F082E1691782E1691F82D1691C0EA8296EC2D16912200000000665C993C2E1691EC6A0E92E4D82E9250DC2E9258DB449222000000FC06768FDCCD7A8F000000000C2E16912200000000000000
08-29 16:11:05.289  4311  3887 W google-breakpad: S 91162E00 902F169100000000242E16911435CC91C02E1691902F169118C14592882E16910000000001000000782E1691682E169122000000C0EA8296CC2F169128941192A8D1329000000000C0EA8296582E169102000000A02E1691B0AAD98FC02E1691208B678F88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000C0EA829601000000F02F16910030169101000000A8D13290070000000700000001000000A06D608F00000000C0EA82960000000000000000060000003CC145923CC145920600000018C1459200000000FFFFFFFF00000000B0D1329022000000A86D608F0700000000000000010000001800D09050F9BB8E010000002C2F1691E0AAFE9107000000A06D608FC0EA8296000000001000D090382F16916C2F1691E8ECFE91F4A2D6B6BB14D3B6A80C348F0CB2868CA02F169101000000080A289DA08F678FE01BD190A06D608F00000000FFFFFFFF50F9BB8E0100000008301691B0B2868C603016917C2F1691C82F169100000000
,08-29 16:11:05.289  4311  3887 W google-breakpad: S 91162F80 0000000078B2868C4003000001000000FFFFFFFF81FFFFFFA06D608F85FFFFFF1000D09085FFFFFFE401DCB46049C69088FFFFFF88FCB08E00000000FFFFFFFFC0F9BB8E0100000008301691381FFC9000000000DC2F16918C29FC90000000000000000088FCB08E42020000010000006049C69088FFFFFF00EAC29088FFFFFF
08-29 16:11:05.289  4311  3887 W google-breakpad: C 0600004000B02E9D00000000B4B3159130B4159188B31591DCB31591C0EA8296B4B3159130454F8F85FFFFFF00665C99ACB3159170B3159178B315917829F4917C29F49110000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-29 16:11:05.290  4311  3887 W google-breakpad: M B6FBA000 00000000 00005000 E72F8FF84F6E260968CCE78B856F06B70 app_process32
08-29 16:11:05.290  4311  3887 W google-breakpad: M 919FB000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-29 16:11:05.290  4311  3887 W google-breakpad: M A25CC000 007F2000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
08-29 16:11:05.290  4311  3887 W google-breakpad: M A89CC000 00000000 00006000 0D31362517BA6979AC917A35D240E1210 libwebviewchromium_loader.so
08-29 16:11:05.290  4311  3887 W google-breakpad: M A8A70000 00000000 00005000 590854A6A5B5D59683870D00EAE455310 libjnigraphics.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8A75000 00000000 0000A000 4AE1FB560051D628B937E5D0F75C69F30 libcompiler_rt.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8A7F000 00000000 00011000 4CBE9A6CCCBDC8B3EF8B751BC123CEE50 libandroid.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8A90000 00000000 0000C000 AFC34749768B41E8D431AF946E23577B0 libqservice.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8A9C000 00000000 0000B000 356C1D2029892384AFE121956A0BB4EA0 libqdutils.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8AA7000 00000000 00005000 95E7634C1A490462E66752EC8939C4530 libqdMetaData.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8AAC000 00000000 00008000 9997EA703403C3035DE00C7EE7880E430 libmemalloc.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8AB4000 00000000 00008000 3FE99556F2945012B0CB1BE7C353A6540 gralloc.msm8084.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8ABC000 00000000 0000C000 A1BCE730F0644DAE1C5CBC146CD02BD90 eglSubDriverAndroid.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8AC8000 00000000 00027000 2A6DCFEF23E3A32055F90972FCABFED60 libGLESv1_CM_adreno.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A8AEF000 00000000 0073D000 2003920CF0749EC2675D7EE282DE502B0 libllvm-glnext.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A923D000 00000000 004AD000 3082CAE2C0BC6E87686AEAA07100FEDE0 libGLESv2_adreno.so
08-29 16:11:05.291  4311  3887 W google-breakpad: M A96EC000 00000000 0003D000 44E63552D97113055F6017F152FAF0340 libgsl.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M A9729000 00000000 00007000 417C9A0548EF994318FDD8293BD2B4A90 libadreno_utils.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M A9732000 00000000 00013000 B4DF6A0A447291C436FE548566C498C00 libEGL_adreno.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB1C3000 00000000 0001B000 B0EFA02804790BBB6DE8B2B9095BE9CB0 libkeymaster1.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB1DE000 00000000 0000B000 D13E1014D51DECF5BF9D21E7C67666130 libkeymaster_messages.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB1E9000 00000000 00017000 6658C7A49E3552941CE5496BFD2B34980 libsoftkeymasterdevice.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB241000 00000000 0000E000 25D7B988B89B18BC0429BB562FA2DE990 libkeystore_binder.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB24F000 00000000 00006000 B33B16D8A7ED9B8FFB7AA215D6923C4B0 libkeystore-engine.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB255000 00000000 00018000 CEF05C42255586B6905B0AF681C33D8C0 libjavacrypto.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB26E000 00000000 00010000 0C521B6A6E9E39A0E22193BB5D5525130 libstagefright_amrnb_common.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB27E000 00000000 0002C000 582DF60B6AA35307BD7198E3A18119AB0 libexif.so
08-29 16:11:05.292  4311  3887 W google-breakpad: M AB2AB000 00000000 0000D000 7CD678568D893C8FE9A4676BCD58F2AD0 libjhead.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M AB2B9000 00000000 00018000 ADA21AF62918F8A878B3FE4F2F0456580 libmtp.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M AB2D1000 00000000 00048000 0262207412DD5679BF20EB25407B7B440 libmedia_jni.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B070A000 00000000 00036000 E15D31AAB91199642EB180D3D4160C520 libjavacore.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B0791000 00000000 00006000 B37EB6398BB0DBE353FE8B1F1DEAB2EB0 memtrack.msm8084.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B373A000 00000000 00007000 79903F128710C73A4159E0E685663A550 libwebviewchromium_plat_support.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B48A5000 00000000 00459000 D1BC38C6D191DBFC4B3B8BE9676A2FBB0 libart.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B4E36000 00000000 00005000 68126D6F94C506C8BE6DAA402968ABD50 libsigchain.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B4E5E000 00000000 00A5C000 0B64AEBAA12EA3FC8CB4E80A5310D9A20 libLLVM.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B58C3000 00000000 00038000 EB0128750F7A47E1274CC11D426A63840 libbcinfo.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B58FB000 00000000 0005B000 8D9A857B04F62EBCFEC94FC226C49F600 libbcc.so
08-29 16:11:05.293  4311  3887 W google-breakpad: M B5956000 00000000 0000E000 BD9845C69DC7ADC5D6D7E1756D34DD830 libcommon_time_client.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5965000 00000000 0001A000 9AC4BF2FD171753488B9C5DB621A9A240 libprotobuf-cpp-lite.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B597F000 00000000 00009000 9B164CEF29D3AA5EAF47FA86862586FF0 libstagefright_avc_common.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5988000 00000000 00005000 4AA290A61993A8A5677655D665763B3D0 libstagefright_enc_common.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B598D000 00000000 00007000 5146A8AEEE822B0CE87F523ABAE749F50 libpowermanager.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5994000 00000000 0001F000 EF15E47D9893659F6C584D4542F099490 libvorbisidec.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B59B3000 00000000 00007000 9C90BE63E61A2127D39B214E6F43AF350 libstagefright_yuv.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B59BB000 00000000 00032000 C3AC584E1FF634156E2797138D35375E0 libstagefright_omx.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B59ED000 00000000 0003D000 B85FA71D8415B28DE38A933B1508D9F00 libopus.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5A2A000 00000000 0000A000 5BEFFA75C748ED7D23421EF091D1F1300 libmediautils.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5A34000 00000000 0001A000 64DF194390054DFAFF82926D89B359340 libdrmframework.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5A4E000 00000000 00021000 A395A730CEF4C5A1BB47058DE0D9186E0 libRScpp.so
08-29 16:11:05.294  4311  3887 W google-breakpad: M B5A6F000 00000000 00042000 70A461E7FEC54E6D7E1E5C66F936CE350 libRS.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5AB1000 00000000 00009000 FDC63F080EB6155F934F885DEB37E94E0 libspeexresampler.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5ABA000 00000000 0000B000 FFD2B97AE5B754AC2E9678225D23B75A0 libnbaio.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5AC5000 00000000 00014000 669F5236C39ADF5E46701FF6C9F768980 libpcre.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5ADB000 00000000 00007000 21F0774A2FE026AA52F7480655D27ABE0 libwpa_client.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5AE2000 00000000 00071000 C8703400FE46F435C2134FB0F3FDE9390 libGLES_trace.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5B53000 00000000 00067000 1821F1842FA60DF842F94DF364C495A10 libft2.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5BBA000 00000000 00027000 C5A689AFC30DE04B5E7E5ACBF12CA9330 libpng.so
08-29 16:11:05.295  4311  3887 W google-breakpad: M B5BE1000 00000000 00005000 E0AD90DEBEAFB376EBAA5415267856B40 libsync.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5BE6000 00000000 00007000 F5424CDA56569E38CF2903ECFAFF296E0 libstdc++.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5BED000 00000000 00012000 B4E430E8258C544A786360668D84BE8B0 libunwind.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5C45000 00000000 0000B000 96BB8488669F21FEDA8649403EB8BB0E0 libbase.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5C50000 00000000 00007000 D32E249CC58B3A22906A78EDFDD545460 libeffects.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5C58000 00000000 00006000 1964BC7CB1EF496E207C18FC55A57E6C0 libstagefright_http_support.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5C5E000 00000000 0001B000 4E010519E1AA1D9D10F586E0C0490F120 libstagefright_foundation.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5C79000 00000000 0015B000 009817DD6F2FD8255E5AAE0FDE05646B0 libstagefright.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5DD4000 00000000 00070000 4054B4690025F8746C0DC28CC9D69D870 libhwui.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5E44000 00000000 00005000 9CA9EF8816A2E0C106C15197423A91AE0 libradio_metadata.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5E49000 00000000 00006000 F1863EB76C05E59645A8AA848D1624570 libnativebridge.so
08-29 16:11:05.296  4311  3887 W google-breakpad: M B5E4F000 00000000 00006000 1D210F6A59079D7FD7F258724A88DEA70 libprocessgroup.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E55000 00000000 00011000 FDCAD8835C0C336BEB30CF765069FC3A0 libminikin.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E66000 00000000 0000E000 238BED0ADF305646BB994A7A676D0A1E0 libsoundtrigger.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E75000 00000000 0000E000 00FDCB77534A86A2594207ABA92E7FBF0 libradio.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E83000 00000000 00006000 BBCF64A69A9F42E7BC0E0BD423E728790 libnetd_client.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E89000 00000000 00010000 727E80AEB01F5239858F79470BB43E850 libimg_utils.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B5E99000 00000000 00420000 2D9D72FD541F8A7DFBF9302532B5F3870 libpdfium.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B62BA000 00000000 00009000 25B29975558839100CC6E366D29212350 libaudioutils.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B62C3000 00000000 0001D000 DFED0D6F37875A07335517F4E69925120 libz.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B62E1000 00000000 0004E000 66D92DD691765147492F9C21B6AD68960 libharfbuzz_ng.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B632F000 00000000 00007000 9008C23BFACF1EF1DDF142956BF976490 libusbhost.so
08-29 16:11:05.297  4311  3887 W google-breakpad: M B6336000 00000000 0003A000 2D00674AA1DD3C58C05B175DD18EE6050 libjpeg.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B6371000 00000000 000AD000 A52E62FD0AC67AE14A01E7E4847F17620 libmedia.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B641E000 00000000 0017F000 14D5DC468D2218AA5F70C2F6FC6EBBF90 libicui18n.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B659D000 00000000 00123000 0990D8BD31465D945F9282189239AB8F0 libicuuc.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B66C4000 00000000 00026000 C4AA0ABF6C41A8583C0E373BD8CA4EE70 libssl.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B66EA000 00000000 0009D000 A14F571CD9F3F8B6362ACC34BB5E42CA0 libcrypto.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B6787000 00000000 00056000 23B95E0161A14BC00A49FE4C0126E1CF0 libsonivox.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B67E2000 00000000 00011000 87F28481D7D1980E2971DFAD611952AA0 libselinux.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B67F3000 00000000 00008000 4E213F2F80F006F539A0A0DBEC2228870 libhardware_legacy.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B67FC000 00000000 00005000 4025C8440BDADD37826842A415EF9BFF0 libhardware.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B6801000 00000000 00006000 0CBDCDD7DFB535EB3876F8035637EAC00 libETC1.so
08-29 16:11:05.298  4311  3887 W google-breakpad: M B6807000 00000000 0000F000 A7B07D10AF426644931390FF2ABC2FEC0 libGLESv2.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6816000 00000000 0000A000 1B33374FB686F15B59530546D8DB39640 libGLESv1_CM.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6820000 00000000 00068000 DAD11DC7527BFB7648299C3DE956986E0 libEGL.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B688B000 00000000 00065000 E94A253EBAA34A7F995352FCEE8DD0D50 libsqlite.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B68F1000 00000000 0026E000 71785D4C7316B73D74AB9E39653907830 libskia.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6B63000 00000000 0000A000 306A2E96AB94641A8076D9195DA933FF0 libcamera_metadata.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6B6D000 00000000 0002D000 7CA8B61C54BAAABF07F3C7847D490E9F0 libcamera_client.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6B9A000 00000000 00040000 6C63D1A1ED4626296733EE132307BF6E0 libinputflinger.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6BDA000 00000000 0001F000 112B3314840A32B638874B51553126190 libinput.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6BF9000 00000000 0005A000 D55348C7DD771E9409BFBF09AB5AAD720 libgui.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6C53000 00000000 00010000 10F3AFD84F2FA6D8D59A78E2331D8AC50 libui.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6C63000 00000000 00009000 8AAEFDEA9747BCF61A977E5DDA0D22620 libnetutils.so
08-29 16:11:05.299  4311  3887 W google-breakpad: M B6C6C000 00000000 00009000 6C034766ACADC7459DB1EE108B8DDDC70 libnativehelper.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6C75000 00000000 00017000 410352CE283FD8305E8A2FD783B3C8160 libexpat.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6C8C000 00000000 0002A000 41777DBC877E41A9712DDD4792610E7A0 libandroidfw.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6CB6000 00000000 00005000 EC03C38C8A2A3C11A25493EEEE8E58C20 libmemtrack.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6CBB000 00000000 0000B000 6AC6874E2835174DF0B2E6A2BB3511ED0 libbacktrace.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6CC6000 00000000 00022000 771243F4B38A04911D7E2EFFC103E81F0 libm.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6CE8000 00000000 00079000 C45DDC3AA3778947F27583335C11C7260 libc.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6D6B000 00000000 0008E000 4F01D021AD7772AE25722B88EF500DF60 libc++.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6DFA000 00000000 0002D000 C02C38CB58D679FECB52E59A954B4AAD0 libwilhelm.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6E27000 00000000 000DC000 ACD6E6927F2247CE8E5F68E6F5579F0E0 libandroid_runtime.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6F08000 00000000 0002E000 1E5AD4B0BC139C0D5814F52EEC059E2E0 libbinder.so
08-29 16:11:05.300  4311  3887 W google-breakpad: M B6F36000 00000000 0000A000 F2FDFCED2E85559AC020655D564D0FFC0 liblog.so
08-29 16:11:05.301  4311  3887 W google-breakpad: M B6F40000 00000000 0001B000 4E3DF0460B95A69E7A1D4ABE2D8C0A690 libutils.so
08-29 16:11:05.301  4311  3887 W google-breakpad: M B6F5B000 00000000 00011000 78F0BD9C3BF5DE7183A84BD26875408C0 libcutils.so
08-29 16:11:05.301  4311  3887 W google-breakpad: M B6F98000 00000000 00020000 C98C597B4AE800CFB3F0589DF3EDED980 linker
08-29 16:11:05.301  4311  3887 W google-breakpad: -----END BREAKPAD MICRODUMP-----
08-29 16:11:05.330  3836  3887 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-29 16:11:05.330  3836  3887 W google-breakpad: Chrome build fingerprint:
08-29 16:11:05.330  3836  3887 W google-breakpad: 0.0.1
08-29 16:11:05.330  3836  3887 W google-breakpad: 19
08-29 16:11:05.330  3836  3887 W google-breakpad: 6ec9b36e-71c4-4d7b-882c-6b145c858100
08-29 16:11:05.331  3836  3887 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-29 16:11:05.331  3836  3887 E chromium: ### WebView Version 44.0.2403.117 (code 246011700)
--------- beginning of crash
08-29 16:11:05.331  3836  3887 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 3887 (Thread-333)
,08-29 16:11:05.389   373   373 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-29 16:11:05.389   373   373 F DEBUG   : Build fingerprint: 'google/shamu/shamu:6.0.1/MOB30M/2862625:user/release-keys'
08-29 16:11:05.389   373   373 F DEBUG   : Revision: '0'
,08-29 16:11:05.389   373   373 F DEBUG   : ABI: 'arm'
,08-29 16:11:05.389   373   373 F DEBUG   : pid: 3836, tid: 3887, name: Thread-333  >>> com.test.thalitest <<<
,08-29 16:11:05.390   373   373 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-29 16:11:05.411   373   373 F DEBUG   :     r0 9d2eb000  r1 00000000  r2 9115b3b4  r3 9115b430
,08-29 16:11:05.412   373   373 F DEBUG   :     r4 9115b388  r5 9115b3dc  r6 9682eac0  r7 9115b3b4
08-29 16:11:05.412   373   373 F DEBUG   :     r8 8f4f4530  r9 ffffff85  sl 995c6600  fp 9115b3ac
08-29 16:11:05.412   373   373 F DEBUG   :     ip 9115b370  sp 9115b378  lr 91f42978  pc 91f4297c  cpsr 200f0010
,08-29 16:11:05.416   373   373 F DEBUG   : 
08-29 16:11:05.416   373   373 F DEBUG   : backtrace:
,08-29 16:11:05.416   373   373 F DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-29 16:11:05.416   373   373 F DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
08-29 16:11:05.417   373   373 F DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,08-29 16:11:06.221   373   373 F DEBUG   : ,
08-29 16:11:06.221   373   373 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_02
08-29 16:11:06.221   373   373 E DEBUG   : AM write failed: Broken pipe
,08-29 16:11:06.223   876   892 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE),
,08-29 16:11:06.234   876  4312 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-29 16:11:06.237   280   280 E lowmemorykiller: Error writing /proc/3836/oom_score_adj; errno=22
,08-29 16:11:06.237   876  4312 I ActivityManager: Killing 3693:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 16:11:06.334   876   887 I WindowState: WIN DEATH: Window{bc0dcd2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 16:11:06.335   876  1692 D GraphicsStats: Buffer count: 2
08-29 16:11:06.335   876  1309 D WifiService: Client connection lost with reason: 4
,08-29 16:11:06.361   876  1402 I ActivityManager: Process com.test.thalitest (pid 3836) has died
,08-29 16:11:06.360   389   389 I Zygote  : Process 3836 exited due to signal (11)
,08-29 16:11:06.424   876  1968 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3836 uid 10000
,08-29 16:11:06.426  1876  1876 I Keyboard.Facilitator: onFinishInput()
,08-29 16:11:08.283   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=245490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:11:08.307  3753  4314 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:11:08.352  3753  4315 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:11:08.377  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:08.383  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:08.448  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:11:08.448  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:11:08.449  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:11:08.449  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:11:08.524  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:08.528  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:08.566  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:11:08.566  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:11:08.566  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:11:08.566  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:11:08.593  3753  4315 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:11:08.594  3753  4314 E BooksSync: Soft error
08-29 16:11:08.594  3753  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:11:08.594  3753  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:11:08.594  3753  4314 E BooksSync: Sync error
08-29 16:11:08.594  3753  4314 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:11:08.594  3753  4314 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:11:08.594  3753  4314 I BooksSync: Finished books sync,
,08-29 16:11:08.605   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 245422, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:11:31.272   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268479, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:11:38.825  3037  4318 V KeepSync: Connecting to GoogleApiClient
,08-29 16:11:38.826   876  1383 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:11:38.878  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:38.880  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:11:38.909  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 16:11:38.909  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 16:11:38.909  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:11:38.909  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:11:38.926  1716  4319 V BaseAuthAsyncOperation: access token request failed
,08-29 16:11:38.927  3037  4318 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:11:38.978  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 16:11:38.978  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:11:38.978  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:11:38.978  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:11:38.995  3037  4318 E KeepSync: IOException
08-29 16:11:38.995  3037  4318 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:11:38.995  3037  4318 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:11:38.995  3037  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:11:38.995  3037  4318 E KeepSync: 	... 10 more
08-29 16:11:38.995  3037  4318 W KeepSync: Sync result 2
,08-29 16:11:39.005   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 252247, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:11:57.352   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294559, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:12:06.467  1876  1927 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-29 16:12:06.467  1876  1927 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 16:12:06.508  1503  1503 I ConfigService: onCreate
,08-29 16:12:09.437  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:09.442  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:09.500  1503  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 16:12:09.501  1503  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 16:12:09.501  1503  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:12:09.501  1503  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:09.535  3550  4327 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:12:09.535  3550  4327 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:12:09.535  3550  4327 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	... 12 more
08-29 16:12:09.535  3550  4327 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at fal.a(PG:38)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:12:09.535  3550  4327 E HttpOperation: 	... 14 more
,08-29 16:12:09.603  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:12:09.603  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 16:12:09.603  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:12:09.603  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:09.624  3550  4327 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:12:09.624  3550  4327 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at hec.a(PG:42)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at hee.a(PG:102)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at czr.a(PG:65)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at kka.a(PG:108)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:12:09.624  3550  4327 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	... 15 more
08-29 16:12:09.624  3550  4327 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at fal.a(PG:38)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:12:09.624  3550  4327 E HttpOperation: 	... 17 more
,08-29 16:12:09.625  3550  4327 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:12:09.625  3550  4327 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	... 15 more
08-29 16:12:09.625  3550  4327 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:12:09.625  3550  4327 E ExperimentLoader: 	... 17 more
,08-29 16:12:09.736   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 285779, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:12:11.581  1503  1503 I ConfigService: onDestroy
,08-29 16:12:28.205   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325412, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:12:37.206  1503  2091 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 16:12:37.323  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:37.325  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:37.335  3780  4329 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:12:37.358  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-29 16:12:37.358  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 16:12:37.358  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:12:37.359  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:12:37.375  3780  4329 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:12:39.837  3753  4331 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:12:39.884  3753  4333 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:12:39.931  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:12:39.931  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 16:12:39.931  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:12:39.931  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:39.968  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:12:39.969  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:12:39.969  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:12:39.969  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:39.978  3037  4332 V KeepSync: Connecting to GoogleApiClient
,08-29 16:12:39.979   876  2000 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:12:39.982  3753  4333 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:12:39.983  3753  4331 E BooksSync: Soft error
08-29 16:12:39.983  3753  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:12:39.983  3753  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:12:39.983  3753  4331 E BooksSync: Sync error
08-29 16:12:39.983  3753  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:12:39.983  3753  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:12:39.983  3753  4331 I BooksSync: Finished books sync
,08-29 16:12:40.003   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307981, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:12:40.063  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 16:12:40.063  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 16:12:40.063  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:12:40.063  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:40.087  1716  4334 V BaseAuthAsyncOperation: access token request failed
,08-29 16:12:40.088  3037  4332 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:12:40.141  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 16:12:40.142  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:12:40.142  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:12:40.142  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:40.169  3037  4332 E KeepSync: IOException
08-29 16:12:40.169  3037  4332 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:12:40.169  3037  4332 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:12:40.169  3037  4332 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:12:40.169  3037  4332 E KeepSync: 	... 10 more
,08-29 16:12:40.169  3037  4332 W KeepSync: Sync result 2
,08-29 16:12:40.176   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 308489, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:12:45.324  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:45.343  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:45.350  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:12:45.435  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 16:12:45.435  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-29 16:12:45.436  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:12:45.436  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:12:45.481  1503  2045 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-29 16:12:45.481  1503  2045 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 16:12:45.494  3510  3539 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 16:12:45.494  3510  3539 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-29 16:12:45.494  3510  3539 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-29 16:12:45.494  3510  3539 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-29 16:12:45.494  3510  3539 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-29 16:12:45.494  3510  3539 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-29 16:12:45.494  3510  3539 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 16:13:10.519  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:13:10.521  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:13:10.556  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 16:13:10.557  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:13:10.557  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:13:10.557  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:13:10.575  3550  4341 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:13:10.575  3550  4341 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:13:10.575  3550  4341 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	... 12 more
08-29 16:13:10.575  3550  4341 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at fal.a(PG:38)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:13:10.575  3550  4341 E HttpOperation: 	... 14 more
,08-29 16:13:10.662  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:13:10.662  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:13:10.662  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:13:10.662  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:13:10.675  3550  4341 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:13:10.675  3550  4341 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at hec.a(PG:42)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at hee.a(PG:102)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at czr.a(PG:65)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at kka.a(PG:108)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:13:10.675  3550  4341 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	... 15 more
08-29 16:13:10.675  3550  4341 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at fal.a(PG:38)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:13:10.675  3550  4341 E HttpOperation: 	... 17 more
,08-29 16:13:10.676  3550  4341 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:13:10.676  3550  4341 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	... 15 more
08-29 16:13:10.676  3550  4341 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:13:10.676  3550  4341 E ExperimentLoader: 	... 17 more
,08-29 16:13:10.814   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 338069, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:13:12.283   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=369490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:13:44.819  3037  4344 V KeepSync: Connecting to GoogleApiClient
,08-29 16:13:44.820   876  1402 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:13:44.876  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:13:44.877  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:13:44.911  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-29 16:13:44.912  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 16:13:44.912  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:13:44.912  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:13:44.933  1716  4345 V BaseAuthAsyncOperation: access token request failed
,08-29 16:13:44.934  3037  4344 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:13:45.003  1503  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 16:13:45.003  1503  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 16:13:45.003  1503  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:13:45.003  1503  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:13:45.029  3037  4344 E KeepSync: IOException
08-29 16:13:45.029  3037  4344 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:13:45.029  3037  4344 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:13:45.029  3037  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:13:45.029  3037  4344 E KeepSync: 	... 10 more
08-29 16:13:45.029  3037  4344 W KeepSync: Sync result 2
,08-29 16:13:45.044   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 401936, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:14:06.725   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:14:15.460  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:15.462  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:15.503  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:14:15.503  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:14:15.503  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:14:15.503  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:14:15.526  3550  4348 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:14:15.526  3550  4348 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:14:15.526  3550  4348 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	... 12 more
08-29 16:14:15.526  3550  4348 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at fal.a(PG:38)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:14:15.526  3550  4348 E HttpOperation: 	... 14 more
,08-29 16:14:15.626  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:14:15.626  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:14:15.626  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:14:15.626  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:14:15.668  3550  4348 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:14:15.668  3550  4348 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at hec.a(PG:42)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at hee.a(PG:102)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at czr.a(PG:65)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at kka.a(PG:108)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:14:15.668  3550  4348 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	... 15 more
08-29 16:14:15.668  3550  4348 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at fal.a(PG:38)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:14:15.668  3550  4348 E HttpOperation: 	... 17 more
,08-29 16:14:15.668  3550  4348 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:14:15.668  3550  4348 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	... 15 more
08-29 16:14:15.668  3550  4348 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:14:15.668  3550  4348 E ExperimentLoader: 	... 17 more
,08-29 16:14:15.796   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 430272, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:14:32.765   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449972, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:14:45.883  3753  4352 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 16:14:45.916  3753  4353 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 16:14:45.926  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:45.931  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:45.964  1503  2045 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:14:45.964  1503  2045 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:14:45.964  1503  2045 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:14:45.964  1503  2045 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:14:45.996  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:45.999  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:14:46.040  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 16:14:46.040  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 16:14:46.041  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:14:46.041  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:14:46.068  3753  4353 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 16:14:46.069  3753  4352 E BooksSync: Soft error
08-29 16:14:46.069  3753  4352 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:14:46.069  3753  4352 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 16:14:46.069  3753  4352 E BooksSync: Sync error
08-29 16:14:46.069  3753  4352 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 16:14:46.069  3753  4352 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 16:14:46.069  3753  4352 I BooksSync: Finished books sync
,08-29 16:14:46.086   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 461547, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:14:47.270   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=464477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:15:13.297   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=490504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:15:46.979   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=524186, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:15:54.274  3037  4357 V KeepSync: Connecting to GoogleApiClient
,08-29 16:15:54.275   876  1967 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 16:15:54.352  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:15:54.356  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:15:54.402  1503  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-29 16:15:54.402  1503  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 16:15:54.403  1503  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 16:15:54.403  1503  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:15:54.436  1716  4358 V BaseAuthAsyncOperation: access token request failed
08-29 16:15:54.438  3037  4357 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 16:15:54.513  1503  3105 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 16:15:54.513  1503  3105 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 16:15:54.513  1503  3105 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:15:54.513  1503  3105 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:15:54.538  3037  4357 E KeepSync: IOException
08-29 16:15:54.538  3037  4357 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 16:15:54.538  3037  4357 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 16:15:54.538  3037  4357 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 16:15:54.538  3037  4357 E KeepSync: 	... 10 more
08-29 16:15:54.538  3037  4357 W KeepSync: Sync result 2
,08-29 16:15:54.551   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 531356, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:16:13.032   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=550239, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:16:18.630   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=555837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:16:24.944  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:16:24.947  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:16:24.992  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:16:24.992  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:16:24.992  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:16:24.992  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:16:25.022  3550  4361 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 16:16:25.022  3550  4361 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at blb.a(PG:3937)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at czp.a(PG:18188)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:16:25.022  3550  4361 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	... 12 more
08-29 16:16:25.022  3550  4361 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at fal.a(PG:38)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:16:25.022  3550  4361 E HttpOperation: 	... 14 more
,08-29 16:16:25.102  1503  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 16:16:25.103  1503  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 16:16:25.103  1503  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:16:25.103  1503  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:16:25.124  3550  4361 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 16:16:25.124  3550  4361 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jdm.a(PG:82)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jcs.o(PG:406)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jcn.a(PG:1379)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jcs.i(PG:143)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at hec.a(PG:42)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at hee.a(PG:102)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at czr.a(PG:65)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at kka.a(PG:108)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at czp.a(PG:19176)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at czp.a(PG:9081)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at czq.run(PG:1686)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:16:25.124  3550  4361 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jdj.a(PG:4091)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jdj.a(PG:1125)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jdm.a(PG:77)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	... 15 more
08-29 16:16:25.124  3550  4361 E HttpOperation: Caused by: faj: BadAuthentication
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at fal.a(PG:38)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	at jdj.a(PG:4089)
08-29 16:16:25.124  3550  4361 E HttpOperation: 	... 17 more
,08-29 16:16:25.125  3550  4361 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 16:16:25.125  3550  4361 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at hec.a(PG:42)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at hee.a(PG:102)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at czr.a(PG:65)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at kka.a(PG:108)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	... 15 more
08-29 16:16:25.125  3550  4361 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at fal.a(PG:38)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 16:16:25.125  3550  4361 E ExperimentLoader: 	... 17 more
,08-29 16:16:25.276   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 557505, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 16:16:37.473  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:16:37.477  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:16:37.490  3780  4363 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:16:37.515  1503  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 16:16:37.515  1503  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 16:16:37.515  1503  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:16:37.515  1503  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:16:37.538  3780  4363 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:16:44.710   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=581917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:16:50.257   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:17:16.285   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=613492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:17:51.272   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648479, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 16:18:17.298   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=674505, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:25:42.359  1716  4391 I EventLogService: Opted in for usage reporting
,08-29 16:25:42.360  1716  4391 I EventLogService: Aggregate from 1472478786783 (log), 1472478786783 (data)
,08-29 16:25:42.400  1716  4391 W EventLogAggregator: Unknown tag: snet_gcore
,08-29 16:25:42.400  1716  4391 W EventLogAggregator: Unknown tag: snet_launch_service
,08-29 16:25:42.506  1716  4391 I ServiceDumpSys: dumping service [account]
,08-29 16:25:42.540  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:25:42.542  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 16:25:42.559  3780  4395 V GoogleAuthProtoRequest: [323] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 16:25:42.643  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 16:25:42.643  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 16:25:42.643  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 16:25:42.643  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 16:25:42.658  3780  4395 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 16:25:47.536   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1124743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 16:26:04.658   876  4265 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141865, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 16:27:21.376   876   888 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-29 16:32:37.286  4417  4417 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 16:32:37.291  4417  4417 D AndroidRuntime: CheckJNI is OFF
08-29 16:32:37.326  4417  4417 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 16:32:37.368  4417  4417 I Radio-JNI: register_android_hardware_Radio DONE
08-29 16:32:37.389  4417  4417 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 16:32:37.400   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-29 16:32:37.523   876   899 W PackageSettings: Skipping PackageSetting{c84dc4a com.example.hello/10273} due to missing metadata
08-29 16:32:37.580   876   899 I art     : Starting a blocking GC Explicit
08-29 16:32:37.636   876   899 I art     : Explicit concurrent mark sweep GC freed 19829(1268KB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 732us total 56ms
08-29 16:32:37.659   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-29 16:32:37.665  4417  4417 I art     : System.exit called, status: 0
08-29 16:32:37.666  4417  4417 I AndroidRuntime: VM exiting with result code 0.
08-29 16:32:37.669   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-29 16:32:37.687  4207  4207 D BluetoothMapAppObserver: onReceive
08-29 16:32:37.687  4207  4207 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 16:32:37.694   876  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 16:32:37.697  1876  1876 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 16:32:37.697  1889  2249 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 16:32:37.700  3639  3639 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-29 16:32:37.711  1876  4432 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 16:32:37.723  1876  4432 I Decoder : createOrResetDecoder
08-29 16:32:37.742  1961  1961 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-29 16:32:37.751   876  1402 I ActivityManager: Start proc 4435:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-29 16:32:37.755  1503  1503 I ConfigService: onCreate
08-29 16:32:37.775  1876  4432 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-29 16:32:37.783   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 16:32:37.802  1876  4432 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-29 16:32:37.804  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 16:32:37.804  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-29 16:32:37.806  4435  4435 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-29 16:32:37.809  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 16:32:37.809  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 16:32:37.810  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 16:32:37.810  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 16:32:37.810  1973  2089 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 16:32:37.811   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-29 16:32:37.811  1876  4432 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 16:32:37.811  1876  4432 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 16:32:37.811  1876  4432 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 16:32:37.811  1876  4432 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 16:32:37.811   876   888 E PackageManager: Failed to write settings, restoring backup
08-29 16:32:37.811   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 16:32:37.811   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 16:32:37.811   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 16:32:37.811   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 16:32:37.811   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 16:32:37.811   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:37.811   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.811   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:37.811  1876  4432 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 16:32:37.811  1876  4432 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-29 16:32:37.815   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-29 16:32:37.815   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 16:32:37.815   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:32:37.815   876   889 E DropBoxManagerService: 	... 13 more
08-29 16:32:37.823   876  1968 I ActivityManager: Start proc 4450:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-29 16:32:37.823  1973  2089 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 16:32:37.823  1973  2089 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1973
08-29 16:32:37.823  1973  2089 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.823  1973  2089 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:37.824   876  1383 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:32:37.825   876  4458 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:32:37.825   876  4458 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:32:37.825   876  4458 E DropBoxManagerService: 	... 5 more
08-29 16:32:37.836  1973  2089 I Process : Sending signal. PID: 1973 SIG: 9
08-29 16:32:37.878  4435  4435 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-29 16:32:37.888   280   280 E lowmemorykiller: Error writing /proc/1973/oom_score_adj; errno=22
08-29 16:32:37.891   876  2024 D GraphicsStats: Buffer count: 1
08-29 16:32:37.891   876  2000 I WindowState: WIN DEATH: Window{aadc52c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 16:32:37.902   876  1968 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1973) has died
08-29 16:32:37.904   876  1968 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 16:32:37.905   876  1968 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 16:32:37.911  4435  4468 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 16:32:37.921   876  2005 I ActivityManager: Start proc 4470:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 16:32:37.933   876   889 I ActivityManager: Start proc 4480:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:32:37.960  4470  4470 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:32:37.982  4480  4480 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:32:37.982  4480  4480 D AndroidRuntime: Shutting down VM
08-29 16:32:37.983  1716  4487 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-29 16:32:37.983  1716  4487 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-29 16:32:37.985  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-29 16:32:37.986  1503  1503 D AndroidRuntime: Shutting down VM
08-29 16:32:37.986  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:32:37.986  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
08-29 16:32:37.986  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 16:32:37.986  1503  1503 E AndroidRuntime: 	... 8 more
08-29 16:32:37.992  4480  4480 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:32:37.992  4480  4480 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4480
08-29 16:32:37.992  4480  4480 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:32:37.992  4480  4480 E AndroidRuntime: 	... 10 more
08-29 16:32:37.995   876  4498 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:32:37.995   876  4498 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:32:37.995   876  4498 E DropBoxManagerService: 	... 5 more
08-29 16:32:37.996  1503  1503 I Process : Sending signal. PID: 1503 SIG: 9
08-29 16:32:37.996   876  1402 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:32:37.997   876  4499 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:32:37.997   876  4499 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:32:37.997   876  4499 E DropBoxManagerService: 	... 5 more
08-29 16:32:37.997  4480  4480 I Process : Sending signal. PID: 4480 SIG: 9
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.003  4435  4465 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:38.012  1716  4487 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-29 16:32:38.013  1716  4487 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.014  4435  4465 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:38.023   876  1967 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4480) has died
08-29 16:32:38.025   876  1967 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 16:32:38.034   876  1309 D WifiService: Client connection lost with reason: 4
08-29 16:32:38.038   876   889 I ActivityManager: Start proc 4501:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:32:38.039   876  2011 I ActivityManager: Process com.google.process.gapps (pid 1503) has died
08-29 16:32:38.039   876  2011 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-29 16:32:38.039   876  2011 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-29 16:32:38.039   876  2011 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-29 16:32:38.049  1716  1716 W RocketImpressions: ClearcutLogger connection suspended: 1
08-29 16:32:38.060   876  1402 I ActivityManager: Start proc 4513:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:32:38.092  4501  4501 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:32:38.092  4501  4501 D AndroidRuntime: Shutting down VM
08-29 16:32:38.101  4501  4501 E AndroidRuntime: FATAL EXCEPTION: main
08-29 16:32:38.101  4501  4501 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4501
08-29 16:32:38.101  4501  4501 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 16:32:38.101  4501  4501 E AndroidRuntime: 	... 10 more
08-29 16:32:38.103   876  1402 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 16:32:38.103  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 16:32:38.103  1716  1716 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 16:32:38.103  4501  4501 I Process : Sending signal. PID: 4501 SIG: 9
08-29 16:32:38.105   876  4527 E DropBoxManagerService: Can't write: system_app_crash
08-29 16:32:38.105   876  4527 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 16:32:38.105   876  4527 E DropBoxManagerService: 	... 5 more
08-29 16:32:38.119  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 16:32:38.119  1716  1716 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 16:32:38.122  1716  4487 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-29 16:32:38.123  1716  4487 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-29 16:32:38.125  4513  4513 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-29 16:32:38.127  4435  4465 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-29 16:32:38.134   876  2011 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
08-29 16:32:38.135   876  2011 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-29 16:32:38.135   876  2011 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 16:32:38.135   876  2011 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
08-29 16:32:38.137  1716  4529 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 16:32:38.143  4513  4513 I MultiDex: VM with version 2.1.0 has multidex support
08-29 16:32:38.143  4513  4513 I MultiDex: install
08-29 16:32:38.143  4513  4513 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 16:32:38.152  1716  4529 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 16:32:38.152  1716  4529 E AndroidRuntime: Process: com.google.android.gms, PID: 1716
08-29 16:32:38.152  1716  4529 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 16:32:38.152  1716  4529 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.153  4435  4468 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 16:32:38.153  4435  4468 E AndroidRuntime: Process: android.process.acore, PID: 4435
08-29 16:32:38.153  4435  4468 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 16:32:38.153  4435  4468 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 16:32:38.154  4435  4465 I Process : Sending signal. PID: 4435 SIG: 9

```
