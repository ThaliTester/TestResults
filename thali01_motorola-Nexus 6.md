#### Test 846186374ed975d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 11:16:58.794   872   885 I ActivityManager: Waited long enough for: ServiceRecord{f391eda u0 com.motorola.android.buacontactadapter/.AuthenticationService}
--------- beginning of main
09-13 11:16:59.267  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:16:59.284  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:16:59.291  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:16:59.378  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 11:16:59.379  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 11:16:59.379  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:16:59.380  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 11:16:59.446  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 11:16:59.450  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 11:16:59.454  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-13 11:17:00.565  3948  3948 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 11:17:00.570  3948  3948 D AndroidRuntime: CheckJNI is OFF
09-13 11:17:00.606  3948  3948 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 11:17:00.650  3948  3948 I Radio-JNI: register_android_hardware_Radio DONE
09-13 11:17:00.670  3948  3948 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 11:17:00.680   872  3268 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 11:17:00.733  2019  2424 W SearchService: Abort, client detached.
09-13 11:17:00.738  2019  2335 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8dfc2a1
09-13 11:17:00.738  2019  2349 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 11:17:00.738  2019  2019 I HotwordDetector: Closing mic
09-13 11:17:00.740  3948  3948 D AndroidRuntime: Shutting down VM
09-13 11:17:00.755   872  1717 I ActivityManager: Start proc 3957:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 11:17:00.796   377  2352 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 11:17:00.799   377  2352 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 11:17:00.804   377  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 11:17:00.806  2019  2348 I MicroRecognitionRnrImpl: Detection finished
09-13 11:17:00.807  2019  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 11:17:00.837  3957  3957 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 11:17:00.865  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 11:17:00.879  3957  3957 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 9811-9819)
09-13 11:17:00.879  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:17:00.927  3957  3957 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fb698d8}
09-13 11:17:00.929  3957  3957 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:17:00.930  3957  3957 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 11:17:00.938  3957  3957 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 11:17:00.940  3957  3957 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 11:17:00.983  3957  3957 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 11:17:01.009  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 11:17:01.009  3957  3957 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 11:17:01.009  3957  3957 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:17:01.009  3957  3957 I Adreno  : Build Date                       : 10/20/15
09-13 11:17:01.009  3957  3957 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:17:01.009  3957  3957 I Adreno  : Local Branch                     : M14
09-13 11:17:01.009  3957  3957 I Adreno  : Remote Branch                    : 
09-13 11:17:01.009  3957  3957 I Adreno  : Remote Branch                    : 
09-13 11:17:01.009  3957  3957 I Adreno  : Reconstruct Branch               : 
,09-13 11:17:01.103   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10cde8b:true
,09-13 11:17:01.159  3957  3957 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 11:17:01.178  3957  3957 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 11:17:01.271  3957  3997 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 11:17:01.288  3957  3983 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 11:17:01.314  3957  3997 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 11:17:01.374   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +636ms
,09-13 11:17:01.378  1874  1874 I Keyboard.Facilitator: onFinishInput()
,09-13 11:17:01.477  3957  3957 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3957
,09-13 11:17:01.550   872   883 I ActivityManager: Killing 3375:com.google.android.gm/u0a78 (adj 15): empty #17
,09-13 11:17:01.596   872   883 I ActivityManager: Killing 3579:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-13 11:17:01.608  3957  3957 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 11:17:01.837  3957  3999 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1681458896
,09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 11:17:01.847  3957  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f974f added. We now have 1 listener(s)
,09-13 11:17:01.851  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 11:17:01.854  3957  3999 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:17:01.855  3957  3999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:17:01.856  3957  3999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 11:17:01.868  3957  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc8596b added. We now have 1 listener(s)
09-13 11:17:01.868  3957  3999 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:01.871   872  1312 D WifiService: New client listening to asynchronous messages
,09-13 11:17:01.872  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:17:01.872  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 11:17:01.872  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 11:17:01.872  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 11:17:01.873  3957  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 11:17:01.875  3957  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:17:01.876  3957  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 11:17:01.881  3957  3999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:01.883  3957  3999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:01.883  3957  3999 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 11:17:01.883  3957  3999 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:17:01.884  3957  3999 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 11:17:02.027  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:02.030  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:02.032  3957  3957 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 11:17:02.461  3957  3966 I art     : Background sticky concurrent mark sweep GC freed 70567(6MB) AllocSpace objects, 17(1308KB) LOS objects, 29% free, 22MB/32MB, paused 763us total 132.304ms
,09-13 11:17:03.007  3957  4008 W jxcore-log: Initializing JXcore engine
,09-13 11:17:03.007  3957  4008 W jxcore-log: JXcore engine is ready
,09-13 11:17:03.023   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 11:17:03.049  4008  4008 W Thread-365: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-13 11:17:03.049  4008  4008 W Thread-365: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12810]" dev="sockfs" ino=12810 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 11:17:03.049  4008  4008 W Thread-365: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 11:17:03.049  4008  4008 W Thread-365: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23541]" dev="sockfs" ino=23541 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 11:17:03.065  3957  4008 W jxcore-log: Starting JXcore engine
,09-13 11:17:03.161  3957  4008 W jxcore-log: Platform android
09-13 11:17:03.161  3957  4008 W jxcore-log: 
,09-13 11:17:03.161  3957  4008 W jxcore-log: Process ARCH arm
09-13 11:17:03.161  3957  4008 W jxcore-log: 
,09-13 11:17:03.371  3957  4008 I jxcore-log: JXcore Cordova bridge is ready!
09-13 11:17:03.371  3957  4008 I jxcore-log: 
,09-13 11:17:03.371  3957  4008 W jxcore-log: JXcore engine is started
,09-13 11:17:03.380  3957  3999 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 11:17:03.384  3957  3957 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 11:17:10.695  3230  4016 V KeepSync: Connecting to GoogleApiClient
,09-13 11:17:10.696   872  3247 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:17:10.730  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:10.732  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:10.783  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 11:17:10.783  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 11:17:10.783  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:17:10.784  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:10.840  1731  4017 V BaseAuthAsyncOperation: access token request failed
,09-13 11:17:10.841  3230  4016 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:17:10.944  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:17:10.944  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 11:17:10.944  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:10.944  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 11:17:10.960  3230  4016 E KeepSync: IOException
09-13 11:17:10.960  3230  4016 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:17:10.960  3230  4016 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:17:10.960  3230  4016 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:17:10.960  3230  4016 E KeepSync: 	... 10 more
09-13 11:17:10.960  3230  4016 W KeepSync: Sync result 2
,09-13 11:17:10.964   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 129507, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:17:14.016   872  1890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:17:17.233  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 11:17:17.233  3957  4008 I jxcore-log: 
,09-13 11:17:17.236  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 11:17:17.236  3957  4008 I jxcore-log: 
,09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:17.248  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:17.254  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:17.256  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 11:17:17.256  3957  4008 I jxcore-log: 
,09-13 11:17:17.258  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 11:17:17.258  3957  4008 I jxcore-log: 
,09-13 11:17:17.609  3957  4008 I jxcore-log: Running unit tests
09-13 11:17:17.609  3957  4008 I jxcore-log: 
,09-13 11:17:17.609  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:17:17.609  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444375c added. We now have 2 listener(s)
,09-13 11:17:17.611  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:17:17.611  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:17:17.611  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:17:17.611  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-13 11:17:17.611  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711ca65 added. We now have 2 listener(s),
,09-13 11:17:17.611  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:17.613  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:17:17.622  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:17.636  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:17.642  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:17.642  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:17:17.645  3957  4008 D executeNativeTests: Running unit tests
,09-13 11:17:17.648  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:17.653  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:17.730  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:17:17.730  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db added. We now have 3 listener(s)
09-13 11:17:17.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:17:17.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:17:17.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:17:17.732  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:17:17.732  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 added. We now have 3 listener(s)
,09-13 11:17:17.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:17.732  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:17:17.738  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:17.750  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:17.756  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:17.757  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:17:17.768  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 11:17:17.768  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:17.768  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 11:17:17.769  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:17.769  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:17.770  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:17.779  3957  4008 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 11:17:17.779  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 11:17:17.780  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:17:17.780  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:17.780  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:17.780  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 11:17:17.780  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:17.781  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:17.781  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:17.781  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:17.782  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.782  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:17:17.782  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:17:17.782  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db removed from the list
09-13 11:17:17.782  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:17.782  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 removed from the list
09-13 11:17:17.782  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:17.782  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.783  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.783  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.784  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:17:17.784  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:17.784  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:17.784  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:17.786  3957  4008 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 11:17:17.787  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:17.787  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:17.787  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:17.787  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:17.787  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.787  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:17.787  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:17.787  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:17.788  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:17.788  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:17.788  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.788  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.788  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.788  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.790  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:17:17.790  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:17.790  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:17.790  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:17.796  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 11:17:17.796  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 11:17:17.796  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:17:17.796  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:17:17.797  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 11:17:17.798  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 11:17:17.798  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:17.798  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:17.798  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:17.799  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:17.799  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:17.799  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.799  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:17.799  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:17.799  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:17.799  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:17:17.799  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.799  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.799  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:17.799  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:17.800  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:17.800  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:17.800  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:17.800  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:17.801  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 11:17:17.803  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:17.807  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:17.809  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:17.809  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:17:17.809  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:17:17.810  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:17:17.810  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:17:17.810  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:17:17.810  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:17:17.815  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 11:17:17.815  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:17:17.815  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:17.819  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:17.819  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:17:17.820  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 11:17:17.821  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:17:17.823  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 11:17:17.827  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 11:17:17.827  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:17:17.828  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:17:17.828  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:17:17.829  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:17.833  2713  2852 D BtGatt.GattService: registerClient() - UUID=d6e8ab0f-ea93-4859-a187-c940e7d0f608
,09-13 11:17:17.834  2713  2739 D BtGatt.GattService: onClientRegistered() - UUID=d6e8ab0f-ea93-4859-a187-c940e7d0f608, clientIf=5
,09-13 11:17:17.835  3957  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:17:17.836  2713  2723 D BtGatt.GattService: start scan with filters
,09-13 11:17:17.840  2713  2746 D BtGatt.ScanManager: handling starting scan
09-13 11:17:17.840  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 11:17:17.840  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:17:17.840  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 11:17:17.841  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 11:17:17.841  2713  2746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:17:17.843  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:17:17.843  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:17:17.844  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:17:17.846  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:17:17.848  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
09-13 11:17:17.849  2713  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 11:17:17.849  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:17.849  2713  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:17:17.857  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:17:17.857  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:17.857  2713  2746 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:17:17.857  2713  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:17:17.868  2713  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:17:17.869  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:17.875  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:17:17.875  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:18.345  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 11:17:18.346  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:17:18.346  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:17:19.384  2713  2713 D BtGatt.ScanManager: awakened up at time 138326
,09-13 11:17:19.391  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:19.416  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-13 11:17:19.416  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:19.416  2713  2739 D BtGatt.GattService: current time is 138358155624
,09-13 11:17:19.417  2713  2739 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -94, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -101, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 11:17:19.418  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 11:17:19.419  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-13 11:17:19.419  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 11:17:19.420  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 11:17:20.937  2713  2713 D BtGatt.ScanManager: awakened up at time 139878
,09-13 11:17:20.939  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:20.967  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 11:17:20.967  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:21.222  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:21.233  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:21.237  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:21.268  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:17:21.269  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 11:17:21.269  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:17:21.269  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:21.294  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 11:17:21.294  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 11:17:21.295  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-13 11:17:22.473  2713  2713 D BtGatt.ScanManager: awakened up at time 141414
,09-13 11:17:22.474  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:22.523  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-13 11:17:22.523  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:22.523  2713  2739 D BtGatt.GattService: current time is 141464949093
,09-13 11:17:22.523  2713  2739 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 11:17:22.524  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 11:17:22.524  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 11:17:22.524  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 11:17:22.525  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 11:17:22.528  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 11:17:22.528  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 11:17:22.858  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:22.859  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:17:22.859  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:17:22.859  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:22.860  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 11:17:22.860  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:17:22.860  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 11:17:22.861  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:17:22.861  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:17:22.863  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 11:17:22.864  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:17:22.867  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:22.868  2713  2852 D BtGatt.GattService: stopScan() - queue size =1
,09-13 11:17:22.871  2713  2723 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:17:22.872  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 11:17:22.872  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 11:17:22.873  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:17:22.873  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:17:22.873  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:17:22.877  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:22.879  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:17:22.879  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:17:22.880  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:17:22.881  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:17:22.883  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:17:22.884  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:22.884  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:22.884  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:22.885  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:22.885  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:17:22.886  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:22.886  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:22.886  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:22.887  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:22.887  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:22.891  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:17:22.891  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:22.892  2713  2746 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:17:22.902  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 11:17:22.902  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:22.903  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:22.919  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 11:17:22.919  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:23.384  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:17:26.893   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 11:17:27.889  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 11:17:27.894  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:27.908  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:27.915  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:27.916  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:17:27.917  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:17:27.918  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:17:27.918  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:17:27.919  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:27.920  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:17:27.923  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:27.932  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:17:27.932  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:17:27.933  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:27.945  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:17:27.948  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:17:27.948  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:17:27.958  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:17:27.958  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:17:27.959  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 11:17:27.960  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:27.967  2713  2852 D BtGatt.GattService: registerClient() - UUID=4fc6ad09-5f3f-4161-8d8e-cc2d0f9c66e4
,09-13 11:17:27.968  2713  2739 D BtGatt.GattService: onClientRegistered() - UUID=4fc6ad09-5f3f-4161-8d8e-cc2d0f9c66e4, clientIf=5
,09-13 11:17:27.969  3957  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 11:17:27.969  2713  2723 D BtGatt.GattService: start scan with filters
,09-13 11:17:27.978  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 11:17:27.978  2713  2746 D BtGatt.ScanManager: handling starting scan
,09-13 11:17:27.978  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 11:17:27.979  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:17:27.979  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:17:27.989  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:17:27.990  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:17:27.990  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:17:27.994  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 11:17:27.997  2713  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:17:27.997  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:27.998  2713  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:17:28.002  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 11:17:28.009  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:28.009  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 11:17:28.009  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:28.009  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:17:28.009  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:28.010  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 11:17:28.010  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:17:28.010  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:17:28.010  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:17:28.010  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 11:17:28.010  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:17:28.010  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:17:28.011  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:28.011  2713  2725 D BtGatt.GattService: stopScan() - queue size =1
09-13 11:17:28.012  2713  2852 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 11:17:28.012  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 11:17:28.012  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 11:17:28.013  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:17:28.013  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:17:28.013  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:17:28.014  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:28.014  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:17:28.014  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:17:28.014  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:17:28.015  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:17:28.017  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:17:28.017  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:28.017  2713  2746 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 11:17:28.017  2713  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:17:28.019  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:28.020  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:28.020  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:17:28.021  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:28.021  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:28.021  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:17:28.021  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:28.021  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:28.022  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:28.022  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:17:28.022  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:28.023  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:28.023  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 11:17:28.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-13 11:17:28.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 11:17:28.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:28.024  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:28.025  3957  4008 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-13 11:17:28.027  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:28.031  2713  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:17:28.031  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
09-13 11:17:28.036  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:28.039  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-13 11:17:28.039  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:17:28.039  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-13 11:17:28.039  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:17:28.039  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:17:28.039  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:28.040  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:17:28.041  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:17:28.041  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-13 11:17:28.042  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:28.044  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 11:17:28.044  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
09-13 11:17:28.045  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:28.052  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-13 11:17:28.053  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:17:28.053  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:17:28.055  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:17:28.055  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:28.056  2713  2746 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:17:28.056  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:17:28.056  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 11:17:28.056  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:17:28.057  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:28.059  2713  2852 D BtGatt.GattService: registerClient() - UUID=6ef18ab5-9609-4bc4-a59f-1ee6e1482dc0
,09-13 11:17:28.060  2713  2739 D BtGatt.GattService: onClientRegistered() - UUID=6ef18ab5-9609-4bc4-a59f-1ee6e1482dc0, clientIf=5
,09-13 11:17:28.060  3957  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:17:28.060  2713  2725 D BtGatt.GattService: start scan with filters
,09-13 11:17:28.062  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 11:17:28.062  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.062  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:28.063  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:17:28.063  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:17:28.063  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-13 11:17:28.063  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:17:28.066  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:17:28.066  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:17:28.066  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:17:28.068  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 11:17:28.068  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.068  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:17:28.069  2713  2746 D BtGatt.ScanManager: handling starting scan
09-13 11:17:28.071  3957  4008 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 11:17:28.075  2713  2739 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:17:28.075  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.075  2713  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:17:28.081  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 11:17:28.081  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.081  2713  2746 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 11:17:28.081  2713  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:17:28.091  2713  2739 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 11:17:28.091  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.097  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 11:17:28.097  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:28.567  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 11:17:28.567  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:17:28.568  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:17:29.606  2713  2713 D BtGatt.ScanManager: awakened up at time 148547
,09-13 11:17:29.609  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:29.639  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 11:17:29.639  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:29.639  2713  2739 D BtGatt.GattService: current time is 148581092212
09-13 11:17:29.641  2713  2739 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 11:17:29.641  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 11:17:29.641  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 11:17:29.642  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-13 11:17:29.642  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-13 11:17:29.642  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 11:17:31.149  2713  2713 D BtGatt.ScanManager: awakened up at time 150090
,09-13 11:17:31.153  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:31.161  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 11:17:31.161  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:31.162   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 11:17:31.174  1874  1874 I Keyboard.Facilitator: onFinishInput()
09-13 11:17:31.176   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:17:31.176   872   892 I Adreno  : Build Date                       : 10/20/15
09-13 11:17:31.176   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:17:31.176   872   892 I Adreno  : Local Branch                     : M14
09-13 11:17:31.176   872   892 I Adreno  : Remote Branch                    : 
09-13 11:17:31.176   872   892 I Adreno  : Remote Branch                    : 
09-13 11:17:31.176   872   892 I Adreno  : Reconstruct Branch               : 
,09-13 11:17:31.220   281   349 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (202 us)
,09-13 11:17:31.852  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 11:17:31.853  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 11:17:31.892  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55192ee Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d185f45, 16908290=android.view.AbsSavedState$1@d185f45}, android:focusedViewId=100}]}]
,09-13 11:17:31.892  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 11:17:31.892  3957  3957 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 11:17:31.892  3957  3957 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 11:17:31.893   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 11:17:31.913   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 11:17:31.922   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 11:17:31.924   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-13 11:17:31.925   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 11:17:31.936   872   881 I art     : Background partial concurrent mark sweep GC freed 23316(1604KB) AllocSpace objects, 7(184KB) LOS objects, 33% free, 29MB/43MB, paused 1.482ms total 106.263ms
,09-13 11:17:32.160   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 11:17:32.164   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 11:17:32.169   872  1335 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
,09-13 11:17:32.174   872   892 I DreamManagerService: Entering dreamland.
,09-13 11:17:32.175   872   892 I PowerManagerService: Dozing...
,09-13 11:17:32.176   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 11:17:32.223   377  1468 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 11:17:32.224   377  1468 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 11:17:32.230  2713  2713 D BtGatt.ScanManager: awakened up at time 151171
,09-13 11:17:32.231  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:32.241   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:17:32.251  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-13 11:17:32.251  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:32.252  2713  2739 D BtGatt.GattService: current time is 151193658925
,09-13 11:17:32.252  2713  2739 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 11:17:32.253  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,09-13 11:17:32.253  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 11:17:32.254  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 11:17:32.256  1929  4026 D NfcService: Discovery configuration equal, not updating.
09-13 11:17:32.257   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-13 11:17:32.257  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 11:17:32.265   872  1310 E native  : do suspend false
,09-13 11:17:32.282   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:17:32.290   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:17:32.293   872  1310 E native  : do suspend true
,09-13 11:17:32.355   377  1283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 11:17:32.356   377  1283 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 11:17:32.748   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 11:17:33.071  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:17:33.072  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:17:33.072  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:17:33.073  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:33.073  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 11:17:33.073  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:17:33.073  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:17:33.074  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:17:33.074  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 11:17:33.074  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:17:33.075  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:17:33.077  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:17:33.079  2713  2723 D BtGatt.GattService: stopScan() - queue size =1
,09-13 11:17:33.082  2713  2852 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 11:17:33.083  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:17:33.083  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:17:33.084  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:17:33.084  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-13 11:17:33.084  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:17:33.088  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:33.090  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 11:17:33.090  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 11:17:33.090  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:17:33.093  2713  2713 D BtGatt.ScanManager: awakened up at time 152034
,09-13 11:17:33.094  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:17:33.097  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:17:33.097  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:33.097  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:17:33.103  2713  2739 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:17:33.103  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:17:33.103  2713  2746 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:17:33.111  2713  2739 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 11:17:33.111  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:33.111  2713  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:17:33.127  2713  2739 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-13 11:17:33.127  2713  2739 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:17:33.127  2713  2739 D BtGatt.GattService: current time is 152068840274
09-13 11:17:33.127  2713  2739 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -87, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 11:17:33.128  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 11:17:33.128  2713  2739 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 11:17:33.599  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:17:33.599  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:33.599  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:17:38.099  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:17:38.099  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.100  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:17:38.101  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:17:38.101  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.101  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:17:38.102  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
,09-13 11:17:38.102  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.103  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.103  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:17:38.103  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.105  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.105  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.109  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.109  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:38.109  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.110  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.112  3957  4008 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 11:17:38.114  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.114  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.114  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.115  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.115  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.115  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.116  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
,09-13 11:17:38.116  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:38.116  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:38.117  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.117  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.117  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.117  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.118  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.121  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.121  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:17:38.121  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.121  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.124  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 11:17:38.124  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.125  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.125  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.125  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.126  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.126  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.126  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.126  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:38.127  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.127  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.127  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.127  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.128  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:38.128  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.130  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.130  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:17:38.130  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.131  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:38.132  3957  4008 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 11:17:38.133  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.133  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.133  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.134  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.134  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.134  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.134  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.135  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.135  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:38.135  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.135  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.136  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.136  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.136  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.138  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.139  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:38.139  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.139  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.141  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 11:17:38.141  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:17:38.141  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.142  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.142  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.142  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.142  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.143  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.143  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.143  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.143  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.144  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.144  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.144  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.144  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.146  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.147  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:38.147  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.147  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:38.149  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 11:17:38.149  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:38.150  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:38.150  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:17:38.150  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:38.151  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:38.151  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 11:17:38.151  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:38.151  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 11:17:38.152  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.152  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.152  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.153  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.153  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.153  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.154  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.154  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.154  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.154  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.154  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.155  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.155  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:38.155  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.158  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:17:38.158  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:17:38.159  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.159  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.160  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:17:38.160  3957  4008 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:17:38.160  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 11:17:38.164  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 11:17:38.165  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 11:17:38.165  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
,09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
09-13 11:17:38.166  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 11:17:38.167  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 11:17:38.167  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 11:17:38.168  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:17:38.168  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 11:17:38.168  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:17:38.168  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 11:17:38.168  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 11:17:38.168  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:17:38.168  3957  4008 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:17:38.169  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 11:17:38.171  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 11:17:38.172  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 11:17:38.172  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 11:17:38.173  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 11:17:38.173  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 11:17:38.173  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 11:17:38.173  3957  4008 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:17:38.173  3957  4008 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 11:17:38.174  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:17:38.174  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.174  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.174  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.175  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.175  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.175  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 11:17:38.176  3957  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
09-13 11:17:38.176  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.176  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.176  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.176  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.176  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.176  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:38.177  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.177  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.178  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.178  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:17:38.178  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.178  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.179  3957  4031 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:17:38.179  3957  4008 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 11:17:38.180  3957  4032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
09-13 11:17:38.180  3957  4032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 429)
,09-13 11:17:38.180  3957  4032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 429)
09-13 11:17:38.182  3957  4031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
09-13 11:17:38.183  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.183  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.183  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.183  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:17:38.183  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.183  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.183  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.183  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.183  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.183  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:17:38.184  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:38.184  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.184  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.184  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.185  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.185  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:38.185  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:38.185  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.186  3957  4008 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 11:17:38.186  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.186  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.186  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.186  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:17:38.187  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.187  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.187  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.187  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.187  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:38.187  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.187  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.187  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.187  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.187  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.188  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.188  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:17:38.188  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:38.188  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 11:17:38.189  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:17:38.189  3957  4008 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 11:17:38.189  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:17:38.189  3957  4008 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 11:17:38.189  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:17:38.189  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:17:38.189  3957  4008 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 11:17:38.190  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:38.190  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:38.190  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:38.190  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.190  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.190  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.190  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.190  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.190  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.190  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.190  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.190  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.190  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.190  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.191  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:38.191  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:38.191  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.191  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.192  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:38.192  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.192  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:38.192  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:38.192  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:38.192  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:38.192  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:38.192  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:38.192  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:39.834  2104  2754 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 11:17:41.447  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:41.584  1522  4035 I VacuumService: Vacuum at: now=1473758261584 tag=VacuumService
09-13 11:17:41.585  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:41.599  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:41.602  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:41.630  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:17:41.630  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 11:17:41.630  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:17:41.630  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:41.659  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 11:17:41.659  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 11:17:41.659  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 11:17:41.711   872   882 I ProcessStatsService: Added stats: 2016-09-13-09-42-59, over +1h0m20s922ms
,09-13 11:17:41.716   872   882 I ProcessStatsService: Added stats: 2016-09-13-06-06-42, over +2h30m0s310ms
,09-13 11:17:41.720   872   882 I ProcessStatsService: Added stats: 2016-09-13-03-06-41, over +3h0m0s365ms
,09-13 11:17:41.728   872   882 I ProcessStatsService: Added stats: 2016-09-13-00-06-19, over +3h0m21s256ms
,09-13 11:17:41.749   872   882 I ProcessStatsService: Added stats: 2016-09-12-21-54-18, over +2h0m0s228ms
,09-13 11:17:41.757   872   882 I ProcessStatsService: Added stats: 2016-09-12-18-53-57, over +3h0m21s77ms
,09-13 11:17:41.765   872   882 I ProcessStatsService: Added stats: 2016-09-12-17-24-42, over +30m23s543ms
,09-13 11:17:41.773   872   882 I ProcessStatsService: Added stats: 2016-09-12-14-42-36, over +2h0m23s757ms
,09-13 11:17:41.781   872   882 I ProcessStatsService: Added stats: 2016-09-12-13-59-13, over +30m23s786ms
,09-13 11:17:42.111  1522  4040 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 11:17:42.117  1522  4040 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 11:17:42.167  1522  4040 W Uploader:  no longer exists, so no auth token.
,09-13 11:17:42.552  3785  4044 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:17:42.595  3785  4045 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:17:42.678  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:17:42.678  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:17:42.679  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:42.679  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:42.805  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:17:42.806  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:17:42.806  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:42.806  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:42.848  3785  4045 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:17:42.850  3785  4044 E BooksSync: Soft error
09-13 11:17:42.850  3785  4044 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:17:42.850  3785  4044 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:17:42.850  3785  4044 E BooksSync: Sync error
09-13 11:17:42.850  3785  4044 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:17:42.850  3785  4044 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:17:42.851  3785  4044 I BooksSync: Finished books sync
,09-13 11:17:42.863   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161402, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:17:43.038   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-13 11:17:43.193  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:43.194  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:43.194  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:43.194  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.195  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.195  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
,09-13 11:17:43.195  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:43.196  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:17:43.196  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:17:43.196  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:43.197  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.197  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:43.197  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.198  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.198  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.198  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:43.199  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.199  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.199  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.200  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.203  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:43.203  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:43.203  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.204  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:43.209  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 11:17:43.210  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:43.212  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 11:17:43.214  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,09-13 11:17:43.215  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 11:17:43.216  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 11:17:43.217  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 11:17:43.217  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 11:17:43.218  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:17:43.219  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 11:17:43.219  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 11:17:43.220  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 11:17:43.220  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.220  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 11:17:43.221  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.221  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 11:17:43.221  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.221  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:17:43.223  3957  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:17:43.224  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:17:43.224  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:17:43.225  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.225  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.228  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:43.229  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:43.229  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
,09-13 11:17:43.229  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:17:43.229  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:43.230  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:17:43.230  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:43.230  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:43.230  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:43.231  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.231  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.231  3957  4046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 11:17:43.231  3957  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 11:17:43.231  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.231  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.231  3957  4046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 11:17:43.232  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.232  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:43.232  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.233  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:43.233  3957  3957 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 11:17:43.233  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.233  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.236  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:43.237  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:43.237  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.237  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.238  3957  4008 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 11:17:43.239  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 11:17:43.239  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 11:17:43.239  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:43.239  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:17:43.239  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:17:43.239  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:43.239  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:43.240  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:43.240  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.240  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:17:43.240  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.240  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.240  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.240  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:43.240  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.240  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.241  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:43.241  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.242  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:43.242  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:43.242  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:43.242  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.246  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:43.246  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:43.246  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:43.247  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:17:43.247  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.247  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.247  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.247  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.247  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.247  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:43.247  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.247  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.247  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:17:43.248  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.249  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:43.249  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:43.249  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.249  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.250  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:17:43.250  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:17:43.250  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:17:43.250  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:17:43.250  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.250  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.250  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c695db not in the list
09-13 11:17:43.250  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.251  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.251  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:43.251  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.251  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.251  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:43.251  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:43.252  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:17:43.252  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:17:43.252  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:43.252  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c98b878 not in the list
09-13 11:17:43.253  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 11:17:43.253  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:17:43.254  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 11:17:43.254  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:17:43.254  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 11:17:43.254  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:17:43.257  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 11:17:43.257  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 11:17:43.258  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 11:17:43.258  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 11:17:43.258  3957  4008 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 11:17:43.258  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 11:17:43.258  3957  4008 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 11:17:43.258  3957  4008 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 11:17:43.259  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 11:17:43.259  3957  4008 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 11:17:43.259  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 11:17:43.260  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 11:17:43.260  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 11:17:43.260  3957  4008 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 11:17:43.261  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:17:43.261  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd4abcb added. We now have 3 listener(s)
09-13 11:17:43.261  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:17:43.263  3957  4008 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 11:17:43.263   872  1967 D WifiService: setWifiEnabled: true pid=3957, uid=10000
09-13 11:17:43.263   872  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:17:43.308  2713  2841 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 11:17:43.310  2713  2849 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-13 11:17:43.731  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:17:44.974  1522  4040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 11:17:44.975  1522  4040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 11:17:44.975  1522  4040 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:17:44.975  1522  4040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:44.992  1522  4040 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 11:17:44.992  1522  4040 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 11:17:44.992  1522  4040 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 11:17:45.320  1522  4040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 11:17:45.320  1522  4040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 11:17:45.320  1522  4040 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:45.320  1522  4040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:45.341  1522  4040 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 11:17:45.341  1522  4040 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 11:17:45.341  1522  4040 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 11:17:45.970  1522  4040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 11:17:45.970  1522  4040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 11:17:45.970  1522  4040 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:45.970  1522  4040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:45.989  1522  4040 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 11:17:45.989  1522  4040 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 11:17:45.989  1522  4040 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 11:17:47.216   872  1890 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:17:48.270  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:17:48.271  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e72fa8 added. We now have 4 listener(s)
09-13 11:17:48.271  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:48.287  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:17:48.288  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e72fa8 removed from the list
09-13 11:17:48.288  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:48.289  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:48.289  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:48.291  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:17:48.292  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de4aac1 added. We now have 4 listener(s)
,09-13 11:17:48.292  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:48.296  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:17:48.296  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de4aac1 removed from the list
,09-13 11:17:48.296  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:17:48.297  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:17:48.297  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:17:48.299  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:17:48.300  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a9b266 added. We now have 4 listener(s)
09-13 11:17:48.300  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:17:48.307   872  1717 D WifiService: setWifiEnabled: false pid=3957, uid=10000
09-13 11:17:48.307   872  1717 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:17:48.316  2713  2733 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 11:17:48.317  2713  2733 D BluetoothAdapterProperties: Setting state to 13
09-13 11:17:48.317  2713  2733 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 11:17:48.318  2713  2733 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 11:17:48.321  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:17:48.322  2713  2733 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:17:48.325  2713  2739 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:17:48.326  2713  2733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 11:17:48.331  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:48.331  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:17:48.337  2713  2713 D HeadsetService: Received stop request...Stopping profile...
,09-13 11:17:48.337  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.337  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:48.338  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:17:48.339   872   872 D BluetoothHeadset: Proxy object disconnected
,09-13 11:17:48.339   872   872 D BluetoothHeadset: Proxy object disconnected
,09-13 11:17:48.340  1942  1956 D BluetoothHeadset: Proxy object disconnected
,09-13 11:17:48.340  2713  2713 D A2dpService: Received stop request...Stopping profile...
,09-13 11:17:48.341  1354  1376 D BluetoothHeadset: Proxy object disconnected
,09-13 11:17:48.341  2713  2855 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:17:48.341  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,09-13 11:17:48.342   872   872 D BluetoothHeadset: Proxy object disconnected
,09-13 11:17:48.342   872   872 D BluetoothA2dp: Proxy object disconnected
,09-13 11:17:48.343  1354  1354 D BluetoothA2dp: Proxy object disconnected
,09-13 11:17:48.344  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:48.345  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.345  2713  2713 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:17:48.345  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.345  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:17:48.346  2713  2713 D HidService: Received stop request...Stopping profile...
,09-13 11:17:48.346  2713  2713 D HidService: Stopping Bluetooth HidService
09-13 11:17:48.346  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:48.347  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-13 11:17:48.347  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 11:17:48.347  2713  2713 D HealthService: Received stop request...Stopping profile...
09-13 11:17:48.349  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:17:48.349  2713  2713 D PanService: Received stop request...Stopping profile...
09-13 11:17:48.349  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:48.350  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:48.350  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.351  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:48.351  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.351  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.352  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 11:17:48.352  1354  1354 D PanProfile: Bluetooth service disconnected
09-13 11:17:48.352   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 11:17:48.352  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.352   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 11:17:48.352  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:17:48.352   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:17:48.352   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:17:48.353  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:48.354  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:48.354  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 11:17:48.354  2713  2713 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:17:48.355  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.355  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:48.355  2713  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 11:17:48.355  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:17:48.355  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:17:48.355  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:17:48.355  2713  2739 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 11:17:48.357  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:17:48.357  2713  2713 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:17:48.357  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:17:48.357  2713  2713 D BluetoothMapService: stop()
,09-13 11:17:48.357  2713  2841 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:17:48.357  2713  2841 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:17:48.357  2713  2841 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:17:48.357  2713  2841 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:17:48.357  2713  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 11:17:48.357  2713  2713 D BluetoothMapAppObserver: deinitObservers()
09-13 11:17:48.357  2713  2713 D BluetoothMapAppObserver: removeReceiver()
09-13 11:17:48.358  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:48.360  1354  1354 D BluetoothMap: Proxy object disconnected
09-13 11:17:48.360  1354  1354 D MapProfile: Bluetooth service disconnected
,09-13 11:17:48.360  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.360  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.361  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.361  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:17:48.363  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:17:48.363  2713  2739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 11:17:48.363   872  1310 E native  : do suspend true
09-13 11:17:48.364  2713  2713 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 11:17:48.365  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.366  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.366  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.367  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:17:48.367  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:17:48.367  2713  2739 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 11:17:48.369  2713  2713 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:17:48.369  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.369  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.369  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.369  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:17:48.370  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 11:17:48.371  2713  2713 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 11:17:48.373  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:48.375  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.377  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.381   872  1891 D DhcpClient: Clearing IP address
,09-13 11:17:48.381   373   871 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:17:48.381  2713  2713 D BluetoothMapService: MAP Service closeService in
,09-13 11:17:48.381  2713  2713 D BluetoothMapMasInstance0: MAP Service shutdown
,09-13 11:17:48.381  2713  2713 D ObexServerSockets0: shutdown(block = true)
09-13 11:17:48.381  2713  2860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 11:17:48.382  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:17:48.382  2713  2861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 11:17:48.383  2713  2849 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 11:17:48.383  2713  2713 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:17:48.383  2713  2713 V BluetoothAdapterState: isTurningOff()=true
09-13 11:17:48.383  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.383  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:17:48.383  2713  2713 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:17:48.383  2713  2713 D BluetoothMapService: cleanup()
09-13 11:17:48.383  2713  2713 D BluetoothMapService: MAP Service closeService in
09-13 11:17:48.384  2713  2713 I BtOppRfcommListener: stopping Accept Thread
09-13 11:17:48.384  2713  2733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 11:17:48.384  2713  3578 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:17:48.384  2713  2733 D BluetoothAdapterProperties: Setting state to 15
09-13 11:17:48.384  2713  2733 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 11:17:48.384  2713  2733 I BluetoothAdapterState: Entering BleOnState
09-13 11:17:48.385  2713  3578 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 11:17:48.387   373   871 D CommandListener: Setting iface cfg
09-13 11:17:48.387   872   885 I ActivityManager: Start proc 4059:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 11:17:48.389   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:17:48.389  1354  1379 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:17:48.389  1522  2485 V NativeCrypto: Read error: ssl=0x9b192c00: I/O error during system call, Connection timed out
,09-13 11:17:48.390  1354  1376 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:17:48.390   872  1892 D DhcpClient: Receive thread stopped
09-13 11:17:48.391   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:17:48.391  1354  2043 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 11:17:48.391   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 11:17:48.392   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 11:17:48.396   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 11:17:48.396  1354  1379 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:17:48.396   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:17:48.396   872  1310 E native  : do suspend true
09-13 11:17:48.397  1354  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:17:48.397   396   396 E Parcel  : Reading a NULL string not supported here.
09-13 11:17:48.398   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:17:48.399   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:17:48.399  1942  1956 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:17:48.399  1354  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:17:48.399  2713  2733 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 11:17:48.400  2713  2733 D BluetoothAdapterProperties: Setting state to 16
09-13 11:17:48.400  2713  2733 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 11:17:48.400  2713  2733 D BluetoothAdapterProperties: onBleDisable
09-13 11:17:48.401  2713  2733 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:17:48.401  2713  2734 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 11:17:48.402  2713  2841 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 11:17:48.402  2713  2841 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:17:48.403  2713  2739 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:17:48.407   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 11:17:48.409  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.409  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:48.411  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.411  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:17:48.413  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.413  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:17:48.414  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.414  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:48.415  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.415  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:48.416  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.416  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:48.417  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.417  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:17:48.418  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.419  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.425  1522  2485 V NativeCrypto: SSL shutdown failed: ssl=0x9b192c00: I/O error during system call, Broken pipe
,09-13 11:17:48.439   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:17:48.441  4059  4059 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 11:17:48.450  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 11:17:48.455   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb59854:true
,09-13 11:17:48.458  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:17:48.459   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 11:17:48.460   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:17:48.461   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 11:17:48.461   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:17:48.465   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:48.476   872   882 I ActivityManager: Start proc 4075:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 11:17:48.481   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 11:17:48.494  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.494  3594  3594 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@387aedc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-13 11:17:48.498   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 11:17:48.500  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.500  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:48.501  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.501  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:17:48.502   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 11:17:48.503  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.503  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:48.503  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.503  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:48.505  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:48.505  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:48.505  2104  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:17:48.506  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:48.506  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:48.507  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:48.508  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:48.515  4059  4059 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 11:17:48.518  4059  4059 D BluetoothMap: Create BluetoothMap proxy object
09-13 11:17:48.522  4075  4075 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
09-13 11:17:48.532  4059  4059 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 11:17:48.539   373   871 E Netd    : netlink response contains error (No such file or directory)
09-13 11:17:48.550  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:17:48.554   872  2632 I ActivityManager: Killing 3155:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 11:17:48.603  2713  2739 I bt_hci  : shut_down
,09-13 11:17:48.608  2713  2748 D bt_hwcfg: hw_epilog_process
,09-13 11:17:48.609  2713  2748 I bt_vendor: low_power_mode_cb
,09-13 11:17:48.638  2713  2748 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 11:17:48.638  2713  2748 I bt_vendor: epilog_cb
,09-13 11:17:48.638  2713  2748 I bt_hci  : epilog_finished_callback
,09-13 11:17:48.640  2713  2739 I bt_hci_h4: hal_close
,09-13 11:17:48.641  2713  2739 I bt_userial_vendor: device fd = 51 close
,09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.728  4075  4075 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.728  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.729  4075  4075 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:17:48.729  4075  4075 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:17:48.735  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:17:48.744  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:17:48.751  2713  2734 D bt_stack_manager: event_shut_down_stack finished.
09-13 11:17:48.751  2713  2733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-13 11:17:48.762  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:17:48.763  2713  2713 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:17:48.768  2713  2733 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 11:17:48.771  2713  2713 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 11:17:48.771  2713  2713 D BtGatt.GattService: stop()
09-13 11:17:48.771  2713  2713 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 11:17:48.776  2713  2713 V BluetoothAdapterState: isTurningOff()=false
09-13 11:17:48.777  2713  2713 V BluetoothAdapterState: isTurningOn()=false
09-13 11:17:48.777  2713  2713 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:17:48.777  2713  2713 V BluetoothAdapterState: isBleTurningOff()=true
09-13 11:17:48.778  2713  2733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 11:17:48.778  2713  2733 D BluetoothAdapterProperties: Setting state to 10
09-13 11:17:48.779  2713  2733 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 11:17:48.780  2713  2733 I BluetoothAdapterState: Entering OffState
09-13 11:17:48.781   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-13 11:17:48.795  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 11:17:48.796  2713  2713 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 11:17:48.796  2713  2713 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 11:17:48.796  2713  2734 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 11:17:48.799   872   883 I ActivityManager: Killing 3594:com.google.android.music:main/u0a66 (adj 15): empty #17
09-13 11:17:48.801  2713  2734 D bt_stack_manager: event_clean_up_stack finished.
09-13 11:17:48.806  2713  2713 I art     : System.exit called, status: 0
09-13 11:17:48.806  2713  2713 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 11:17:48.942   872  1717 I ActivityManager: Process com.android.bluetooth (pid 2713) has died
,09-13 11:17:48.954  4075  4096 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 11:17:48.976  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:17:48.977   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62befa1:true
,09-13 11:17:48.982  1731  1731 D SystemUpdateService: onCreate
,09-13 11:17:49.003  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:17:49.005  1731  4113 I SystemUpdateService: active receiver: enabled
,09-13 11:17:49.009  1731  4113 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:17:49.011  1731  4113 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 11:17:49.011  1731  4113 I SystemUpdateService: now status is 0 (complete)
09-13 11:17:49.011  1731  4113 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:17:49.011  1731  4113 I SystemUpdateService: file has been verified
09-13 11:17:49.012  1731  4113 I SystemUpdateService: OTA package size = 12249756
09-13 11:17:49.012  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 11:17:49.015  1731  2453 I iu.UploadsManager: num queued entries: 0
,09-13 11:17:49.015  1731  4113 I SystemUpdateService: showing system update notification
,09-13 11:17:49.017  1731  2453 I iu.UploadsManager: num updated entries: 0
,09-13 11:17:49.018  1731  2453 I iu.SyncManager: NEXT; no task
,09-13 11:17:49.029  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:17:49.030  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:17:49.043   872  1950 I ActivityManager: Start proc 4115:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 11:17:49.046  1731  1731 D SystemUpdateService: onDestroy
,09-13 11:17:49.080  4115  4115 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 11:17:49.083  4115  4115 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:49.087  4115  4115 D SprintDMHelper: simOperator: 
,09-13 11:17:49.087  4115  4115 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:17:49.101   872  1718 I ActivityManager: Start proc 4127:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 11:17:49.224   872  3268 I ActivityManager: Start proc 4142:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 11:17:49.228  2865  4141 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 11:17:49.231   872   882 I ActivityManager: Killing 3640:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 11:17:49.301  4142  4142 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 11:17:49.363  4142  4142 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 11:17:49.363  4142  4142 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 11:17:49.363  4142  4142 I GAv4    :   adb logcat -s GAv4
,09-13 11:17:49.382  4142  4142 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:17:49.390  4142  4142 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:17:49.420  4142  4159 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:17:49.533  4142  4142 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 11:17:49.579  4142  4142 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 11:17:49.587  4142  4142 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8525-8528)
09-13 11:17:49.588  4142  4142 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 11:17:49.600  4142  4142 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {102870c}
,09-13 11:17:49.600  4142  4142 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 11:17:49.602  4142  4142 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 11:17:49.610  4142  4142 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 11:17:49.612  4142  4142 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 11:17:49.628  4142  4142 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 11:17:49.641  4142  4142 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 11:17:49.641  4142  4142 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 11:17:49.641  4142  4142 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:17:49.641  4142  4142 I Adreno  : Build Date                       : 10/20/15
09-13 11:17:49.641  4142  4142 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:17:49.641  4142  4142 I Adreno  : Local Branch                     : M14
09-13 11:17:49.641  4142  4142 I Adreno  : Remote Branch                    : 
09-13 11:17:49.641  4142  4142 I Adreno  : Remote Branch                    : 
09-13 11:17:49.641  4142  4142 I Adreno  : Reconstruct Branch               : 
,09-13 11:17:49.701  4142  4142 I NSApplication: Starting up...
,09-13 11:17:49.725  4142  4188 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 11:17:49.728   872  1967 I ActivityManager: Start proc 4193:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-13 11:17:49.729   872  1967 I ActivityManager: Killing 1703:android.process.acore/u0a5 (adj 15): empty #17
,09-13 11:17:49.823  4193  4193 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 11:17:50.023   872  3247 I ActivityManager: Killing 3838:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 11:17:50.097   872   882 I ActivityManager: Start proc 4207:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 11:17:50.173  4207  4207 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 11:17:50.231  4207  4207 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 11:17:50.250   872  3247 I ActivityManager: Killing 3855:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 11:17:53.340   872  1967 D WifiService: setWifiEnabled: true pid=3957, uid=10000
,09-13 11:17:53.341   872  1967 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:17:53.353   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-13 11:17:53.360  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:53.360  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:17:53.360  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:53.361  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:53.364  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:53.364  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:53.364  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-13 11:17:53.365  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:53.367  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:53.367  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:53.368  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:53.368  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:53.383   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-13 11:17:53.384   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 11:17:53.385   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 11:17:53.386   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 11:17:53.386   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 11:17:53.387   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 11:17:53.387   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 11:17:53.431   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 11:17:53.432   373   871 D CommandListener: Setting iface cfg
,09-13 11:17:53.432   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:17:53.432   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 11:17:53.432   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 11:17:53.445   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
09-13 11:17:53.445   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 11:17:53.447   872  1310 E native  : do suspend true
,09-13 11:17:53.500   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:17:54.101   872  1717 I ActivityManager: Killing 2240:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 11:17:54.782   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:17:54.826   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.94 rxSuccessRate=8.94 delta 1000 -> 994
,09-13 11:17:54.827   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 11:17:54.828   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:17:54.849   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 11:17:54.907   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 11:17:54.909  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 11:17:55.504  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 11:17:55.552  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 11:17:55.552  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 11:17:55.555   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:17:55.563   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 11:17:55.563   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:17:55.564   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 11:17:55.581   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:17:55.600   373   871 D CommandListener: Setting iface cfg
,09-13 11:17:55.601   872  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 11:17:55.609   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 11:17:55.648   872  4241 D DhcpClient: Receive thread started
,09-13 11:17:55.746   872  1310 E native  : do suspend false
,09-13 11:17:55.774   872  1891 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 11:17:55.788   872  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,09-13 11:17:55.789   872  1891 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,09-13 11:17:55.793   872  1891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 11:17:55.809   872  4241 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 11:17:55.810   872  1891 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 11:17:55.815   373   871 D CommandListener: Setting iface cfg
,09-13 11:17:55.828   872  1891 D DhcpClient: Scheduling renewal in 86399s
,09-13 11:17:55.829   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 11:17:55.835   872  1310 E native  : do suspend true
,09-13 11:17:55.861   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 11:17:55.865   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:17:55.866   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 11:17:55.869   872  1313 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 11:17:55.880   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 11:17:55.919   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 11:17:55.919   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 11:17:55.921   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 11:17:55.923   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 11:17:55.925   872  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 11:17:55.933   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 11:17:55.938   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 11:17:55.938   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 11:17:55.938   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 11:17:55.938   872  1313 D ConnectivityService:    accepting network in place of null
,09-13 11:17:55.938   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 11:17:55.939   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:17:55.939   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:17:55.956   872  4240 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174897, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:17:55.986   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:17:56.026   872  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 11:17:56.028   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:17:56.036   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 11:17:56.036   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:56.043   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 11:17:56.047   872   889 D Tethering: MasterInitialState.processMessage what=3
09-13 11:17:56.052  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:56.052  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:56.052  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.053  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:56.059  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:56.059  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:56.059  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.059  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:56.062  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:56.063  3957  3957 V io.jxcore,.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:17:56.063  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:17:56.063  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:56.063  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:17:56.082  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:17:56.086  1731  1731 D SystemUpdateService: onCreate
,09-13 11:17:56.091  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:17:56.104   872  4239 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 09:17:56 GMT], X-Android-Received-Millis=[1473758276104], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473758276067]}
,09-13 11:17:56.105   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-13 11:17:56.106   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-13 11:17:56.106   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 11:17:56.110   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 11:17:56.137  1731  4253 I SystemUpdateService: active receiver: enabled
,09-13 11:17:56.186  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 11:17:56.208  1731  2453 I iu.UploadsManager: num queued entries: 0
,09-13 11:17:56.212  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:17:56.213  1731  2453 I iu.UploadsManager: num updated entries: 0
,09-13 11:17:56.224  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:17:56.228  1731  4253 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:17:56.229  1731  2453 I iu.SyncManager: NEXT; no task
,09-13 11:17:56.235  4115  4115 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:56.236  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:56.251  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:17:56.253  1731  4256 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 11:17:56.253  1731  4256 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 11:17:56.266  4115  4115 D SprintDMHelper: simOperator: 
09-13 11:17:56.266  4115  4115 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:17:56.273  1731  4256 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 11:17:56.284  1731  4253 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 11:17:56.284  1731  4253 I SystemUpdateService: now status is 0 (complete)
09-13 11:17:56.284  1731  4253 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:17:56.284  1731  4253 I SystemUpdateService: file has been verified
09-13 11:17:56.285  1731  4253 I SystemUpdateService: OTA package size = 12249756
,09-13 11:17:56.357  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:17:56.358  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:17:56.358  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:56.358  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:56.404  1731  4253 I SystemUpdateService: showing system update notification
,09-13 11:17:56.410  3715  4252 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:17:56.410  3715  4252 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:17:56.410  3715  4252 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	... 12 more
09-13 11:17:56.410  3715  4252 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at fal.a(PG:38)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:17:56.410  3715  4252 E HttpOperation: 	... 14 more
,09-13 11:17:56.420  2865  4261 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 11:17:56.480  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:17:56.480  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:17:56.480  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:17:56.480  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:56.512  3715  4252 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:17:56.512  3715  4252 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at hec.a(PG:42)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at hee.a(PG:102)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at czr.a(PG:65)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at kka.a(PG:108)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:17:56.512  3715  4252 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	... 15 more
09-13 11:17:56.512  3715  4252 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at fal.a(PG:38)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:17:56.512  3715  4252 E HttpOperation: 	... 17 more
,09-13 11:17:56.513  3715  4252 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:17:56.513  3715  4252 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at hec.a(PG:42)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	... 15 more
09-13 11:17:56.513  3715  4252 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:17:56.513  3715  4252 E ExperimentLoader: 	... 17 more
,09-13 11:17:56.543  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 11:17:56.543  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 11:17:56.543  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:17:56.543  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:17:56.554  1731  1731 D SystemUpdateService: onDestroy
,09-13 11:17:56.603  1731  4256 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-13 11:17:56.732   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 163993, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:17:57.036   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 11:17:58.347   872  3247 D WifiService: setWifiEnabled: false pid=3957, uid=10000
,09-13 11:17:58.347   872  3247 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:17:58.388  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 11:17:58.398   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 11:17:58.399   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 11:17:58.399   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 11:17:58.400   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:17:58.420   872  1310 E native  : do suspend true
,09-13 11:17:58.442   872  1891 D DhcpClient: Clearing IP address
,09-13 11:17:58.442   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:17:58.450   373   871 D CommandListener: Setting iface cfg
,09-13 11:17:58.460  1522  4263 V NativeCrypto: Read error: ssl=0x99dd4200: I/O error during system call, Connection timed out
,09-13 11:17:58.460   872  4241 D DhcpClient: Receive thread stopped
09-13 11:17:58.465   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 11:17:58.465   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
09-13 11:17:58.465  1522  4263 V NativeCrypto: SSL shutdown failed: ssl=0x99dd4200: I/O error during system call, Broken pipe
09-13 11:17:58.465   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 11:17:58.466   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:17:58.466   872  1310 E native  : do suspend true
09-13 11:17:58.472   396   396 E Parcel  : Reading a NULL string not supported here.
,09-13 11:17:58.484   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 11:17:58.488   373   871 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:17:58.491   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:17:58.510   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:17:58.513  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:58.513  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:58.513  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:58.513  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:58.514  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:58.514  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:58.514  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:58.514  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:58.515  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:17:58.515  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:17:58.515  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:17:58.515  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:17:58.517   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 11:17:58.521  2104  2320 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:17:58.525   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:17:58.555   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:17:58.556   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 11:17:58.556   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:58.558   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 11:17:58.565  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:58.567  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:17:58.568  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:17:58.577  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:17:58.582  1731  1731 D SystemUpdateService: onCreate
,09-13 11:17:58.585  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:17:58.598  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-13 11:17:58.601  1731  2453 I iu.UploadsManager: num queued entries: 0
,09-13 11:17:58.607  1731  4278 I SystemUpdateService: active receiver: enabled
,09-13 11:17:58.609  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:17:58.610  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:17:58.612  4115  4115 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:17:58.616  4115  4115 D SprintDMHelper: simOperator: 
,09-13 11:17:58.616  4115  4115 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:17:58.640  1731  2453 I iu.UploadsManager: num updated entries: 0
,09-13 11:17:58.642  2865  4281 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 11:17:58.646  1731  2453 I iu.SyncManager: NEXT; no task
,09-13 11:17:58.647  1731  4278 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:17:58.649   373   871 E Netd    : netlink response contains error (No such file or directory)
,09-13 11:17:58.652  1731  4278 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 11:17:58.652  1731  4278 I SystemUpdateService: now status is 0 (complete)
09-13 11:17:58.652  1731  4278 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:17:58.652  1731  4278 I SystemUpdateService: file has been verified
09-13 11:17:58.652  1731  4278 I SystemUpdateService: OTA package size = 12249756
,09-13 11:17:58.657  1731  4278 I SystemUpdateService: showing system update notification
,09-13 11:17:58.664  1731  1731 D SystemUpdateService: onDestroy
,09-13 11:18:03.404   872   889 I ActivityManager: Start proc 4284:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 11:18:03.540  4284  4284 D AdapterServiceConfig: Adding HeadsetService
09-13 11:18:03.541  4284  4284 D AdapterServiceConfig: Adding A2dpService
,09-13 11:18:03.541  4284  4284 D AdapterServiceConfig: Adding HidService
09-13 11:18:03.543  4284  4284 D AdapterServiceConfig: Adding HealthService
09-13 11:18:03.543  4284  4284 D AdapterServiceConfig: Adding PanService
09-13 11:18:03.544  4284  4284 D AdapterServiceConfig: Adding GattService
09-13 11:18:03.545  4284  4284 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 11:18:03.570   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16dbab3:true
,09-13 11:18:03.570  4284  4284 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 11:18:03.575  4284  4284 I bt_bluedroid: init
,09-13 11:18:03.576  4284  4296 I BluetoothAdapterState: Entering OffState
,09-13 11:18:03.581  4284  4297 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 11:18:03.582  4284  4297 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 11:18:03.582  4284  4297 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 11:18:03.583  4284  4297 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 11:18:03.584  4284  4284 I bt_bluedroid: get_profile_interface socket
,09-13 11:18:03.586  4284  4284 I bt_bluedroid: get_profile_interface sdp
,09-13 11:18:03.591  4284  4295 I bt_bluedroid: config_hci_snoop_log
,09-13 11:18:03.593  4284  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:18:03.594   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 11:18:03.598  4284  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:18:03.605  4284  4296 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 11:18:03.606  4284  4296 D BluetoothAdapterProperties: Setting state to 14
09-13 11:18:03.606  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 11:18:03.610  4284  4296 D BluetoothBondStateMachine: make
,09-13 11:18:03.614  4284  4301 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 11:18:03.622  4284  4296 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:18:03.624  4284  4284 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 11:18:03.630  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:03.631  4284  4284 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 11:18:03.632  4284  4284 D BtGatt.GattService: Received start request. Starting profile...
,09-13 11:18:03.633  4284  4284 D BtGatt.GattService: start()
09-13 11:18:03.633  4284  4284 I bt_bluedroid: get_profile_interface gatt
09-13 11:18:03.634  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:18:03.635  4284  4284 D BtGatt.AdvertiseManager: advertise manager created
,09-13 11:18:03.646  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:03.646  4284  4284 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:03.646  4284  4284 V BluetoothAdapterState: isBleTurningOn()=true
09-13 11:18:03.647  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:03.647  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 11:18:03.648  4284  4296 I bt_bluedroid: enable
,09-13 11:18:03.649  4284  4297 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 11:18:03.650  4284  4297 I bt_hci  : start_up
,09-13 11:18:03.657  4284  4297 I bt_vendor: alloc value 0xb3a15189
,09-13 11:18:03.657  4284  4297 I bt_vendor: init
09-13 11:18:03.657  4284  4297 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-13 11:18:03.657  4284  4297 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 11:18:03.765  4284  4297 D bt_hci  : start_up starting async portion
,09-13 11:18:03.766  4284  4304 I bt_hci  : event_finish_startup
09-13 11:18:03.766  4284  4304 I bt_hci_h4: hal_open
09-13 11:18:03.767  4284  4304 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 11:18:03.780  4284  4304 I bt_userial_vendor: device fd = 51 open
,09-13 11:18:03.806  4284  4304 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:18:03.837  4284  4304 D bt_hwcfg: Chipset BCM4354A2
,09-13 11:18:03.838  4284  4304 D bt_hwcfg: Target name = [BCM4354A2]
09-13 11:18:03.839  4284  4304 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 11:18:03.944   872  1313 D ConnectivityService: handlePromptUnvalidated 101
,09-13 11:18:04.502  4284  4304 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 11:18:04.504  4284  4304 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 11:18:04.504  4284  4304 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 11:18:04.621  4284  4304 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:18:04.622  4284  4304 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 11:18:04.651  4284  4304 I bt_hwcfg: vendor lib fwcfg completed
,09-13 11:18:04.651  4284  4304 I bt_vendor: firmware callback
09-13 11:18:04.651  4284  4304 I bt_hci  : firmware_config_callback
,09-13 11:18:04.662  4284  4306 I bt_btu  : btu_task pending for preload complete event
,09-13 11:18:04.663  4284  4306 I bt_btu_task: Bluetooth chip preload is complete
09-13 11:18:04.663  4284  4306 I bt_btu  : btu_task received preload complete event
,09-13 11:18:04.675  4284  4306 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:18:04.676  4284  4306 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 11:18:04.676  4284  4306 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 11:18:04.676  4284  4306 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 11:18:04.677  4284  4306 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 11:18:04.677  4284  4306 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 11:18:04.679  4284  4306 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 11:18:04.679  4284  4306 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 11:18:04.679  4284  4306 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 11:18:04.680  4284  4306 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 11:18:04.680  4284  4306 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 11:18:04.680  4284  4306 I         : BTE_InitTraceLevels -- TRC_GATT
,09-13 11:18:04.680  4284  4306 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 11:18:04.681  4284  4306 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 11:18:04.681  4284  4306 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 11:18:04.815  4284  4306 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
,09-13 11:18:04.816  4284  4306 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,09-13 11:18:04.826  4284  4300 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 11:18:04.828  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 11:18:04.829  4284  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:18:04.833  4284  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:18:04.836  4284  4300 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:18:04.837  4284  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:18:04.838  4284  4300 D bt_hci  : do_postload posting postload work item
,09-13 11:18:04.839  4284  4304 I bt_hci  : event_postload
,09-13 11:18:04.839  4284  4304 I bt_vendor: sco_config_cb
09-13 11:18:04.839  4284  4304 I bt_hci  : sco_config_callback postload finished.
09-13 11:18:04.843  4284  4300 D bt_bte_conf: Device ID record 1 : primary
,09-13 11:18:04.843  4284  4300 D bt_bte_conf:   vendorId            = 000f
09-13 11:18:04.844  4284  4300 D bt_bte_conf:   vendorIdSource      = 0001
09-13 11:18:04.844  4284  4300 D bt_bte_conf:   product             = 1200
09-13 11:18:04.844  4284  4300 D bt_bte_conf:   version             = 1436,
09-13 11:18:04.844  4284  4300 D bt_bte_conf:   clientExecutableURL = 
,09-13 11:18:04.844  4284  4300 D bt_bte_conf:   serviceDescription  = 
09-13 11:18:04.845  4284  4300 D bt_bte_conf:   documentationURL    = 
09-13 11:18:04.845  4284  4300 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 11:18:04.846  4284  4297 D bt_stack_manager: event_start_up_stack finished
09-13 11:18:04.847  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:04.847  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 11:18:04.848  4284  4296 D BluetoothAdapterProperties: Setting state to 15
09-13 11:18:04.848  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 11:18:04.852  4284  4304 I bt_vendor: low_power_mode_cb
09-13 11:18:04.852  4284  4296 I BluetoothAdapterState: Entering BleOnState
09-13 11:18:04.853  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:04.859  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:04.859  4284  4296 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 11:18:04.859  4284  4296 D BluetoothAdapterProperties: Setting state to 11
09-13 11:18:04.859  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 11:18:04.863  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:04.865  4284  4284 D HeadsetService: Received start request. Starting profile...
,09-13 11:18:04.869  4284  4284 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 11:18:04.870  4284  4284 D HeadsetStateMachine: make
,09-13 11:18:04.876  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:04.878  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:04.879  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:04.888  4284  4284 D HeadsetStateMachine: max_hf_connections = 1
,09-13 11:18:04.888  4284  4284 I bt_bluedroid: get_profile_interface handsfree
09-13 11:18:04.888  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 11:18:04.889  4284  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 11:18:04.893  4284  4296 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:18:04.895  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:04.896  4284  4284 D A2dpService: Received start request. Starting profile...
09-13 11:18:04.897  4284  4284 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 11:18:04.897  4284  4284 I bt_bluedroid: get_profile_interface avrcp
,09-13 11:18:04.904  4284  4284 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 11:18:04.904  4284  4284 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:18:04.904  4284  4284 D A2dpStateMachine: make
,09-13 11:18:04.906  4284  4284 I bt_bluedroid: get_profile_interface a2dp
,09-13 11:18:04.906  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-13 11:18:04.908  4284  4315 D A2dpStateMachine: Enter Disconnected: -2
,09-13 11:18:04.909  4284  4284 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 11:18:04.910  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:04.911  4284  4284 D HidService: Received start request. Starting profile...
09-13 11:18:04.912  4284  4284 I bt_bluedroid: get_profile_interface hidhost
09-13 11:18:04.912  4284  4300 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
09-13 11:18:04.912  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 11:18:04.912  4284  4284 D HidService: setHidService(): set to: null
,09-13 11:18:04.912  4059  4059 D BluetoothInputDevice: Proxy object connected
,09-13 11:18:04.914  4059  4059 D HidProfile: Bluetooth service connected
09-13 11:18:04.915  4284  4284 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:18:04.915  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2,
09-13 11:18:04.916  4284  4284 D HealthService: Received start request. Starting profile...
,09-13 11:18:04.918  4284  4284 I bt_bluedroid: get_profile_interface health
,09-13 11:18:04.920  4284  4284 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 11:18:04.921  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:18:04.922  4284  4284 D PanService: Received start request. Starting profile...
,09-13 11:18:04.922  4284  4284 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 11:18:04.922  4284  4284 I bt_bluedroid: get_profile_interface pan
09-13 11:18:04.923  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,09-13 11:18:04.923  4284  4300 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 11:18:04.924  4059  4059 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 11:18:04.925  4059  4059 D PanProfile: Bluetooth service connected
09-13 11:18:04.927  4284  4284 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:18:04.928  4284  4284 D BluetoothMapService: Received start request. Starting profile...
09-13 11:18:04.928  4284  4284 D BluetoothMapService: start(),
09-13 11:18:04.928  4059  4059 D BluetoothMap: Proxy object connected
09-13 11:18:04.929  4059  4059 D MapProfile: Bluetooth service connected
,09-13 11:18:04.930  4059  4059 D BluetoothMap: getConnectedDevices()
,09-13 11:18:04.930  4059  4059 D BluetoothMap: Bluetooth is Not enabled
09-13 11:18:04.930  4284  4284 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-13 11:18:04.931  4284  4284 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 11:18:04.931  4284  4284 D BluetoothMapAppObserver: createReceiver()
,09-13 11:18:04.932  4284  4284 D BluetoothMapAppObserver: initObservers()
09-13 11:18:04.932  4284  4284 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 11:18:04.938  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:04.938  4284  4284 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:04.938  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:18:04.939  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false,
09-13 11:18:04.940  4284  4313 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isTurningOn()=true
,09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:04.940  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isTurningOn()=true
,09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:04.941  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:04.942  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:04.942  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:04.942  4284  4284 V BluetoothAdapterState: isTurningOn()=true
,09-13 11:18:04.942  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:04.942  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:04.942  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 11:18:04.942  4284  4296 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:18:04.943  4284  4296 D BluetoothAdapterProperties: State =  11
09-13 11:18:04.943  4284  4296 D BluetoothAdapterProperties: Setting state to 12
,09-13 11:18:04.943  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 11:18:04.944   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:18:04.944  4284  4296 I BluetoothAdapterState: Entering OnState
09-13 11:18:04.944  4059  4069 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:18:04.945  1354  2043 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:18:04.946  4284  4300 D BluetoothAdapterProperties: Scan Mode:21
,09-13 11:18:04.946  4284  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:18:04.948  1354  1354 D BluetoothMap: Proxy object connected
,09-13 11:18:04.948  1354  1354 D MapProfile: Bluetooth service connected
,09-13 11:18:04.948  1354  1354 D BluetoothMap: getConnectedDevices()
09-13 11:18:04.948  1354  1379 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:04.949  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:18:04.950  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:18:04.950  1354  1354 D PanProfile: Bluetooth service connected
09-13 11:18:04.950   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 11:18:04.951  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:18:04.951  1354  2043 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 11:18:04.951   872   872 D BluetoothA2dp: Proxy object connected
09-13 11:18:04.953  1354  1354 D BluetoothInputDevice: Proxy object connected
,09-13 11:18:04.953  1354  1354 D HidProfile: Bluetooth service connected
,09-13 11:18:04.953  1354  1379 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:04.954  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:04.955  4059  4071 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:18:04.955  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:04.955  1354  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:18:04.958  1354  1354 D BluetoothA2dp: Proxy object connected
09-13 11:18:04.958  4284  4284 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:04.958  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:18:04.958  4059  4069 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 11:18:04.958  4284  4284 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 11:18:04.960  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:04.960  4284  4284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:18:04.961   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:04.961   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:04.961  1942  1955 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:04.962  4284  4284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:18:04.962  1354  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:04.962  4284  4284 D ObexServerSockets: Succeed to create listening sockets 
09-13 11:18:04.962  4059  4071 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:18:04.962  4284  4284 D ObexServerSockets0: startAccept()
09-13 11:18:04.962  4284  4284 D ObexServerSockets0: prepareForNewConnect()
09-13 11:18:04.964  4284  4284 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-13 11:18:04.964  4284  4284 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 11:18:04.966  4284  4322 D ObexServerSockets0: Accepting socket connection...
09-13 11:18:04.966  4284  4321 D ObexServerSockets0: Accepting socket connection...
09-13 11:18:04.969   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 11:18:04.970  4284  4284 D BluetoothMapService: onReceive
09-13 11:18:04.970  4284  4284 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:18:04.970  4284  4284 D BluetoothMapService: STATE_ON
09-13 11:18:04.971  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:04.972  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:04.973  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:04.976  4059  4059 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 11:18:04.981  4059  4059 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 11:18:04.986  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 11:18:04.987  4059  4059 D BluetoothA2dp: Proxy object connected
,09-13 11:18:04.990  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:18:04.994  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:18:04.995  4284  4284 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 11:18:04.995  4284  4284 D ObexServerSockets0: prepareForNewConnect()
09-13 11:18:04.996  4059  4059 D BluetoothPbap: Proxy object connected
,09-13 11:18:04.996  4059  4059 D PbapServerProfile: Bluetooth service connected
,09-13 11:18:04.997  1354  1354 D BluetoothPbap: Proxy object connected
09-13 11:18:04.997  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-13 11:18:05.003  4284  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:05.012  4284  4331 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:05.013  4284  4331 I BtOppRfcommListener: Accept thread started.
,09-13 11:18:05.045   872   872 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.045   872   872 D BluetoothHeadset: Proxy object connected
09-13 11:18:05.046  1942  2062 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.047  1354  2043 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.047  1354  1354 D HeadsetProfile: Bluetooth service connected
09-13 11:18:05.047   872   872 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.061   872   889 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.061   872   889 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.062  1942  2203 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.063  1354  1376 D BluetoothHeadset: Proxy object connected
09-13 11:18:05.063  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-13 11:18:05.083  4059  4071 D BluetoothHeadset: Proxy object connected
,09-13 11:18:05.084  4059  4059 D HeadsetProfile: Bluetooth service connected
,09-13 11:18:07.746  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:07.758  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:07.762  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:07.808  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:18:07.809  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 11:18:07.809  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:18:07.810  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:07.842  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 11:18:07.842  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 11:18:07.842  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 11:18:08.369  4284  4296 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 11:18:08.370  4284  4296 D BluetoothAdapterProperties: Setting state to 13
,09-13 11:18:08.370  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 11:18:08.371  4284  4296 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 11:18:08.378  4284  4296 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:18:08.381  4284  4284 D BluetoothMapService: onReceive
09-13 11:18:08.382  4284  4284 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 11:18:08.382  4284  4284 D BluetoothMapService: STATE_TURNING_OFF
,09-13 11:18:08.383  4284  4284 D BluetoothMapService: MAP Service closeService in
,09-13 11:18:08.383  4284  4284 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 11:18:08.383  4284  4284 D ObexServerSockets0: shutdown(block = true)
09-13 11:18:08.384  4284  4321 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 11:18:08.394  4284  4300 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:18:08.395  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 11:18:08.396  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:08.397  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:18:08.397  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:18:08.397  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:08.400  4284  4284 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:18:08.400  4284  4322 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 11:18:08.401  4284  4308 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 11:18:08.401  4284  4284 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:18:08.402  4284  4284 D HeadsetService: Received stop request...Stopping profile...
,09-13 11:18:08.402  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:08.402  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:18:08.404  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:18:08.404  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:08.404  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:18:08.405   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 11:18:08.405   872   872 D BluetoothHeadset: Proxy object disconnected
,09-13 11:18:08.405  1942  1955 D BluetoothHeadset: Proxy object disconnected
09-13 11:18:08.406  4284  4284 D A2dpService: Received stop request...Stopping profile...
09-13 11:18:08.406  1354  1376 D BluetoothHeadset: Proxy object disconnected
09-13 11:18:08.406   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 11:18:08.406  4284  4315 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:18:08.407  4059  4069 D BluetoothHeadset: Proxy object disconnected
09-13 11:18:08.407   872   872 D BluetoothA2dp: Proxy object disconnected
09-13 11:18:08.408  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:18:08.408  4284  4284 D HidService: Received stop request...Stopping profile...
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:08.408  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:18:08.408  4284  4284 D HidService: Stopping Bluetooth HidService
,09-13 11:18:08.409  3957  3957 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:18:08.409  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:18:08.411  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.411  1354  1354 D HeadsetProfile: Bluetooth service disconnected
09-13 11:18:08.411  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-13 11:18:08.411  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-13 11:18:08.411  1354  1354 D HidProfile: Bluetooth service disconnected
09-13 11:18:08.412  4284  4284 I BtOppRfcommListener: stopping Accept Thread
,09-13 11:18:08.412  4284  4331 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:18:08.412  4284  4331 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 11:18:08.414  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.415  4284  4284 D HealthService: Received stop request...Stopping profile...
,09-13 11:18:08.415  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.415  4059  4059 D HeadsetProfile: Bluetooth service disconnected
09-13 11:18:08.416  4059  4059 D BluetoothA2dp: Proxy object disconnected
09-13 11:18:08.417  4284  4284 V BluetoothAdapterState: isTurningOff()=true
09-13 11:18:08.417  4284  4284 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:18:08.417  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.417  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:08.417  4284  4284 D PanService: Received stop request...Stopping profile...
09-13 11:18:08.419  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 11:18:08.419  1354  1354 D PanProfile: Bluetooth service disconnected
09-13 11:18:08.419  4284  4284 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:18:08.419  4284  4284 D BluetoothMapService: stop()
09-13 11:18:08.420  4284  4284 D BluetoothMapAppObserver: deinitObservers()
09-13 11:18:08.420  4284  4284 D BluetoothMapAppObserver: removeReceiver()
09-13 11:18:08.421  1354  1354 D BluetoothMap: Proxy object disconnected
09-13 11:18:08.421  1354  1354 D MapProfile: Bluetooth service disconnected
,09-13 11:18:08.421  4059  4059 D DockEventReceiver: finishStartingService: stopping service
09-13 11:18:08.423  4284  4284 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 11:18:08.424  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:18:08.424  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:18:08.424  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:18:08.424  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 11:18:08.424  4284  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 11:18:08.424  4284  4284 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:18:08.425  4284  4284 V BluetoothAdapterState: isTurningOff()=true
09-13 11:18:08.425  4059  4059 D BluetoothInputDevice: Proxy object disconnected
,09-13 11:18:08.425  4284  4284 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:08.425  4059  4059 D HidProfile: Bluetooth service disconnected
09-13 11:18:08.425  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.425  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:08.426  4059  4059 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 11:18:08.426  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:18:08.426  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:18:08.427  4059  4059 D PanProfile: Bluetooth service disconnected
09-13 11:18:08.427  4284  4306 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:18:08.427  4284  4306 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:18:08.427  4284  4306 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 11:18:08.427  4284  4306 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:18:08.427  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 11:18:08.427  4059  4059 D BluetoothMap: Proxy object disconnected
09-13 11:18:08.427  4284  4284 V BluetoothAdapterState: isTurningOff()=true
09-13 11:18:08.427  4059  4059 D MapProfile: Bluetooth service disconnected
09-13 11:18:08.427  4284  4284 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:08.427  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.428  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:08.428  4284  4284 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:18:08.428  4284  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 11:18:08.428  4284  4284 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 11:18:08.432  4284  4284 V BluetoothAdapterState: isTurningOff()=true
,09-13 11:18:08.432  4284  4284 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:08.432  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:18:08.433  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:08.433  4284  4284 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:18:08.433  4284  4300 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 11:18:08.433  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:18:08.433  4284  4284 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-13 11:18:08.433  4284  4284 V BluetoothAdapterState: isTurningOff()=true,
,09-13 11:18:08.433  4284  4284 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:18:08.434  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.434  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:08.434  4284  4284 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 11:18:08.434  4284  4284 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 11:18:08.435  4284  4284 D BluetoothMapService: MAP Service closeService in
09-13 11:18:08.435  4284  4284 V BluetoothAdapterState: isTurningOff()=true
09-13 11:18:08.435  4284  4284 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:08.435  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.435  4284  4284 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:08.436  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 11:18:08.436  4284  4296 D BluetoothAdapterProperties: Setting state to 15
09-13 11:18:08.436  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 11:18:08.436  4284  4296 I BluetoothAdapterState: Entering BleOnState
09-13 11:18:08.436   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:18:08.437  4284  4284 D BluetoothMapService: cleanup()
09-13 11:18:08.437  4284  4284 D BluetoothMapService: MAP Service closeService in
09-13 11:18:08.437  4059  4069 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 11:18:08.438  1354  1376 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:18:08.439  1354  1354 D BluetoothPbap: Proxy object disconnected
,09-13 11:18:08.439  1354  1354 D PbapServerProfile: Bluetooth service disconnected
09-13 11:18:08.440  1354  2043 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:18:08.440  4059  4059 D BluetoothPbap: Proxy object disconnected
09-13 11:18:08.440  4059  4059 D PbapServerProfile: Bluetooth service disconnected
09-13 11:18:08.442  4059  4069 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:18:08.443   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:18:08.443  1354  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 11:18:08.445  1354  1376 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:18:08.446  4059  4338 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:18:08.446  4059  4071 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:18:08.447  1354  2043 D BluetoothA2dp: onBluetoothStateChange: up=false,
09-13 11:18:08.447  4059  4069 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:18:08.448   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:18:08.448   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:18:08.448  1942  2062 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:18:08.448  1354  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:18:08.449  4059  4338 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:18:08.449  4284  4296 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 11:18:08.449  4284  4296 D BluetoothAdapterProperties: Setting state to 16
09-13 11:18:08.450  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 11:18:08.450  4284  4296 D BluetoothAdapterProperties: onBleDisable
09-13 11:18:08.450  4284  4296 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:18:08.451  4284  4297 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-13 11:18:08.452  4284  4306 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 11:18:08.452  4284  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:18:08.452  4284  4300 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:18:08.453  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:08.457  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.458  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.458  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:18:08.459  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:08.461  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:08.462  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 11:18:08.462  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:08.468  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:18:08.656  4284  4300 I bt_hci  : shut_down
,09-13 11:18:08.676  4284  4304 D bt_hwcfg: hw_epilog_process
,09-13 11:18:08.677  4284  4304 I bt_vendor: low_power_mode_cb
,09-13 11:18:08.694  4284  4304 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-13 11:18:08.694  4284  4304 I bt_vendor: epilog_cb
,09-13 11:18:08.695  4284  4304 I bt_hci  : epilog_finished_callback
,09-13 11:18:08.702  4284  4300 I bt_hci_h4: hal_close
,09-13 11:18:08.703  4284  4300 I bt_userial_vendor: device fd = 51 close
,09-13 11:18:08.825  4284  4297 D bt_stack_manager: event_shut_down_stack finished.
,09-13 11:18:08.826  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 11:18:08.832  4284  4296 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 11:18:08.833  4284  4284 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:18:08.835  4284  4284 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 11:18:08.835  4284  4284 D BtGatt.GattService: stop()
09-13 11:18:08.835  4284  4284 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 11:18:08.840  4284  4284 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:18:08.840  4284  4284 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:18:08.841  4284  4284 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:08.841  4284  4284 V BluetoothAdapterState: isBleTurningOff()=true
09-13 11:18:08.842  4284  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 11:18:08.843  4284  4296 D BluetoothAdapterProperties: Setting state to 10
,09-13 11:18:08.843  4284  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 11:18:08.844  4284  4296 I BluetoothAdapterState: Entering OffState
,09-13 11:18:08.846   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 11:18:08.873  4284  4284 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 11:18:08.873  4284  4284 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 11:18:08.873  4284  4297 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.,
,09-13 11:18:08.880  4284  4297 D bt_stack_manager: event_clean_up_stack finished.
,09-13 11:18:08.882  4284  4284 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 11:18:08.886  4284  4284 I art     : System.exit called, status: 0
,09-13 11:18:08.887  4284  4284 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 11:18:08.979   872  1980 I ActivityManager: Process com.android.bluetooth (pid 4284) has died
,09-13 11:18:13.366  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:18:13.367  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:13.374  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:13.374  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a9b266 removed from the list
,09-13 11:18:13.374  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:18:13.375  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:13.375  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:13.379  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:18:13.379  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7539e54 added. We now have 4 listener(s)
,09-13 11:18:13.379  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:18:13.381  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:13.381  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7539e54 removed from the list
09-13 11:18:13.382  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:18:13.382  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:18:13.382  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:13.384  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:13.385  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d031fd added. We now have 4 listener(s)
09-13 11:18:13.385  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:18:18.399  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:18.445   872   889 I ActivityManager: Start proc 4343:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 11:18:18.609  4343  4343 D AdapterServiceConfig: Adding HeadsetService
09-13 11:18:18.609  4343  4343 D AdapterServiceConfig: Adding A2dpService
,09-13 11:18:18.609  4343  4343 D AdapterServiceConfig: Adding HidService
09-13 11:18:18.609  4343  4343 D AdapterServiceConfig: Adding HealthService
09-13 11:18:18.609  4343  4343 D AdapterServiceConfig: Adding PanService
09-13 11:18:18.610  4343  4343 D AdapterServiceConfig: Adding GattService
09-13 11:18:18.610  4343  4343 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 11:18:18.623  4343  4343 D BluetoothAdapterState: make() - Creating AdapterState
09-13 11:18:18.623   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97c2e06:true
,09-13 11:18:18.628  4343  4343 I bt_bluedroid: init
09-13 11:18:18.629  4343  4355 I BluetoothAdapterState: Entering OffState
,09-13 11:18:18.631  4343  4356 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 11:18:18.631  4343  4356 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 11:18:18.632  4343  4356 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 11:18:18.632  4343  4356 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 11:18:18.633  4343  4343 I bt_bluedroid: get_profile_interface socket
,09-13 11:18:18.634  4343  4359 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:18:18.635  4343  4343 I bt_bluedroid: get_profile_interface sdp
09-13 11:18:18.636  4343  4359 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:18:18.639  4343  4354 I bt_bluedroid: config_hci_snoop_log
,09-13 11:18:18.640   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 11:18:18.649  4343  4355 D BluetoothAdapterState: Current state: OFF, message: 0
09-13 11:18:18.649  4343  4355 D BluetoothAdapterProperties: Setting state to 14
09-13 11:18:18.649  4343  4355 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 11:18:18.651  4343  4355 D BluetoothBondStateMachine: make
,09-13 11:18:18.654  4343  4360 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 11:18:18.657  4343  4355 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:18:18.660  4343  4343 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 11:18:18.667  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:18.669  4343  4343 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 11:18:18.671  4343  4343 D BtGatt.GattService: Received start request. Starting profile...
09-13 11:18:18.671  4343  4343 D BtGatt.GattService: start()
,09-13 11:18:18.671  4343  4343 I bt_bluedroid: get_profile_interface gatt
,09-13 11:18:18.673  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:18:18.674  4343  4343 D BtGatt.AdvertiseManager: advertise manager created
,09-13 11:18:18.687  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:18.687  4343  4343 V BluetoothAdapterState: isTurningOn()=false
09-13 11:18:18.687  4343  4343 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 11:18:18.688  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:18.689  4343  4355 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 11:18:18.689  4343  4355 I bt_bluedroid: enable
09-13 11:18:18.690  4343  4356 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 11:18:18.690  4343  4356 I bt_hci  : start_up
,09-13 11:18:18.704  4343  4356 I bt_vendor: alloc value 0xb3a15189
09-13 11:18:18.704  4343  4356 I bt_vendor: init
09-13 11:18:18.704  4343  4356 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 11:18:18.704  4343  4356 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 11:18:18.811  4343  4356 D bt_hci  : start_up starting async portion
09-13 11:18:18.811  4343  4363 I bt_hci  : event_finish_startup
,09-13 11:18:18.812  4343  4363 I bt_hci_h4: hal_open
09-13 11:18:18.812  4343  4363 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 11:18:18.823  4343  4363 I bt_userial_vendor: device fd = 51 open
,09-13 11:18:18.854  4343  4363 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:18:18.885  4343  4363 D bt_hwcfg: Chipset BCM4354A2
,09-13 11:18:18.886  4343  4363 D bt_hwcfg: Target name = [BCM4354A2]
09-13 11:18:18.886  4343  4363 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 11:18:19.742  4343  4363 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 11:18:19.744  4343  4363 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 11:18:19.744  4343  4363 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 11:18:19.862  4343  4363 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:18:19.863  4343  4363 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 11:18:19.892  4343  4363 I bt_hwcfg: vendor lib fwcfg completed
,09-13 11:18:19.892  4343  4363 I bt_vendor: firmware callback
09-13 11:18:19.892  4343  4363 I bt_hci  : firmware_config_callback
,09-13 11:18:19.905  4343  4365 I bt_btu  : btu_task pending for preload complete event
,09-13 11:18:19.905  4343  4365 I bt_btu_task: Bluetooth chip preload is complete
09-13 11:18:19.905  4343  4365 I bt_btu  : btu_task received preload complete event
,09-13 11:18:19.918  4343  4365 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:18:19.918  4343  4365 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 11:18:19.918  4343  4365 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 11:18:19.919  4343  4365 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 11:18:19.919  4343  4365 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 11:18:19.919  4343  4365 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 11:18:19.919  4343  4365 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 11:18:19.920  4343  4365 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 11:18:19.920  4343  4365 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 11:18:19.920  4343  4365 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 11:18:19.921  4343  4365 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 11:18:19.921  4343  4365 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 11:18:19.922  4343  4365 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 11:18:19.922  4343  4365 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 11:18:19.922  4343  4365 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 11:18:20.068  4343  4365 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3992d9d
,09-13 11:18:20.068  4343  4365 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3992d9d 
,09-13 11:18:20.080  4343  4359 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 11:18:20.082  4343  4359 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 11:18:20.083  4343  4359 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:18:20.089  4343  4359 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:18:20.093  4343  4359 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:18:20.093  4343  4359 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:18:20.094  4343  4359 D bt_hci  : do_postload posting postload work item
,09-13 11:18:20.094  4343  4363 I bt_hci  : event_postload
,09-13 11:18:20.094  4343  4363 I bt_vendor: sco_config_cb
,09-13 11:18:20.094  4343  4363 I bt_hci  : sco_config_callback postload finished.
,09-13 11:18:20.097  4343  4359 D bt_bte_conf: Device ID record 1 : primary
,09-13 11:18:20.097  4343  4359 D bt_bte_conf:   vendorId            = 000f
,09-13 11:18:20.097  4343  4359 D bt_bte_conf:   vendorIdSource      = 0001
09-13 11:18:20.097  4343  4359 D bt_bte_conf:   product             = 1200
,09-13 11:18:20.098  4343  4359 D bt_bte_conf:   version             = 1436
,09-13 11:18:20.098  4343  4359 D bt_bte_conf:   clientExecutableURL = 
09-13 11:18:20.098  4343  4359 D bt_bte_conf:   serviceDescription  = 
,09-13 11:18:20.098  4343  4359 D bt_bte_conf:   documentationURL    = 
09-13 11:18:20.099  4343  4359 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 11:18:20.099  4343  4356 D bt_stack_manager: event_start_up_stack finished
,09-13 11:18:20.100  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:20.102  4343  4355 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 11:18:20.102  4343  4355 D BluetoothAdapterProperties: Setting state to 15
09-13 11:18:20.103  4343  4355 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-13 11:18:20.104  4343  4355 I BluetoothAdapterState: Entering BleOnState
09-13 11:18:20.105  4343  4363 I bt_vendor: low_power_mode_cb
09-13 11:18:20.105  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 11:18:20.109  4343  4355 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 11:18:20.109  4343  4355 D BluetoothAdapterProperties: Setting state to 11,
09-13 11:18:20.110  4343  4355 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 11:18:20.118  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:20.121  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:20.129  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
09-13 11:18:20.129  4343  4343 D HeadsetService: Received start request. Starting profile...
,09-13 11:18:20.132  4343  4343 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 11:18:20.132  4343  4343 D HeadsetStateMachine: make
,09-13 11:18:20.140  4343  4355 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:18:20.147  4343  4343 D HeadsetStateMachine: max_hf_connections = 1
,09-13 11:18:20.147  4343  4343 I bt_bluedroid: get_profile_interface handsfree
09-13 11:18:20.147  4343  4359 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 11:18:20.148  4343  4359 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 11:18:20.152  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:20.153  4343  4343 D A2dpService: Received start request. Starting profile...
,09-13 11:18:20.153  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:18:20.153  4343  4343 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 11:18:20.153  4343  4343 I bt_bluedroid: get_profile_interface avrcp
,09-13 11:18:20.160  4343  4343 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 11:18:20.160  4343  4343 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:18:20.160  4343  4343 D A2dpStateMachine: make
,09-13 11:18:20.161  4343  4343 I bt_bluedroid: get_profile_interface a2dp
,09-13 11:18:20.162  4343  4359 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 11:18:20.163  4343  4374 D A2dpStateMachine: Enter Disconnected: -2
,09-13 11:18:20.164  4343  4343 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 11:18:20.164  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:20.165  4343  4343 D HidService: Received start request. Starting profile...
,09-13 11:18:20.165  4343  4343 I bt_bluedroid: get_profile_interface hidhost
09-13 11:18:20.165  4343  4343 D HidService: setHidService(): set to: null
,09-13 11:18:20.166  4343  4359 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39743e5
09-13 11:18:20.166  4343  4359 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 11:18:20.166  4343  4343 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:18:20.167  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:20.167  4343  4343 D HealthService: Received start request. Starting profile...
,09-13 11:18:20.169  4343  4343 I bt_bluedroid: get_profile_interface health
,09-13 11:18:20.169  4343  4343 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 11:18:20.170  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:20.171  4343  4343 D PanService: Received start request. Starting profile...
09-13 11:18:20.171  4343  4343 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 11:18:20.171  4343  4343 I bt_bluedroid: get_profile_interface pan
09-13 11:18:20.171  4343  4359 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 11:18:20.173  4343  4343 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:20.174  4343  4343 D BluetoothMapService: Received start request. Starting profile...
09-13 11:18:20.174  4343  4343 D BluetoothMapService: start()
,09-13 11:18:20.176  4343  4343 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 11:18:20.177  4343  4343 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 11:18:20.177  4343  4343 D BluetoothMapAppObserver: createReceiver()
,09-13 11:18:20.178  4343  4343 D BluetoothMapAppObserver: initObservers()
,09-13 11:18:20.178  4343  4343 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 11:18:20.186  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.186  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.186  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.186  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:20.188  4343  4372 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.192  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isTurningOff()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isTurningOn()=true
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:18:20.193  4343  4343 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:18:20.194  4343  4355 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 11:18:20.194  4343  4355 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:18:20.194  4343  4355 D BluetoothAdapterProperties: State =  11
,09-13 11:18:20.196  4343  4359 D BluetoothAdapterProperties: Scan Mode:21
,09-13 11:18:20.196  4343  4355 D BluetoothAdapterProperties: Setting state to 12
,09-13 11:18:20.196  4343  4355 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 11:18:20.196  4343  4359 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:18:20.197   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.197  4059  4071 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:18:20.198  4343  4355 I BluetoothAdapterState: Entering OnState
09-13 11:18:20.199  4059  4059 D BluetoothInputDevice: Proxy object connected
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:20.199  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:20.199  4059  4059 D HidProfile: Bluetooth service connected
,09-13 11:18:20.199  1354  1376 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:18:20.201  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:20.202  1354  1354 D BluetoothMap: Proxy object connected
09-13 11:18:20.202  1354  1354 D MapProfile: Bluetooth service connected
,09-13 11:18:20.202  1354  1354 D BluetoothMap: getConnectedDevices()
09-13 11:18:20.202  1354  1379 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:18:20.204  4059  4338 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 11:18:20.204  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 11:18:20.204  1354  1354 D PanProfile: Bluetooth service connected
09-13 11:18:20.204  4343  4343 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:20.205  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:20.205  4343  4343 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 11:18:20.206  4343  4343 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:20.207  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:18:20.208   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 11:18:20.208  4343  4343 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:18:20.208  1354  2043 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:18:20.210  4343  4343 D ObexServerSockets: Succeed to create listening sockets 
09-13 11:18:20.210  4343  4343 D ObexServerSockets0: startAccept()
,09-13 11:18:20.210  1354  1354 D BluetoothInputDevice: Proxy object connected
09-13 11:18:20.210  1354  1354 D HidProfile: Bluetooth service connected
,09-13 11:18:20.210  1354  1376 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:18:20.210  4343  4343 D ObexServerSockets0: prepareForNewConnect()
09-13 11:18:20.211  4059  4071 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.211  4059  4069 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 11:18:20.212  4343  4343 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 11:18:20.212  4343  4343 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 11:18:20.213  1354  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:18:20.213   872   872 D BluetoothA2dp: Proxy object connected
09-13 11:18:20.214  4343  4380 D ObexServerSockets0: Accepting socket connection...
09-13 11:18:20.214  4343  4381 D ObexServerSockets0: Accepting socket connection...
09-13 11:18:20.215  1354  1354 D BluetoothA2dp: Proxy object connected
09-13 11:18:20.215  4059  4338 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:18:20.216  4059  4059 D BluetoothMap: Proxy object connected
09-13 11:18:20.216  4059  4059 D MapProfile: Bluetooth service connected
09-13 11:18:20.216  4059  4059 D BluetoothMap: getConnectedDevices()
09-13 11:18:20.216   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.216   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.216  1942  1956 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.216  1354  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:18:20.217  4059  4069 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:18:20.220  4343  4343 D BluetoothMapService: onReceive
09-13 11:18:20.220  4343  4343 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:18:20.220  4343  4343 D BluetoothMapService: STATE_ON
09-13 11:18:20.220   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 11:18:20.221  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:20.221  4059  4059 D BluetoothA2dp: Proxy object connected
09-13 11:18:20.222  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:20.224  4059  4059 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:18:20.224  4059  4059 D PanProfile: Bluetooth service connected
09-13 11:18:20.229  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:18:20.241  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:18:20.243  4343  4343 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 11:18:20.243  4343  4343 D ObexServerSockets0: prepareForNewConnect()
,09-13 11:18:20.245  1354  1354 D BluetoothPbap: Proxy object connected
09-13 11:18:20.245  1354  1354 D PbapServerProfile: Bluetooth service connected
09-13 11:18:20.246  4343  4384 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:20.248  4059  4059 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:18:20.250  4059  4059 D BluetoothPbap: Proxy object connected
09-13 11:18:20.250  4059  4059 D PbapServerProfile: Bluetooth service connected
,09-13 11:18:20.278  4343  4390 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:20.279  4343  4390 I BtOppRfcommListener: Accept thread started.
,09-13 11:18:20.299   872   872 D BluetoothHeadset: Proxy object connected
09-13 11:18:20.299   872   872 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.300  1942  1955 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.301  1354  2043 D BluetoothHeadset: Proxy object connected
09-13 11:18:20.301  1354  1354 D HeadsetProfile: Bluetooth service connected
09-13 11:18:20.302   872   872 D BluetoothHeadset: Proxy object connected
09-13 11:18:20.302  4059  4338 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.302  4059  4059 D HeadsetProfile: Bluetooth service connected
,09-13 11:18:20.312  4059  4071 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.313  4059  4059 D HeadsetProfile: Bluetooth service connected
,09-13 11:18:20.316   872   889 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.316   872   889 D BluetoothHeadset: Proxy object connected
09-13 11:18:20.316  1942  2062 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.318  1354  1379 D BluetoothHeadset: Proxy object connected
,09-13 11:18:20.318  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:23.419  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:23.426  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:18:23.427  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:23.428  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d031fd removed from the list
09-13 11:18:23.428  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:18:23.428  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:23.428  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:23.435  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:18:23.435  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8e8ef2 added. We now have 4 listener(s)
09-13 11:18:23.436  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:18:23.441   872  1381 D WifiService: setWifiEnabled: false pid=3957, uid=10000
,09-13 11:18:23.442   872  1381 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:18:28.331  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:28.340  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:28.345  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:28.408  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:18:28.409  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 11:18:28.409  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:18:28.409  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:28.455  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:28.456   872  1718 D WifiService: setWifiEnabled: true pid=3957, uid=10000
09-13 11:18:28.457   872  1718 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:18:28.474   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:28.492  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:28.499  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:18:28.501   872  1310 D WifiConfigStore: loaded 0 passpoint configs
09-13 11:18:28.502  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 11:18:28.502   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 11:18:28.502  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 11:18:28.503  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
09-13 11:18:28.503   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 11:18:28.504   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 11:18:28.504   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 11:18:28.504   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 11:18:28.504   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:18:28.510  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:18:28.518  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:18:28.520   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-13 11:18:28.522   373   871 D CommandListener: Setting iface cfg
09-13 11:18:28.522   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:18:28.523   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-13 11:18:28.523   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 11:18:28.574   872  1310 E native  : do suspend true
,09-13 11:18:28.587   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:18:28.589   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 11:18:28.589   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 11:18:29.881   872  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 11:18:30.025   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=10.50 delta 1000 -> 994
,09-13 11:18:30.029   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 11:18:30.030   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-13 11:18:30.053   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 11:18:30.124   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 11:18:30.127  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 11:18:30.566  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 11:18:30.607  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 11:18:30.607  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 11:18:30.613   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:18:30.629   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:18:30.630   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:18:30.630   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 11:18:30.660   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:18:30.682   373   871 D CommandListener: Setting iface cfg
,09-13 11:18:30.684   872  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 11:18:30.699   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 11:18:30.741   872  4400 D DhcpClient: Receive thread started
,09-13 11:18:30.845   872  1310 E native  : do suspend false
,09-13 11:18:30.873   872  1891 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 11:18:30.891   872  4400 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-13 11:18:30.893   872  1891 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-13 11:18:30.896   872  1891 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 11:18:30.910   872  4400 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 11:18:30.912   872  1891 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 11:18:30.917   373   871 D CommandListener: Setting iface cfg
,09-13 11:18:30.930   872  1891 D DhcpClient: Scheduling renewal in 86399s
,09-13 11:18:30.931   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-13 11:18:30.933   872  1310 E native  : do suspend true
,09-13 11:18:30.965   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 11:18:30.969   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:18:30.970   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 11:18:30.973   872  1313 D ConnectivityService: Adding iface wlan0 to network 102
09-13 11:18:30.975   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 11:18:31.052   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 11:18:31.053   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 11:18:31.056   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 11:18:31.060   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 11:18:31.065   872  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 11:18:31.078   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 11:18:31.084   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-13 11:18:31.084   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-13 11:18:31.084   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 11:18:31.085   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:18:31.085   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-13 11:18:31.086   872  1313 D ConnectivityService:    accepting network in place of null
,09-13 11:18:31.087   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:18:31.137   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210078, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:18:31.138   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:18:31.201   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:18:31.207   872  4398 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-13 11:18:31.209   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 11:18:31.210   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:18:31.213  1874  1914 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-13 11:18:31.213  1874  1914 I Keyboard.Facilitator: flushDynamicLanguageModels()
09-13 11:18:31.214   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-13 11:18:31.215   872   889 D Tethering: MasterInitialState.processMessage what=3
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:31.241  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:18:31.243  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:31.249  3957  3957 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:18:31.252  3957  3957 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:31.254  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:18:31.262  1731  1731 D SystemUpdateService: onCreate
09-13 11:18:31.266  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:18:31.272  1522  1522 I ConfigService: onCreate
09-13 11:18:31.277   872  4398 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 09:18:31 GMT], X-Android-Received-Millis=[1473758311276], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473758311251]}
,09-13 11:18:31.278   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-13 11:18:31.278   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 11:18:31.278   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 11:18:31.280   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 11:18:31.294  1731  4409 I SystemUpdateService: active receiver: enabled
,09-13 11:18:31.298  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 11:18:31.302  1731  2453 I iu.UploadsManager: num queued entries: 0
,09-13 11:18:31.317  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:18:31.318  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:18:31.320  4115  4115 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:18:31.325  1731  4412 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 11:18:31.325  1731  4412 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 11:18:31.326  1731  4412 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 11:18:31.327  4115  4115 D SprintDMHelper: simOperator: 
09-13 11:18:31.327  4115  4115 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:18:31.338  1731  4409 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:18:31.340  1731  2453 I iu.UploadsManager: num updated entries: 0
,09-13 11:18:31.357  1731  2453 I iu.SyncManager: NEXT; no task
,09-13 11:18:31.358  1731  4409 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 11:18:31.359  1731  4409 I SystemUpdateService: now status is 0 (complete)
,09-13 11:18:31.360  1731  4409 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 11:18:31.415  1731  4409 I SystemUpdateService: file has been verified
,09-13 11:18:31.415  1731  4409 I SystemUpdateService: OTA package size = 12249756
,09-13 11:18:31.440  1731  4409 I SystemUpdateService: showing system update notification
,09-13 11:18:31.452  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 11:18:31.452  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 11:18:31.453  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:18:31.453  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:31.481  2865  4417 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 11:18:31.491  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:18:31.492  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:18:31.492  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:18:31.492  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:31.507  3715  4416 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:18:31.507  3715  4416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:18:31.507  3715  4416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	... 12 more
09-13 11:18:31.507  3715  4416 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at fal.a(PG:38)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:18:31.507  3715  4416 E HttpOperation: 	... 14 more
,09-13 11:18:31.582  1731  4412 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-13 11:18:31.611  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:18:31.612  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:18:31.612  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:18:31.612  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:31.619  1731  1731 D SystemUpdateService: onDestroy
,09-13 11:18:31.633  3715  4416 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:18:31.633  3715  4416 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at hec.a(PG:42)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at hee.a(PG:102)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at czr.a(PG:65)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at kka.a(PG:108)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:18:31.633  3715  4416 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	... 15 more
09-13 11:18:31.633  3715  4416 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at fal.a(PG:38)
09-13 11:18:31.633  3715  4416 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:18:31.633  3715  4416 E HttpOperation: ,	... 17 more
09-13 11:18:31.633  3715  4416 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:18:31.633  3715  4416 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at hec.a(PG:42)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	... 15 more
09-13 11:18:31.633  3715  4416 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:18:31.633  3715  4416 E ExperimentLoader: 	... 17 more
,09-13 11:18:31.791   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 206649, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:18:32.210   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:33.493  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:33.501  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:33.503  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:33.503  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8e8ef2 removed from the list
,09-13 11:18:33.503  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:18:33.504  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:33.504  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:33.518  3957  4425 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 11:18:33.518  3957  4425 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 11:18:36.364  1522  1522 I ConfigService: onDestroy
,09-13 11:18:36.523  3957  4428 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 11:18:36.524  3957  4425 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 11:18:36.525  3957  4428 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 11:18:36.525  3957  4425 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 11:18:36.526  3957  4428 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 11:18:36.526  3957  4425 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 11:18:36.528  3957  4428 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 11:18:36.528  3957  4425 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 11:18:36.532  3957  4425 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 11:18:36.532  3957  4428 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 11:18:36.534  3957  4430 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: IncomingSocketThread/Sender)
09-13 11:18:36.536  3957  4431 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: OutgoingSocketThread/Sender)
,09-13 11:18:36.545  3957  4432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: IncomingSocketThread/Receiver)
,09-13 11:18:36.547  3957  4433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: OutgoingSocketThread/Receiver)
09-13 11:18:36.547  3957  4432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: IncomingSocketThread/Receiver)
,09-13 11:18:36.547  3957  4432 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 11:18:36.548  3957  4433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: OutgoingSocketThread/Receiver)
09-13 11:18:36.548  3957  4432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 11:18:36.548  3957  4433 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 11:18:36.548  3957  4433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 11:18:39.091   872  1313 D ConnectivityService: handlePromptUnvalidated 102
,09-13 11:18:39.524  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 11:18:39.526  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 11:18:39.534  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55192ee Bundle[{}]
09-13 11:18:39.535  3957  4008 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 11:18:39.535  3957  4008 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 11:18:39.535  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 11:18:39.536  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 11:18:39.536  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 11:18:39.537  3957  4008 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 11:18:39.541  3957  4008 I System.out: Running OutgoingSocketThread
,09-13 11:18:39.544  3957  4435 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 11:18:39.545  3957  4435 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 11:18:42.554  3957  4436 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 11:18:42.554  3957  4436 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 11:18:42.555  3957  4436 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 11:18:42.555  3957  4435 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 11:18:42.556  3957  4435 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 11:18:42.556  3957  4436 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 11:18:42.556  3957  4435 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 11:18:42.560  3957  4436 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 11:18:42.561  3957  4435 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 11:18:42.565  3957  4438 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: IncomingSocketThread/Sender)
,09-13 11:18:42.566  3957  4435 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 11:18:42.573  3957  4439 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: IncomingSocketThread/Receiver)
,09-13 11:18:42.574  3957  4439 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 473, thread name: IncomingSocketThread/Receiver)
,09-13 11:18:42.574  3957  4440 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: OutgoingSocketThread/Sender)
09-13 11:18:42.575  3957  4439 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 11:18:42.575  3957  4439 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 473, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 11:18:42.577  3957  4441 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 475, name: OutgoingSocketThread/Receiver)
09-13 11:18:42.578  3957  4441 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 475, thread name: OutgoingSocketThread/Receiver)
09-13 11:18:42.578  3957  4441 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 11:18:42.579  3957  4441 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 475, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 11:18:45.556  3957  4008 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 484)
,09-13 11:18:45.559  3957  4008 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 11:18:45.559  3957  4008 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 485)
,09-13 11:18:45.565  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:18:45.565  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6cc943 added. We now have 3 listener(s)
09-13 11:18:45.567  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:18:45.567  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:18:45.567  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:18:45.567  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:45.567  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c764bc0 added. We now have 4 listener(s)
09-13 11:18:45.567  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:18:45.569  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:18:45.571  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:45.583  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:45.586  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:45.586  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:18:45.587  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:18:45.588  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:18:45.588  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:18:45.588  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:45.588  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:18:45.588  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:18:45.588  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 11:18:45.589  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:45.588  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6cc943 removed from the list
09-13 11:18:45.590  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:45.591  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c764bc0 removed from the list
,09-13 11:18:45.591  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:45.591  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:18:45.592  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:45.593  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:45.593  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:45.595  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:45.596  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:45.596  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:45.596  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c764bc0 not in the list
,09-13 11:18:45.596  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:45.597  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:45.599  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:45.599  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:45.599  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:45.600  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c764bc0 not in the list
09-13 11:18:45.600  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:18:45.600  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:45.600  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:45.600  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6cc943 not in the list
09-13 11:18:45.602  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:18:45.603  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@972a83e added. We now have 3 listener(s)
,09-13 11:18:45.609  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:18:45.609  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:18:45.610  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:18:45.610  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:45.610  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308b69f added. We now have 4 listener(s)
,09-13 11:18:45.611  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:18:45.613  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:18:45.618  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:45.627  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:45.633  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:45.633  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:18:45.634  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:18:45.634  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:18:45.634  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:18:45.634  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:45.635  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:18:45.637  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:45.641  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:18:45.641  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:18:45.642  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:45.647  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:18:45.649  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:18:45.649  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:18:45.656  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:18:45.656  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:18:45.656  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:18:45.657  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:18:45.663  4343  4353 D BtGatt.GattService: registerClient() - UUID=8b85b36c-3a9e-474a-b55e-0a5cd9004de4
,09-13 11:18:45.665  4343  4359 D BtGatt.GattService: onClientRegistered() - UUID=8b85b36c-3a9e-474a-b55e-0a5cd9004de4, clientIf=5
,09-13 11:18:45.666  3957  3967 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:18:45.668  4343  4370 D BtGatt.GattService: start scan with filters
,09-13 11:18:45.676  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:18:45.676  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 11:18:45.676  4343  4362 D BtGatt.ScanManager: handling starting scan
09-13 11:18:45.676  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:18:45.676  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:18:45.679  4343  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a4b2ea2
,09-13 11:18:45.681  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:18:45.681  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:18:45.682  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:18:45.685  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:18:45.691  3957  4008 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 11:18:45.691  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:18:45.691  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 11:18:45.691  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:45.691  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 11:18:45.692  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:18:45.692  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 11:18:45.693  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:18:45.693  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:18:45.693  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:18:45.693  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:18:45.694  4343  4359 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-13 11:18:45.694  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:45.696  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:18:45.696  4343  4362 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 11:18:45.697  4343  4353 D BtGatt.GattService: stopScan() - queue size =1
,09-13 11:18:45.699  4343  4370 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:18:45.700  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:18:45.700  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:18:45.700  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 11:18:45.701  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:18:45.701  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 11:18:45.704  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:18:45.704  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 11:18:45.704  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:18:45.704  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:18:45.705  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:18:45.707  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:18:45.708  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:18:45.708  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:18:45.712  4343  4359 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:18:45.712  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:45.713  4343  4362 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:18:45.714  4343  4362 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:18:45.744  4343  4359 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:18:45.744  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:45.761  4343  4359 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:18:45.761  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:45.787  4343  4359 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
09-13 11:18:45.787  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:45.788  4343  4362 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:18:45.809  4343  4359 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
09-13 11:18:45.810  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-13 11:18:45.810  4343  4362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:18:45.830  4343  4359 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
09-13 11:18:45.830  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:46.209  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:18:46.210  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-13 11:18:46.210  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:18:48.709  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:18:48.710  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:18:48.710  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:18:48.710  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:48.711  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:48.711  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:18:48.711  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:18:48.711  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@972a83e removed from the list
09-13 11:18:48.712  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:48.712  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308b69f removed from the list
09-13 11:18:48.712  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:18:48.713  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:48.714  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:48.714  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:48.717  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:48.717  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:48.718  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:48.718  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308b69f not in the list
09-13 11:18:48.718  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:48.719  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:48.721  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:18:48.722  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:18:48.722  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:48.722  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308b69f not in the list
,09-13 11:18:48.723  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:18:48.723  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:48.723  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:48.723  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@972a83e not in the list
09-13 11:18:48.725  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:18:48.725  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@919d2d8 added. We now have 3 listener(s)
09-13 11:18:48.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:18:48.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:18:48.732  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:18:48.733  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:48.733  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cc631 added. We now have 4 listener(s)
,09-13 11:18:48.734  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:18:48.735  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:18:48.741  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:48.749  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:48.753  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:48.753  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:18:48.753  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 11:18:48.755  3957  4008 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 11:18:48.755  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1,
,09-13 11:18:48.755  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 11:18:48.755  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 11:18:48.756  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 11:18:48.756  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:18:48.756  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:48.757  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 11:18:48.759  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:18:48.759  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 11:18:48.759  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 11:18:48.760  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 11:18:48.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 11:18:48.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 11:18:48.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:18:48.761  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:18:48.763  3957  4442 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:18:48.766  3957  4442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 11:18:48.772  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:18:48.772  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:18:48.777  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:18:48.778  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 11:18:48.778  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:18:48.788  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 11:18:48.789  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:18:48.790  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-13 11:18:48.793  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 11:18:48.793  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 11:18:48.794  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 11:18:48.795  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:18:48.799  4343  4353 D BtGatt.GattService: registerClient() - UUID=e355e09e-1de4-4fca-b385-c6edff5152a7
,09-13 11:18:48.799  4343  4359 D BtGatt.GattService: onClientRegistered() - UUID=e355e09e-1de4-4fca-b385-c6edff5152a7, clientIf=5
09-13 11:18:48.800  3957  3969 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
09-13 11:18:48.801  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:48.804  4343  4361 D BtGatt.AdvertiseManager: message : 0
,09-13 11:18:48.806  4343  4361 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 11:18:48.808  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:48.810  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:18:48.817  4343  4359 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 11:18:48.825  4343  4359 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 11:18:48.827  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 11:18:48.828  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:18:48.832  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:18:48.834  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:18:48.834  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 11:18:48.834  3957  3957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 11:18:48.834  3957  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 11:18:48.834  3957  3957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 11:18:48.835  3957  3957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 11:18:48.835  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 11:18:48.835  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 11:18:48.835  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:18:48.835  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:18:48.837  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 11:18:48.840  3957  3957 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 11:18:48.840  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 11:18:48.856  3674  3674 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 11:18:48.856  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 11:18:48.856  3674  3674 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 11:18:49.340  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 11:18:49.341  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 11:18:49.341  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:18:51.839  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:18:51.839  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 11:18:51.840  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 11:18:51.840  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 11:18:51.840  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 11:18:51.841  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 11:18:51.841  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 11:18:51.842  3957  4008 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 11:18:51.842  3957  4442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 11:18:51.842  3957  4442 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 11:18:51.842  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:18:51.842  3957  3957 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 11:18:51.843  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:18:51.843  3957  4442 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 11:18:51.843  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:18:51.843  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:18:51.843  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:18:51.846  3957  4008 D BluetoothAdapter: STATE_ON
09-13 11:18:51.847  3957  4008 D BluetoothLeScanner: could not find callback wrapper
09-13 11:18:51.847  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:18:51.847  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 11:18:51.850  4343  4361 D BtGatt.AdvertiseManager: message : 1
09-13 11:18:51.851  4343  4361 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 11:18:51.862  4343  4359 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 11:18:51.862  4343  4359 D BtGatt.GattService: Client app is not null!
,09-13 11:18:51.865  4343  4370 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:18:51.866  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 11:18:51.867  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 11:18:51.867  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 11:18:51.867  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 11:18:51.867  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 11:18:51.869  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:18:51.870  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 11:18:51.870  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 11:18:51.870  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:18:51.872  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:18:51.872  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:51.872  3957  3957 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 11:18:51.872  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:18:51.872  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:18:51.872  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@919d2d8 removed from the list
09-13 11:18:51.872  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:18:51.872  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:51.872  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cc631 removed from the list
09-13 11:18:51.873  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:18:51.873  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:51.873  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:18:51.873  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:18:51.873  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:51.873  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:18:51.875  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:51.875  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:51.875  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:51.875  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cc631 not in the list
09-13 11:18:51.875  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:18:51.876  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:51.877  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:51.877  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:51.877  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:51.877  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94cc631 not in the list
09-13 11:18:51.877  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:51.877  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:51.877  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:51.877  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@919d2d8 not in the list
,09-13 11:18:51.878  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:18:51.879  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8498a2 added. We now have 3 listener(s)
09-13 11:18:51.881  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:18:51.881  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:18:51.881  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:18:51.881  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:51.882  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a428933 added. We now have 4 listener(s)
09-13 11:18:51.882  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:18:51.883  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:18:51.889  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:51.899  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:51.903  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:51.904  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:18:51.904  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:18:51.904  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:18:51.905  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:18:51.905  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:18:51.905  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:18:51.909  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:51.912  3957  4008 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:18:51.913  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:18:51.913  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:51.922  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:18:51.922  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 11:18:51.922  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:18:51.927  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:18:51.927  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:18:51.927  3957  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:18:51.928  3957  4008 D BluetoothAdapter: STATE_ON
,09-13 11:18:51.930  4343  4379 D BtGatt.GattService: registerClient() - UUID=9042b78d-e826-485c-9739-5524bae8ce83
,09-13 11:18:51.931  4343  4359 D BtGatt.GattService: onClientRegistered() - UUID=9042b78d-e826-485c-9739-5524bae8ce83, clientIf=5
,09-13 11:18:51.932  3957  3969 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 11:18:51.933  4343  4370 D BtGatt.GattService: start scan with filters
,09-13 11:18:51.938  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:18:51.938  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 11:18:51.938  4343  4362 D BtGatt.ScanManager: handling starting scan
,09-13 11:18:51.938  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:18:51.938  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:18:51.943  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:18:51.944  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 11:18:51.944  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:18:51.948  4343  4359 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:18:51.948  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 11:18:51.948  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:51.948  4343  4362 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:18:51.957  4343  4359 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 11:18:51.957  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:51.958  4343  4362 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:18:51.958  4343  4362 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:18:51.974  4343  4359 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 11:18:51.975  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:51.984  4343  4359 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:18:51.984  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:52.373  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:18:52.444  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 11:18:52.445  3957  3957 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:18:52.445  3957  3957 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 11:18:53.490  4343  4343 D BtGatt.ScanManager: awakened up at time 232431,
,09-13 11:18:53.492  4343  4362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:18:53.529  4343  4359 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 11:18:53.530  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:18:53.530  4343  4359 D BtGatt.GattService: current time is 232471859502
,09-13 11:18:53.531  4343  4359 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 99, 79, -122, 50, -86, 103, 1, -128, -53, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -95, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -92, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 11:18:53.532  4343  4359 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 11:18:53.533  4343  4359 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,09-13 11:18:53.533  4343  4359 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 11:18:53.533  4343  4359 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 11:18:53.534  4343  4359 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 11:18:53.537  3957  3957 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
09-13 11:18:53.538  3957  3957 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-13 11:18:54.961  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:18:54.961  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:18:54.962  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:18:54.962  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:54.963  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 11:18:54.963  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 11:18:54.964  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:18:54.964  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:18:54.964  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:18:54.965  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 11:18:54.966  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:18:54.968  3957  4008 D BluetoothAdapter: STATE_ON
09-13 11:18:54.970  4343  4379 D BtGatt.GattService: stopScan() - queue size =1
09-13 11:18:54.973  4343  4370 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:18:54.974  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:18:54.975  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:18:54.975  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:18:54.976  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:18:54.976  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 11:18:54.980  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:18:54.980  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 11:18:54.980  3957  4008 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:18:54.981  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:18:54.983  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:18:54.983  3957  4008 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 11:18:54.984  4343  4343 D BtGatt.ScanManager: awakened up at time 233925
,09-13 11:18:54.991  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:18:54.991  3957  3957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:18:54.992  3957  3957 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:18:54.993  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:18:54.993  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:54.993  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:18:54.994  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:18:54.994  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8498a2 removed from the list
,09-13 11:18:54.994  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:54.994  4343  4359 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 11:18:54.994  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a428933 removed from the list
,09-13 11:18:54.995  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:18:54.995  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:54.995  4343  4362 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:18:54.995  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:54.996  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:18:54.996  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:54.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:54.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:54.997  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:54.997  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a428933 not in the list
09-13 11:18:54.997  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:54.997  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:54.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:54.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:54.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:54.998  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a428933 not in the list
09-13 11:18:54.998  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:54.998  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:54.999  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:54.999  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8498a2 not in the list
09-13 11:18:54.999  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:18:55.000  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4ae425 added. We now have 3 listener(s)
09-13 11:18:55.001  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:18:55.001  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:18:55.002  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:18:55.002  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:18:55.002  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0499fa added. We now have 4 listener(s)
09-13 11:18:55.002  3957  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:18:55.003  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:18:55.004  4343  4359 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 11:18:55.004  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:55.005  4343  4362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 11:18:55.006  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:18:55.012  3957  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:18:55.014  3957  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:18:55.014  3957  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:18:55.015  3957  4008 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:18:55.016  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:18:55.016  3957  4008 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:18:55.016  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:55.016  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 11:18:55.017  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:18:55.017  3957  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:18:55.017  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:55.017  3957  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4ae425 removed from the list
09-13 11:18:55.017  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:18:55.017  3957  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0499fa removed from the list
09-13 11:18:55.019  3957  3957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:18:55.019  3957  4008 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:18:55.019  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:55.020  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:55.020  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:55.021  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:55.021  4343  4359 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-13 11:18:55.022  4343  4359 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:18:55.022  4343  4359 D BtGatt.GattService: current time is 233963536965
09-13 11:18:55.022  4343  4359 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 11:18:55.022  4343  4359 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 11:18:55.023  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:55.023  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:55.023  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0499fa not in the list
09-13 11:18:55.023  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:55.023  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:55.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:18:55.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:18:55.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:18:55.024  3957  4008 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0499fa not in the list
09-13 11:18:55.024  3957  4008 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:18:55.024  3957  4008 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:18:55.024  3957  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:18:55.024  3957  4008 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4ae425 not in the list
09-13 11:18:55.025  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 11:18:55.026  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 11:18:55.026  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation:, Should start/stop everything
09-13 11:18:55.026  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:18:55.026  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 11:18:55.026  3957  4008 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:18:55.493  3957  3957 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:18:57.041  3957  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: My test thread name)
,09-13 11:18:59.039  3957  4008 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 494
09-13 11:18:59.039  3957  4008 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 494, name: My test thread name)
,09-13 11:18:59.045  3957  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: My test thread name)
,09-13 11:18:59.046  3957  4444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 495, thread name: My test thread name)
,09-13 11:18:59.046  3957  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 495, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 11:18:59.050  3957  4008 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 11:18:59.059  3957  4445 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: My test thread name)
,09-13 11:18:59.060  3957  4445 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 499, thread name: My test thread name): Test exception.
09-13 11:18:59.060  3957  4445 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 11:18:59.069  3957  4008 I jxcore-log: Total number of executed tests:  82
09-13 11:18:59.069  3957  4008 I jxcore-log: 
,09-13 11:18:59.070  3957  4008 I jxcore-log: Number of passed tests:  82
09-13 11:18:59.070  3957  4008 I jxcore-log: 
09-13 11:18:59.071  3957  4008 I jxcore-log: Number of failed tests:  0
09-13 11:18:59.071  3957  4008 I jxcore-log: 
,09-13 11:18:59.072  3957  4008 I jxcore-log: Number of ignored tests:  0
09-13 11:18:59.072  3957  4008 I jxcore-log: 
,09-13 11:18:59.072  3957  4008 I jxcore-log: Total duration:  101336
09-13 11:18:59.072  3957  4008 I jxcore-log: 
,09-13 11:18:59.082  3957  4008 I jxcore-log: Unit Test app is loaded
09-13 11:18:59.082  3957  4008 I jxcore-log: 
,09-13 11:18:59.107  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.107  3957  4008 I jxcore-log: 
,09-13 11:18:59.110  3957  3957 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 11:18:59.115  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.115  3957  4008 I jxcore-log: 
,09-13 11:18:59.117  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.117  3957  4008 I jxcore-log: 
,09-13 11:18:59.118  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.118  3957  4008 I jxcore-log: 
09-13 11:18:59.119  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 11:18:59.119  3957  4008 I jxcore-log: 
,09-13 11:18:59.120  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.120  3957  4008 I jxcore-log: 
,09-13 11:18:59.123  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.123  3957  4008 I jxcore-log: 
,09-13 11:18:59.125  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.125  3957  4008 I jxcore-log: 
,09-13 11:18:59.126  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 11:18:59.126  3957  4008 I jxcore-log: 
,09-13 11:18:59.127  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.127  3957  4008 I jxcore-log: 
09-13 11:18:59.128  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.128  3957  4008 I jxcore-log: 
09-13 11:18:59.129  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.129  3957  4008 I jxcore-log: 
,09-13 11:18:59.130  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.130  3957  4008 I jxcore-log: 
09-13 11:18:59.131  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.131  3957  4008 I jxcore-log: 
,09-13 11:18:59.131  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.131  3957  4008 I jxcore-log: 
,09-13 11:18:59.133  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.133  3957  4008 I jxcore-log: 
09-13 11:18:59.134  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.134  3957  4008 I jxcore-log: 
,09-13 11:18:59.134  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.134  3957  4008 I jxcore-log: 
09-13 11:18:59.135  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.135  3957  4008 I jxcore-log: 
09-13 11:18:59.136  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.136  3957  4008 I jxcore-log: 
,09-13 11:18:59.137  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.137  3957  4008 I jxcore-log: 
09-13 11:18:59.138  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.138  3957  4008 I jxcore-log: 
,09-13 11:18:59.138  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.138  3957  4008 I jxcore-log: 
09-13 11:18:59.139  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.139  3957  4008 I jxcore-log: 
,09-13 11:18:59.140  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.140  3957  4008 I jxcore-log: 
09-13 11:18:59.141  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.141  3957  4008 I jxcore-log: 
09-13 11:18:59.142  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.142  3957  4008 I jxcore-log: 
,09-13 11:18:59.142  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.142  3957  4008 I jxcore-log: 
09-13 11:18:59.143  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.143  3957  4008 I jxcore-log: 
,09-13 11:18:59.144  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.144  3957  4008 I jxcore-log: 
09-13 11:18:59.145  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.145  3957  4008 I jxcore-log: 
,09-13 11:18:59.145  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.145  3957  4008 I jxcore-log: 
09-13 11:18:59.146  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.146  3957  4008 I jxcore-log: 
09-13 11:18:59.147  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.147  3957  4008 I jxcore-log: 
,09-13 11:18:59.148  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.148  3957  4008 I jxcore-log: 
09-13 11:18:59.148  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.148  3957  4008 I jxcore-log: 
,09-13 11:18:59.149  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.149  3957  4008 I jxcore-log: 
09-13 11:18:59.150  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:18:59.150  3957  4008 I jxcore-log: 
,09-13 11:18:59.151  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.151  3957  4008 I jxcore-log: 
09-13 11:18:59.151  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:18:59.151  3957  4008 I jxcore-log: 
,09-13 11:18:59.153  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.153  3957  4008 I jxcore-log: 
09-13 11:18:59.154  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.154  3957  4008 I jxcore-log: 
09-13 11:18:59.154  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.154  3957  4008 I jxcore-log: 
,09-13 11:18:59.155  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.155  3957  4008 I jxcore-log: 
09-13 11:18:59.155  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.155  3957  4008 I jxcore-log: 
09-13 11:18:59.156  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.156  3957  4008 I jxcore-log: 
09-13 11:18:59.156  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.156  3957  4008 I jxcore-log: 
,09-13 11:18:59.157  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 11:18:59.157  3957  4008 I jxcore-log: 
09-13 11:18:59.157  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.157  3957  4008 I jxcore-log: 
09-13 11:18:59.158  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.158  3957  4008 I jxcore-log: 
09-13 11:18:59.158  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 11:18:59.158  3957  4008 I jxcore-log: 
,09-13 11:18:59.159  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 11:18:59.159  3957  4008 I jxcore-log: 
09-13 11:18:59.160  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:18:59.160  3957  4008 I jxcore-log: 
,09-13 11:18:59.160  3957  4008 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:18:59.160  3957  4008 I jxcore-log: 
,09-13 11:18:59.165  3957  4008 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-13 11:18:59.165  3957  4008 I jxcore-log:   bluetooth: 'on',
09-13 11:18:59.165  3957  4008 I jxcore-log:   wifi: 'on',
09-13 11:18:59.165  3957  4008 I jxcore-log:   cellular: 'doNotCare',
09-13 11:18:59.165  3957  4008 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 11:18:59.165  3957  4008 I jxcore-log: 
,09-13 11:18:59.170  3957  4008 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-13 11:18:59.170  3957  4008 I jxcore-log:   bluetooth: 'on',
09-13 11:18:59.170  3957  4008 I jxcore-log:   wifi: 'on',
09-13 11:18:59.170  3957  4008 I jxcore-log:   cellular: 'doNotCare',
09-13 11:18:59.170  3957  4008 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 11:18:59.170  3957  4008 I jxcore-log: 
,09-13 11:18:59.171  3957  4008 I jxcore-log: My device name is: motorola-Nexus 6
09-13 11:18:59.171  3957  4008 I jxcore-log: 
09-13 11:18:59.171  3957  4008 I jxcore-log: Running for WIFI network type
09-13 11:18:59.171  3957  4008 I jxcore-log: 
,09-13 11:18:59.195  3957  4443 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 494, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 11:19:00.862   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=239803, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:19:01.619  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 11:19:01.619  3957  4008 I jxcore-log: 
,09-13 11:19:02.064  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 11:19:02.064  3957  4008 I jxcore-log: 
,09-13 11:19:02.097  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 11:19:02.097  3957  4008 I jxcore-log: 
,09-13 11:19:03.416  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:19:03.421  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:19:03.459  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:19:03.460  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:19:03.460  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:19:03.460  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:19:03.480  3715  4447 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:19:03.480  3715  4447 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:19:03.480  3715  4447 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	... 12 more
09-13 11:19:03.480  3715  4447 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at fal.a(PG:38)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:19:03.480  3715  4447 E HttpOperation: 	... 14 more
,09-13 11:19:03.521  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:19:03.521  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 11:19:03.521  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:19:03.521  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:19:03.521  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 11:19:03.521  3957  4008 I jxcore-log: 
,09-13 11:19:03.544  3715  4447 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:19:03.544  3715  4447 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at hec.a(PG:42)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at hee.a(PG:102)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at czr.a(PG:65)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at kka.a(PG:108)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:19:03.544  3715  4447 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	... 15 more
09-13 11:19:03.544  3715  4447 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:19:03.544  3715  4447 E HttpOperation: 	at fal.a(PG:38)
09-13 11:19:03.544  3715  4447 E HttpOperation: ,	at jdj.a(PG:4089)
09-13 11:19:03.544  3715  4447 E HttpOperation: 	... 17 more
,09-13 11:19:03.545  3715  4447 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:19:03.545  3715  4447 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at hec.a(PG:42)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	... 15 more
09-13 11:19:03.545  3715  4447 E ExperimentLoader: Caused by: faj: BadAuthentication,
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:19:03.545  3715  4447 E ExperimentLoader: 	... 17 more
,09-13 11:19:03.671   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 242058, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:19:03.789  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 11:19:03.789  3957  4008 I jxcore-log: 
,09-13 11:19:03.794  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 11:19:03.794  3957  4008 I jxcore-log: 
,09-13 11:19:03.800  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 11:19:03.800  3957  4008 I jxcore-log: 
,09-13 11:19:03.877  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 11:19:03.877  3957  4008 I jxcore-log: 
,09-13 11:19:03.898  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 11:19:03.898  3957  4008 I jxcore-log: 
,09-13 11:19:03.903  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 11:19:03.903  3957  4008 I jxcore-log: 
,09-13 11:19:04.829  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 11:19:04.829  3957  4008 I jxcore-log: 
,09-13 11:19:04.996  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 11:19:04.996  3957  4008 I jxcore-log: 
,09-13 11:19:05.328  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 11:19:05.328  3957  4008 I jxcore-log: 
,09-13 11:19:05.339  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 11:19:05.339  3957  4008 I jxcore-log: 
,09-13 11:19:05.346  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 11:19:05.346  3957  4008 I jxcore-log: 
,09-13 11:19:05.353  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 11:19:05.353  3957  4008 I jxcore-log: 
,09-13 11:19:05.393  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 11:19:05.393  3957  4008 I jxcore-log: 
,09-13 11:19:05.441  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 11:19:05.441  3957  4008 I jxcore-log: 
,09-13 11:19:05.448  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 11:19:05.448  3957  4008 I jxcore-log: 
,09-13 11:19:05.456  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 11:19:05.456  3957  4008 I jxcore-log: 
,09-13 11:19:05.476  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 11:19:05.476  3957  4008 I jxcore-log: 
,09-13 11:19:05.481  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 11:19:05.481  3957  4008 I jxcore-log: 
,09-13 11:19:05.487  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 11:19:05.487  3957  4008 I jxcore-log: 
,09-13 11:19:05.504  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 11:19:05.504  3957  4008 I jxcore-log: 
,09-13 11:19:05.530  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 11:19:05.530  3957  4008 I jxcore-log: 
,09-13 11:19:05.542  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 11:19:05.542  3957  4008 I jxcore-log: 
,09-13 11:19:05.556  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 11:19:05.556  3957  4008 I jxcore-log: 
,09-13 11:19:05.568  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 11:19:05.568  3957  4008 I jxcore-log: 
,09-13 11:19:05.584  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 11:19:05.584  3957  4008 I jxcore-log: 
,09-13 11:19:05.595  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 11:19:05.595  3957  4008 I jxcore-log: 
,09-13 11:19:05.601  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 11:19:05.601  3957  4008 I jxcore-log: 
,09-13 11:19:05.632  3957  4008 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 11:19:05.632  3957  4008 I jxcore-log: 
,09-13 11:19:05.644  3957  4008 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 11:19:05.645  3957  4008 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 11:19:05.645  3957  4008 I jxcore-log: 
,09-13 11:19:05.648  3957  4008 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 11:19:05.648  3957  4008 I jxcore-log: 
,09-13 11:19:05.648  3957  4008 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 11:19:05.648  3957  4008 I jxcore-log: 
,09-13 11:19:05.653  3957  4008 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 11:19:05.653  3957  4008 I jxcore-log: 
,09-13 11:19:05.779  3957  4008 I jxcore-log: ThaliTape :: Connected to the test server
09-13 11:19:05.779  3957  4008 I jxcore-log: 
,09-13 11:19:07.966  3957  4008 I jxcore-log: TAP version 13
09-13 11:19:07.966  3957  4008 I jxcore-log: 
,09-13 11:19:07.972  3957  4008 I jxcore-log: # setup
09-13 11:19:07.972  3957  4008 I jxcore-log: 
,09-13 11:19:08.241  3957  4008 I jxcore-log: # 1. calling createNativeListener directly rejects
09-13 11:19:08.241  3957  4008 I jxcore-log: 
,09-13 11:19:09.309  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:09.309  3957  4008 I jxcore-log: 
,09-13 11:19:09.312  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 37108
09-13 11:19:09.312  3957  4008 I jxcore-log: 
,09-13 11:19:09.319  3957  4008 I jxcore-log: ok 1 Should throw
09-13 11:19:09.319  3957  4008 I jxcore-log: 
,09-13 11:19:09.321  3957  4008 I jxcore-log: # teardown
09-13 11:19:09.321  3957  4008 I jxcore-log: 
,09-13 11:19:09.561  3957  4008 I jxcore-log: # setup
09-13 11:19:09.561  3957  4008 I jxcore-log: 
,09-13 11:19:09.707  3957  4008 I jxcore-log: # 2. emits incomingConnectionState
09-13 11:19:09.707  3957  4008 I jxcore-log: 
,09-13 11:19:09.861  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:09.861  3957  4008 I jxcore-log: 
,09-13 11:19:09.865  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 48162
09-13 11:19:09.865  3957  4008 I jxcore-log: 
,09-13 11:19:09.874  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:09.874  3957  4008 I jxcore-log: 
,09-13 11:19:09.877  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:09.877  3957  4008 I jxcore-log: 
,09-13 11:19:09.887  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:09.887  3957  4008 I jxcore-log: 
,09-13 11:19:09.894  3957  4008 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-13 11:19:09.894  3957  4008 I jxcore-log: 
,09-13 11:19:09.915  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:09.915  3957  4008 I jxcore-log: 
,09-13 11:19:09.916  3957  4008 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-13 11:19:09.916  3957  4008 I jxcore-log: 
,09-13 11:19:09.923  3957  4008 I jxcore-log: # teardown
09-13 11:19:09.923  3957  4008 I jxcore-log: 
,09-13 11:19:10.020  3957  4008 I jxcore-log: # setup
,09-13 11:19:10.020  3957  4008 I jxcore-log: 
,09-13 11:19:10.113  3957  4008 I jxcore-log: # 3. emits routerPortConnectionFailed
09-13 11:19:10.113  3957  4008 I jxcore-log: 
,09-13 11:19:10.257  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:10.257  3957  4008 I jxcore-log: 
,09-13 11:19:10.260  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 44382
09-13 11:19:10.260  3957  4008 I jxcore-log: 
,09-13 11:19:10.266  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:10.266  3957  4008 I jxcore-log: 
,09-13 11:19:10.268  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:10.268  3957  4008 I jxcore-log: 
,09-13 11:19:10.269  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:10.269  3957  4008 I jxcore-log: 
,09-13 11:19:10.299  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:10.299  3957  4008 I jxcore-log: 
,09-13 11:19:10.301  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:10.301  3957  4008 I jxcore-log: 
,09-13 11:19:10.306  3957  4008 I jxcore-log: DEBUG createNativeListener: 
09-13 11:19:10.306  3957  4008 I jxcore-log: 
,09-13 11:19:10.307  3957  4008 I jxcore-log: ok 4 tried to connect to right port
09-13 11:19:10.307  3957  4008 I jxcore-log: 
09-13 11:19:10.307  3957  4008 I jxcore-log: ok 5 failed due to refused connection
09-13 11:19:10.307  3957  4008 I jxcore-log: 
,09-13 11:19:10.308  3957  4008 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-13 11:19:10.308  3957  4008 I jxcore-log: 
,09-13 11:19:10.310  3957  4008 I jxcore-log: # teardown
09-13 11:19:10.310  3957  4008 I jxcore-log: 
,09-13 11:19:10.312  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:10.312  3957  4008 I jxcore-log: 
,09-13 11:19:10.418  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:10.418  3957  4008 I jxcore-log: 
,09-13 11:19:10.424  3957  4008 I jxcore-log: # setup
09-13 11:19:10.424  3957  4008 I jxcore-log: 
,09-13 11:19:10.425  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:10.425  3957  4008 I jxcore-log: 
,09-13 11:19:10.561  3957  4008 I jxcore-log: # 4. native server connections all up
09-13 11:19:10.561  3957  4008 I jxcore-log: 
,09-13 11:19:10.643  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:10.643  3957  4008 I jxcore-log: 
,09-13 11:19:10.652  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 41326
09-13 11:19:10.652  3957  4008 I jxcore-log: 
,09-13 11:19:10.665  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:10.665  3957  4008 I jxcore-log: 
,09-13 11:19:10.666  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:10.666  3957  4008 I jxcore-log: 
,09-13 11:19:10.668  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:10.668  3957  4008 I jxcore-log: 
,09-13 11:19:10.700  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:10.700  3957  4008 I jxcore-log: 
,09-13 11:19:10.704  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:10.704  3957  4008 I jxcore-log: 
,09-13 11:19:10.707  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:10.707  3957  4008 I jxcore-log: 
,09-13 11:19:10.709  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:10.709  3957  4008 I jxcore-log: 
,09-13 11:19:10.709   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=249650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:19:10.729  3957  4008 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-13 11:19:10.729  3957  4008 I jxcore-log: 
,09-13 11:19:10.730  3957  4008 I jxcore-log: ok 8 Send/recvd #1 should be same
09-13 11:19:10.730  3957  4008 I jxcore-log: 
,09-13 11:19:10.732  3957  4008 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-13 11:19:10.732  3957  4008 I jxcore-log: 
,09-13 11:19:10.732  3957  4008 I jxcore-log: ok 10 Send/recvd #2 should be same
09-13 11:19:10.732  3957  4008 I jxcore-log: 
,09-13 11:19:10.734  3957  4008 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-13 11:19:10.734  3957  4008 I jxcore-log: 
,09-13 11:19:10.740  3957  4008 I jxcore-log: # teardown
09-13 11:19:10.740  3957  4008 I jxcore-log: 
,09-13 11:19:10.852  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:10.852  3957  4008 I jxcore-log: 
,09-13 11:19:10.854  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:10.854  3957  4008 I jxcore-log: 
,09-13 11:19:10.856  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:10.856  3957  4008 I jxcore-log: 
,09-13 11:19:10.858  3957  4008 I jxcore-log: # setup
09-13 11:19:10.858  3957  4008 I jxcore-log: 
,09-13 11:19:10.859  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:10.859  3957  4008 I jxcore-log: 
,09-13 11:19:10.959  3957  4008 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-13 11:19:10.959  3957  4008 I jxcore-log: 
,09-13 11:19:11.080  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:11.080  3957  4008 I jxcore-log: 
,09-13 11:19:11.087  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 47227
09-13 11:19:11.087  3957  4008 I jxcore-log: 
,09-13 11:19:11.100  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:11.100  3957  4008 I jxcore-log: 
,09-13 11:19:11.102  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:11.102  3957  4008 I jxcore-log: 
,09-13 11:19:11.103  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:11.103  3957  4008 I jxcore-log: 
,09-13 11:19:11.119  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:11.119  3957  4008 I jxcore-log: 
,09-13 11:19:11.122  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:11.122  3957  4008 I jxcore-log: 
,09-13 11:19:11.134  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:11.134  3957  4008 I jxcore-log: 
,09-13 11:19:11.148  3957  4008 I jxcore-log: ok 12 socket shouldn't close until after stream
09-13 11:19:11.148  3957  4008 I jxcore-log: 
,09-13 11:19:11.148  3957  4008 I jxcore-log: ok 13 incoming remains open
09-13 11:19:11.148  3957  4008 I jxcore-log: 
,09-13 11:19:11.151  3957  4008 I jxcore-log: # teardown
09-13 11:19:11.151  3957  4008 I jxcore-log: 
,09-13 11:19:11.237  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:11.237  3957  4008 I jxcore-log: 
,09-13 11:19:11.244  3957  4008 I jxcore-log: # setup
09-13 11:19:11.244  3957  4008 I jxcore-log: 
,09-13 11:19:11.246  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:11.246  3957  4008 I jxcore-log: 
,09-13 11:19:11.343  3957  4008 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-13 11:19:11.343  3957  4008 I jxcore-log: 
,09-13 11:19:11.439  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:11.439  3957  4008 I jxcore-log: 
,09-13 11:19:11.446  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 42472
09-13 11:19:11.446  3957  4008 I jxcore-log: 
,09-13 11:19:11.458  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:11.458  3957  4008 I jxcore-log: 
,09-13 11:19:11.461  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:11.461  3957  4008 I jxcore-log: 
,09-13 11:19:11.462  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:11.462  3957  4008 I jxcore-log: 
,09-13 11:19:11.478  3957  4008 I jxcore-log: ok 14 we should not have gotten an error
09-13 11:19:11.478  3957  4008 I jxcore-log: 
,09-13 11:19:11.487  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:11.487  3957  4008 I jxcore-log: 
,09-13 11:19:11.492  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:11.492  3957  4008 I jxcore-log: 
,09-13 11:19:11.503  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:11.503  3957  4008 I jxcore-log: 
,09-13 11:19:11.505  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:11.505  3957  4008 I jxcore-log: 
,09-13 11:19:11.513  3957  4008 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-13 11:19:11.513  3957  4008 I jxcore-log: 
,09-13 11:19:11.513  3957  4008 I jxcore-log: ok 16 incoming is cleaned up
09-13 11:19:11.513  3957  4008 I jxcore-log: 
,09-13 11:19:11.517  3957  4008 I jxcore-log: # teardown
09-13 11:19:11.517  3957  4008 I jxcore-log: 
,09-13 11:19:11.633  3957  4008 I jxcore-log: # setup
09-13 11:19:11.633  3957  4008 I jxcore-log: 
,09-13 11:19:11.717  3957  4008 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-13 11:19:11.717  3957  4008 I jxcore-log: 
,09-13 11:19:11.817  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:11.817  3957  4008 I jxcore-log: 
,09-13 11:19:11.824  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 42329
09-13 11:19:11.824  3957  4008 I jxcore-log: 
,09-13 11:19:11.836  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:11.836  3957  4008 I jxcore-log: 
,09-13 11:19:11.840  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:11.840  3957  4008 I jxcore-log: 
,09-13 11:19:11.843  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:11.843  3957  4008 I jxcore-log: 
,09-13 11:19:11.858  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:11.858  3957  4008 I jxcore-log: 
,09-13 11:19:11.860  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:11.860  3957  4008 I jxcore-log: 
,09-13 11:19:11.875  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:11.875  3957  4008 I jxcore-log: 
,09-13 11:19:11.891  3957  4008 I jxcore-log: ok 17 stream was closed
09-13 11:19:11.891  3957  4008 I jxcore-log: 
,09-13 11:19:11.891  3957  4008 I jxcore-log: ok 18 incoming should survive
09-13 11:19:11.891  3957  4008 I jxcore-log: 
09-13 11:19:11.891  3957  4008 I jxcore-log: ok 19 mux should have no streams
09-13 11:19:11.891  3957  4008 I jxcore-log: 
,09-13 11:19:11.896  3957  4008 I jxcore-log: # teardown
09-13 11:19:11.896  3957  4008 I jxcore-log: 
,09-13 11:19:12.261  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:12.261  3957  4008 I jxcore-log: 
,09-13 11:19:12.266  3957  4008 I jxcore-log: # setup
09-13 11:19:12.266  3957  4008 I jxcore-log: 
,09-13 11:19:12.268  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:12.268  3957  4008 I jxcore-log: 
,09-13 11:19:12.327  3957  4008 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-13 11:19:12.327  3957  4008 I jxcore-log: 
,09-13 11:19:12.433  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:12.433  3957  4008 I jxcore-log: 
,09-13 11:19:12.440  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 37750
09-13 11:19:12.440  3957  4008 I jxcore-log: 
,09-13 11:19:12.447  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.447  3957  4008 I jxcore-log: 
,09-13 11:19:12.448  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.448  3957  4008 I jxcore-log: 
,09-13 11:19:12.450  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.450  3957  4008 I jxcore-log: 
,09-13 11:19:12.459  3957  4008 I jxcore-log: ok 20 we should not have gotten an error
09-13 11:19:12.459  3957  4008 I jxcore-log: 
,09-13 11:19:12.473  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:12.473  3957  4008 I jxcore-log: 
,09-13 11:19:12.476  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:12.476  3957  4008 I jxcore-log: 
,09-13 11:19:12.486  3957  4008 I jxcore-log: ok 21 Buffers are identical
09-13 11:19:12.486  3957  4008 I jxcore-log: 
,09-13 11:19:12.488  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:12.488  3957  4008 I jxcore-log: 
,09-13 11:19:12.490  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:12.490  3957  4008 I jxcore-log: 
,09-13 11:19:12.492  3957  4008 I jxcore-log: ok 22 native server is nulled out
09-13 11:19:12.492  3957  4008 I jxcore-log: 
09-13 11:19:12.493  3957  4008 I jxcore-log: ok 23 native server should be closed
09-13 11:19:12.493  3957  4008 I jxcore-log: 
09-13 11:19:12.493  3957  4008 I jxcore-log: ok 24 incoming has been removed
09-13 11:19:12.493  3957  4008 I jxcore-log: 
09-13 11:19:12.493  3957  4008 I jxcore-log: ok 25 Incoming should be done
09-13 11:19:12.493  3957  4008 I jxcore-log: 
,09-13 11:19:12.494  3957  4008 I jxcore-log: ok 26 The mux object should be closed
09-13 11:19:12.494  3957  4008 I jxcore-log: 
09-13 11:19:12.494  3957  4008 I jxcore-log: ok 27 The mux stream should be closed
09-13 11:19:12.494  3957  4008 I jxcore-log: 
09-13 11:19:12.495  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:12.495  3957  4008 I jxcore-log: 
,09-13 11:19:12.507  3957  4008 I jxcore-log: # teardown
09-13 11:19:12.507  3957  4008 I jxcore-log: 
,09-13 11:19:12.644  3957  4008 I jxcore-log: # setup
09-13 11:19:12.644  3957  4008 I jxcore-log: 
,09-13 11:19:12.709  3957  4008 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-13 11:19:12.709  3957  4008 I jxcore-log: 
,09-13 11:19:12.830  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:12.830  3957  4008 I jxcore-log: 
,09-13 11:19:12.840  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 46737
09-13 11:19:12.840  3957  4008 I jxcore-log: 
,09-13 11:19:12.861  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.861  3957  4008 I jxcore-log: 
,09-13 11:19:12.862  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.862  3957  4008 I jxcore-log: 
09-13 11:19:12.864  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.864  3957  4008 I jxcore-log: 
,09-13 11:19:12.867  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.867  3957  4008 I jxcore-log: 
,09-13 11:19:12.868  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.868  3957  4008 I jxcore-log: 
09-13 11:19:12.869  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.869  3957  4008 I jxcore-log: 
,09-13 11:19:12.872  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.872  3957  4008 I jxcore-log: 
,09-13 11:19:12.873  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.873  3957  4008 I jxcore-log: 
09-13 11:19:12.874  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.874  3957  4008 I jxcore-log: 
,09-13 11:19:12.878  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.878  3957  4008 I jxcore-log: 
,09-13 11:19:12.880  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.880  3957  4008 I jxcore-log: 
,09-13 11:19:12.881  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.881  3957  4008 I jxcore-log: 
,09-13 11:19:12.883  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.883  3957  4008 I jxcore-log: 
,09-13 11:19:12.884  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.884  3957  4008 I jxcore-log: 
09-13 11:19:12.885  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.885  3957  4008 I jxcore-log: 
,09-13 11:19:12.887  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.887  3957  4008 I jxcore-log: 
09-13 11:19:12.887  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.887  3957  4008 I jxcore-log: 
09-13 11:19:12.888  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.888  3957  4008 I jxcore-log: 
,09-13 11:19:12.894  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.894  3957  4008 I jxcore-log: 
,09-13 11:19:12.895  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.895  3957  4008 I jxcore-log: 
,09-13 11:19:12.897  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.897  3957  4008 I jxcore-log: 
,09-13 11:19:12.901  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.901  3957  4008 I jxcore-log: 
,09-13 11:19:12.901  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.901  3957  4008 I jxcore-log: 
09-13 11:19:12.902  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.902  3957  4008 I jxcore-log: 
,09-13 11:19:12.905  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.905  3957  4008 I jxcore-log: 
09-13 11:19:12.905  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.905  3957  4008 I jxcore-log: 
,09-13 11:19:12.906  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.906  3957  4008 I jxcore-log: 
,09-13 11:19:12.908  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:12.908  3957  4008 I jxcore-log: 
09-13 11:19:12.908  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:12.908  3957  4008 I jxcore-log: 
09-13 11:19:12.909  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:12.909  3957  4008 I jxcore-log: 
,09-13 11:19:12.995  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:12.995  3957  4008 I jxcore-log: 
,09-13 11:19:12.997  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:12.997  3957  4008 I jxcore-log: 
,09-13 11:19:13.000  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.000  3957  4008 I jxcore-log: 
,09-13 11:19:13.001  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.001  3957  4008 I jxcore-log: 
,09-13 11:19:13.004  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.004  3957  4008 I jxcore-log: 
,09-13 11:19:13.006  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.006  3957  4008 I jxcore-log: 
,09-13 11:19:13.008  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.008  3957  4008 I jxcore-log: 
,09-13 11:19:13.010  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.010  3957  4008 I jxcore-log: 
,09-13 11:19:13.013  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.013  3957  4008 I jxcore-log: 
,09-13 11:19:13.014  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.014  3957  4008 I jxcore-log: 
,09-13 11:19:13.016  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.016  3957  4008 I jxcore-log: 
,09-13 11:19:13.017  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.017  3957  4008 I jxcore-log: 
09-13 11:19:13.018  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.018  3957  4008 I jxcore-log: 
,09-13 11:19:13.020  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.020  3957  4008 I jxcore-log: 
,09-13 11:19:13.024  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.024  3957  4008 I jxcore-log: 
,09-13 11:19:13.026  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.026  3957  4008 I jxcore-log: 
,09-13 11:19:13.029  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.029  3957  4008 I jxcore-log: 
,09-13 11:19:13.030  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.030  3957  4008 I jxcore-log: 
,09-13 11:19:13.031  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.031  3957  4008 I jxcore-log: 
,09-13 11:19:13.033  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.033  3957  4008 I jxcore-log: 
09-13 11:19:13.034  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.034  3957  4008 I jxcore-log: 
,09-13 11:19:13.035  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.035  3957  4008 I jxcore-log: 
,09-13 11:19:13.036  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.036  3957  4008 I jxcore-log: 
,09-13 11:19:13.038  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.038  3957  4008 I jxcore-log: 
,09-13 11:19:13.040  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.040  3957  4008 I jxcore-log: 
,09-13 11:19:13.041  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.041  3957  4008 I jxcore-log: 
09-13 11:19:13.042  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.042  3957  4008 I jxcore-log: 
,09-13 11:19:13.044  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.044  3957  4008 I jxcore-log: 
,09-13 11:19:13.045  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.045  3957  4008 I jxcore-log: 
09-13 11:19:13.046  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.046  3957  4008 I jxcore-log: 
,09-13 11:19:13.047  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.047  3957  4008 I jxcore-log: 
,09-13 11:19:13.049  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.049  3957  4008 I jxcore-log: 
,09-13 11:19:13.050  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.050  3957  4008 I jxcore-log: 
,09-13 11:19:13.052  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.052  3957  4008 I jxcore-log: 
09-13 11:19:13.053  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.053  3957  4008 I jxcore-log: 
,09-13 11:19:13.054  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.054  3957  4008 I jxcore-log: 
,09-13 11:19:13.056  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.056  3957  4008 I jxcore-log: 
,09-13 11:19:13.063  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.063  3957  4008 I jxcore-log: 
,09-13 11:19:13.065  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.065  3957  4008 I jxcore-log: 
,09-13 11:19:13.066  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.066  3957  4008 I jxcore-log: 
,09-13 11:19:13.069  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.069  3957  4008 I jxcore-log: 
,09-13 11:19:13.070  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.070  3957  4008 I jxcore-log: 
,09-13 11:19:13.071  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.071  3957  4008 I jxcore-log: 
,09-13 11:19:13.073  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.073  3957  4008 I jxcore-log: 
09-13 11:19:13.074  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.074  3957  4008 I jxcore-log: 
,09-13 11:19:13.075  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.075  3957  4008 I jxcore-log: 
,09-13 11:19:13.076  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.076  3957  4008 I jxcore-log: 
09-13 11:19:13.078  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.078  3957  4008 I jxcore-log: 
,09-13 11:19:13.079  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.079  3957  4008 I jxcore-log: 
,09-13 11:19:13.081  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.081  3957  4008 I jxcore-log: 
,09-13 11:19:13.082  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.082  3957  4008 I jxcore-log: 
,09-13 11:19:13.083  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.083  3957  4008 I jxcore-log: 
09-13 11:19:13.084  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.084  3957  4008 I jxcore-log: 
,09-13 11:19:13.086  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.086  3957  4008 I jxcore-log: 
,09-13 11:19:13.087  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.087  3957  4008 I jxcore-log: 
09-13 11:19:13.088  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.088  3957  4008 I jxcore-log: 
,09-13 11:19:13.090  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.090  3957  4008 I jxcore-log: 
,09-13 11:19:13.091  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.091  3957  4008 I jxcore-log: 
,09-13 11:19:13.093  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.093  3957  4008 I jxcore-log: 
09-13 11:19:13.094  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.094  3957  4008 I jxcore-log: 
09-13 11:19:13.095  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.095  3957  4008 I jxcore-log: 
,09-13 11:19:13.096  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.096  3957  4008 I jxcore-log: 
,09-13 11:19:13.097  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.097  3957  4008 I jxcore-log: 
09-13 11:19:13.099  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.099  3957  4008 I jxcore-log: 
,09-13 11:19:13.101  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.101  3957  4008 I jxcore-log: 
,09-13 11:19:13.102  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.102  3957  4008 I jxcore-log: 
09-13 11:19:13.103  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.103  3957  4008 I jxcore-log: 
,09-13 11:19:13.105  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.105  3957  4008 I jxcore-log: 
,09-13 11:19:13.106  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.106  3957  4008 I jxcore-log: 
09-13 11:19:13.107  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.107  3957  4008 I jxcore-log: 
,09-13 11:19:13.108  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.108  3957  4008 I jxcore-log: 
,09-13 11:19:13.109  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.109  3957  4008 I jxcore-log: 
,09-13 11:19:13.111  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.111  3957  4008 I jxcore-log: 
09-13 11:19:13.113  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.113  3957  4008 I jxcore-log: 
,09-13 11:19:13.114  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.114  3957  4008 I jxcore-log: 
09-13 11:19:13.115  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.115  3957  4008 I jxcore-log: 
,09-13 11:19:13.116  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.116  3957  4008 I jxcore-log: 
,09-13 11:19:13.118  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.118  3957  4008 I jxcore-log: 
09-13 11:19:13.119  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:13.119  3957  4008 I jxcore-log: 
,09-13 11:19:13.120  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:13.120  3957  4008 I jxcore-log: 
,09-13 11:19:13.197  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.197  3957  4008 I jxcore-log: 
,09-13 11:19:13.200  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.200  3957  4008 I jxcore-log: 
,09-13 11:19:13.201  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.201  3957  4008 I jxcore-log: 
,09-13 11:19:13.202  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.202  3957  4008 I jxcore-log: 
,09-13 11:19:13.204  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.204  3957  4008 I jxcore-log: 
,09-13 11:19:13.205  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.205  3957  4008 I jxcore-log: 
09-13 11:19:13.206  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.206  3957  4008 I jxcore-log: 
,09-13 11:19:13.207  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.207  3957  4008 I jxcore-log: 
,09-13 11:19:13.208  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.208  3957  4008 I jxcore-log: 
09-13 11:19:13.209  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.209  3957  4008 I jxcore-log: 
,09-13 11:19:13.210  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.210  3957  4008 I jxcore-log: 
,09-13 11:19:13.213  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.213  3957  4008 I jxcore-log: 
,09-13 11:19:13.215  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.215  3957  4008 I jxcore-log: 
,09-13 11:19:13.216  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.216  3957  4008 I jxcore-log: 
,09-13 11:19:13.217  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.217  3957  4008 I jxcore-log: 
,09-13 11:19:13.223  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.223  3957  4008 I jxcore-log: 
,09-13 11:19:13.225  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.225  3957  4008 I jxcore-log: 
,09-13 11:19:13.226  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.226  3957  4008 I jxcore-log: 
,09-13 11:19:13.227  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.227  3957  4008 I jxcore-log: 
09-13 11:19:13.228  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.228  3957  4008 I jxcore-log: 
,09-13 11:19:13.229  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.229  3957  4008 I jxcore-log: 
,09-13 11:19:13.230  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.230  3957  4008 I jxcore-log: 
09-13 11:19:13.231  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.231  3957  4008 I jxcore-log: 
09-13 11:19:13.232  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.232  3957  4008 I jxcore-log: 
,09-13 11:19:13.233  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.233  3957  4008 I jxcore-log: 
,09-13 11:19:13.234  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.234  3957  4008 I jxcore-log: 
09-13 11:19:13.235  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.235  3957  4008 I jxcore-log: 
,09-13 11:19:13.236  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.236  3957  4008 I jxcore-log: 
09-13 11:19:13.237  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.237  3957  4008 I jxcore-log: 
,09-13 11:19:13.238  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.238  3957  4008 I jxcore-log: 
,09-13 11:19:13.239  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.239  3957  4008 I jxcore-log: 
09-13 11:19:13.240  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.240  3957  4008 I jxcore-log: 
,09-13 11:19:13.240  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.240  3957  4008 I jxcore-log: 
09-13 11:19:13.241  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.241  3957  4008 I jxcore-log: 
,09-13 11:19:13.242  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.242  3957  4008 I jxcore-log: 
,09-13 11:19:13.243  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.243  3957  4008 I jxcore-log: 
09-13 11:19:13.244  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.244  3957  4008 I jxcore-log: 
,09-13 11:19:13.245  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.245  3957  4008 I jxcore-log: 
09-13 11:19:13.246  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.246  3957  4008 I jxcore-log: 
,09-13 11:19:13.246  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.246  3957  4008 I jxcore-log: 
09-13 11:19:13.247  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.247  3957  4008 I jxcore-log: 
,09-13 11:19:13.248  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.248  3957  4008 I jxcore-log: 
09-13 11:19:13.249  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.249  3957  4008 I jxcore-log: 
,09-13 11:19:13.250  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.250  3957  4008 I jxcore-log: 
09-13 11:19:13.251  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.251  3957  4008 I jxcore-log: 
,09-13 11:19:13.252  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.252  3957  4008 I jxcore-log: 
09-13 11:19:13.252  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.252  3957  4008 I jxcore-log: 
,09-13 11:19:13.253  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.253  3957  4008 I jxcore-log: 
09-13 11:19:13.254  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:13.254  3957  4008 I jxcore-log: 
,09-13 11:19:13.255  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:13.255  3957  4008 I jxcore-log: 
,09-13 11:19:13.258  3957  4008 I jxcore-log: ok 28 native server is nulled out
09-13 11:19:13.258  3957  4008 I jxcore-log: 
,09-13 11:19:13.259  3957  4008 I jxcore-log: ok 29 native server should be closed
09-13 11:19:13.259  3957  4008 I jxcore-log: 
09-13 11:19:13.259  3957  4008 I jxcore-log: ok 30 incoming has been removed
09-13 11:19:13.259  3957  4008 I jxcore-log: 
09-13 11:19:13.260  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.260  3957  4008 I jxcore-log: 
,09-13 11:19:13.261  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.261  3957  4008 I jxcore-log: 
09-13 11:19:13.262  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.262  3957  4008 I jxcore-log: 
,09-13 11:19:13.262  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.262  3957  4008 I jxcore-log: 
09-13 11:19:13.263  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.263  3957  4008 I jxcore-log: 
,09-13 11:19:13.263  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.263  3957  4008 I jxcore-log: 
09-13 11:19:13.263  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.263  3957  4008 I jxcore-log: 
09-13 11:19:13.264  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.264  3957  4008 I jxcore-log: 
,09-13 11:19:13.264  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.264  3957  4008 I jxcore-log: 
09-13 11:19:13.264  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:13.264  3957  4008 I jxcore-log: 
,09-13 11:19:13.374  3957  4008 I jxcore-log: # teardown
09-13 11:19:13.374  3957  4008 I jxcore-log: 
,09-13 11:19:13.557  3957  4008 I jxcore-log: # setup
09-13 11:19:13.557  3957  4008 I jxcore-log: 
,09-13 11:19:14.211  3957  4008 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-13 11:19:14.211  3957  4008 I jxcore-log: 
,09-13 11:19:14.817  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:14.817  3957  4008 I jxcore-log: 
,09-13 11:19:14.820  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 46841
09-13 11:19:14.820  3957  4008 I jxcore-log: 
,09-13 11:19:14.826  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:14.826  3957  4008 I jxcore-log: 
,09-13 11:19:14.827  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:14.827  3957  4008 I jxcore-log: 
,09-13 11:19:14.828  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:14.828  3957  4008 I jxcore-log: 
,09-13 11:19:14.836  3957  4008 I jxcore-log: ok 31 we should not have gotten an error
09-13 11:19:14.836  3957  4008 I jxcore-log: 
,09-13 11:19:14.846  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:14.846  3957  4008 I jxcore-log: 
,09-13 11:19:14.849  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:14.849  3957  4008 I jxcore-log: 
,09-13 11:19:14.857  3957  4008 I jxcore-log: ok 32 Buffers are identical
09-13 11:19:14.857  3957  4008 I jxcore-log: 
,09-13 11:19:14.858  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:14.858  3957  4008 I jxcore-log: 
,09-13 11:19:14.859  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:14.859  3957  4008 I jxcore-log: 
,09-13 11:19:14.870  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:14.870  3957  4008 I jxcore-log: 
,09-13 11:19:14.870  3957  4008 I jxcore-log: ok 33 server should be fine
09-13 11:19:14.870  3957  4008 I jxcore-log: 
09-13 11:19:14.871  3957  4008 I jxcore-log: ok 34 server should be open
09-13 11:19:14.871  3957  4008 I jxcore-log: 
,09-13 11:19:14.871  3957  4008 I jxcore-log: ok 35 incoming has been removed
09-13 11:19:14.871  3957  4008 I jxcore-log: 
09-13 11:19:14.872  3957  4008 I jxcore-log: ok 36 The mux object should be closed
09-13 11:19:14.872  3957  4008 I jxcore-log: 
09-13 11:19:14.872  3957  4008 I jxcore-log: ok 37 The mux stream should be closed
09-13 11:19:14.872  3957  4008 I jxcore-log: 
,09-13 11:19:14.876  3957  4008 I jxcore-log: # teardown
09-13 11:19:14.876  3957  4008 I jxcore-log: 
,09-13 11:19:15.843  3957  4008 I jxcore-log: # setup
09-13 11:19:15.843  3957  4008 I jxcore-log: 
,09-13 11:19:17.084  3957  4008 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-13 11:19:17.084  3957  4008 I jxcore-log: 
,09-13 11:19:17.147  3957  4008 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 11:19:17.147  3957  4008 I jxcore-log: 
,09-13 11:19:17.152  3957  4008 I jxcore-log: DEBUG createNativeListener: listening 38770
09-13 11:19:17.152  3957  4008 I jxcore-log: 
,09-13 11:19:17.161  3957  4008 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 11:19:17.161  3957  4008 I jxcore-log: 
,09-13 11:19:17.163  3957  4008 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 11:19:17.163  3957  4008 I jxcore-log: 
,09-13 11:19:17.165  3957  4008 I jxcore-log: DEBUG createNativeListener: new mux
09-13 11:19:17.165  3957  4008 I jxcore-log: 
,09-13 11:19:17.176  3957  4008 I jxcore-log: ok 38 we should not have gotten an error
09-13 11:19:17.176  3957  4008 I jxcore-log: 
,09-13 11:19:17.183  3957  4008 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 11:19:17.183  3957  4008 I jxcore-log: 
,09-13 11:19:17.185  3957  4008 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 11:19:17.185  3957  4008 I jxcore-log: 
,09-13 11:19:17.192  3957  4008 I jxcore-log: ok 39 Buffers are identical
09-13 11:19:17.192  3957  4008 I jxcore-log: 
,09-13 11:19:17.197  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-13 11:19:17.197  3957  4008 I jxcore-log: 
,09-13 11:19:17.198  3957  4008 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 11:19:17.198  3957  4008 I jxcore-log: 
,09-13 11:19:17.200  3957  4008 I jxcore-log: DEBUG createNativeListener: mux close
09-13 11:19:17.200  3957  4008 I jxcore-log: 
,09-13 11:19:17.205  3957  4008 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 11:19:17.205  3957  4008 I jxcore-log: 
,09-13 11:19:17.205  3957  4008 I jxcore-log: ok 40 server should be fine
09-13 11:19:17.205  3957  4008 I jxcore-log: 
09-13 11:19:17.206  3957  4008 I jxcore-log: ok 41 server should be open
09-13 11:19:17.206  3957  4008 I jxcore-log: 
09-13 11:19:17.206  3957  4008 I jxcore-log: ok 42 incoming has been removed
09-13 11:19:17.206  3957  4008 I jxcore-log: 
,09-13 11:19:17.207  3957  4008 I jxcore-log: ok 43 The mux object should be closed
09-13 11:19:17.207  3957  4008 I jxcore-log: 
09-13 11:19:17.207  3957  4008 I jxcore-log: ok 44 The mux stream should be closed
09-13 11:19:17.207  3957  4008 I jxcore-log: 
,09-13 11:19:17.213  3957  4008 I jxcore-log: # teardown
09-13 11:19:17.213  3957  4008 I jxcore-log: 
,09-13 11:19:17.993  3957  4008 I jxcore-log: # setup
09-13 11:19:17.993  3957  4008 I jxcore-log: 
,09-13 11:19:18.064  3957  4008 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
09-13 11:19:18.064  3957  4008 I jxcore-log: 
,09-13 11:19:18.276  3957  4008 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
09-13 11:19:18.276  3957  4008 I jxcore-log: 
,09-13 11:19:18.278  3957  4008 I jxcore-log: ok 45 Got right error
09-13 11:19:18.278  3957  4008 I jxcore-log: 
,09-13 11:19:18.283  3957  4008 I jxcore-log: # teardown
09-13 11:19:18.283  3957  4008 I jxcore-log: 
,09-13 11:19:18.485  3957  4008 I jxcore-log: # setup
09-13 11:19:18.485  3957  4008 I jxcore-log: 
,09-13 11:19:18.566  3957  4008 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
09-13 11:19:18.566  3957  4008 I jxcore-log: 
,09-13 11:19:18.685  3957  4008 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
09-13 11:19:18.685  3957  4008 I jxcore-log: 
,09-13 11:19:18.687  3957  4008 I jxcore-log: ok 46 Got socket hang up
09-13 11:19:18.687  3957  4008 I jxcore-log: 
,09-13 11:19:18.691  3957  4008 I jxcore-log: # teardown
09-13 11:19:18.691  3957  4008 I jxcore-log: 
,09-13 11:19:18.788  3957  4008 I jxcore-log: # setup
09-13 11:19:18.788  3957  4008 I jxcore-log: 
,09-13 11:19:18.885  3957  4008 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
09-13 11:19:18.885  3957  4008 I jxcore-log: 
,09-13 11:19:19.073  3957  4008 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
09-13 11:19:19.073  3957  4008 I jxcore-log: 
,09-13 11:19:19.074  3957  4008 I jxcore-log: ok 47 Got 500 as expected
09-13 11:19:19.074  3957  4008 I jxcore-log: 
,09-13 11:19:19.078  3957  4008 I jxcore-log: # teardown
09-13 11:19:19.078  3957  4008 I jxcore-log: 
,09-13 11:19:19.226  3957  4008 I jxcore-log: # setup
09-13 11:19:19.226  3957  4008 I jxcore-log: 
,09-13 11:19:19.334  3957  4008 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
09-13 11:19:19.334  3957  4008 I jxcore-log: 
,09-13 11:19:21.582  3957  4008 I jxcore-log: ok 48 should be equal
09-13 11:19:21.582  3957  4008 I jxcore-log: 
,09-13 11:19:21.583  3957  4008 I jxcore-log: ok 49 revs are equal
09-13 11:19:21.583  3957  4008 I jxcore-log: 
,09-13 11:19:21.587  3957  4008 I jxcore-log: # teardown
09-13 11:19:21.587  3957  4008 I jxcore-log: 
,09-13 11:19:33.901  3230  4458 V KeepSync: Connecting to GoogleApiClient
,09-13 11:19:33.902   872  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:19:33.963  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:19:33.966  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:19:33.998  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-13 11:19:33.999  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 11:19:33.999  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:19:33.999  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:19:34.025  1731  4459 V BaseAuthAsyncOperation: access token request failed
,09-13 11:19:34.026  3230  4458 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:19:34.113  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:19:34.113  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 11:19:34.113  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:19:34.113  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:19:34.151  3230  4458 E KeepSync: IOException
09-13 11:19:34.151  3230  4458 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:19:34.151  3230  4458 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:19:34.151  3230  4458 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:19:34.151  3230  4458 E KeepSync: 	... 10 more
,09-13 11:19:34.151  3230  4458 W KeepSync: Sync result 2
,09-13 11:19:34.165   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 253777, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:19:41.687  1522  2139 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 11:20:04.409  3785  4465 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:20:04.426  3785  4466 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:20:04.452  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:04.454  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:04.477  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:20:04.478  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:20:04.478  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:04.478  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:04.511  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:04.516  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:04.557  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:20:04.557  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 11:20:04.557  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:04.557  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:04.575  3785  4466 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:20:04.576  3785  4465 E BooksSync: Soft error
09-13 11:20:04.576  3785  4465 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:20:04.576  3785  4465 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:20:04.576  3785  4465 E BooksSync: Sync error
09-13 11:20:04.576  3785  4465 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:20:04.576  3785  4465 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:20:04.576  3785  4465 I BooksSync: Finished books sync
,09-13 11:20:04.584   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:20:34.836  3230  4468 V KeepSync: Connecting to GoogleApiClient
09-13 11:20:34.837   872  3247 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:20:34.887  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:34.890  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:34.915  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 11:20:34.915  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 11:20:34.915  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:34.915  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:34.949  1731  4471 V BaseAuthAsyncOperation: access token request failed
09-13 11:20:34.950  3230  4468 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:20:34.984  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 11:20:34.984  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:20:34.984  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:34.984  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:35.003  3715  4470 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:20:35.003  3715  4470 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:20:35.003  3715  4470 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	... 12 more
09-13 11:20:35.003  3715  4470 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at fal.a(PG:38)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:20:35.003  3715  4470 E HttpOperation: 	... 14 more
,09-13 11:20:35.069  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:20:35.070  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:20:35.070  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:35.070  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:35.086  3715  4470 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:20:35.086  3715  4470 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at hec.a(PG:42)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at hee.a(PG:102)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at czr.a(PG:65)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at kka.a(PG:108)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:20:35.086  3715  4470 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	... 15 more
09-13 11:20:35.086  3715  4470 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at fal.a(PG:38)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:20:35.086  3715  4470 E HttpOperation: 	... 17 more
,09-13 11:20:35.086  3715  4470 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:20:35.086  3715  4470 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at hec.a(PG:42)
,09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	... 15 more
09-13 11:20:35.086  3715  4470 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:20:35.086  3715  4470 E ExperimentLoader: 	... 17 more
,09-13 11:20:35.183  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:20:35.183  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 11:20:35.183  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:35.183  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:35.199   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 305263, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:20:35.210  3230  4468 E KeepSync: IOException
09-13 11:20:35.210  3230  4468 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:20:35.210  3230  4468 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:20:35.210  3230  4468 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:20:35.210  3230  4468 E KeepSync: 	... 10 more
,09-13 11:20:35.211  3230  4468 W KeepSync: Sync result 2
,09-13 11:20:35.236   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 305175, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:20:35.260  3785  4474 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:20:35.280  3785  4475 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:20:35.307  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:20:35.307  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 11:20:35.307  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:35.307  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:35.348  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:20:35.348  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:20:35.348  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:20:35.348  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:35.365  3785  4475 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:20:35.366  3785  4474 E BooksSync: Soft error
09-13 11:20:35.366  3785  4474 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:20:35.366  3785  4474 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 11:20:35.366  3785  4474 E BooksSync: Sync error
09-13 11:20:35.366  3785  4474 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:20:35.366  3785  4474 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 11:20:35.366  3785  4474 I BooksSync: Finished books sync
,09-13 11:20:35.381   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 334131, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:20:45.434  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:45.444  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:45.449  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:20:45.501  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 11:20:45.502  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 11:20:45.502  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:20:45.502  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:20:45.538  1522  2395 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 11:20:45.538  1522  2395 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 11:20:45.547  3674  3705 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 11:20:45.547  3674  3705 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 11:20:45.547  3674  3705 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 11:20:45.547  3674  3705 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 11:20:45.547  3674  3705 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 11:20:45.547  3674  3705 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 11:20:45.547  3674  3705 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 11:21:36.653  3785  4482 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:21:36.677  3785  4484 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:21:36.691  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:21:36.694  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:21:36.727  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:21:36.727  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:21:36.727  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:21:36.727  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:21:36.756  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:21:36.759  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:21:36.804  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 11:21:36.814  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:21:36.814  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:21:36.814  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:21:36.850  3785  4484 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:21:36.851  3785  4482 E BooksSync: Soft error
09-13 11:21:36.851  3785  4482 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:21:36.851  3785  4482 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:21:36.851  3785  4482 E BooksSync: Sync error
09-13 11:21:36.851  3785  4482 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:21:36.851  3785  4482 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:21:36.851  3785  4482 I BooksSync: Finished books sync
,09-13 11:21:36.863   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 395532, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:22:07.238  3230  4487 V KeepSync: Connecting to GoogleApiClient
,09-13 11:22:07.239   872  3268 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:22:07.304  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:22:07.309  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:22:07.340  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 11:22:07.340  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 11:22:07.340  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:22:07.340  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:22:07.363  1731  4488 V BaseAuthAsyncOperation: access token request failed
,09-13 11:22:07.364  3230  4487 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:22:07.430  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:22:07.430  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 11:22:07.430  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:22:07.430  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:22:07.448  3230  4487 E KeepSync: IOException
09-13 11:22:07.448  3230  4487 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:22:07.448  3230  4487 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:22:07.448  3230  4487 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:22:07.448  3230  4487 E KeepSync: 	... 10 more
,09-13 11:22:07.448  3230  4487 W KeepSync: Sync result 2
,09-13 11:22:07.458   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 398314, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:22:34.982  1522  2139 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 11:22:40.774  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:22:40.779  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:22:40.821  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:22:40.821  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:22:40.821  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:22:40.821  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:22:40.843  3715  4491 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:22:40.843  3715  4491 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:22:40.843  3715  4491 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	... 12 more
09-13 11:22:40.843  3715  4491 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at fal.a(PG:38)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:22:40.843  3715  4491 E HttpOperation: 	... 14 more
,09-13 11:22:40.891  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 11:22:40.891  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:22:40.891  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:22:40.891  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:22:40.907  3715  4491 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:22:40.907  3715  4491 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at hec.a(PG:42)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at hee.a(PG:102)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at czr.a(PG:65)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at kka.a(PG:108)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:22:40.907  3715  4491 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	... 15 more
09-13 11:22:40.907  3715  4491 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at fal.a(PG:38)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:22:40.907  3715  4491 E HttpOperation: 	... 17 more
,09-13 11:22:40.908  3715  4491 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:22:40.908  3715  4491 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at hec.a(PG:42)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	... 15 more
09-13 11:22:40.908  3715  4491 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:22:40.908  3715  4491 E ExperimentLoader: 	... 17 more
,09-13 11:22:41.016   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 459441, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:23:39.353  3785  4495 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:23:39.394  3785  4496 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:23:39.416  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:23:39.423  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:23:39.473  1522  2395 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:23:39.474  1522  2395 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:23:39.474  1522  2395 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:23:39.474  1522  2395 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:23:39.512  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:23:39.515  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:23:39.549  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:23:39.549  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 11:23:39.550  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:23:39.550  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:23:39.571  3785  4496 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:23:39.572  3785  4495 E BooksSync: Soft error
09-13 11:23:39.572  3785  4495 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:23:39.572  3785  4495 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 11:23:39.572  3785  4495 E BooksSync: Sync error
09-13 11:23:39.572  3785  4495 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:23:39.572  3785  4495 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 11:23:39.572  3785  4495 I BooksSync: Finished books sync
,09-13 11:23:39.583   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 518224, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:24:15.882  3230  4499 V KeepSync: Connecting to GoogleApiClient
,09-13 11:24:15.882   872  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:24:15.952  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:24:15.955  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:24:15.995  1522  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 11:24:15.997  1522  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 11:24:15.997  1522  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:24:15.997  1522  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:24:16.029  1731  4500 V BaseAuthAsyncOperation: access token request failed
,09-13 11:24:16.030  3230  4499 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:24:16.112  1522  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:24:16.112  1522  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 11:24:16.112  1522  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:24:16.112  1522  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:24:16.144  3230  4499 E KeepSync: IOException
09-13 11:24:16.144  3230  4499 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:24:16.144  3230  4499 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:24:16.144  3230  4499 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:24:16.144  3230  4499 E KeepSync: 	... 10 more
,09-13 11:24:16.145  3230  4499 W KeepSync: Sync result 2
,09-13 11:24:16.161   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 554672, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:26:16.143  1522  2139 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 11:29:48.043   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=886983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:30:03.016   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=901957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:30:13.110   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=912050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:30:28.083   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=927024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:30:38.176   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=937117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:30:53.136   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=952077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:31:03.243   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=962184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:31:18.203   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:31:28.309   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=987250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:31:43.270   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1002211, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:31:53.376   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1012317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:32:08.350   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:32:18.442   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1037383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:32:33.403   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1052344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:32:43.509   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:32:58.470   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1077411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:33:08.896   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:33:20.148   872  1984 I ActivityManager: Start proc 4529:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-13 11:33:20.247  4529  4529 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-13 11:33:20.276  4529  4529 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 11:33:20.276  4529  4529 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 11:33:20.276  4529  4529 I GAv4    :   adb logcat -s GAv4
,09-13 11:33:20.291  4529  4529 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:33:20.299  4529  4529 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:33:20.314  4529  4544 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:33:20.418   872  1718 I ActivityManager: Killing 3878:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 11:33:23.856   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1102797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:33:33.963   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1112904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:33:48.923   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1127864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:33:59.029   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:34:13.989   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1152930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:34:24.096   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1163037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:34:39.056   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1177997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:34:42.803   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1181744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:35:04.123   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:35:07.869   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1206810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:35:19.117   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 11:35:29.190   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:35:32.936   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1231877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:35:54.256   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:35:58.002   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1256943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:36:19.323   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1278264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:36:23.069   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1282010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:36:44.390   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1303330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:36:48.229   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:37:09.550   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1328490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:37:13.522   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1332463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:37:34.843   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1353784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:37:38.589   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1357530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:37:59.910   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1378851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:38:03.656   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382596, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:38:24.976   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1403917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:38:28.709   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1407650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:38:50.030   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1428970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:38:53.776   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1432717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:39:15.123   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1454063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:39:18.869   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1457810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:39:40.190   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1479130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:39:44.789   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1483730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:40:05.243   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1504184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:40:09.856   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1508797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 11:40:30.309   872  4399 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1529250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
