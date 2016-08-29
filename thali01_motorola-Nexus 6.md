#### Test 8289468293e136b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-29 13:12:09.279   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-29 13:12:09.944  3751  3751 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 13:12:09.949  3751  3751 D AndroidRuntime: CheckJNI is OFF
08-29 13:12:09.994  3751  3751 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 13:12:10.073  3751  3751 I Radio-JNI: register_android_hardware_Radio DONE
08-29 13:12:10.099  3751  3751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:12:10.104   874  1982 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 13:12:10.132  2033  2045 W SearchService: Abort, client detached.
08-29 13:12:10.136  3751  3751 D AndroidRuntime: Shutting down VM
08-29 13:12:10.140  2033  2033 I HotwordDetector: Closing mic
08-29 13:12:10.140  2033  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@77dc658
08-29 13:12:10.141  2033  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 13:12:10.166   874  2046 I ActivityManager: Start proc 3760:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 13:12:10.185   377  2349 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 13:12:10.186   377  2349 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 13:12:10.192   377  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 13:12:10.194  2033  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 13:12:10.194  2033  2345 I MicroRecognitionRnrImpl: Detection finished
08-29 13:12:10.235  3760  3760 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 13:12:10.258  3760  3760 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 13:12:10.264  3760  3760 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7418-7420)
08-29 13:12:10.265  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:10.276  3760  3760 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {73a3358}
08-29 13:12:10.276  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:12:10.277  3760  3760 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:12:10.282  3760  3760 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 13:12:10.283  3760  3760 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 13:12:10.295  3760  3760 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 13:12:10.306  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:12:10.306  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:12:10.306  3760  3760 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:12:10.306  3760  3760 I Adreno  : Build Date                       : 10/20/15
08-29 13:12:10.306  3760  3760 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:12:10.306  3760  3760 I Adreno  : Local Branch                     : M14
08-29 13:12:10.306  3760  3760 I Adreno  : Remote Branch                    : 
08-29 13:12:10.306  3760  3760 I Adreno  : Remote Branch                    : 
08-29 13:12:10.306  3760  3760 I Adreno  : Reconstruct Branch               : 
,08-29 13:12:10.368   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb724e3:true
08-29 13:12:10.389  3760  3760 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 13:12:10.401  3760  3760 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-29 13:12:10.444  3760  3798 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-29 13:12:10.451  3760  3785 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-29 13:12:10.492  3760  3798 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 13:12:10.552   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +413ms
08-29 13:12:10.560  1884  1884 I Keyboard.Facilitator: onFinishInput()
08-29 13:12:10.661  3760  3760 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3760
08-29 13:12:10.766  3760  3760 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-29 13:12:10.947   874  2015 I ActivityManager: Killing 2981:com.google.android.calendar/u0a37 (adj 15): empty #17
08-29 13:12:10.970  3760  3800 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1697973968
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 13:12:10.976  3760  3800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d63cf added. We now have 1 listener(s)
08-29 13:12:10.979  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-29 13:12:10.980  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:10.980  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:10.980  3760  3800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 13:12:10.984  3760  3800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16abd3a added. We now have 1 listener(s)
08-29 13:12:10.984  3760  3800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:10.989   874  1310 D WifiService: New client listening to asynchronous messages
08-29 13:12:10.989  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:10.989  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 13:12:10.989   874  2015 I ActivityManager: Killing 3096:com.google.android.apps.maps/u0a65 (adj 15): empty #18
08-29 13:12:10.991  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:12:10.991  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:12:10.991  3760  3800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 13:12:11.029  3760  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:11.030  3760  3800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-29 13:12:11.033  3760  3800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:11.033  3760  3800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:11.033  3760  3800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:12:11.033  3760  3800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:11.034  3760  3800 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:12:11.184  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:11.191  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:11.194  3760  3760 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-29 13:12:11.914  3760  3810 W jxcore-log: Initializing JXcore engine
08-29 13:12:11.915  3760  3810 W jxcore-log: JXcore engine is ready
08-29 13:12:11.953  3810  3810 W Thread-318: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8941 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-29 13:12:11.953  3810  3810 W Thread-318: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11964]" dev="sockfs" ino=11964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 13:12:11.953  3810  3810 W Thread-318: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 13:12:11.953  3810  3810 W Thread-318: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24260]" dev="sockfs" ino=24260 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-29 13:12:11.968  3760  3810 W jxcore-log: Starting JXcore engine
,08-29 13:12:12.053  3760  3810 W jxcore-log: Platform android
08-29 13:12:12.053  3760  3810 W jxcore-log: 
,08-29 13:12:12.053  3760  3810 W jxcore-log: Process ARCH arm
08-29 13:12:12.053  3760  3810 W jxcore-log: 
,08-29 13:12:12.302   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 13:12:12.362  3760  3810 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:12:12.362  3760  3810 I jxcore-log: 
,08-29 13:12:12.362  3760  3810 W jxcore-log: JXcore engine is started
,08-29 13:12:12.371  3760  3800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 13:12:12.376  3760  3760 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 13:12:15.813   874  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 13:12:18.209  3040  3817 V KeepSync: Connecting to GoogleApiClient
08-29 13:12:18.209   874  1951 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 13:12:18.248  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:18.249  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:18.264  1499  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
08-29 13:12:18.264  1499  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 13:12:18.264  1499  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:18.264  1499  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:12:18.275  1694  3818 V BaseAuthAsyncOperation: access token request failed
08-29 13:12:18.276  3040  3817 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 13:12:18.354  1499  2170 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 13:12:18.354  1499  2170 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 13:12:18.355  1499  2170 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:18.355  1499  2170 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-29 13:12:18.378  3040  3817 E KeepSync: IOException
08-29 13:12:18.378  3040  3817 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 13:12:18.378  3040  3817 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:12:18.378  3040  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 13:12:18.378  3040  3817 E KeepSync: 	... 10 more
,08-29 13:12:18.380  3040  3817 W KeepSync: Sync result 2
,08-29 13:12:18.387   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 124525, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 13:12:20.404  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:20.428  1499  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 13:12:20.428  1499  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:12:20.428  1499  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:20.428  1499  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:12:20.440  3512  3512 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 13:12:20.440  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 13:12:20.440  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 13:12:22.372  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 13:12:22.372  3760  3810 I jxcore-log: 
,08-29 13:12:22.375  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 13:12:22.375  3760  3810 I jxcore-log: 
,08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:22.388  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:22.394  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:22.396  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:12:22.396  3760  3810 I jxcore-log: 
,08-29 13:12:22.398  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:12:22.398  3760  3810 I jxcore-log: 
,08-29 13:12:22.904  3760  3810 D executeNativeTests: Running unit tests
,08-29 13:12:22.961  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:22.961  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c added. We now have 2 listener(s)
08-29 13:12:22.962  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:22.962  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:22.962  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:22.962  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:22.962  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 added. We now have 2 listener(s)
08-29 13:12:22.962  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:22.963  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:22.967  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:22.985  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:22.989  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:22.989  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:22.992  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:22.993  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:12:22.993  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:12:22.995  3760  3810 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 13:12:22.995  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 13:12:22.995  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:22.995  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 13:12:22.995  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:22.996  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:22.996  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:22.996  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:22.996  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:22.996  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:22.996  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:22.996  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:22.997  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c removed from the list
08-29 13:12:22.997  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:22.997  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 removed from the list
,08-29 13:12:22.999  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.000  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.001  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:23.001  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.003  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.004  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:23.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.006  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.013  3760  3810 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 13:12:23.015  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:23.015  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:23.016  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.016  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.017  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.017  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:23.017  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.017  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:23.018  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.018  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.018  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.018  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.018  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.019  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.021  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:23.021  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.021  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.022  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.029  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:23.029  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:23.029  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:23.029  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:23.029  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:23.030  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:12:23.031  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:23.031  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.031  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:23.031  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.032  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.032  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.032  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.032  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.032  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.032  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.032  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:23.032  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.032  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.032  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.032  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.033  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.034  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.034  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.034  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.034  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:12:23.036  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:23.042  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:23.045  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:23.045  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:23.045  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:23.046  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 13:12:23.046  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:12:23.046  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:23.047  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:23.048  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.051  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:23.052  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:12:23.052  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:23.057  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:23.059  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 13:12:23.059  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:23.061  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 13:12:23.065  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 13:12:23.065  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:23.065  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:12:23.066  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:12:23.067  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:23.071  2693  2860 D BtGatt.GattService: registerClient() - UUID=5065a482-9565-48c4-afae-6350d44c784c
,08-29 13:12:23.072  2693  2714 D BtGatt.GattService: onClientRegistered() - UUID=5065a482-9565-48c4-afae-6350d44c784c, clientIf=5
,08-29 13:12:23.072  3760  3772 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:12:23.073  2693  2706 D BtGatt.GattService: start scan with filters
,08-29 13:12:23.076  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:23.076  2693  2718 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:23.076  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:12:23.077  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:23.077  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:12:23.077  2693  2718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:23.078  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:23.079  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:23.079  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-29 13:12:23.080  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:23.082  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:12:23.084  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.084  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:23.084  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:23.084  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:23.084  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.084  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:12:23.084  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 13:12:23.084  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:12:23.084  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:23.085  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:23.085  2693  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:12:23.085  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.085  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 13:12:23.085  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:12:23.085  2693  2718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:12:23.086  3760  3810 D BluetoothAdapter: STATE_ON
08-29 13:12:23.086  2693  3507 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:23.087  2693  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:12:23.087  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:12:23.087  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:23.087  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:12:23.087  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:23.087  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:23.088  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:23.088  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:23.088  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:12:23.088  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:23.089  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:23.090  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:23.090  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:23.090  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:23.090  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:23.090  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.090  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:23.090  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
,08-29 13:12:23.090  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:23.090  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
,08-29 13:12:23.090  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:23.090  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:23.091  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:12:23.092  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:23.093  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:12:23.093  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.093  2693  2718 D BtGatt.ScanManager: Starting BLE batch scan,
08-29 13:12:23.093  2693  2718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:23.095  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:23.097  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.097  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:23.097  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-29 13:12:23.097  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:23.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:12:23.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:23.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:23.099  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:23.101  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:12:23.101  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:23.102  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 13:12:23.104  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:23.104  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:12:23.104  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:23.106  2693  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:12:23.106  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:23.107  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:23.107  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-29 13:12:23.107  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:12:23.107  3760  3810 D BluetoothAdapter: STATE_ON,
08-29 13:12:23.109  2693  2704 D BtGatt.GattService: registerClient() - UUID=848e33b2-7983-4d78-9c4b-a52b7484c423
08-29 13:12:23.109  2693  2714 D BtGatt.GattService: onClientRegistered() - UUID=848e33b2-7983-4d78-9c4b-a52b7484c423, clientIf=5
,08-29 13:12:23.109  3760  3770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:12:23.110  2693  2706 D BtGatt.GattService: start scan with filters
08-29 13:12:23.112  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 13:12:23.112  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:12:23.112  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.112  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-29 13:12:23.112  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:23.112  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:23.116  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:23.116  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:23.116  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:23.118  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:23.120  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:12:23.120  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.120  2693  2718 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:23.120  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:12:23.122  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.122  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:12:23.122  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.122  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:12:23.122  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.122  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:23.122  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 13:12:23.122  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:12:23.122  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:23.122  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:12:23.123  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:23.123  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:12:23.123  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:23.124  2693  2860 D BtGatt.GattService: stopScan() - queue size =0
08-29 13:12:23.124  2693  2704 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:12:23.124  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:23.124  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:23.124  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:12:23.124  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:23.124  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:23.125  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:23.125  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:23.125  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:23.125  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-29 13:12:23.125  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 13:12:23.125  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.126  2693  2718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:12:23.126  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:23.126  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:23.126  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:23.127  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:23.127  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.127  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 13:12:23.127  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:23.127  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.127  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:23.127  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.127  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.127  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:23.127  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.127  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 13:12:23.128  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.128  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:23.128  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.128  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.129  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:12:23.130  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:23.131  2693  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:12:23.131  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:23.133  2693  2718 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:23.134  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:23.135  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.135  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:23.135  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:23.135  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:23.135  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:23.135  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:23.135  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:23.137  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.139  2693  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:12:23.140  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.140  2693  2718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:12:23.140  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:23.141  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:12:23.141  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:23.143  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:23.144  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:12:23.144  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:23.147  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:23.147  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:23.147  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:12:23.147  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:23.147  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:12:23.147  2693  2718 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:23.147  2693  2718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:12:23.147  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:23.149  2693  2859 D BtGatt.GattService: registerClient() - UUID=5ebbbbe1-7bd5-460e-ad0b-02f4fddb2e8e
08-29 13:12:23.149  2693  2714 D BtGatt.GattService: onClientRegistered() - UUID=5ebbbbe1-7bd5-460e-ad0b-02f4fddb2e8e, clientIf=5
,08-29 13:12:23.149  3760  3806 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:12:23.150  2693  2704 D BtGatt.GattService: start scan with filters
,08-29 13:12:23.152  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:23.152  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:23.153  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:23.153  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:23.156  2693  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:12:23.156  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.157  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:23.157  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:23.157  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:12:23.159  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:23.160  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:12:23.160  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:23.162  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:12:23.163  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.163  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:12:23.163  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.163  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:23.163  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.163  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:23.163  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:23.163  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:12:23.163  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:23.163  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:12:23.164  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:23.164  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:23.168  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:23.168  2693  2859 D BtGatt.GattService: stopScan() - queue size =0
,08-29 13:12:23.169  2693  2704 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-29 13:12:23.169  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:23.169  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 13:12:23.169  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:12:23.169  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:23.169  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:23.171  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:12:23.171  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.171  2693  2718 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:23.172  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:23.172  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:23.172  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:23.173  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:12:23.174  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:23.177  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 13:12:23.178  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.178  2693  2718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:12:23.181  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:23.181  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:23.181  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:23.181  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:23.181  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:23.182  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.182  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:23.183  2693  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:12:23.183  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.183  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 13:12:23.183  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.183  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:23.184  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.184  2693  2718 D BtGatt.ScanManager: handling starting scan
08-29 13:12:23.184  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:23.184  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.184  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.184  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:23.184  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.185  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 13:12:23.186  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.186  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:23.186  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.186  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.186  3760  3810 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:12:23.187  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:23.187  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.187  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:23.187  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.188  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.188  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.188  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
,08-29 13:12:23.188  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.188  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.188  2693  2714 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:12:23.188  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.188  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:23.188  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.188  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:23.188  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.188  2693  2718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:12:23.188  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.189  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:23.190  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.190  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:23.190  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.190  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 13:12:23.191  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:23.191  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.191  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.191  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 13:12:23.191  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.191  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.191  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
,08-29 13:12:23.191  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.191  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
,08-29 13:12:23.192  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.192  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.192  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.192  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:23.192  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.193  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:12:23.193  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.193  2693  2718 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:12:23.193  2693  2718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:12:23.194  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.194  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.194  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.196  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.197  3760  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 13:12:23.197  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.197  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.197  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.197  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.197  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.198  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.198  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.198  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.198  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.198  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:23.198  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.198  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.198  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.198  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.199  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.199  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.199  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.199  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.200  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 13:12:23.200  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.200  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.200  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.200  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.200  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.201  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.201  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.201  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.201  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.201  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.201  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.201  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.201  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.201  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.202  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.202  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.202  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.202  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.203  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:23.203  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:23.203  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:23.203  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:23.203  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:23.204  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:23.204  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.204  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.204  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.204  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.204  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.204  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.204  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.204  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.204  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.204  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.205  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.205  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.205  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.205  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.206  2693  2714 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:12:23.206  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.207  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.207  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.207  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.207  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.209  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:23.209  3760  3810 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:23.210  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:23.212  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:12:23.212  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.217  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:23.217  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:23.218  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:12:23.219  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:23.220  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:23.220  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:23.220  2693  2714 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:12:23.220  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:23.220  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.220  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:12:23.220  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:23.220  2693  2718 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:12:23.220  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:12:23.220  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:23.220  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:12:23.221  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:12:23.221  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:23.221  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:12:23.221  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:23.221  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:23.221  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:23.225  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 13:12:23.226  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:12:23.226  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 13:12:23.227  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:12:23.227  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 13:12:23.227  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:12:23.227  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:23.228  2693  2714 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:12:23.228  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.228  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 13:12:23.228  2693  2718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:12:23.229  3760  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
08-29 13:12:23.229  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.230  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.230  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.231  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.231  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.231  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.232  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:12:23.234  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.234  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.234  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.234  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.234  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.234  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.234  3760  3824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:23.234  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.235  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.236  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.236  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.236  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.237  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.238  3760  3810 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:12:23.239  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.239  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.239  3760  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
08-29 13:12:23.239  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.239  3760  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 382)
08-29 13:12:23.239  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.239  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.240  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.240  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.240  3760  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 382)
08-29 13:12:23.240  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.240  2693  2840 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-29 13:12:23.240  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.240  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.240  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.240  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.240  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.241  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.241  3760  3824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
08-29 13:12:23.241  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.241  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.241  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.241  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.242  3760  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:12:23.242  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.242  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.242  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.242  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.242  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.243  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.243  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.243  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.243  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.243  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.243  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.243  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.243  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.243  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.245  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.245  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.245  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.245  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.245  2693  2714 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-29 13:12:23.246  2693  2714 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:23.246  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:12:23.246  2693  2714 D BtGatt.GattService: current time is 130402190864
08-29 13:12:23.246  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:12:23.246  2693  2714 D BtGatt.GattService: Batch record : [-52, 11, 57, -70, 107, -17, 1, 0, -103, 0, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 0]
08-29 13:12:23.246  2693  2714 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82]
08-29 13:12:23.246  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:23.251  3760  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:12:23.251  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:23.251  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:12:23.251  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:23.251  3760  3810 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:12:23.251  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:23.251  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:23.251  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:23.251  3760  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:12:23.252  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.252  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.252  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.252  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.252  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.252  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.252  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.252  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.252  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.252  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.252  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.252  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.252  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.253  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.253  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.254  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.254  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.254  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.254  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.254  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.254  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.254  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.254  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.255  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.255  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.255  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.255  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.255  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.255  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.255  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.255  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.255  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.255  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.255  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.255  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.255  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.255  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.255  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.256  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.256  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.256  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.256  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.256  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.256  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.256  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.256  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.256  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.257  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.257  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.257  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.257  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.258  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:12:23.258  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:23.259  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:12:23.260  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:12:23.260  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 13:12:23.260  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 13:12:23.260  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:23.260  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:12:23.260  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.260  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:12:23.261  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.261  3760  3826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:12:23.261  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.261  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:12:23.261  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.261  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:23.261  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.261  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.262  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:23.262  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.262  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.262  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:23.262  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.262  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.262  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:23.262  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.262  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:23.262  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.262  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.262  3760  3826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 13:12:23.262  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.262  3760  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:12:23.262  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.263  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.263  3760  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:12:23.263  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.263  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.263  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.263  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.263  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.263  3760  3760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 13:12:23.263  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.264  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.264  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.264  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.264  3760  3810 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:12:23.264  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:12:23.264  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:23.265  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:23.266  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.266  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.266  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.266  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.266  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.266  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.266  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.266  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.266  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.266  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.266  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.266  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.266  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.266  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.267  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.267  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.267  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.267  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.270  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.270  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.270  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.270  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.270  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.270  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.270  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.270  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.270  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.270  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.270  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.270  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.270  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.270  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.271  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.271  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.271  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.271  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.272  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:23.272  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:23.272  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:23.272  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:23.273  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.273  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.273  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc892c not in the list
08-29 13:12:23.273  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.273  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.273  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:23.273  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.273  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.273  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:23.273  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:23.274  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:23.274  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:23.274  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:23.274  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e9fff5 not in the list
08-29 13:12:23.274  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:12:23.274  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:23.274  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:12:23.274  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:23.275  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:12:23.275  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:23.276  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:12:23.276  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:12:23.276  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:12:23.276  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:23.276  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 13:12:23.276  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:23.276  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:12:23.277  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:12:23.278  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:23.278  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@50c07cf added. We now have 2 listener(s)
08-29 13:12:23.278  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:23.279  3760  3810 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 13:12:23.279   874  2046 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-29 13:12:23.279   874  2046 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:12:23.280  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:23.280  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@99a955c added. We now have 3 listener(s)
08-29 13:12:23.280  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:23.285  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:23.285  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17bd065 added. We now have 4 listener(s)
08-29 13:12:23.285  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:23.286  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:23.286  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e54b13a added. We now have 5 listener(s)
08-29 13:12:23.286  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:23.287   874  1912 D WifiService: setWifiEnabled: false pid=3760, uid=10000
08-29 13:12:23.287   874  1912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:12:23.291  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:23.291  2693  2709 D BluetoothAdapterState: Current state: ON, message: 23
08-29 13:12:23.292  2693  2709 D BluetoothAdapterProperties: Setting state to 13
08-29 13:12:23.292  2693  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:12:23.292  2693  2709 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:12:23.293  2693  2709 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:12:23.294  2693  2693 D BluetoothMapService: onReceive
08-29 13:12:23.294  2693  2693 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:23.294  2693  2693 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:12:23.294  2693  2693 D BluetoothMapService: MAP Service closeService in
08-29 13:12:23.294  2693  2693 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 13:12:23.295  2693  2693 D ObexServerSockets0: shutdown(block = true)
08-29 13:12:23.295  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:12:23.295  2693  2693 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:12:23.295  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:23.295  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:23.295  2693  2863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 13:12:23.296  2693  2864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 13:12:23.296  2693  2840 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 13:12:23.296  2693  2693 I BtOppRfcommListener: stopping Accept Thread
08-29 13:12:23.296  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.296  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.297  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:23.297  2693  3444 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:23.297  2693  3444 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:12:23.298  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:12:23.299  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.300   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:12:23.300   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 13:12:23.300   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:12:23.301   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:23.302  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.305  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:23.305  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:23.306  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.306  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:23.308   874  2117 D DhcpClient: Clearing IP address
,08-29 13:12:23.308   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:23.308  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.311   373   873 D CommandListener: Setting iface cfg
08-29 13:12:23.312  1499  3480 V NativeCrypto: Read error: ssl=0x9b47f600: I/O error during system call, Connection timed out
08-29 13:12:23.313  1499  3480 V NativeCrypto: SSL shutdown failed: ssl=0x9b47f600: I/O error during system call, Broken pipe
08-29 13:12:23.315   874  2046 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 13:12:23.315   874  2102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-29 13:12:23.318   874  2102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 13:12:23.319   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 13:12:23.319   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 13:12:23.320   874  2133 D DhcpClient: Receive thread stopped
08-29 13:12:23.320   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 13:12:23.325   874   887 I ActivityManager: Start proc 3831:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 13:12:23.325  2693  2714 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:23.325  2693  2709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 13:12:23.328   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 13:12:23.328   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 13:12:23.332  2693  2693 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:12:23.332   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 13:12:23.333   404   404 E Parcel  : Reading a NULL string not supported here.
08-29 13:12:23.334  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.334  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:23.335   874   874 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:23.335   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:23.336   874   874 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:23.336   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 13:12:23.336  1958  2284 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:23.336  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.336  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:23.337   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:12:23.337  1363  1390 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:23.338  1363  1363 D HeadsetProfile: Bluetooth service disconnected
,08-29 13:12:23.338  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.338  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:23.339  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.339  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:23.339  2693  2693 D A2dpService: Received stop request...Stopping profile...
08-29 13:12:23.340  2693  2851 D A2dpStateMachine: Exit Disconnected: -1
,08-29 13:12:23.341  1363  1363 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:23.341   874   874 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:23.341   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:23.341  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.342  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.342  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.342  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:23.343  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:12:23.343  2693  2693 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:23.343  2693  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:12:23.344  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:23.344  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:23.344  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:23.344  2693  2714 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 13:12:23.344  2693  2693 D HidService: Received stop request...Stopping profile...
08-29 13:12:23.344  2693  2693 D HidService: Stopping Bluetooth HidService
08-29 13:12:23.348  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-29 13:12:23.348  1363  1363 D HidProfile: Bluetooth service disconnected
08-29 13:12:23.348  2693  2693 D HealthService: Received stop request...Stopping profile...
08-29 13:12:23.349  2693  2693 D PanService: Received stop request...Stopping profile...
08-29 13:12:23.352  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:23.352  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.352  2693  2693 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:12:23.352  1363  1363 D PanProfile: Bluetooth service disconnected
,08-29 13:12:23.353  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.353  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:23.353  2693  2693 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:12:23.353  2693  2693 D BluetoothMapService: stop()
08-29 13:12:23.354  2693  2693 D BluetoothMapAppObserver: deinitObservers()
08-29 13:12:23.354  2693  2693 D BluetoothMapAppObserver: removeReceiver()
08-29 13:12:23.356  2693  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 13:12:23.356  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:12:23.356  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:23.356  2693  2811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:23.356  2693  2811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:23.356  2693  2811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:23.356  2693  2811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:23.356  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.356  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.356  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.356  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:23.357  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:23.357  2693  2714 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:12:23.357  2693  2693 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:12:23.357  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.357  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:23.358  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:12:23.358  2693  2714 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:12:23.358  2693  2693 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.358  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:23.359  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 13:12:23.359  2693  2693 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:12:23.360  2693  2693 D BluetoothMapService: MAP Service closeService in
08-29 13:12:23.360  2693  2693 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:23.360  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.360  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.360  2693  2693 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:23.361  2693  2709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 13:12:23.361  2693  2709 D BluetoothAdapterProperties: Setting state to 15
08-29 13:12:23.361  2693  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 13:12:23.361  2693  2709 I BluetoothAdapterState: Entering BleOnState
08-29 13:12:23.361  2693  2693 D BluetoothMapService: cleanup()
08-29 13:12:23.362  2693  2693 D BluetoothMapService: MAP Service closeService in
,08-29 13:12:23.363   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:23.363   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:23.363   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:23.363  1363  1390 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:12:23.364  1363  1377 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:12:23.365   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:23.365  1363  1390 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:12:23.365  1958  2099 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:12:23.365  1363  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:23.366  1363  2095 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:12:23.367  1363  1390 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:23.368  2693  2709 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:12:23.370  2693  2709 D BluetoothAdapterProperties: Setting state to 16
08-29 13:12:23.370  2693  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 13:12:23.371  2693  2709 D BluetoothAdapterProperties: onBleDisable
08-29 13:12:23.371  2693  2709 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:12:23.372  2693  2711 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 13:12:23.372  2693  2811 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:12:23.372  2693  2811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:23.373  2693  2714 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:23.375  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.375  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:23.377  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.377  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:23.378  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.379  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:23.391   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:23.394  3831  3831 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 13:12:23.404  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:23.408   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cdc7918:true
,08-29 13:12:23.408  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:23.412   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:23.413   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 13:12:23.413   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:23.421   874  1983 I ActivityManager: Start proc 3847:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 13:12:23.424   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:23.428  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.429  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:23.429   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 13:12:23.429  3380  3380 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c46c15c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) },
08-29 13:12:23.433  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.433  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:23.433  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:23.433  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:23.434   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:12:23.435  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:23.435  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:23.435  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:23.435  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:23.440  1852  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:23.450  3831  3831 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 13:12:23.452  3831  3831 D BluetoothMap: Create BluetoothMap proxy object
,08-29 13:12:23.460  3831  3831 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 13:12:23.471  3831  3831 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:23.473   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-29 13:12:23.474   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 13:12:23.474   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 13:12:23.477  3847  3847 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 13:12:23.481   874  2046 I ActivityManager: Killing 3203:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 13:12:23.582  2693  2714 I bt_hci  : shut_down
,08-29 13:12:23.582  2693  2719 D bt_hwcfg: hw_epilog_process
,08-29 13:12:23.583  2693  2719 I bt_vendor: low_power_mode_cb
,08-29 13:12:23.603  2693  2719 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 13:12:23.604  2693  2719 I bt_vendor: epilog_cb
08-29 13:12:23.604  2693  2719 I bt_hci  : epilog_finished_callback
,08-29 13:12:23.612  2693  2714 I bt_hci_h4: hal_close
,08-29 13:12:23.612  2693  2714 I bt_userial_vendor: device fd = 51 close
,08-29 13:12:23.648  3847  3847 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.648  3847  3847 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.648  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.649  3847  3847 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:23.649  3847  3847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:23.655  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 13:12:23.670  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:23.679  3831  3831 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:23.685   874  1951 I ActivityManager: Killing 3380:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 13:12:23.762  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:12:23.767  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:12:23.794  1694  1694 D SystemUpdateService: onCreate
,08-29 13:12:23.800  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 13:12:23.801  2693  2711 D bt_stack_manager: event_shut_down_stack finished.
08-29 13:12:23.801  2693  2709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:12:23.807  2693  2693 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:23.807  2693  2709 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 13:12:23.809  2693  2693 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 13:12:23.809  2693  2693 D BtGatt.GattService: stop()
08-29 13:12:23.809  2693  2693 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:12:23.818  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:12:23.819  2693  2693 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:23.819  2693  2693 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:23.820  2693  2693 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:23.820  2693  2693 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 13:12:23.820  2693  2709 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 13:12:23.821  2693  2709 D BluetoothAdapterProperties: Setting state to 10
,08-29 13:12:23.821  2693  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 13:12:23.822  2693  2709 I BluetoothAdapterState: Entering OffState
08-29 13:12:23.823   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 13:12:23.827  1694  3882 I SystemUpdateService: active receiver: enabled
,08-29 13:12:23.831  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 13:12:23.831  2693  2693 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 13:12:23.832  2693  2693 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 13:12:23.832  2693  2711 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 13:12:23.835  2693  2711 D bt_stack_manager: event_clean_up_stack finished.
,08-29 13:12:23.829  1694  2519 I iu.UploadsManager: num queued entries: 0
,08-29 13:12:23.838  2693  2693 I art     : System.exit called, status: 0
,08-29 13:12:23.838  2693  2693 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:12:23.841  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:12:23.842  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:12:23.837  1694  2519 I iu.UploadsManager: num updated entries: 0
,08-29 13:12:23.859  1694  3882 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:12:23.861  1694  2519 I iu.SyncManager: NEXT; no task
08-29 13:12:23.861   874  2046 I ActivityManager: Start proc 3885:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
08-29 13:12:23.862  1694  3882 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 13:12:23.863  1694  3882 I SystemUpdateService: now status is 0 (complete)
08-29 13:12:23.863  1694  3882 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:12:23.863  1694  3882 I SystemUpdateService: file has been verified
,08-29 13:12:23.863  1694  3882 I SystemUpdateService: OTA package size = 12249756
,08-29 13:12:23.872  1694  3882 I SystemUpdateService: showing system update notification
,08-29 13:12:23.894  1694  1694 D SystemUpdateService: onDestroy
08-29 13:12:23.905   874   884 I ActivityManager: Process com.android.bluetooth (pid 2693) has died
,08-29 13:12:23.917  3885  3885 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 13:12:23.924  3885  3885 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:23.930  3885  3885 D SprintDMHelper: simOperator: 
08-29 13:12:23.930  3885  3885 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:12:23.959   874  2017 I ActivityManager: Start proc 3897:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 13:12:23.961   874  2017 I ActivityManager: Killing 2785:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 13:12:24.000  3847  3871 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:12:24.011   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@edf3bf:true
,08-29 13:12:24.138  2210  3913 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 13:12:24.165   874  1515 I ActivityManager: Start proc 3914:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 13:12:24.234  3914  3914 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 13:12:24.289  3914  3914 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 13:12:24.289  3914  3914 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:12:24.289  3914  3914 I GAv4    :   adb logcat -s GAv4
,08-29 13:12:24.317  3914  3914 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:24.324  3914  3914 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:24.346  3914  3932 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:24.457  3914  3914 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 13:12:24.502  3914  3914 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 13:12:24.515  3914  3914 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 1664-1671)
08-29 13:12:24.516  3914  3914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:12:24.525  3914  3914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2eb398c}
,08-29 13:12:24.526  3914  3914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:12:24.527  3914  3914 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:12:24.536  3914  3914 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 13:12:24.538  3914  3914 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 13:12:24.557  3914  3914 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 13:12:24.570  3914  3914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:12:24.570  3914  3914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:12:24.570  3914  3914 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:12:24.570  3914  3914 I Adreno  : Build Date                       : 10/20/15
08-29 13:12:24.570  3914  3914 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:12:24.570  3914  3914 I Adreno  : Local Branch                     : M14
08-29 13:12:24.570  3914  3914 I Adreno  : Remote Branch                    : 
08-29 13:12:24.570  3914  3914 I Adreno  : Remote Branch                    : 
08-29 13:12:24.570  3914  3914 I Adreno  : Reconstruct Branch               : 
,08-29 13:12:24.631  3914  3914 I NSApplication: Starting up...
,08-29 13:12:24.639  3914  3960 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 13:12:24.673   874  1515 I ActivityManager: Start proc 3965:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 13:12:24.674   874  1515 I ActivityManager: Killing 1708:android.process.acore/u0a5 (adj 15): empty #17
,08-29 13:12:24.749  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 13:12:24.956   874   885 I ActivityManager: Killing 3616:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 13:12:25.022   874  1515 I ActivityManager: Start proc 3979:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 13:12:25.066  3979  3979 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 13:12:25.123  3979  3979 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 13:12:25.175   874   885 I ActivityManager: Killing 3629:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 13:12:26.299   874  2015 D WifiService: setWifiEnabled: true pid=3760, uid=10000
,08-29 13:12:26.299   874  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:26.314   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:12:26.322  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:26.323  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:26.323  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:26.324  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:26.330  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:26.331  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:26.333  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:26.333  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:26.345   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:12:26.346   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 13:12:26.347   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 13:12:26.347   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:12:26.348   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 13:12:26.348   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 13:12:26.348   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 13:12:26.365   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 13:12:26.367   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.12 rxSuccessRate=15.00 delta 1000 -> 994
,08-29 13:12:26.367   373   873 D CommandListener: Setting iface cfg
08-29 13:12:26.368   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-29 13:12:26.368   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:12:26.376   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 13:12:26.376   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:12:26.376   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:26.377   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:12:26.383   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:12:26.442   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:12:26.445  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:12:26.871  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:12:26.919  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:12:26.922  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:12:26.927   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:12:26.938   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 13:12:26.938   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:26.938   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 13:12:26.962   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:26.972   373   873 D CommandListener: Setting iface cfg
,08-29 13:12:26.973   874  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 13:12:26.985   874  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 13:12:26.987   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:12:27.018   874  4015 D DhcpClient: Receive thread started
,08-29 13:12:27.101   874  1309 E native  : do suspend false
,08-29 13:12:27.121   874  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 13:12:27.135   874  4015 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,08-29 13:12:27.137   874  2117 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,08-29 13:12:27.140   874  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:12:27.160   874  4015 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 13:12:27.162   874  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:12:27.169   373   873 D CommandListener: Setting iface cfg
,08-29 13:12:27.181   874  2117 D DhcpClient: Scheduling renewal in 86399s
08-29 13:12:27.181   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 13:12:27.197   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 13:12:27.198   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 13:12:27.198   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:12:27.199   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 13:12:27.201   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:12:27.207   874  1311 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 13:12:27.269   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 13:12:27.269   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 13:12:27.271   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 13:12:27.273   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 13:12:27.274   874  1311 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 13:12:27.281   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:12:27.287   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 13:12:27.287   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 13:12:27.287   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 13:12:27.287   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 13:12:27.287   874  1311 D ConnectivityService:    accepting network in place of null
08-29 13:12:27.288   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:12:27.288   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:12:27.335   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:27.370   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:27.378   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 13:12:27.378   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:27.391   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:27.392   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 13:12:27.402  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:27.402  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:27.402  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:27.402  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:27.406  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:27.406  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:27.406  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:27.407  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:27.417  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:12:27.420  1694  1694 D SystemUpdateService: onCreate
,08-29 13:12:27.424  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:12:27.426  1694  4025 I SystemUpdateService: active receiver: enabled
,08-29 13:12:27.429  1694  4025 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-29 13:12:27.432  1694  4025 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 13:12:27.432  1694  4025 I SystemUpdateService: now status is 0 (complete)
08-29 13:12:27.432  1694  4025 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:12:27.432  1694  4025 I SystemUpdateService: file has been verified
08-29 13:12:27.432  1694  4025 I SystemUpdateService: OTA package size = 12249756
,08-29 13:12:27.440  1694  4025 I SystemUpdateService: showing system update notification
,08-29 13:12:27.444  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:12:27.447  1694  2519 I iu.UploadsManager: num queued entries: 0
,08-29 13:12:27.448  1694  2519 I iu.UploadsManager: num updated entries: 0
08-29 13:12:27.449  1694  2519 I iu.SyncManager: NEXT; no task
,08-29 13:12:27.452  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 13:12:27.453  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:12:27.456  1694  1694 D SystemUpdateService: onDestroy
,08-29 13:12:27.457  3885  3885 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:27.458  1694  4029 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 13:12:27.458  1694  4029 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 13:12:27.460  1694  4029 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com,
,08-29 13:12:27.465  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:12:27.466  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:27.470  3885  3885 D SprintDMHelper: simOperator: 
,08-29 13:12:27.470  3885  3885 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:12:27.500  1499  2994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:12:27.500  1499  2994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 13:12:27.500  1499  2994 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:27.500  1499  2994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:12:27.518  1694  4029 E MDM     : [173] SitrepService.a: Error sending sitrep.
,08-29 13:12:28.286   874  4014 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135442, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 13:12:28.379   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 13:12:29.309   874  1982 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-29 13:12:29.309   874  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:29.331  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 13:12:29.339   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 13:12:29.339   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 13:12:29.340   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:12:29.340   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:29.360   874  2117 D DhcpClient: Clearing IP address
,08-29 13:12:29.360   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:29.375   373   873 D CommandListener: Setting iface cfg
,08-29 13:12:29.385   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 13:12:29.385   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 13:12:29.387   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 13:12:29.387   404   404 E Parcel  : Reading a NULL string not supported here.
08-29 13:12:29.388   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:12:29.390   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:29.404   874  4015 D DhcpClient: Receive thread stopped
08-29 13:12:29.404   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:12:29.407  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.407  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:29.408  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.407   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:12:29.408  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:29.411  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.411  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:29.411  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.411  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:29.412  1852  2297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:29.413   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 13:12:29.441   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:29.462   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:29.464   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 13:12:29.465   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:29.472   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:29.475  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.476  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:29.481  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.481  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:29.485  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:12:29.490  1694  1694 D SystemUpdateService: onCreate
,08-29 13:12:29.493  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:12:29.501  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:12:29.505  1694  4044 I SystemUpdateService: active receiver: enabled
,08-29 13:12:29.506  1694  2519 I iu.UploadsManager: num queued entries: 0
,08-29 13:12:29.508  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:12:29.509  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:12:29.511  3885  3885 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:29.515  1694  2519 I iu.UploadsManager: num updated entries: 0
,08-29 13:12:29.515  3885  3885 D SprintDMHelper: simOperator: 
08-29 13:12:29.515  3885  3885 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:12:29.519  1694  4044 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:12:29.528  1694  2519 I iu.SyncManager: NEXT; no task
,08-29 13:12:29.528  1694  4044 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 13:12:29.531  1694  4044 I SystemUpdateService: now status is 0 (complete)
,08-29 13:12:29.532  1694  4044 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 13:12:29.532  1694  4044 I SystemUpdateService: file has been verified
,08-29 13:12:29.535   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-29 13:12:29.539  1694  4044 I SystemUpdateService: OTA package size = 12249756
,08-29 13:12:29.547  1694  4044 I SystemUpdateService: showing system update notification
,08-29 13:12:29.555  1694  1694 D SystemUpdateService: onDestroy
,08-29 13:12:32.303   874  4013 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 13:12:32.305   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 13:12:32.368   874   891 I ActivityManager: Start proc 4051:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 13:12:32.489  4051  4051 D AdapterServiceConfig: Adding HeadsetService
,08-29 13:12:32.489  4051  4051 D AdapterServiceConfig: Adding A2dpService
,08-29 13:12:32.489  4051  4051 D AdapterServiceConfig: Adding HidService
08-29 13:12:32.489  4051  4051 D AdapterServiceConfig: Adding HealthService
,08-29 13:12:32.490  4051  4051 D AdapterServiceConfig: Adding PanService
08-29 13:12:32.490  4051  4051 D AdapterServiceConfig: Adding GattService
,08-29 13:12:32.490  4051  4051 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:12:32.494  2210  4031 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-29 13:12:32.495  2210  4031 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 13:12:32.498  2210  4031 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-29 13:12:32.500   874  1515 I ActivityManager: Killing 3409:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 13:12:32.504   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce6ec75:true
08-29 13:12:32.504  4051  4051 D BluetoothAdapterState: make() - Creating AdapterState
08-29 13:12:32.510  4051  4051 I bt_bluedroid: init
08-29 13:12:32.510  4051  4063 I BluetoothAdapterState: Entering OffState
08-29 13:12:32.512  4051  4064 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:12:32.512  4051  4064 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:12:32.512  4051  4064 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:12:32.512  4051  4064 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:12:32.512  4051  4051 I bt_bluedroid: get_profile_interface socket
,08-29 13:12:32.514  4051  4051 I bt_bluedroid: get_profile_interface sdp
,08-29 13:12:32.518  4051  4067 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:12:32.564  4051  4067 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:12:32.565  4051  4062 I bt_bluedroid: config_hci_snoop_log
,08-29 13:12:32.566   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:12:32.570  4051  4063 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 13:12:32.570  4051  4063 D BluetoothAdapterProperties: Setting state to 14
08-29 13:12:32.570  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:12:32.571  4051  4063 D BluetoothBondStateMachine: make
,08-29 13:12:32.574  4051  4068 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:12:32.576  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:12:32.577  4051  4051 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-29 13:12:32.579  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:32.580  4051  4051 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:12:32.580  4051  4051 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:12:32.580  4051  4051 D BtGatt.GattService: start()
08-29 13:12:32.580  4051  4051 I bt_bluedroid: get_profile_interface gatt
08-29 13:12:32.581  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:32.582  4051  4051 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:12:32.587  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:32.587  4051  4051 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:12:32.587  4051  4051 V BluetoothAdapterState: isBleTurningOn()=true
,08-29 13:12:32.587  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:32.587  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 13:12:32.588  4051  4063 I bt_bluedroid: enable
08-29 13:12:32.588  4051  4064 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 13:12:32.588  4051  4064 I bt_hci  : start_up
,08-29 13:12:32.593  4051  4064 I bt_vendor: alloc value 0xb3a70189
,08-29 13:12:32.593  4051  4064 I bt_vendor: init
08-29 13:12:32.593  4051  4064 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 13:12:32.593  4051  4064 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:12:32.705  4051  4064 D bt_hci  : start_up starting async portion
,08-29 13:12:32.706  4051  4071 I bt_hci  : event_finish_startup
,08-29 13:12:32.706  4051  4071 I bt_hci_h4: hal_open
,08-29 13:12:32.706  4051  4071 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:12:32.719  4051  4071 I bt_userial_vendor: device fd = 51 open
,08-29 13:12:32.744  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:12:32.777  4051  4071 D bt_hwcfg: Chipset BCM4354A2
,08-29 13:12:32.778  4051  4071 D bt_hwcfg: Target name = [BCM4354A2]
08-29 13:12:32.778  4051  4071 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:12:33.450  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:12:33.452  4051  4071 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 13:12:33.452  4051  4071 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:12:33.570  4051  4071 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:12:33.571  4051  4071 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:12:33.599  4051  4071 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:12:33.600  4051  4071 I bt_vendor: firmware callback
08-29 13:12:33.600  4051  4071 I bt_hci  : firmware_config_callback
,08-29 13:12:33.613  4051  4074 I bt_btu  : btu_task pending for preload complete event
08-29 13:12:33.613  4051  4074 I bt_btu_task: Bluetooth chip preload is complete
,08-29 13:12:33.613  4051  4074 I bt_btu  : btu_task received preload complete event
,08-29 13:12:33.624  4051  4074 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:12:33.624  4051  4074 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 13:12:33.624  4051  4074 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:12:33.625  4051  4074 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 13:12:33.625  4051  4074 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:12:33.625  4051  4074 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:33.626  4051  4074 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 13:12:33.626  4051  4074 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:33.626  4051  4074 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:12:33.626  4051  4074 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:12:33.627  4051  4074 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:12:33.627  4051  4074 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:12:33.627  4051  4074 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 13:12:33.628  4051  4074 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:12:33.628  4051  4074 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:12:33.762  4051  4074 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,08-29 13:12:33.762  4051  4074 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,08-29 13:12:33.790  4051  4067 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:12:33.791  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 13:12:33.792  4051  4067 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 13:12:33.794  4051  4067 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:12:33.796  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:12:33.797  4051  4067 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:12:33.797  4051  4067 D bt_hci  : do_postload posting postload work item
,08-29 13:12:33.798  4051  4071 I bt_hci  : event_postload,
08-29 13:12:33.798  4051  4071 I bt_vendor: sco_config_cb
,08-29 13:12:33.798  4051  4071 I bt_hci  : sco_config_callback postload finished.
08-29 13:12:33.800  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:33.803  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:33.803  4051  4067 D bt_bte_conf: Device ID record 1 : primary
08-29 13:12:33.803  4051  4067 D bt_bte_conf:   vendorId            = 000f
,08-29 13:12:33.804  4051  4067 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 13:12:33.804  4051  4067 D bt_bte_conf:   product             = 1200
,08-29 13:12:33.805  4051  4067 D bt_bte_conf:   version             = 1436
08-29 13:12:33.805  4051  4067 D bt_bte_conf:   clientExecutableURL = 
08-29 13:12:33.805  4051  4071 I bt_vendor: low_power_mode_cb
08-29 13:12:33.805  4051  4067 D bt_bte_conf:   serviceDescription  = 
08-29 13:12:33.805  4051  4067 D bt_bte_conf:   documentationURL    = 
08-29 13:12:33.806  4051  4067 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 13:12:33.806  4051  4064 D bt_stack_manager: event_start_up_stack finished
08-29 13:12:33.808  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 13:12:33.809  4051  4063 D BluetoothAdapterProperties: Setting state to 15
08-29 13:12:33.809  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 13:12:33.810  4051  4063 I BluetoothAdapterState: Entering BleOnState
,08-29 13:12:33.814  4051  4063 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 13:12:33.814  4051  4063 D BluetoothAdapterProperties: Setting state to 11
08-29 13:12:33.815  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 13:12:33.828  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:33.830  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:33.831  4051  4051 D HeadsetService: Received start request. Starting profile...
,08-29 13:12:33.834  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:33.835  4051  4051 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-29 13:12:33.836  4051  4051 D HeadsetStateMachine: make
,08-29 13:12:33.845  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:12:33.852  4051  4051 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:12:33.852  4051  4051 I bt_bluedroid: get_profile_interface handsfree
,08-29 13:12:33.853  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 13:12:33.853  4051  4067 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 13:12:33.858  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:33.858  4051  4051 D A2dpService: Received start request. Starting profile...
08-29 13:12:33.859  4051  4051 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:12:33.859  4051  4051 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:12:33.865  4051  4051 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:12:33.865  4051  4051 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:33.865  4051  4051 D A2dpStateMachine: make
,08-29 13:12:33.867  4051  4051 I bt_bluedroid: get_profile_interface a2dp
,08-29 13:12:33.868  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 13:12:33.870  4051  4083 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:12:33.872  4051  4051 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:12:33.873  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:33.873  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:33.877  3831  3831 D BluetoothInputDevice: Proxy object connected
,08-29 13:12:33.877  3831  3831 D HidProfile: Bluetooth service connected
08-29 13:12:33.878  4051  4051 D HidService: Received start request. Starting profile...
08-29 13:12:33.878  4051  4051 I bt_bluedroid: get_profile_interface hidhost
,08-29 13:12:33.882  4051  4067 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
,08-29 13:12:33.882  4051  4051 D HidService: setHidService(): set to: null
08-29 13:12:33.882  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 13:12:33.883  4051  4051 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 13:12:33.885  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:33.886  4051  4051 D HealthService: Received start request. Starting profile...
,08-29 13:12:33.889  4051  4051 I bt_bluedroid: get_profile_interface health
,08-29 13:12:33.890  4051  4051 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:12:33.891  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:33.893  3831  3831 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:12:33.893  4051  4051 D PanService: Received start request. Starting profile...
,08-29 13:12:33.893  4051  4051 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:12:33.893  3831  3831 D PanProfile: Bluetooth service connected
,08-29 13:12:33.893  4051  4051 I bt_bluedroid: get_profile_interface pan
08-29 13:12:33.894  4051  4067 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:12:33.900  4051  4051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:33.901  3831  3831 D BluetoothMap: Proxy object connected
,08-29 13:12:33.901  4051  4051 D BluetoothMapService: Received start request. Starting profile...
08-29 13:12:33.901  4051  4051 D BluetoothMapService: start()
08-29 13:12:33.902  3831  3831 D MapProfile: Bluetooth service connected,
08-29 13:12:33.902  3831  3831 D BluetoothMap: getConnectedDevices()
,08-29 13:12:33.904  3831  3831 D BluetoothMap: Bluetooth is Not enabled
,08-29 13:12:33.905  4051  4051 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 13:12:33.906  4051  4051 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 13:12:33.906  4051  4051 D BluetoothMapAppObserver: createReceiver()
,08-29 13:12:33.907  4051  4051 D BluetoothMapAppObserver: initObservers()
08-29 13:12:33.907  4051  4051 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 13:12:33.919  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:33.920  4051  4051 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:33.920  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.920  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:33.922  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:33.923  4051  4051 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:12:33.923  4051  4081 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 13:12:33.923  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.923  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:33.925  4051  4051 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:33.925  4051  4051 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:33.926  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.926  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:33.926  4051  4051 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:33.927  4051  4051 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:33.927  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.927  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:33.929  4051  4051 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:33.929  4051  4051 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:33.930  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.930  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:33.931  4051  4051 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:33.931  4051  4051 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:33.931  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:33.931  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:33.932  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:12:33.933  4051  4063 D BluetoothAdapterProperties: ScanMode =  20
,08-29 13:12:33.933  4051  4063 D BluetoothAdapterProperties: State =  11
08-29 13:12:33.934  4051  4067 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:12:33.935  4051  4063 D BluetoothAdapterProperties: Setting state to 12
08-29 13:12:33.935  4051  4067 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:33.935  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:12:33.936   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:33.936   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:33.936  4051  4063 I BluetoothAdapterState: Entering OnState
,08-29 13:12:33.938  3831  3841 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:33.939  4051  4051 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 13:12:33.940  4051  4051 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 13:12:33.943  3831  3843 D BluetoothPan: onBluetoothStateChange on: true
,08-29 13:12:33.943  4051  4051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:33.944   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:12:33.945  1363  2095 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:33.945  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:33.947  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:33.947  4051  4051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:33.947  1363  1390 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:12:33.947  1363  1363 D BluetoothMap: Proxy object connected
08-29 13:12:33.947  1363  1363 D MapProfile: Bluetooth service connected
08-29 13:12:33.948  1363  1363 D BluetoothMap: getConnectedDevices()
08-29 13:12:33.948  4051  4051 D ObexServerSockets: Succeed to create listening sockets 
08-29 13:12:33.949  4051  4051 D ObexServerSockets0: startAccept()
,08-29 13:12:33.949  4051  4051 D ObexServerSockets0: prepareForNewConnect()
08-29 13:12:33.949  3831  3841 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:33.950  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:33.950  1363  1363 D PanProfile: Bluetooth service connected
08-29 13:12:33.950  3831  3843 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:33.951   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:12:33.951  1363  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:33.952  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:33.952  4051  4051 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 13:12:33.952  4051  4051 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 13:12:33.952  1363  1363 D BluetoothInputDevice: Proxy object connected
08-29 13:12:33.953  1363  1363 D HidProfile: Bluetooth service connected
,08-29 13:12:33.953   874   874 D BluetoothA2dp: Proxy object connected
08-29 13:12:33.953  1958  1979 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:33.954  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:33.955  1363  1390 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:33.957  4051  4089 D ObexServerSockets0: Accepting socket connection...
,08-29 13:12:33.957  4051  4090 D ObexServerSockets0: Accepting socket connection...
08-29 13:12:33.959  1363  1363 D BluetoothA2dp: Proxy object connected
08-29 13:12:33.959  1363  1377 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:33.960  1363  2095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:33.964   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:12:33.968  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:33.968  4051  4051 D BluetoothMapService: onReceive
08-29 13:12:33.968  4051  4051 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:33.968  4051  4051 D BluetoothMapService: STATE_ON
08-29 13:12:33.969  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:33.971  3831  3831 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 13:12:33.976  3831  3831 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 13:12:33.983  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:33.986  3831  3831 D BluetoothA2dp: Proxy object connected
,08-29 13:12:33.989  4051  4051 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:12:33.990  4051  4051 D ObexServerSockets0: prepareForNewConnect()
,08-29 13:12:33.996  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:33.997  3831  3831 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:34.010  1363  1363 D BluetoothPbap: Proxy object connected
,08-29 13:12:34.010  1363  1363 D PbapServerProfile: Bluetooth service connected
08-29 13:12:34.010  3831  3831 D BluetoothPbap: Proxy object connected
08-29 13:12:34.011  3831  3831 D PbapServerProfile: Bluetooth service connected
,08-29 13:12:34.022  4051  4095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:34.038   874   874 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.038   874   874 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.038   874   874 D BluetoothHeadset: Proxy object connected
08-29 13:12:34.039  1958  1973 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.039  1363  1377 D BluetoothHeadset: Proxy object connected
08-29 13:12:34.040  1363  1363 D HeadsetProfile: Bluetooth service connected
08-29 13:12:34.041  4051  4099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:34.043  4051  4099 I BtOppRfcommListener: Accept thread started.
,08-29 13:12:34.044   874   891 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.051   874   891 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.054  1958  2099 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.061  1363  2095 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.061  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:34.080  3831  3843 D BluetoothHeadset: Proxy object connected
,08-29 13:12:34.081  3831  3831 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:35.290   874  1311 D ConnectivityService: handlePromptUnvalidated 101
,08-29 13:12:35.327  4051  4063 D BluetoothAdapterState: Current state: ON, message: 23
08-29 13:12:35.327  4051  4063 D BluetoothAdapterProperties: Setting state to 13
,08-29 13:12:35.327  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 13:12:35.330  4051  4063 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 13:12:35.337  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:12:35.339  4051  4051 D BluetoothMapService: onReceive
,08-29 13:12:35.339  4051  4051 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:35.340  4051  4051 D BluetoothMapService: STATE_TURNING_OFF
,08-29 13:12:35.342  4051  4051 D BluetoothMapService: MAP Service closeService in
,08-29 13:12:35.342  4051  4051 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 13:12:35.342  4051  4051 D ObexServerSockets0: shutdown(block = true)
08-29 13:12:35.343  4051  4089 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 13:12:35.346  4051  4051 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:12:35.347  4051  4090 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 13:12:35.347  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:35.348  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:35.348  4051  4076 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 13:12:35.349  4051  4051 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 13:12:35.349  4051  4051 I BtOppRfcommListener: stopping Accept Thread
,08-29 13:12:35.350  4051  4099 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:12:35.350  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:35.351  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:35.351  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:35.351  4051  4099 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:12:35.352  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 13:12:35.356  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:35.356  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:35.357  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:35.357  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:35.359  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.359  4051  4051 D HeadsetService: Received stop request...Stopping profile...
08-29 13:12:35.360  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 13:12:35.361  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.365   874   874 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:35.365   874   874 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:35.366  4051  4051 D A2dpService: Received stop request...Stopping profile...
08-29 13:12:35.367  4051  4083 D A2dpStateMachine: Exit Disconnected: -1
,08-29 13:12:35.367  3831  3843 D BluetoothHeadset: Proxy object disconnected
,08-29 13:12:35.367   874   874 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:35.367  1958  2284 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:35.368  1363  1377 D BluetoothHeadset: Proxy object disconnected
08-29 13:12:35.368   874   874 D BluetoothA2dp: Proxy object disconnected
,08-29 13:12:35.368  1363  1363 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:35.369  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-29 13:12:35.369  4051  4051 D HidService: Received stop request...Stopping profile...
08-29 13:12:35.369  4051  4051 D HidService: Stopping Bluetooth HidService
,08-29 13:12:35.370  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-29 13:12:35.370  1363  1363 D HidProfile: Bluetooth service disconnected
08-29 13:12:35.370  4051  4051 D HealthService: Received stop request...Stopping profile...
08-29 13:12:35.371  3831  3831 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:35.372  4051  4051 D PanService: Received stop request...Stopping profile...
08-29 13:12:35.372  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:35.372  1363  1363 D PanProfile: Bluetooth service disconnected
08-29 13:12:35.373  3831  3831 D HeadsetProfile: Bluetooth service disconnected
08-29 13:12:35.373  4051  4051 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:35.373  3831  3831 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:35.373  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.373  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.373  3831  3831 D BluetoothInputDevice: Proxy object disconnected
08-29 13:12:35.373  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:35.373  3831  3831 D HidProfile: Bluetooth service disconnected
08-29 13:12:35.374  4051  4051 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:12:35.374  4051  4051 D BluetoothMapService: stop()
,08-29 13:12:35.375  4051  4051 D BluetoothMapAppObserver: deinitObservers()
08-29 13:12:35.375  4051  4051 D BluetoothMapAppObserver: removeReceiver()
08-29 13:12:35.375  3831  3831 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:35.375  3831  3831 D PanProfile: Bluetooth service disconnected
08-29 13:12:35.377  1363  1363 D BluetoothMap: Proxy object disconnected
08-29 13:12:35.377  1363  1363 D MapProfile: Bluetooth service disconnected
08-29 13:12:35.377  3831  3831 D BluetoothMap: Proxy object disconnected
08-29 13:12:35.378  3831  3831 D MapProfile: Bluetooth service disconnected
08-29 13:12:35.378  4051  4051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:12:35.378  4051  4051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:35.378  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.379  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.379  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.379  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:12:35.379  4051  4067 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-29 13:12:35.380  4051  4051 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:35.380  4051  4051 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:12:35.380  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.380  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:35.381  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.381  4051  4051 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:35.381  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.381  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.381  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.382  4051  4074 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:35.382  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:35.382  4051  4074 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:35.382  4051  4074 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:35.382  4051  4074 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:35.382  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 13:12:35.382  4051  4051 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:35.382  4051  4051 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 13:12:35.382  4051  4067 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:12:35.382  4051  4051 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:35.382  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.382  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.382  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:35.382  4051  4051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:12:35.383  4051  4067 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:12:35.383  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:35.383  4051  4051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:35.384  4051  4051 V BluetoothAdapterState: isTurningOff()=true
08-29 13:12:35.384  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.384  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.384  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:35.384  4051  4051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:12:35.384  4051  4051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:12:35.385  4051  4051 D BluetoothMapService: MAP Service closeService in
08-29 13:12:35.385  4051  4051 V BluetoothAdapterState: isTurningOff()=true
,08-29 13:12:35.385  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.385  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:35.386  4051  4051 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:35.386  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 13:12:35.386  4051  4063 D BluetoothAdapterProperties: Setting state to 15
08-29 13:12:35.386  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 13:12:35.387   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.387   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:35.387  4051  4063 I BluetoothAdapterState: Entering BleOnState
08-29 13:12:35.387  3831  3841 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:12:35.388  4051  4051 D BluetoothMapService: cleanup()
08-29 13:12:35.388  4051  4051 D BluetoothMapService: MAP Service closeService in
,08-29 13:12:35.388  3831  3843 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:12:35.389   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.389  1363  1363 D BluetoothPbap: Proxy object disconnected
08-29 13:12:35.389  1363  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:12:35.389  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-29 13:12:35.391  1363  1390 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:12:35.397  3831  3841 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:12:35.398  3831  3843 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:12:35.398   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.398  1363  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:12:35.399  1958  1979 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.400  3831  3841 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:35.401  3831  3843 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.401  1363  2095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:35.401  1363  1390 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:12:35.402  1363  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:12:35.402  4051  4063 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:12:35.402  4051  4063 D BluetoothAdapterProperties: Setting state to 16
08-29 13:12:35.402  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 13:12:35.403  4051  4063 D BluetoothAdapterProperties: onBleDisable
08-29 13:12:35.403  4051  4063 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:12:35.403  4051  4064 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 13:12:35.405  4051  4074 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:12:35.405  4051  4074 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:12:35.405  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.406  4051  4067 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:35.406  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.407  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.408  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:35.409  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:35.414  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:35.416  3831  3831 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:35.606  4051  4067 I bt_hci  : shut_down
,08-29 13:12:35.606  4051  4071 D bt_hwcfg: hw_epilog_process
08-29 13:12:35.607  4051  4071 I bt_vendor: low_power_mode_cb
,08-29 13:12:35.630  4051  4071 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 13:12:35.631  4051  4071 I bt_vendor: epilog_cb
,08-29 13:12:35.631  4051  4071 I bt_hci  : epilog_finished_callback
,08-29 13:12:35.641  4051  4067 I bt_hci_h4: hal_close
,08-29 13:12:35.642  4051  4067 I bt_userial_vendor: device fd = 51 close
,08-29 13:12:35.768  4051  4064 D bt_stack_manager: event_shut_down_stack finished.
,08-29 13:12:35.769  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:12:35.775  4051  4051 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:35.776  4051  4051 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 13:12:35.776  4051  4063 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 13:12:35.777  4051  4051 D BtGatt.GattService: stop()
,08-29 13:12:35.777  4051  4051 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:12:35.782  4051  4051 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:35.782  4051  4051 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:35.782  4051  4051 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:12:35.782  4051  4051 V BluetoothAdapterState: isBleTurningOff()=true
08-29 13:12:35.783  4051  4063 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 13:12:35.784  4051  4063 D BluetoothAdapterProperties: Setting state to 10
08-29 13:12:35.784  4051  4063 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 13:12:35.786  4051  4063 I BluetoothAdapterState: Entering OffState
08-29 13:12:35.788   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 13:12:35.803  4051  4051 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 13:12:35.804  4051  4051 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 13:12:35.808  4051  4064 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 13:12:35.808  4051  4051 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:12:35.820  4051  4064 D bt_stack_manager: event_clean_up_stack finished.
,08-29 13:12:35.825  4051  4051 I art     : System.exit called, status: 0
,08-29 13:12:35.825  4051  4051 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:12:35.880   874  1376 I ActivityManager: Process com.android.bluetooth (pid 4051) has died
,08-29 13:12:38.323  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:38.323  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.333  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:41.334  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e9ab48 added. We now have 6 listener(s)
08-29 13:12:41.334  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.339  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.339  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45e0de1 added. We now have 7 listener(s)
08-29 13:12:41.339  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.341  3760  3810 I System.out: IsBluetoothEnabled
,08-29 13:12:41.352  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.400   874   891 I ActivityManager: Start proc 4110:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 13:12:41.526  4110  4110 D AdapterServiceConfig: Adding HeadsetService
,08-29 13:12:41.526  4110  4110 D AdapterServiceConfig: Adding A2dpService
,08-29 13:12:41.526  4110  4110 D AdapterServiceConfig: Adding HidService
08-29 13:12:41.527  4110  4110 D AdapterServiceConfig: Adding HealthService
,08-29 13:12:41.527  4110  4110 D AdapterServiceConfig: Adding PanService
08-29 13:12:41.527  4110  4110 D AdapterServiceConfig: Adding GattService
08-29 13:12:41.527  4110  4110 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:12:41.541   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@594e0be:true
08-29 13:12:41.541  4110  4110 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 13:12:41.546  4110  4110 I bt_bluedroid: init
,08-29 13:12:41.547  4110  4122 I BluetoothAdapterState: Entering OffState
,08-29 13:12:41.556  4110  4123 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 13:12:41.556  4110  4123 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 13:12:41.557  4110  4123 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 13:12:41.558  4110  4123 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:12:41.559  4110  4110 I bt_bluedroid: get_profile_interface socket
,08-29 13:12:41.566  4110  4110 I bt_bluedroid: get_profile_interface sdp
,08-29 13:12:41.569  4110  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:12:41.573  4110  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:12:41.574  4110  4121 I bt_bluedroid: config_hci_snoop_log
,08-29 13:12:41.578   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:12:41.587  4110  4122 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 13:12:41.587  4110  4122 D BluetoothAdapterProperties: Setting state to 14
08-29 13:12:41.588  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:12:41.590  4110  4122 D BluetoothBondStateMachine: make
,08-29 13:12:41.592  4110  4127 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:12:41.597  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:12:41.598  4110  4110 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 13:12:41.601  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:41.602  4110  4110 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:12:41.603  4110  4110 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:12:41.603  4110  4110 D BtGatt.GattService: start()
08-29 13:12:41.603  4110  4110 I bt_bluedroid: get_profile_interface gatt
08-29 13:12:41.604  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:41.604  4110  4110 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:12:41.613  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:41.614  4110  4110 V BluetoothAdapterState: isTurningOn()=false
08-29 13:12:41.614  4110  4110 V BluetoothAdapterState: isBleTurningOn()=true
08-29 13:12:41.614  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:41.614  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 13:12:41.615  4110  4122 I bt_bluedroid: enable
08-29 13:12:41.615  4110  4123 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 13:12:41.616  4110  4123 I bt_hci  : start_up
,08-29 13:12:41.624  4110  4123 I bt_vendor: alloc value 0xb3a70189
,08-29 13:12:41.624  4110  4123 I bt_vendor: init
08-29 13:12:41.624  4110  4123 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 13:12:41.624  4110  4123 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:12:41.733  4110  4123 D bt_hci  : start_up starting async portion
,08-29 13:12:41.734  4110  4130 I bt_hci  : event_finish_startup
,08-29 13:12:41.734  4110  4130 I bt_hci_h4: hal_open
08-29 13:12:41.734  4110  4130 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:12:41.744  4110  4130 I bt_userial_vendor: device fd = 51 open
,08-29 13:12:41.775  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:12:41.807  4110  4130 D bt_hwcfg: Chipset BCM4354A2
08-29 13:12:41.807  4110  4130 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 13:12:41.808  4110  4130 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:12:42.480  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:12:42.481  4110  4130 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 13:12:42.482  4110  4130 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:12:42.600  4110  4130 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:12:42.601  4110  4130 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:12:42.629  4110  4130 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:12:42.629  4110  4130 I bt_vendor: firmware callback
08-29 13:12:42.630  4110  4130 I bt_hci  : firmware_config_callback
,08-29 13:12:42.662  4110  4132 I bt_btu  : btu_task pending for preload complete event
,08-29 13:12:42.662  4110  4132 I bt_btu_task: Bluetooth chip preload is complete
08-29 13:12:42.662  4110  4132 I bt_btu  : btu_task received preload complete event
,08-29 13:12:42.679  4110  4132 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:12:42.679  4110  4132 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:12:42.680  4110  4132 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:12:42.680  4110  4132 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 13:12:42.680  4110  4132 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 13:12:42.681  4110  4132 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:42.681  4110  4132 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:12:42.681  4110  4132 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:42.681  4110  4132 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:12:42.681  4110  4132 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:12:42.682  4110  4132 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:12:42.682  4110  4132 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:12:42.682  4110  4132 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:12:42.682  4110  4132 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:12:42.682  4110  4132 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:12:42.802   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 13:12:42.810  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-29 13:12:42.824  4110  4132 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,08-29 13:12:42.824  4110  4132 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,08-29 13:12:42.828  4110  4126 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:12:42.828   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:12:42.828   874   894 I Adreno  : Build Date                       : 10/20/15
08-29 13:12:42.828   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:12:42.828   874   894 I Adreno  : Local Branch                     : M14
08-29 13:12:42.828   874   894 I Adreno  : Remote Branch                    : 
08-29 13:12:42.828   874   894 I Adreno  : Remote Branch                    : 
08-29 13:12:42.828   874   894 I Adreno  : Reconstruct Branch               : 
,08-29 13:12:42.829  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 13:12:42.830  4110  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:12:42.832  4110  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:12:42.833  4110  4126 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:12:42.833  4110  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:42.833  4110  4126 D bt_hci  : do_postload posting postload work item
08-29 13:12:42.833  4110  4130 I bt_hci  : event_postload
08-29 13:12:42.833  4110  4130 I bt_vendor: sco_config_cb
08-29 13:12:42.833  4110  4130 I bt_hci  : sco_config_callback postload finished.
,08-29 13:12:42.835  4110  4126 D bt_bte_conf: Device ID record 1 : primary
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   vendorId            = 000f
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   vendorIdSource      = 0001
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   product             = 1200
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   version             = 1436
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   clientExecutableURL = 
,08-29 13:12:42.835  4110  4126 D bt_bte_conf:   serviceDescription  = 
08-29 13:12:42.835  4110  4126 D bt_bte_conf:   documentationURL    = 
08-29 13:12:42.835  4110  4126 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 13:12:42.836  4110  4123 D bt_stack_manager: event_start_up_stack finished
08-29 13:12:42.836  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:42.836  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 13:12:42.837  4110  4122 D BluetoothAdapterProperties: Setting state to 15
,08-29 13:12:42.837  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 13:12:42.837  4110  4122 I BluetoothAdapterState: Entering BleOnState
08-29 13:12:42.838  4110  4130 I bt_vendor: low_power_mode_cb
,08-29 13:12:42.843  4110  4122 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 13:12:42.845  4110  4122 D BluetoothAdapterProperties: Setting state to 11
,08-29 13:12:42.845  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 13:12:42.852  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:42.858  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:42.860  4110  4110 D HeadsetService: Received start request. Starting profile...
,08-29 13:12:42.862  4110  4122 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:12:42.864  4110  4110 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:12:42.866  4110  4110 D HeadsetStateMachine: make
,08-29 13:12:42.871   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (127 us)
,08-29 13:12:42.873  4110  4110 D HeadsetStateMachine: max_hf_connections = 1
,08-29 13:12:42.873  4110  4110 I bt_bluedroid: get_profile_interface handsfree
08-29 13:12:42.873  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 13:12:42.873  4110  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 13:12:42.879  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:42.881  4110  4110 D A2dpService: Received start request. Starting profile...
,08-29 13:12:42.886  4110  4110 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 13:12:42.888  4110  4110 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:12:42.894  4110  4110 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:12:42.894  4110  4110 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:42.895  4110  4110 D A2dpStateMachine: make
,08-29 13:12:42.896  4110  4110 I bt_bluedroid: get_profile_interface a2dp
,08-29 13:12:42.897  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 13:12:42.901  4110  4141 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:12:42.901  4110  4110 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:12:42.902  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:42.902  4110  4110 D HidService: Received start request. Starting profile...
08-29 13:12:42.902  4110  4110 I bt_bluedroid: get_profile_interface hidhost
,08-29 13:12:42.902  4110  4110 D HidService: setHidService(): set to: null
08-29 13:12:42.902  4110  4126 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
08-29 13:12:42.902  4110  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 13:12:42.903  4110  4110 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:12:42.903  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:42.904  4110  4110 D HealthService: Received start request. Starting profile...
,08-29 13:12:42.905  4110  4110 I bt_bluedroid: get_profile_interface health
08-29 13:12:42.906  4110  4110 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 13:12:42.906  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
,08-29 13:12:42.907  4110  4110 D PanService: Received start request. Starting profile...
,08-29 13:12:42.907  4110  4110 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:12:42.907  4110  4110 I bt_bluedroid: get_profile_interface pan
08-29 13:12:42.907  4110  4126 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:12:42.909  4110  4110 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:42.910  4110  4110 D BluetoothMapService: Received start request. Starting profile...
08-29 13:12:42.910  4110  4110 D BluetoothMapService: start()
08-29 13:12:42.912  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 13:12:42.912  4110  4110 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 13:12:42.913  4110  4110 D BluetoothMapAppObserver: createReceiver()
08-29 13:12:42.914  4110  4110 D BluetoothMapAppObserver: initObservers()
08-29 13:12:42.914  4110  4110 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 13:12:42.921  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:42.923  4110  4139 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:12:42.924  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:42.924  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.924  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:42.924  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:42.925  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:42.925  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.925  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOff()=false
08-29 13:12:42.926  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isTurningOn()=true
08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:12:42.927  4110  4110 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:12:42.927  4110  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:12:42.927  4110  4122 D BluetoothAdapterProperties: ScanMode =  20,
08-29 13:12:42.927  4110  4122 D BluetoothAdapterProperties: State =  11
08-29 13:12:42.928  4110  4122 D BluetoothAdapterProperties: Setting state to 12
08-29 13:12:42.928  4110  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:12:42.929  4110  4126 D BluetoothAdapterProperties: Scan Mode:21
,08-29 13:12:42.929  4110  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:42.929  4110  4122 I BluetoothAdapterState: Entering OnState
08-29 13:12:42.929   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.929   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:42.932  3831  3841 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:42.932  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:42.935   874   874 D BluetoothA2dp: Proxy object connected
08-29 13:12:42.935  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:42.935  3831  3843 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:12:42.937   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.937  1363  2095 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:42.938  1363  1390 D BluetoothPan: onBluetoothStateChange on: true
,08-29 13:12:42.939  1363  1363 D BluetoothMap: Proxy object connected
08-29 13:12:42.939  1363  1363 D MapProfile: Bluetooth service connected
08-29 13:12:42.939  1363  1363 D BluetoothMap: getConnectedDevices()
08-29 13:12:42.940  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:12:42.941  4110  4110 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 13:12:42.941  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:42.941  3831  3843 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:42.942  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:42.943  1363  1363 D PanProfile: Bluetooth service connected
08-29 13:12:42.944  4110  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:42.945  3831  3841 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:12:42.947  4110  4110 D ObexServerSockets: Succeed to create listening sockets 
08-29 13:12:42.947   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.948  4110  4110 D ObexServerSockets0: startAccept()
,08-29 13:12:42.948  1363  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:12:42.949  4110  4110 D ObexServerSockets0: prepareForNewConnect()
08-29 13:12:42.952  4110  4147 D ObexServerSockets0: Accepting socket connection...
,08-29 13:12:42.950  1958  1979 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.951  4110  4110 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 13:12:42.952  4110  4110 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 13:12:42.955  4110  4148 D ObexServerSockets0: Accepting socket connection...
08-29 13:12:42.955  3831  3841 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:42.956  1363  1363 D BluetoothInputDevice: Proxy object connected
08-29 13:12:42.956  1363  1363 D HidProfile: Bluetooth service connected
,08-29 13:12:42.962  3831  4149 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.955  3831  3831 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:42.962  3831  3831 D PanProfile: Bluetooth service connected
08-29 13:12:42.962  3831  3831 D BluetoothMap: Proxy object connected
08-29 13:12:42.962  3831  3831 D MapProfile: Bluetooth service connected
08-29 13:12:42.962  3831  3831 D BluetoothMap: getConnectedDevices()
08-29 13:12:42.962  1363  1390 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:42.963  3831  3831 D BluetoothInputDevice: Proxy object connected
08-29 13:12:42.963  3831  3831 D HidProfile: Bluetooth service connected
08-29 13:12:42.964  1363  1363 D BluetoothA2dp: Proxy object connected
08-29 13:12:42.964  1363  2095 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:12:42.965  3831  3831 D BluetoothA2dp: Proxy object connected
08-29 13:12:42.966  1363  1390 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:12:42.967   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 13:12:42.969  4110  4110 D BluetoothMapService: onReceive
08-29 13:12:42.969  4110  4110 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:42.969  4110  4110 D BluetoothMapService: STATE_ON
08-29 13:12:42.969  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:42.977  3831  3831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:42.982  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:42.986  3831  3831 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:42.989  3831  3831 D BluetoothPbap: Proxy object connected
08-29 13:12:42.989  3831  3831 D PbapServerProfile: Bluetooth service connected
,08-29 13:12:42.996  4110  4110 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 13:12:42.996  4110  4110 D ObexServerSockets0: prepareForNewConnect()
08-29 13:12:43.000  1363  1363 D BluetoothPbap: Proxy object connected
08-29 13:12:43.000  1363  1363 D PbapServerProfile: Bluetooth service connected
08-29 13:12:43.003  4110  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:43.015  4110  4158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:43.016  4110  4158 I BtOppRfcommListener: Accept thread started.
,08-29 13:12:43.023  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:43.028  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:43.030  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:12:43.030   874   874 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.030   874   874 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.031  3831  3843 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.031   874   874 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.031  1958  1973 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.031  3831  3831 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:43.031  1363  2095 D BluetoothHeadset: Proxy object connected
08-29 13:12:43.032  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:43.037   874   891 D BluetoothHeadset: Proxy object connected
,08-29 13:12:43.047  1499  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 13:12:43.047  1499  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:12:43.047  1499  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:43.047  1499  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 13:12:43.048   874   891 D BluetoothHeadset: Proxy object connected
,08-29 13:12:43.053  1958  2099 D BluetoothHeadset: Proxy object connected
,08-29 13:12:43.059  3512  3512 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 13:12:43.059  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 13:12:43.059  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 13:12:43.062  3831  4149 D BluetoothHeadset: Proxy object connected
,08-29 13:12:43.062  3831  3831 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:43.067  1363  1390 D BluetoothHeadset: Proxy object connected
,08-29 13:12:43.068  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:43.376  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:43.385  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:43.389  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:43.389  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14ca706 added. We now have 8 listener(s)
08-29 13:12:43.390  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:43.395   874  1912 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-29 13:12:43.395   874  1912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:43.411  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:43.413   874  1951 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-29 13:12:43.413   874  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:43.445  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:43.468  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-29 13:12:43.480  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:12:43.480  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 13:12:43.480  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-29 13:12:43.481  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:12:43.483  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@aadebb3 Bundle[{}]
08-29 13:12:43.484  3760  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:12:43.484  3760  3810 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 13:12:43.485  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 13:12:43.485  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:12:43.486  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 13:12:43.486  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:12:43.501  3760  3810 I System.out: Running OutgoingSocketThread
08-29 13:12:43.503  3760  4165 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 413)
,08-29 13:12:43.504  3760  4165 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40242
08-29 13:12:43.504  3760  4165 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:12:43.541   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 13:12:43.542   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:12:43.548   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:43.551  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:43.552   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 13:12:43.555   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-29 13:12:43.555   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-29 13:12:43.557  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:43.558  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@aadebb3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d2b21c7, 16908290=android.view.AbsSavedState$1@d2b21c7}, android:focusedViewId=100}]}]
08-29 13:12:43.558  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 13:12:43.558  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:12:43.558  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 13:12:43.577   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:12:43.578   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 13:12:43.578   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 13:12:43.579   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:12:43.579   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 13:12:43.579   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 13:12:43.579   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 13:12:43.580   874   883 I art     : Background partial concurrent mark sweep GC freed 25329(2022KB) AllocSpace objects, 14(512KB) LOS objects, 33% free, 29MB/43MB, paused 1.754ms total 132.781ms
,08-29 13:12:43.586   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 13:12:43.587   373   873 D CommandListener: Setting iface cfg
,08-29 13:12:43.588   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-29 13:12:43.588   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:12:43.589   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.25 delta 1000 -> 1000
,08-29 13:12:43.592   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-29 13:12:43.592   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:12:43.605   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 13:12:43.605   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:43.611   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:12:43.663   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:12:43.664  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:12:43.784   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 13:12:43.786   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-29 13:12:43.788   874  1333 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-29 13:12:43.794   874   894 I DreamManagerService: Entering dreamland.
,08-29 13:12:43.794   874   894 I PowerManagerService: Dozing...
08-29 13:12:43.795   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 13:12:43.874   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 13:12:43.874   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 13:12:43.879   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:12:43.889   874  1309 E native  : do suspend false
,08-29 13:12:43.893  1944  4168 D NfcService: Discovery configuration equal, not updating.
,08-29 13:12:43.900   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 13:12:43.932   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 13:12:43.934  1459  1459 E wpa_supplicant: PNO: In assoc process
,08-29 13:12:43.935   874  1309 E WifiStateMachine:  Fail to set up pno, want true now false
,08-29 13:12:43.940   874  1309 E native  : do suspend true
,08-29 13:12:44.011   377  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 13:12:44.011   377  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 13:12:44.167  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:12:44.215  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:12:44.217  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:12:44.225   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:12:44.241   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:12:44.242   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 13:12:44.244   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:44.277   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:44.293   373   873 D CommandListener: Setting iface cfg
08-29 13:12:44.294   874  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 13:12:44.308   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:12:44.339   874  4175 D DhcpClient: Receive thread started
,08-29 13:12:44.425   874  1309 E native  : do suspend false
,08-29 13:12:44.443   874  2117 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 13:12:44.457   874  4175 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 13:12:44.458   874  2117 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-29 13:12:44.462   874  2117 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:12:44.477   874  4175 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 13:12:44.478   874  2117 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:12:44.483   373   873 D CommandListener: Setting iface cfg
,08-29 13:12:44.496   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 13:12:44.497   874  2117 D DhcpClient: Scheduling renewal in 86399s
,08-29 13:12:44.501   874  1309 E native  : do suspend true
,08-29 13:12:44.505  3760  3810 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 414)
,08-29 13:12:44.506  3760  3810 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 414)
,08-29 13:12:44.515  3760  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 419)
,08-29 13:12:44.517  3760  3810 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 13:12:44.518  3760  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 420)
,08-29 13:12:44.522  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:44.522   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-29 13:12:44.522  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69233f4 added. We now have 2 listener(s)
,08-29 13:12:44.523   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 13:12:44.524  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:44.524   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 13:12:44.525  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.525  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.525  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:44.525  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acca71d added. We now have 9 listener(s)
,08-29 13:12:44.525  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.526  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:44.529   874  1311 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 13:12:44.531  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.532   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:44.536  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:44.539  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:44.539  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:44.540  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.540  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae1363 added. We now have 3 listener(s)
,08-29 13:12:44.541  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:44.542  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.542  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:12:44.542  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:44.542  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d989b60 added. We now have 10 listener(s)
08-29 13:12:44.542  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.542  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:44.542  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:44.542  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:44.543  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.543  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.543  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:44.543  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-29 13:12:44.543  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69233f4 removed from the list
08-29 13:12:44.543  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.543  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acca71d removed from the list
,08-29 13:12:44.543  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:44.543  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:44.546  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:44.546  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.546  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.548  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:44.548  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.548  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:44.548  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acca71d not in the list
08-29 13:12:44.548  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.548  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.551  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.551  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:44.551  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.552  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d989b60 removed from the list
08-29 13:12:44.552  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.552  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.552  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.552  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:44.553  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ae1363 removed from the list
,08-29 13:12:44.555  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.555  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5919819 added. We now have 2 listener(s)
,08-29 13:12:44.560  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:44.561  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:44.561  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.562  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:44.562  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab90de added. We now have 9 listener(s)
08-29 13:12:44.562  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.563  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:44.566  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:44.570  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:44.573  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:44.573  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:44.573  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.573  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dc0d8c added. We now have 3 listener(s)
,08-29 13:12:44.575  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:44.575  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.575  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:44.575  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.576  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:44.576  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a9cd5 added. We now have 10 listener(s)
08-29 13:12:44.576  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:44.576  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:44.576  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:44.576  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:44.576  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:44.576  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:44.582  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:44.584   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:12:44.584   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 13:12:44.584   874  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
08-29 13:12:44.584  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:12:44.585  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:44.585   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 13:12:44.586   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 13:12:44.587   874  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 13:12:44.594  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:44.595  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:12:44.595   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 13:12:44.595  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:44.598  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:44.598  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:44.598  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:44.599  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:44.601   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 13:12:44.601   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 13:12:44.601   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 13:12:44.601   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 13:12:44.601   874  1311 D ConnectivityService:    accepting network in place of null
08-29 13:12:44.602   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:12:44.602  4110  4159 D BtGatt.GattService: registerClient() - UUID=90ab761b-82a5-4ce1-a3cc-6d8bc67f2aaa
,08-29 13:12:44.602  4110  4126 D BtGatt.GattService: onClientRegistered() - UUID=90ab761b-82a5-4ce1-a3cc-6d8bc67f2aaa, clientIf=5
08-29 13:12:44.602   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 13:12:44.604  3760  3770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:12:44.605  4110  4138 D BtGatt.GattService: start scan with filters
,08-29 13:12:44.608  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:44.608  4110  4129 D BtGatt.ScanManager: handling starting scan
08-29 13:12:44.608  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:12:44.608  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:44.608  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:12:44.609  4110  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8cdf522
08-29 13:12:44.611  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:44.611  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:44.611  4110  4126 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:12:44.612  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.612  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:44.612  4110  4129 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:12:44.613  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:12:44.614  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:12:44.614  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.614  4110  4129 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:12:44.615  4110  4129 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-29 13:12:44.617  4110  4126 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:12:44.617  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.617  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:44.617  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:44.617  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:12:44.617  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.617  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:12:44.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:44.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:44.618  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:44.618  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:44.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:44.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:44.618  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:12:44.619  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.619  3760  3810 D BluetoothAdapter: STATE_ON
08-29 13:12:44.619  4110  4138 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:44.620  4110  4121 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:12:44.621  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:44.621  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:44.621  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:12:44.621  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 13:12:44.621  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:44.622  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:44.622  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:44.622  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:12:44.622  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:44.623  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:12:44.623  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.623  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:44.623  4110  4129 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:44.624  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:44.624  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:44.624  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:44.626  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:12:44.626  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.626  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:44.626  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:44.626  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:44.626  4110  4129 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:12:44.626  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.626  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.626  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:44.626  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:44.626  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5919819 removed from the list
08-29 13:12:44.627  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.627  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab90de removed from the list
08-29 13:12:44.627  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:44.627  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.627  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.627  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.627  4110  4126 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:12:44.628  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.628  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:44.628  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.629  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab90de not in the list
08-29 13:12:44.629  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.629  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:44.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:44.630  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1a9cd5 removed from the list
08-29 13:12:44.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.630  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:44.630  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dc0d8c removed from the list
08-29 13:12:44.631  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.631  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf53151 added. We now have 2 listener(s)
08-29 13:12:44.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:44.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.633  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:44.633  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f12ddb6 added. We now have 9 listener(s)
08-29 13:12:44.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.634  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:44.636  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:44.638  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:44.640  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.640  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:44.640  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:44.640  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5248224 added. We now have 3 listener(s)
08-29 13:12:44.641  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:44.641  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.641  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.641  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:44.641  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0a918d added. We now have 10 listener(s)
08-29 13:12:44.642  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:44.642  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:44.642  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.642  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:44.642  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 13:12:44.642  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:44.642  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.642  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:44.644  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:44.645  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:12:44.645  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:44.645   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:12:44.647  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:44.648  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:12:44.648  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:44.650  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:44.650  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:44.651  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:44.651  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:44.653  4110  4121 D BtGatt.GattService: registerClient() - UUID=6d6fa805-d614-4f10-a468-404598e22fad
,08-29 13:12:44.653  4110  4126 D BtGatt.GattService: onClientRegistered() - UUID=6d6fa805-d614-4f10-a468-404598e22fad, clientIf=5
08-29 13:12:44.653  3760  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:12:44.654  4110  4120 D BtGatt.GattService: start scan with filters
,08-29 13:12:44.656  4110  4129 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:44.657  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:44.657  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:44.657  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:44.657  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:44.658  4110  4126 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:12:44.658  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.658  4110  4129 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:12:44.659  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:44.659  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:12:44.659  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:44.659  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:12:44.659  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.659  4110  4129 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:12:44.659  4110  4129 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:12:44.661  4110  4126 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:12:44.661  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.661  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:44.664  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:44.664  3760  3810 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 13:12:44.664  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:12:44.664  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.664  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:44.664  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:44.664  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:44.664  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:44.664  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.664  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:44.664  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:12:44.665  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf53151 removed from the list
08-29 13:12:44.665  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:44.665  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f12ddb6 removed from the list
08-29 13:12:44.665  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:44.665  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:44.665  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.665  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 13:12:44.665  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.665  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:44.666  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:44.666  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:44.666  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.666  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f12ddb6 not in the list
,08-29 13:12:44.666  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:44.666  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 13:12:44.667  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:12:44.667  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 13:12:44.667  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:12:44.668  3760  3810 D BluetoothAdapter: STATE_ON
08-29 13:12:44.668   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 13:12:44.668  4110  4159 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:12:44.670  4110  4138 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:12:44.670  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:12:44.670  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:44.670  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:44.670  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 13:12:44.670  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:44.671  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:44.671  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:44.671  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:44.671  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:44.672  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:44.673  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:12:44.673  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.673   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 13:12:44.673  4110  4129 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:12:44.673   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:44.674  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:44.674  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:44.674  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:44.674  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.674  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:44.674  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:44.674  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0a918d removed from the list
08-29 13:12:44.674  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.674  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.675  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.675  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:12:44.675  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5248224 removed from the list
08-29 13:12:44.676  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.676  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bb989 added. We now have 2 listener(s)
08-29 13:12:44.677   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 13:12:44.678   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:44.685  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:44.687  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.687  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:44.688  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:44.688  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.688  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:12:44.689  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 13:12:44.688  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:44.689  4110  4129 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:12:44.689  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcbed8e added. We now have 9 listener(s)
08-29 13:12:44.689  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.689  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:44.693  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.694  4110  4126 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:12:44.694  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:44.697  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:44.699  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.699  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:44.699  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:44.699  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943f1bc added. We now have 3 listener(s)
,08-29 13:12:44.701  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:44.703  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:44.703  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.703  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.703  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.703  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:44.703  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd6545 added. We now have 10 listener(s)
08-29 13:12:44.703  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:44.703  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:44.703  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:44.703  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:12:44.703  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.704  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:44.706  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:12:44.706  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 13:12:44.706  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:44.709  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:44.709  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:12:44.709  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:44.710  1694  1694 D SystemUpdateService: onCreate
,08-29 13:12:44.712  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:44.712  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:44.712  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:12:44.712  3760  3810 D BluetoothAdapter: STATE_ON
,08-29 13:12:44.712  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:12:44.714  4110  4138 D BtGatt.GattService: registerClient() - UUID=b6f68288-052a-4c4a-997f-7c1e3b2467ad
,08-29 13:12:44.714  4110  4126 D BtGatt.GattService: onClientRegistered() - UUID=b6f68288-052a-4c4a-997f-7c1e3b2467ad, clientIf=5
,08-29 13:12:44.715  3760  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:12:44.715  4110  4120 D BtGatt.GattService: start scan with filters
,08-29 13:12:44.717  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:44.717  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:44.717  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:12:44.718  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-29 13:12:44.718  4110  4129 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:44.720  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:44.720  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:44.720  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:12:44.722  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:12:44.724  4110  4126 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:12:44.724  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:44.724  4110  4129 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:12:44.725  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:44.726  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:44.726  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:44.726  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.726  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.726  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:44.726  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:44.726  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bb989 removed from the list
,08-29 13:12:44.726  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.726  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcbed8e removed from the list
,08-29 13:12:44.726  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:44.726  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:44.728  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.728  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:12:44.728  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.728  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.729  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcbed8e not in the list
08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:44.729  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:44.729  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:44.729  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:44.729  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.729  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:12:44.729  4110  4129 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:44.730  4110  4129 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:12:44.730  3760  3810 D BluetoothAdapter: STATE_ON
08-29 13:12:44.730  4110  4120 D BtGatt.GattService: stopScan() - queue size =1,
08-29 13:12:44.731  4110  4159 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:12:44.731  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-29 13:12:44.731  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:44.731  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:44.731  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-29 13:12:44.731  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:44.732  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:44.732  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:44.732  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:12:44.732  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:44.733  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:44.733  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:44.733  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:44.733  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.733  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:44.733  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd6545 removed from the list
08-29 13:12:44.733  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.733  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:44.733  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.734  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:44.734  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:44.734  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:12:44.734  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943f1bc removed from the list
08-29 13:12:44.734  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:44.734  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1410c1 added. We now have 2 listener(s)
08-29 13:12:44.734  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:12:44.735  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:12:44.735  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:44.735  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:12:44.735  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:44.735  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec2066 added. We now have 9 listener(s)
08-29 13:12:44.736  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:44.736  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:44.739  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:44.741  1694  2519 I iu.UploadsManager: num queued entries: 0
,08-29 13:12:44.741  4110  4126 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:12:44.741  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:44.742  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:44.744  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:44.744  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:44.745  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:12:44.745  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.746  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:44.747  1694  4184 I SystemUpdateService: active receiver: enabled
08-29 13:12:44.747  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:44.747  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bebc54 added. We now have 3 listener(s)
08-29 13:12:44.748  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:44.748  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:12:44.748  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:44.748  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:44.749  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:44.749  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ff7fd added. We now have 10 listener(s)
08-29 13:12:44.749  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:44.749  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:44.749  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:44.749  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:44.749  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:44.749  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:44.749  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:44.749  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:12:44.749  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 13:12:44.749  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1410c1 removed from the list
08-29 13:12:44.749  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.749  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec2066 removed from the list
08-29 13:12:44.749  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:44.750  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.750  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.750  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.751  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.751  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec2066 not in the list
08-29 13:12:44.751  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.751  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.751  4110  4126 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:12:44.751  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:12:44.751  4110  4129 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:44.751  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:44.752  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88ff7fd removed from the list
,08-29 13:12:44.752  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:44.752  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:44.752  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:44.752  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:44.752  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bebc54 removed from the list
08-29 13:12:44.752  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 13:12:44.752  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:12:44.752  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 13:12:44.753  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:44.753  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-29 13:12:44.753  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:44.753  3885  3885 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:44.757  4110  4126 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:12:44.757  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.757  3760  4189 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: My test thread name)
08-29 13:12:44.757  4110  4129 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:12:44.757  3760  4189 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: My test thread name)
08-29 13:12:44.757  3885  3885 D SprintDMHelper: simOperator: 
08-29 13:12:44.757  3885  3885 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 13:12:44.757  3760  4189 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:12:44.761  3760  4190 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,08-29 13:12:44.761  3760  4190 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
08-29 13:12:44.761  3760  4190 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:12:44.762  3760  3810 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:12:44.762  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:12:44.762  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:12:44.762  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:12:44.762  3760  3810 D com.test.thalitest.ThaliTestRunner: Total duration: 21803 ms
08-29 13:12:44.763  4110  4126 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:12:44.763  4110  4126 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:12:44.764  3760  3810 I jxcore-log: *Native tests were executed*
08-29 13:12:44.764  3760  3810 I jxcore-log: 
08-29 13:12:44.764  3760  3810 I jxcore-log: Total number of executed tests:  80
08-29 13:12:44.764  3760  3810 I jxcore-log: 
08-29 13:12:44.764  3760  3810 I jxcore-log: Number of passed tests:  80
08-29 13:12:44.764  3760  3810 I jxcore-log: 
08-29 13:12:44.764  3760  3810 I jxcore-log: Number of failed tests:  0
08-29 13:12:44.764  3760  3810 I jxcore-log: 
08-29 13:12:44.764  3760  3810 I jxcore-log: Number of ignored tests:  0
08-29 13:12:44.764  3760  3810 I jxcore-log: 
08-29 13:12:44.765  3760  3810 I jxcore-log: Total duration:  21803
08-29 13:12:44.765  3760  3810 I jxcore-log: 
08-29 13:12:44.765  3760  3810 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:12:44.765  3760  3810 I jxcore-log: 
,08-29 13:12:44.770  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.770  3760  3810 I jxcore-log: 
08-29 13:12:44.770  3760  3760 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 13:12:44.772  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.772  3760  3810 I jxcore-log: 
08-29 13:12:44.773  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.773  3760  3810 I jxcore-log: 
08-29 13:12:44.774  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.774  3760  3810 I jxcore-log: 
08-29 13:12:44.775  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.775  3760  3810 I jxcore-log: 
08-29 13:12:44.776  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.776  3760  3810 I jxcore-log: 
08-29 13:12:44.778  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.778  3760  3810 I jxcore-log: 
08-29 13:12:44.780  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.780  3760  3810 I jxcore-log: 
08-29 13:12:44.781  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.781  3760  3810 I jxcore-log: 
08-29 13:12:44.781  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.781  3760  3810 I jxcore-log: 
,08-29 13:12:44.782  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.782  3760  3810 I jxcore-log: 
,08-29 13:12:44.784  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:44.784  3760  3810 I jxcore-log: 
,08-29 13:12:44.784  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.784  3760  3810 I jxcore-log: 
,08-29 13:12:44.785  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.785  3760  3810 I jxcore-log: 
,08-29 13:12:44.786  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.786  3760  3810 I jxcore-log: 
,08-29 13:12:44.786  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.786  3760  3810 I jxcore-log: 
,08-29 13:12:44.787  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.787  3760  3810 I jxcore-log: 
,08-29 13:12:44.788  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.788  3760  3810 I jxcore-log: 
,08-29 13:12:44.788  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.788  3760  3810 I jxcore-log: 
08-29 13:12:44.789  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.789  3760  3810 I jxcore-log: 
,08-29 13:12:44.790  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.790  3760  3810 I jxcore-log: 
,08-29 13:12:44.790  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.790  3760  3810 I jxcore-log: 
08-29 13:12:44.791  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.791  3760  3810 I jxcore-log: 
,08-29 13:12:44.792  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:44.792  3760  3810 I jxcore-log: 
,08-29 13:12:44.792  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.792  3760  3810 I jxcore-log: 
,08-29 13:12:44.793  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.793  3760  3810 I jxcore-log: 
,08-29 13:12:44.794  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.794  3760  3810 I jxcore-log: 
,08-29 13:12:44.794  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:44.794  3760  3810 I jxcore-log: 
,08-29 13:12:44.795  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.795  3760  3810 I jxcore-log: 
,08-29 13:12:44.795  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.795  3760  3810 I jxcore-log: 
,08-29 13:12:44.796  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.796  3760  3810 I jxcore-log: 
,08-29 13:12:44.797  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:44.797  3760  3810 I jxcore-log: 
,08-29 13:12:44.797  1694  4187 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 13:12:44.797  1694  4187 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 13:12:44.798  1694  4187 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 13:12:44.804  1694  2519 I iu.UploadsManager: num updated entries: 0
,08-29 13:12:44.814  1694  4184 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:12:44.815  1694  2519 I iu.SyncManager: NEXT; no task
,08-29 13:12:44.818  1694  4184 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 13:12:44.818  1694  4184 I SystemUpdateService: now status is 0 (complete)
08-29 13:12:44.818  1694  4184 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:12:44.819  1694  4184 I SystemUpdateService: file has been verified
08-29 13:12:44.819  1694  4184 I SystemUpdateService: OTA package size = 12249756
,08-29 13:12:44.827  1694  4184 I SystemUpdateService: showing system update notification
,08-29 13:12:44.833  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:12:44.833  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 13:12:44.833  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:12:44.833  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:12:44.836  1694  1694 D SystemUpdateService: onDestroy
,08-29 13:12:44.845  1694  4187 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-29 13:12:45.124  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:12:45.126  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:45.126  3760  3810 I jxcore-log: 
,08-29 13:12:45.174  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:12:45.176  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:45.176  3760  3810 I jxcore-log: 
,08-29 13:12:45.234  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:12:45.236  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:45.236  3760  3810 I jxcore-log: 
,08-29 13:12:45.384  4195  4195 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 13:12:45.389  4195  4195 D AndroidRuntime: CheckJNI is OFF
,08-29 13:12:45.432  4195  4195 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 13:12:45.480  4195  4195 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 13:12:45.503  4195  4195 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:12:45.513   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 13:12:45.514   874   887 I ActivityManager: Killing 3760:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 13:12:45.625   874  4174 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152781, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 13:12:45.639   874  1376 D GraphicsStats: Buffer count: 2
,08-29 13:12:45.639   874  1515 I WindowState: WIN DEATH: Window{62b0cd3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:12:45.640   874  1310 D WifiService: Client connection lost with reason: 4
,08-29 13:12:45.643   874   897 W PackageSettings: Skipping PackageSetting{1a94ea7 com.example.hello/10273} due to missing metadata
,08-29 13:12:45.672   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 13:12:45.680   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 13:12:45.681   874   897 I art     : Starting a blocking GC Explicit
08-29 13:12:45.681   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 13:12:45.681   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-29 13:12:45.681   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 13:12:45.681   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:45.681   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
,08-29 13:12:45.681   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:12:45.681   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 13:12:45.682   874   887 I ActivityManager:   Force finishing activity ActivityRecord{f73af98 u0 com.test.thalitest/.MainActivity t2}
,08-29 13:12:45.695   874  1376 W ActivityManager: Spurious death for ProcessRecord{2ef66a2 0:com.test.thalitest/u0a0}, curProc for 3760: null
,08-29 13:12:45.732   874   897 I art     : Explicit concurrent mark sweep GC freed 46362(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 753us total 49.707ms
,08-29 13:12:45.757   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 13:12:45.760  4195  4195 I art     : System.exit called, status: 0
,08-29 13:12:45.760  4195  4195 I AndroidRuntime: VM exiting with result code 0.
,08-29 13:12:45.763   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 13:12:45.789   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 13:12:45.795  1884  1884 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 13:12:45.797  4110  4110 D BluetoothMapAppObserver: onReceive
08-29 13:12:45.797  4110  4110 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 13:12:45.799   874  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 13:12:45.799  3602  3602 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-29 13:12:45.800  1852  2241 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 13:12:45.801  1884  4207 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 13:12:45.806  1884  4207 I Decoder : createOrResetDecoder
,08-29 13:12:45.818   874  2046 I ActivityManager: Start proc 4210:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 13:12:45.822  1958  1958 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 13:12:45.867  4210  4210 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 13:12:45.874  1499  1499 I ConfigService: onCreate
,08-29 13:12:45.899   874  1982 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3760 uid 10000
,08-29 13:12:45.901   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 13:12:45.904  1884  1884 I Keyboard.Facilitator: onFinishInput()
,08-29 13:12:45.908  1884  4207 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 13:12:45.937   874  1334 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-29 13:12:45.937   874  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
,08-29 13:12:45.937   874  1334 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-29 13:12:45.937   874  1334 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-29 13:12:45.937   874  1334 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,08-29 13:12:45.939   874  1334 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-29 13:12:45.939   874  1334 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,08-29 13:12:45.939   874  1334 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,08-29 13:12:45.939   874  1334 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,08-29 13:12:45.939   874  1334 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
,08-29 13:12:45.939   874  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,08-29 13:12:45.940   874  1334 W System.err: 	... 4 more
,08-29 13:12:45.940   874  1334 D skia    : ------- write threw an exception
,08-29 13:12:45.949  1974  2075 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 13:12:45.949   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 13:12:45.950   874   886 E PackageManager: Failed to write settings, restoring backup
08-29 13:12:45.950   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 13:12:45.950   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 13:12:45.950   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 13:12:45.950   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 13:12:45.950   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 13:12:45.950   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:45.950   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:45.950   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:12:45.953   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-29 13:12:45.953   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 13:12:45.953   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:45.953   874   887 E DropBoxManagerService: 	... 13 more
,08-29 13:12:45.959  1884  4207 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 13:12:45.961  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 13:12:45.961  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 13:12:45.962   874  1982 I ActivityManager: Start proc 4227:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 13:12:45.962  1974  2075 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 13:12:45.962  1974  2075 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1974
08-29 13:12:45.962  1974  2075 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:45.962  1974  2075 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:12:45.964   874  1515 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:12:45.966  4210  4210 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-29 13:12:45.967  1974  2075 I Process : Sending signal. PID: 1974 SIG: 9
,08-29 13:12:45.971   874  4235 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:12:45.971   874  4235 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:45.971   874  4235 E DropBoxManagerService: 	... 5 more
,08-29 13:12:45.971  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 13:12:45.971  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 13:12:45.972  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 13:12:45.972  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 13:12:45.973  1884  4207 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 13:12:45.973  1884  4207 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-29 13:12:45.973  1884  4207 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-29 13:12:45.973  1884  4207 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-29 13:12:45.973  1884  4207 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 13:12:45.973  1884  4207 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 13:12:45.988   874  2015 I ActivityManager: Start proc 4242:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 13:12:45.991  4210  4241 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 13:12:46.027  4210  4241 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.027  4210  4241 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:12:46.028  4210  4241 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 13:12:46.028  4210  4241 E AndroidRuntime: Process: android.process.acore, PID: 4210
08-29 13:12:46.028  4210  4241 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.028  4210  4241 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:12:46.030   874  4255 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:12:46.030   874  4255 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:46.030   874  4255 E DropBoxManagerService: 	... 5 more
,08-29 13:12:46.032  4210  4241 I Process : Sending signal. PID: 4210 SIG: 9
,08-29 13:12:46.036  4242  4242 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 13:12:46.046   279   279 E lowmemorykiller: Error writing /proc/4210/oom_score_adj; errno=22
,08-29 13:12:46.060  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 13:12:46.060  1499  1499 D AndroidRuntime: Shutting down VM
08-29 13:12:46.061  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:12:46.061  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
08-29 13:12:46.061  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 13:12:46.061  1499  1499 E AndroidRuntime: 	... 8 more
,08-29 13:12:46.064  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
,08-29 13:12:46.064   874  4259 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:12:46.064   874  4259 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:46.064   874  4259 E DropBoxManagerService: 	... 5 more
08-29 13:12:46.069   279   279 E lowmemorykiller: Error writing /proc/4210/oom_score_adj; errno=22
,08-29 13:12:46.082  1694  4260 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-29 13:12:46.082  1694  4260 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@7f1eea
08-29 13:12:46.082   874  1983 I ActivityManager: Process com.google.process.gapps (pid 1499) early provider death
,08-29 13:12:46.092   874  1310 D WifiService: Client connection lost with reason: 4
,08-29 13:12:46.093   874  1983 I ActivityManager: Process com.google.process.gapps (pid 1499) has died
,08-29 13:12:46.094   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,08-29 13:12:46.094   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-29 13:12:46.094   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-29 13:12:46.094   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
08-29 13:12:46.095   279   279 E lowmemorykiller: Error writing /proc/4210/oom_score_adj; errno=22
08-29 13:12:46.096   874   884 W ActivityManager: Spurious death for ProcessRecord{1ad57a5 0:com.google.process.gapps/u0a11}, curProc for 1499: null
,08-29 13:12:46.096   279   279 E lowmemorykiller: Error writing /proc/4210/oom_score_adj; errno=22
,08-29 13:12:46.105   874   885 I WindowState: WIN DEATH: Window{8490718 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-29 13:12:46.105   874   884 D GraphicsStats: Buffer count: 1
,08-29 13:12:46.139   874  1376 I ActivityManager: Start proc 4264:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-29 13:12:46.141   874  1982 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1974) has died
,08-29 13:12:46.141   874  1982 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40953ms
08-29 13:12:46.142   874  1982 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 13:12:46.145   874   885 I ActivityManager: Process android.process.acore (pid 4210) has died
08-29 13:12:46.145   874   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40949ms
,08-29 13:12:46.157   874   887 I ActivityManager: Start proc 4276:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:12:46.157  1694  1694 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 13:12:46.171  4264  4264 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 13:12:46.176  4264  4264 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-29 13:12:46.178  4264  4264 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.178  4264  4264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.178  4264  4264 D AndroidRuntime: Shutting down VM
08-29 13:12:46.179  4264  4264 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:12:46.179  4264  4264 E AndroidRuntime: Process: com.google.process.gapps, PID: 4264
08-29 13:12:46.17,9  4264  4264 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.179  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29, 13:12:46.179  4264  4264 E AndroidRuntime: 	... 10 more
08-29 13:12:46.182   874  4288 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:12:46.182   874  4288 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:46.182   874  4288 E DropBoxManagerService: 	... 5 more
08-29 13:12:46.192  4264  4264 I Process : Sending signal. PID: 4264 SIG: 9
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.216  4276  4276 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.216  4276  4276 D AndroidRuntime: Shutting down VM
,08-29 13:12:46.218   874  2017 I ActivityManager: Process com.google.process.gapps (pid 4264) has died
08-29 13:12:46.218   874  2017 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{d6c0268 u0 com.google.android.gms/.config.ConfigService}
08-29 13:12:46.218   874  2017 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{894bde5 u0 com.google.android.gms/.gcm.GcmService}
08-29 13:12:46.218   874  2017 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8331170 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-29 13:12:46.219   874  2017 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{71cd18a u0 com.google.android.gms/.auth.GetToken}
08-29 13:12:46.232   874  2017 I ActivityManager: Start proc 4291:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-29 13:12:46.237  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 13:12:46.237  1694  1694 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 13:12:46.245  4276  4276 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:12:46.245  4276  4276 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4276
08-29 13:12:46.245  4276  4276 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:12:46.245  4276  4276 E AndroidRuntime: 	... 10 more
08-29 13:12:46.247   874  2046 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:12:46.248   874  4303 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:12:46.248   874  4303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:12:46.248   874  4303 E DropBoxManagerService: 	... 5 more
08-29 13:12:46.248  4276  4276 I Process : Sending signal. PID: 4276 SIG: 9
,08-29 13:12:46.262  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 13:12:46.263  1694  1694 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 13:12:46.266  1694  4304 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 13:12:46.270  4291  4291 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-29 13:12:46.276  4291  4291 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 13:12:46.276   874  1515 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4276) has died
08-29 13:12:46.278   874  1515 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.279  4291  4291 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.279  4291  4291 D AndroidRuntime: Shutting down VM
08-29 13:12:46.280  4291  4291 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:12:46.280  4291  4291 E AndroidRuntime: Process: com.google.process.gapps, PID: 4291
08-29 13:12:46.280  4291  4291 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:12:46.280  4291  4291 E AndroidRuntime: 	... 10 more

```
