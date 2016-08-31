#### Test 832760828839a22_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-31 11:29:16.150   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-31 11:29:17.448  3806  3806 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 11:29:17.452  3806  3806 D AndroidRuntime: CheckJNI is OFF
08-31 11:29:17.495  3806  3806 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 11:29:17.545  3806  3806 I Radio-JNI: register_android_hardware_Radio DONE
08-31 11:29:17.567  3806  3806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:29:17.573   871  1977 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 11:29:17.625  2008  2019 W SearchService: Abort, client detached.
08-31 11:29:17.630  2008  2008 I HotwordDetector: Closing mic
08-31 11:29:17.630  2008  2306 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@799b3ec
08-31 11:29:17.631  2008  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 11:29:17.654  3806  3806 D AndroidRuntime: Shutting down VM
08-31 11:29:17.684   871  2036 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 11:29:17.697   375  2341 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 11:29:17.698   375  2341 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 11:29:17.704   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 11:29:17.707  2008  2337 I MicroRecognitionRnrImpl: Detection finished
08-31 11:29:17.708  2008  2323 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 11:29:17.771  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 11:29:17.800  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 11:29:17.809  3815  3815 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7546-7551)
08-31 11:29:17.810  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:29:17.828  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {437edbf}
08-31 11:29:17.829  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 11:29:17.829  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 11:29:17.839  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 11:29:17.840  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 11:29:17.861  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 11:29:17.876  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:29:17.876  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:29:17.876  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:29:17.876  3815  3815 I Adreno  : Build Date                       : 10/20/15
08-31 11:29:17.876  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:29:17.876  3815  3815 I Adreno  : Local Branch                     : M14
08-31 11:29:17.876  3815  3815 I Adreno  : Remote Branch                    : 
08-31 11:29:17.876  3815  3815 I Adreno  : Remote Branch                    : 
08-31 11:29:17.876  3815  3815 I Adreno  : Reconstruct Branch               : 
,08-31 11:29:17.948   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1878939:true
,08-31 11:29:18.013  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 11:29:18.031  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 11:29:18.110  3815  3855 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 11:29:18.121  3815  3841 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 11:29:18.173  3815  3855 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 11:29:18.250   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +595ms
,08-31 11:29:18.257  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-31 11:29:18.329  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,08-31 11:29:18.501   871  1379 I ActivityManager: Killing 3399:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 11:29:18.525  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:29:18.549   871  1379 I ActivityManager: Killing 2978:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-31 11:29:18.680  3815  3857 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1713768144
,08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 11:29:18.689  3815  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fce13 added. We now have 1 listener(s)
,08-31 11:29:18.698  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 11:29:18.700  3815  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 11:29:18.700  3815  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:18.701  3815  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533,
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:29:18.705  3815  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55dcf4e added. We now have 1 listener(s)
08-31 11:29:18.705  3815  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:18.709   871  1314 D WifiService: New client listening to asynchronous messages
,08-31 11:29:18.710  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:18.710  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 11:29:18.710  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-31 11:29:18.710  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-31 11:29:18.710  3815  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 11:29:18.713  3815  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:18.713  3815  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 11:29:18.722  3815  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:18.723  3815  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:18.723  3815  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 11:29:18.723  3815  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:18.723  3815  3857 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:18.802  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:18.805  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:18.806  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:29:19.557  3815  3867 W jxcore-log: Initializing JXcore engine
,08-31 11:29:19.557  3815  3867 W jxcore-log: JXcore engine is ready
,08-31 11:29:19.596  3867  3867 W Thread-334: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8982 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 11:29:19.596  3867  3867 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11071]" dev="sockfs" ino=11071 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 11:29:19.596  3867  3867 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 11:29:19.596  3867  3867 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25832]" dev="sockfs" ino=25832 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 11:29:19.612  3815  3867 W jxcore-log: Starting JXcore engine
,08-31 11:29:19.696  3815  3867 W jxcore-log: Platform android
08-31 11:29:19.696  3815  3867 W jxcore-log: 
,08-31 11:29:19.697  3815  3867 W jxcore-log: Process ARCH arm
08-31 11:29:19.697  3815  3867 W jxcore-log: 
,08-31 11:29:19.925  3815  3867 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:29:19.925  3815  3867 I jxcore-log: 
,08-31 11:29:19.925  3815  3867 W jxcore-log: JXcore engine is started
,08-31 11:29:19.935  3815  3857 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:29:19.939  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:29:22.587   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-31 11:29:27.924  3593  3878 V KeepSync: Connecting to GoogleApiClient
,08-31 11:29:27.924   871  1977 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 11:29:27.942  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:29:27.951  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:29:27.953  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:29:27.987  1526  2351 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 11:29:27.987  1526  2351 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-31 11:29:27.987  1526  2351 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:29:27.987  1526  2351 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:29:27.991  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-31 11:29:27.991  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 11:29:27.991  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:29:27.991  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:29:28.003  1754  3879 V BaseAuthAsyncOperation: access token request failed
,08-31 11:29:28.003  3593  3878 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 11:29:28.010  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 11:29:28.010  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 11:29:28.011  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-31 11:29:28.053  1526  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-31 11:29:28.053  1526  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 11:29:28.054  1526  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 11:29:28.054  1526  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:29:28.078  3593  3878 E KeepSync: IOException
08-31 11:29:28.078  3593  3878 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 11:29:28.078  3593  3878 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 11:29:28.078  3593  3878 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 11:29:28.078  3593  3878 E KeepSync: 	... 10 more
08-31 11:29:28.078  3593  3878 W KeepSync: Sync result 2
,08-31 11:29:28.084   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 11:29:28.254   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 11:29:29.650  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:29:29.650  3815  3867 I jxcore-log: 
,08-31 11:29:29.653  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:29:29.653  3815  3867 I jxcore-log: 
,08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:29.669  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:29.676  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:29.683  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:29:29.683  3815  3867 I jxcore-log: 
,08-31 11:29:29.691  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:29:29.691  3815  3867 I jxcore-log: 
,08-31 11:29:30.212  3815  3867 I jxcore-log: Unit Test app is loaded
08-31 11:29:30.212  3815  3867 I jxcore-log: 
,08-31 11:29:30.217  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:30.217  3815  3867 I jxcore-log: 
,08-31 11:29:30.222  3815  3867 D executeNativeTests: Running unit tests
,08-31 11:29:30.242  3815  3815 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:29:30.279  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:30.280  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 added. We now have 2 listener(s)
08-31 11:29:30.280  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:30.281  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:30.281  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:30.281  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:30.281  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 added. We now have 2 listener(s)
08-31 11:29:30.281  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:30.282  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:30.284  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.295  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:30.299  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.300  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:30.306  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.307  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:29:30.312  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:29:30.312  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:30.313  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.317  3815  3867 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 11:29:30.318  3815  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-31 11:29:30.318  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-31 11:29:30.319  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:29:30.319  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:30.319  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.320  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:30.320  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.320  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.320  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.321  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:30.321  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:30.321  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 removed from the list
08-31 11:29:30.321  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.321  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 removed from the list
08-31 11:29:30.321  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.321  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.322  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.322  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.324  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.324  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.324  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.324  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.326  3815  3867 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 11:29:30.327  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.327  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:30.327  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.327  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:30.327  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.327  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.327  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
,08-31 11:29:30.327  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.327  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.327  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.327  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.327  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.328  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.328  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.329  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.329  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.329  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.329  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:30.335  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:29:30.336  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:29:30.337  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:29:30.337  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.337  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.337  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.337  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.337  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.338  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.338  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.338  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.338  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.338  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.338  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.338  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.338  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.338  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.340  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.340  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.340  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.340  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.343  3815  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:29:30.347  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.358  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:30.364  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.365  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:30.365  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:30.367  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:30.367  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:30.367  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.367  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.367  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:30.379  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.385  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:29:30.385  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:30.394  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:30.396  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:29:30.397  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:30.402  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 11:29:30.409  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 11:29:30.409  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:30.409  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:30.410  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:30.411  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:30.417  2682  2816 D BtGatt.GattService: registerClient() - UUID=ccba3d73-24ea-4671-b10e-49efc0556d3f
,08-31 11:29:30.419  2682  2709 D BtGatt.GattService: onClientRegistered() - UUID=ccba3d73-24ea-4671-b10e-49efc0556d3f, clientIf=5
,08-31 11:29:30.421  3815  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 11:29:30.422  2682  2693 D BtGatt.GattService: start scan with filters
,08-31 11:29:30.427  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:30.427  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:30.427  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:30.427  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:30.428  2682  2715 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:30.434  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:30.434  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:30.434  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:30.435  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:29:30.434  2682  2715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:30.441  3815  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:30.456  2682  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 11:29:30.456  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.457  2682  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:29:30.459  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:30.460  3815  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:30.461  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.461  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 11:29:30.461  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.462  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:29:30.463  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:30.463  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:30.463  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:30.463  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:30.465  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:30.466  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:30.467  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 11:29:30.467  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.468  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:30.468  2682  2715 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:29:30.468  2682  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:29:30.469  2682  2816 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:30.471  2682  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:29:30.472  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:29:30.472  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:30.473  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:30.473  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 11:29:30.473  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:30.477  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:30.477  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:30.477  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:29:30.478  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:30.479  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:30.480  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:30.480  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.480  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.481  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:30.481  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.481  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.481  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.481  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.481  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.481  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.481  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:30.483  3815  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:29:30.486  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.487  2682  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:30.487  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.492  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:30.495  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:30.495  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:30.495  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:29:30.495  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.496  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:30.496  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:30.496  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:30.496  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.496  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:30.497  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.500  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 11:29:30.500  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:30.500  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.504  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:30.506  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 11:29:30.506  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:30.507  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:29:30.508  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.508  2682  2715 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:30.510  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:30.510  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:29:30.510  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:30.511  3815  3867 D BluetoothAdapter: STATE_ON
,08-31 11:29:30.514  2682  2816 D BtGatt.GattService: registerClient() - UUID=de989c21-c86e-4ecc-927c-7766c11c98ad
08-31 11:29:30.514  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:29:30.514  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.514  2682  2709 D BtGatt.GattService: onClientRegistered() - UUID=de989c21-c86e-4ecc-927c-7766c11c98ad, clientIf=5
08-31 11:29:30.515  2682  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:29:30.515  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:29:30.515  2682  2694 D BtGatt.GattService: start scan with filters
,08-31 11:29:30.519  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:30.519  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:30.519  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:30.519  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:30.521  2682  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 11:29:30.521  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.521  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:30.522  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:30.522  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:30.523  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:30.523  2682  2715 D BtGatt.ScanManager: handling starting scan
08-31 11:29:30.525  3815  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:30.527  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.527  3815  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:30.528  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:30.528  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:30.528  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.528  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:30.528  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:30.528  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:30.528  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:30.528  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:30.528  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:30.528  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:29:30.528  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:30.529  2682  2694 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:30.529  2682  2693 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:29:30.530  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:30.530  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:29:30.530  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:30.530  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:30.530  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:30.531  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:30.531  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:30.531  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:30.531  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:30.532  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:30.533  2682  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:29:30.533  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.533  2682  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:29:30.533  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.534  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.534  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:30.534  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:30.534  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.536  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:30.536  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.536  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.537  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.537  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:30.537  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.537  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.537  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.538  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.538  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:30.538  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.538  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.539  3815  3867 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:29:30.540  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.541  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:29:30.541  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.541  2682  2715 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:30.541  2682  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.547  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:30.550  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:30.550  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:30.551  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:30.551  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:30.551  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:30.552  2682  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:30.552  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.552  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.552  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:30.554  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.559  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.560  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:29:30.560  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:30.561  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 11:29:30.561  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.570  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:29:30.571  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-31 11:29:30.571  2682  2715 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:30.571  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:30.572  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:29:30.572  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:30.578  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:30.578  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:30.579  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:29:30.579  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.579  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-31 11:29:30.579  2682  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:29:30.580  3815  3867 D BluetoothAdapter: STATE_ON
,08-31 11:29:30.584  2682  2693 D BtGatt.GattService: registerClient() - UUID=abbc1093-9c98-4b07-b7d6-5454670a4be0
,08-31 11:29:30.584  2682  2709 D BtGatt.GattService: onClientRegistered() - UUID=abbc1093-9c98-4b07-b7d6-5454670a4be0, clientIf=5
08-31 11:29:30.584  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:29:30.585  2682  2817 D BtGatt.GattService: start scan with filters
,08-31 11:29:30.587  2682  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:29:30.587  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.592  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:30.592  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:30.592  2682  2715 D BtGatt.ScanManager: handling starting scan
08-31 11:29:30.592  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:30.592  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:30.596  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:30.596  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:30.596  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:30.600  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:30.600  2682  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-31 11:29:30.601  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.601  2682  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:29:30.605  3815  3867 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:30.605  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.605  3815  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-31 11:29:30.605  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.605  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:30.605  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.606  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:30.606  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:30.606  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:29:30.606  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:29:30.606  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:30.606  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:30.606  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:29:30.607  3815  3867 D BluetoothAdapter: STATE_ON
,08-31 11:29:30.608  2682  2817 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:30.609  2682  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:29:30.609  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:30.609  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:30.609  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:29:30.610  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:30.610  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:30.611  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:30.611  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:30.611  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:30.611  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:30.612  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:29:30.612  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.612  2682  2715 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:30.612  2682  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:29:30.612  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:30.613  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.613  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.613  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:30.613  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.613  3815  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:30.613  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.613  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.614  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:30.614  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.614  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:30.614  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.614  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.614  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.614  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.614  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.615  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.615  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.616  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.616  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.617  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.617  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.617  3815  3867 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 11:29:30.618  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.618  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.618  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.618  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.619  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.619  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.619  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.619  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.619  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.619  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:30.619  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.619  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.619  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.620  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.621  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.621  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.621  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.621  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.623  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:29:30.623  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.623  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.623  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:30.624  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.624  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.624  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.624  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.624  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.624  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.624  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.624  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.625  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.625  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.625  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.626  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.626  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.626  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.626  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.627  3815  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:29:30.627  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.627  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.627  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.627  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.627  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.628  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.628  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.628  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.628  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.628  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.628  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.628  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.628  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.628  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.629  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.629  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.629  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.630  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.630  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-31 11:29:30.630  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.630  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.630  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.631  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.631  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.631  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.631  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.631  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.631  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.631  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.631  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.631  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.632  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.632  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.635  2682  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:30.635  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.638  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.638  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.638  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.638  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.639  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:29:30.639  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:30.639  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:30.639  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:30.640  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:30.640  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:30.640  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:30.640  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.640  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.640  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.640  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.640  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.640  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.641  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.641  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.641  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.641  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 11:29:30.641  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.641  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.641  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.643  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.643  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.643  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.644  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.646  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:30.646  3815  3867 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:29:30.646  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:30.648  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:29:30.648  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.656  2682  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 11:29:30.656  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.657  2682  2715 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:30.658  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:30.658  3815  3867 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:29:30.658  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:29:30.658  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 11:29:30.658  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:29:30.659  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-31 11:29:30.660  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:29:30.660  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-31 11:29:30.661  3815  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 11:29:30.661  3815  3867 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:29:30.661  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:30.661  3815  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:30.661  3815  3867 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:29:30.661  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:30.661  3815  3867 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-31 11:29:30.661  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:30.663  2682  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-31 11:29:30.663  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:30.663  2682  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:29:30.664  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:29:30.666  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:29:30.666  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-31 11:29:30.667  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:29:30.667  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:29:30.667  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:29:30.667  3815  3867 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:30.667  3815  3867 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:29:30.668  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:30.668  2682  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:29:30.669  2682  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:30.669  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.669  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:30.669  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.669  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.669  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.669  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-31 11:29:30.669  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 11:29:30.670  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.670  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.670  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.670  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.670  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.670  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.670  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.670  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.672  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.672  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.672  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.672  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.672  3815  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:30.673  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-31 11:29:30.673  3815  3867 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:29:30.673  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 398)
08-31 11:29:30.673  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 398)
,08-31 11:29:30.673  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.674  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.674  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:30.674  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.674  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.674  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.674  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.674  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.674  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.674  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.674  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.675  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.675  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.675  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.675  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-31 11:29:30.677  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.677  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.677  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.677  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.679  3815  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:29:30.679  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.679  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:30.679  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.679  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.680  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.680  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.680  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.680  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.680  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.680  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.680  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.680  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.680  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.680  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.681  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.681  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.681  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.681  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.682  3815  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-31 11:29:30.682  3815  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:29:30.682  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:30.682  3815  3867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:29:30.682  3815  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:30.683  3815  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:29:30.683  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:30.683  3815  3867 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:29:30.683  3815  3867 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:30.683  3815  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-31 11:29:30.683  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:30.683  3815  3867 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:29:30.683  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.683  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.683  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.683  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.683  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.684  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.684  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.684  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.684  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.684  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.684  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.684  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.684  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.684  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.685  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.685  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.685  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.685  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.686  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.686  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.686  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.686  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.686  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.686  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.686  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.686  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.687  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.687  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.687  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.687  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.687  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.687  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.687  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.687  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.687  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:30.687  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.688  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.688  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.688  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.688  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.688  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.688  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.688  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.688  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.688  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.688  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.688  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.689  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:30.689  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:30.690  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.690  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.691  3815  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:29:30.691  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.692  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-31 11:29:30.693  3815  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:29:30.693  3815  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:29:30.693  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:29:30.693  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:30.693  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:29:30.694  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:30.694  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:29:30.694  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:29:30.694  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:29:30.694  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.694  3815  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:29:30.694  3815  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:29:30.694  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-31 11:29:30.694  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.694  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.694  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:29:30.694  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:30.694  3815  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:29:30.694  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:30.695  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.695  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.696  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:30.696  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:30.696  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.696  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:30.696  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.696  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.696  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.696  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.696  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:29:30.696  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.696  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.696  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:30.696  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.696  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.697  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.697  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.697  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.697  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.697  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.697  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.698  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.698  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:30.698  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.698  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.699  3815  3867 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-31 11:29:30.699  3815  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:29:30.699  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:30.699  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:30.700  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.700  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.700  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.700  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.700  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:30.700  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.700  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.700  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.700  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.700  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:30.700  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.700  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.700  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.701  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.701  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.702  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.702  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.702  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.707  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:30.707  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.707  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:30.707  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.707  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.707  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.707  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.707  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.707  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.707  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:30.707  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.707  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.708  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.708  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.709  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.709  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.709  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:30.709  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.710  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:30.710  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:30.710  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:30.710  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:30.710  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.710  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.710  3815  3867 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12e7a23 not in the list
08-31 11:29:30.710  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.710  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
08-31 11:29:30.710  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:30.710  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.711  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:30.711  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:30.711  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:30.712  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:30.712  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:30.712  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:30.712  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@412db20 not in the list
,08-31 11:29:30.713  3815  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-31 11:29:30.713  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-31 11:29:30.713  3815  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:29:30.714  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-31 11:29:30.714  3815  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:29:30.714  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:30.716  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:29:30.716  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-31 11:29:30.717  3815  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:29:30.717  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:29:30.717  3815  3867 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:29:30.717  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:29:30.717  3815  3867 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:29:30.717  3815  3867 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 11:29:30.718  3815  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:29:30.718  3815  3867 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:29:30.718  3815  3867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-31 11:29:30.718  3815  3867 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:29:30.719  3815  3867 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:29:30.719  3815  3867 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 11:29:30.720  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:30.720  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c7d902 added. We now have 2 listener(s)
08-31 11:29:30.720  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:30.721  3815  3867 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 11:29:30.721   871   881 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-31 11:29:30.722   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:30.722  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:30.723  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c23213 added. We now have 3 listener(s)
08-31 11:29:30.723  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:30.729  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:30.729  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba34c50 added. We now have 4 listener(s)
08-31 11:29:30.729  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:30.730  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:30.730  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba80e49 added. We now have 5 listener(s)
,08-31 11:29:30.730  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:30.732   871  1976 D WifiService: setWifiEnabled: false pid=3815, uid=10000
08-31 11:29:30.732   871  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:30.737  2682  2705 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 11:29:30.737  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:30.737  2682  2705 D BluetoothAdapterProperties: Setting state to 13
08-31 11:29:30.737  2682  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:29:30.738  2682  2705 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:29:30.739  2682  2705 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:29:30.739  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.739  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:30.740  2682  2682 D BluetoothMapService: onReceive
08-31 11:29:30.740  2682  2682 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:30.740  2682  2682 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:29:30.740  2682  2682 D BluetoothMapService: MAP Service closeService in
,08-31 11:29:30.741  2682  2682 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 11:29:30.741  2682  2682 D ObexServerSockets0: shutdown(block = true)
08-31 11:29:30.741  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:29:30.741  2682  2682 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-31 11:29:30.741  2682  2813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:29:30.741  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:30.741  2682  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 11:29:30.741  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.741  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:30.742  2682  2826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 11:29:30.742  2682  2682 I BtOppRfcommListener: stopping Accept Thread
08-31 11:29:30.742  2682  3406 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:29:30.742  2682  3406 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:29:30.744  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.747  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.748  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:29:30.749  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:30.749  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:30.750   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:29:30.750  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:30.750   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 11:29:30.750  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:30.750   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:29:30.750   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:30.752  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.754   871   884 I ActivityManager: Start proc 3886:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 11:29:30.755  2682  2709 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:30.755  2682  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 11:29:30.758  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.758   871  1888 D DhcpClient: Clearing IP address
08-31 11:29:30.759   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:30.761  2682  2682 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:29:30.762  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.762   371   869 D CommandListener: Setting iface cfg
08-31 11:29:30.763   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:30.763   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:30.763  1370  2047 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:30.763   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:30.763  1928  2096 D BluetoothHeadset: Proxy object disconnected
,08-31 11:29:30.764  1526  2288 V NativeCrypto: Read error: ssl=0xaebeac00: I/O error during system call, Connection timed out
,08-31 11:29:30.764  2682  2682 D A2dpService: Received stop request...Stopping profile...
,08-31 11:29:30.764  2682  2820 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:29:30.765  1526  2288 V NativeCrypto: SSL shutdown failed: ssl=0xaebeac00: I/O error during system call, Broken pipe
,08-31 11:29:30.766   871   871 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:30.766  2682  2682 D HidService: Received stop request...Stopping profile...
,08-31 11:29:30.767   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:29:30.767  2682  2682 D HidService: Stopping Bluetooth HidService
,08-31 11:29:30.767   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-31 11:29:30.767   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-31 11:29:30.767   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:29:30.771   397   397 E Parcel  : Reading a NULL string not supported here.
08-31 11:29:30.772  2682  2682 D HealthService: Received stop request...Stopping profile...
,08-31 11:29:30.772   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:30.773  2682  2682 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:29:30.773  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:30.773  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:30.774  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:30.774  2682  2682 D PanService: Received stop request...Stopping profile...
08-31 11:29:30.774   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 11:29:30.776  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-31 11:29:30.776  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:30.777  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-31 11:29:30.777  1370  1370 D HidProfile: Bluetooth service disconnected
08-31 11:29:30.777  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:29:30.777  1370  1370 D PanProfile: Bluetooth service disconnected
08-31 11:29:30.780   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:29:30.780  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:29:30.780  2682  2682 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:29:30.781  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.781  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.781  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.781  2682  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:29:30.781  2682  2709 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 11:29:30.783  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:30.783  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:30.783   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:29:30.784  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:30.784  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:30.786  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:30.786  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:30.787  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:30.787  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:30.787  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:30.787  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:30.787  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:30.788  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:30.788  2682  2682 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:29:30.788  2682  2682 D BluetoothMapService: stop()
08-31 11:29:30.788  2682  2682 D BluetoothMapAppObserver: deinitObservers()
08-31 11:29:30.788  2682  2682 D BluetoothMapAppObserver: removeReceiver()
08-31 11:29:30.790  1370  1370 D BluetoothMap: Proxy object disconnected
08-31 11:29:30.790  1370  1370 D MapProfile: Bluetooth service disconnected
08-31 11:29:30.790  2167  2355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:30.793  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:30.793  2682  2682 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:30.793  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:30.793  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 11:29:30.794  2682  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:29:30.794  2682  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:29:30.794  2682  2709 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 11:29:30.794  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.794  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.794  2682  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:30.794  2682  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:30.794  2682  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:29:30.794  2682  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:30.797  2682  2682 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:29:30.797  2682  2682 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:30.797  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:30.797  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:30.797  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:30.798  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:29:30.798  2682  2682 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:29:30.799  2682  2682 D BluetoothMapService: MAP Service closeService in
08-31 11:29:30.799  2682  2682 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:29:30.799  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:30.799  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:30.799  2682  2682 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:30.799  2682  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 11:29:30.799  2682  2705 D BluetoothAdapterProperties: Setting state to 15
08-31 11:29:30.799  2682  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:29:30.800  1370  1393 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:30.800  1370  2047 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:30.801   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:30.801  2682  2705 I BluetoothAdapterState: Entering BleOnState
08-31 11:29:30.801  1928  2208 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:29:30.801  1370  1382 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:29:30.801   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:30.801   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:30.802  1370  1393 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:29:30.802   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:30.802  1370  2047 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:29:30.803  2682  2682 D BluetoothMapService: cleanup()
08-31 11:29:30.803  2682  2682 D BluetoothMapService: MAP Service closeService in
08-31 11:29:30.807  1370  1382 D BluetoothPan: onBluetoothStateChange on: false
,08-31 11:29:30.808  2682  2705 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:29:30.808  2682  2705 D BluetoothAdapterProperties: Setting state to 16
,08-31 11:29:30.808  2682  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 11:29:30.809  2682  2705 D BluetoothAdapterProperties: onBleDisable
08-31 11:29:30.809  2682  2705 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:29:30.810  2682  2706 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 11:29:30.810  2682  2797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 11:29:30.810  2682  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:30.812   871  1889 D DhcpClient: Receive thread stopped
08-31 11:29:30.813  2682  2709 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:30.814  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.815  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.816  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.817  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:30.821   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:30.838  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-31 11:29:30.842   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:30.843   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 11:29:30.843   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:30.845   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:29:30.849  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.851  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:30.854  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:30.858  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:30.859   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@81ddb38:true
,08-31 11:29:30.871   871  1379 I ActivityManager: Start proc 3905:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 11:29:30.879  3886  3886 D LocalBluetoothProfileManager: Adding local MAP profile
,08-31 11:29:30.882  3886  3886 D BluetoothMap: Create BluetoothMap proxy object
,08-31 11:29:30.888  3886  3886 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 11:29:30.894   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-31 11:29:30.902  3905  3905 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 11:29:30.904  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:30.911   871  2251 I ActivityManager: Killing 2473:com.google.android.talk/u0a61 (adj 15): empty #17
,08-31 11:29:31.014  2682  2709 I bt_hci  : shut_down
,08-31 11:29:31.014  2682  2716 D bt_hwcfg: hw_epilog_process
,08-31 11:29:31.015  2682  2716 I bt_vendor: low_power_mode_cb
,08-31 11:29:31.038  2682  2716 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 11:29:31.038  2682  2716 I bt_vendor: epilog_cb
08-31 11:29:31.038  2682  2716 I bt_hci  : epilog_finished_callback
,08-31 11:29:31.043  2682  2709 I bt_hci_h4: hal_close
,08-31 11:29:31.044  2682  2709 I bt_userial_vendor: device fd = 51 close
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.072  3905  3905 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.072  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.073  3905  3905 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.073  3905  3905 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:31.073  3905  3905 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:31.104   871  1977 I ActivityManager: Start proc 3936:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-31 11:29:31.105   871  1977 I ActivityManager: Killing 3228:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-31 11:29:31.177  2682  2706 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:29:31.178  2682  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:29:31.180  2682  2705 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 11:29:31.180  2682  2682 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:29:31.185  2682  2682 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:29:31.186  2682  2682 D BtGatt.GattService: stop()
08-31 11:29:31.186  2682  2682 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:29:31.189  2682  2682 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:31.189  2682  2682 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:31.189  2682  2682 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:31.189  2682  2682 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:29:31.190  2682  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 11:29:31.190  2682  2705 D BluetoothAdapterProperties: Setting state to 10
08-31 11:29:31.190  2682  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 11:29:31.190  2682  2705 I BluetoothAdapterState: Entering OffState
,08-31 11:29:31.191   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-31 11:29:31.198  3936  3936 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-31 11:29:31.198  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:31.200  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:29:31.201  2682  2682 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 11:29:31.201  2682  2682 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:29:31.201  2682  2706 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:29:31.204  2682  2706 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:29:31.216  2682  2682 I art     : System.exit called, status: 0
,08-31 11:29:31.216  2682  2682 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:29:31.271   871   881 I ActivityManager: Process com.android.bluetooth (pid 2682) has died
,08-31 11:29:31.461  3936  3956 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-31 11:29:31.461  3936  3956 I Babel_SMS: MmsConfig.loadMmsSettings
,08-31 11:29:31.466  3936  3956 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-31 11:29:31.479  3936  3956 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 11:29:31.524  3936  3956 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-31 11:29:31.524  3936  3956 I Babel_SMS: MmsConfig.loadFromResources
,08-31 11:29:31.526  3936  3956 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 11:29:31.527  3936  3956 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-31 11:29:31.648  3936  3936 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:31.652  3936  3936 I Babel_Crash: startup - clean
,08-31 11:29:31.690  3936  3936 I Babel_telephony: TeleModule.launchCompleted
,08-31 11:29:31.707   871  2037 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 11:29:31.719  3936  3936 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-31 11:29:31.734  3936  3936 W Babel   : BAM#gBA: invalid account id: -1
,08-31 11:29:31.734  3936  3936 W Babel   : BAM#gBA: invalid account id: -1
08-31 11:29:31.734  3936  3936 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-31 11:29:31.742  3936  3962 I Babel   : deleted: false for 0
,08-31 11:29:31.746   871  1379 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-31 11:29:31.833   871   882 I ActivityManager: Start proc 3964:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 11:29:31.842  3936  3936 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:31.871  3936  3936 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:29:31.875  3905  3926 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:29:31.880  3936  3936 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:31.884  3936  3936 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:31.889  3936  3936 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:31.896  3964  3964 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 11:29:31.900  3936  3936 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:31.911  3936  3936 I vclib   : onServiceConnected
,08-31 11:29:31.956   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6373fb0:true
,08-31 11:29:31.959  3964  3964 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 11:29:31.994  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:32.040   871  1976 I ActivityManager: Start proc 3989:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-31 11:29:32.041  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:32.043   871  2036 I ActivityManager: Killing 3568:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-31 11:29:32.146  3989  3989 D AdapterServiceConfig: Adding HeadsetService
08-31 11:29:32.147  3989  3989 D AdapterServiceConfig: Adding A2dpService
08-31 11:29:32.147  3989  3989 D AdapterServiceConfig: Adding HidService
08-31 11:29:32.147  3989  3989 D AdapterServiceConfig: Adding HealthService
,08-31 11:29:32.147  3989  3989 D AdapterServiceConfig: Adding PanService
08-31 11:29:32.148  3989  3989 D AdapterServiceConfig: Adding GattService
08-31 11:29:32.148  3989  3989 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:29:32.153   871   882 I ActivityManager: Killing 3446:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 11:29:32.196  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:32.220  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:29:32.226  1754  1754 D SystemUpdateService: onCreate
,08-31 11:29:32.235  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:29:32.244  1754  4001 I SystemUpdateService: active receiver: enabled
,08-31 11:29:32.266  1754  4001 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:29:32.268  1754  4001 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:29:32.268  1754  4001 I SystemUpdateService: now status is 0 (complete)
08-31 11:29:32.268  1754  4001 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:29:32.268  1754  4001 I SystemUpdateService: file has been verified
08-31 11:29:32.269  1754  4001 I SystemUpdateService: OTA package size = 12249756
,08-31 11:29:32.271  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:29:32.273  1754  2435 I iu.UploadsManager: num queued entries: 0
,08-31 11:29:32.274  1754  2435 I iu.UploadsManager: num updated entries: 0
08-31 11:29:32.274  1754  4001 I SystemUpdateService: showing system update notification
,08-31 11:29:32.275  1754  2435 I iu.SyncManager: NEXT; no task
,08-31 11:29:32.288  1754  1754 D SystemUpdateService: onDestroy
,08-31 11:29:32.291  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:32.293  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:29:32.307   871  1540 I ActivityManager: Start proc 4003:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 11:29:32.337  4003  4003 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 11:29:32.340  4003  4003 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:32.345  4003  4003 D SprintDMHelper: simOperator: 
08-31 11:29:32.345  4003  4003 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:29:32.378   871   882 I ActivityManager: Start proc 4015:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 11:29:32.379   871   882 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-31 11:29:32.553   871  1379 I ActivityManager: Start proc 4030:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 11:29:32.557  3936  4029 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 11:29:32.562   871  1977 I ActivityManager: Killing 3663:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 11:29:32.631  4030  4030 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 11:29:32.691  4030  4030 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:29:32.691  4030  4030 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:29:32.691  4030  4030 I GAv4    :   adb logcat -s GAv4
,08-31 11:29:32.707  4030  4030 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:32.714  4030  4030 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:32.745  4030  4047 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:32.863  4030  4030 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 11:29:32.904  4030  4030 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 11:29:32.913  4030  4030 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2651-2654)
,08-31 11:29:32.913  4030  4030 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:29:32.923  4030  4030 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a86203}
,08-31 11:29:32.924  4030  4030 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 11:29:32.924  4030  4030 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:29:32.937  4030  4030 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 11:29:32.939  4030  4030 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:29:32.955  4030  4030 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 11:29:32.971  4030  4030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:29:32.971  4030  4030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 11:29:32.971  4030  4030 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:29:32.971  4030  4030 I Adreno  : Build Date                       : 10/20/15
08-31 11:29:32.971  4030  4030 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:29:32.971  4030  4030 I Adreno  : Local Branch                     : M14
08-31 11:29:32.971  4030  4030 I Adreno  : Remote Branch                    : 
08-31 11:29:32.971  4030  4030 I Adreno  : Remote Branch                    : 
08-31 11:29:32.971  4030  4030 I Adreno  : Reconstruct Branch               : 
,08-31 11:29:33.036  4030  4030 I NSApplication: Starting up...
,08-31 11:29:33.053  4030  4076 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 11:29:33.095   871  1943 I ActivityManager: Start proc 4081:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 11:29:33.096   871  1943 I ActivityManager: Killing 3680:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 11:29:33.181  4081  4081 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 11:29:33.374   871  1976 I ActivityManager: Killing 2233:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 11:29:33.744   871  2037 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-31 11:29:33.744   871  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:33.766  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:33.767  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:33.767  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.767   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:29:33.767  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:33.771  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:33.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:33.771  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:33.772  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:33.793   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-31 11:29:33.794   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 11:29:33.795   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 11:29:33.796   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:29:33.796   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 11:29:33.796   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 11:29:33.796   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,08-31 11:29:33.813   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:29:33.813   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=22.50 delta 1000 -> 994
,08-31 11:29:33.814   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:33.815   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '133 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 133 Failed to set address (No such device)'
,08-31 11:29:33.816   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:29:33.822   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 11:29:33.823   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:33.831   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:29:33.866   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:29:33.867   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:29:33.907   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:29:33.910  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:29:34.333  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:29:34.381  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:29:34.383  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:29:34.386   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:29:34.394   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 11:29:34.394   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:34.394   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:29:34.414   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:34.428   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:34.430   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-31 11:29:34.449   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.451   871  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 11:29:34.457   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:29:34.486   871  4106 D DhcpClient: Receive thread started
,08-31 11:29:34.572   871  1313 E native  : do suspend false
,08-31 11:29:34.591   871  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:29:34.610   871  4106 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,08-31 11:29:34.611   871  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,08-31 11:29:34.616   871  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:29:34.628   871  4106 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:29:34.629   871  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:29:34.634   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:34.644   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 11:29:34.646   871  1888 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:29:34.666   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:29:34.669   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:29:34.671   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:29:34.678   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 11:29:34.694   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:29:34.725   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 11:29:34.726   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 11:29:34.729   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 11:29:34.732   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 11:29:34.733   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 11:29:34.753   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.758   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-31 11:29:34.758   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.759   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 11:29:34.760   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:29:34.760   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.760   871  1315 D ConnectivityService:    accepting network in place of null
,08-31 11:29:34.763   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:29:34.771   871  4105 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134512, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 11:29:34.814   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:34.846   871  4104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
,08-31 11:29:34.849   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:34.859   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 11:29:34.860   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:34.868   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.869   871   888 D Tethering: MasterInitialState.processMessage what=3
08-31 11:29:34.882  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:34.882  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:34.882  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:34.883  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:34.886  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:34.886  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:34.886  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:34.887  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:34.906  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:29:34.909  1754  1754 D SystemUpdateService: onCreate
,08-31 11:29:34.912  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:29:34.912   871  4104 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:29:34 GMT], X-Android-Received-Millis=[1472635774912], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472635774887]}
08-31 11:29:34.914   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 11:29:34.914   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-31 11:29:34.914   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 11:29:34.917   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:29:34.920  1754  4118 I SystemUpdateService: active receiver: enabled
,08-31 11:29:34.925  1754  4118 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:29:34.927  1754  4118 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 11:29:34.927  1754  4118 I SystemUpdateService: now status is 0 (complete)
08-31 11:29:34.927  1754  4118 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:29:34.927  1754  4118 I SystemUpdateService: file has been verified
08-31 11:29:34.927  1754  4118 I SystemUpdateService: OTA package size = 12249756
,08-31 11:29:34.930  1754  4118 I SystemUpdateService: showing system update notification
,08-31 11:29:34.939  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 11:29:34.946  1754  2435 I iu.UploadsManager: num queued entries: 0
,08-31 11:29:34.948  1754  2435 I iu.UploadsManager: num updated entries: 0
,08-31 11:29:34.949  1754  4121 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 11:29:34.949  1754  4121 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 11:29:34.950  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:34.952  1754  2435 I iu.SyncManager: NEXT; no task
,08-31 11:29:34.953  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 11:29:34.953  1754  4121 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 11:29:34.953  1754  1754 D SystemUpdateService: onDestroy
08-31 11:29:34.956  4003  4003 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:29:34.960  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:29:34.962  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 11:29:34.965  4003  4003 D SprintDMHelper: simOperator: 
,08-31 11:29:34.965  4003  4003 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:29:34.992  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:29:34.992  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 11:29:34.992  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:29:34.992  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:29:35.010  1754  4121 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-31 11:29:35.076  3936  4123 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 11:29:35.859   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 11:29:36.603   871   881 I ActivityManager: Killing 3701:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 11:29:36.751   871  1539 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,08-31 11:29:36.751   871  1539 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:36.789  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 11:29:36.798   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 11:29:36.799   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-31 11:29:36.799   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 11:29:36.800   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:36.823   871  1888 D DhcpClient: Clearing IP address
08-31 11:29:36.824   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:36.827   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:36.837  1526  4128 V NativeCrypto: Read error: ssl=0x9b0fac00: I/O error during system call, Connection timed out
,08-31 11:29:36.839  1526  4128 V NativeCrypto: SSL shutdown failed: ssl=0x9b0fac00: I/O error during system call, Broken pipe
,08-31 11:29:36.844   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 11:29:36.844   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-31 11:29:36.850   871  4106 D DhcpClient: Receive thread stopped
08-31 11:29:36.853   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-31 11:29:36.853   397   397 E Parcel  : Reading a NULL string not supported here.
08-31 11:29:36.854   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:29:36.857   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:36.872   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 11:29:36.872   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:29:36.875  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:36.875  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:36.875  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:36.875  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:36.876  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:36.877  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:36.877  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:36.877  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:36.879   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:29:36.885  2167  2355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:36.916   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:36.951   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 11:29:36.952   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 11:29:36.953   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:36.957   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:29:36.961  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:36.962  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:36.969  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 11:29:36.974  1754  1754 D SystemUpdateService: onCreate
,08-31 11:29:36.977  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:29:36.984  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:29:36.990  1754  2435 I iu.UploadsManager: num queued entries: 0
,08-31 11:29:36.990  1754  2435 I iu.UploadsManager: num updated entries: 0
,08-31 11:29:36.992  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:36.993  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 11:29:36.996  4003  4003 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:37.000  4003  4003 D SprintDMHelper: simOperator: 
08-31 11:29:37.000  4003  4003 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 11:29:37.004  1754  4138 I SystemUpdateService: active receiver: enabled
,08-31 11:29:37.021  1754  4138 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:29:37.023   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-31 11:29:37.023   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 11:29:37.027  1754  2435 I iu.SyncManager: NEXT; no task
,08-31 11:29:37.027  3936  4143 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 11:29:37.031  1754  4138 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-31 11:29:37.031  1754  4138 I SystemUpdateService: now status is 0 (complete)
,08-31 11:29:37.032  1754  4138 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:29:37.033  1754  4138 I SystemUpdateService: file has been verified
08-31 11:29:37.033  1754  4138 I SystemUpdateService: OTA package size = 12249756
,08-31 11:29:37.036  1754  4138 I SystemUpdateService: showing system update notification
,08-31 11:29:37.045  1754  1754 D SystemUpdateService: onDestroy
,08-31 11:29:39.803  3989  3989 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:29:39.803   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a012c9:true
,08-31 11:29:39.810  3989  3989 I bt_bluedroid: init
,08-31 11:29:39.811  3989  4147 I BluetoothAdapterState: Entering OffState
,08-31 11:29:39.814  3989  4148 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:29:39.814  3989  4148 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:29:39.814  3989  4148 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:29:39.814  3989  4148 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 11:29:39.815  3989  3989 I bt_bluedroid: get_profile_interface socket
,08-31 11:29:39.818  3989  3989 I bt_bluedroid: get_profile_interface sdp
,08-31 11:29:39.821  3989  3999 I bt_bluedroid: config_hci_snoop_log
,08-31 11:29:39.821  3989  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:29:39.822   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:29:39.824  3989  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:29:39.832  3989  4147 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:29:39.832  3989  4147 D BluetoothAdapterProperties: Setting state to 14
08-31 11:29:39.832  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:29:39.834  3989  4147 D BluetoothBondStateMachine: make
,08-31 11:29:39.836  3989  4152 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:29:39.838  3989  4147 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:29:39.839  3989  3989 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:29:39.841  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:39.842  3989  3989 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:29:39.842  3989  3989 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:29:39.842  3989  3989 D BtGatt.GattService: start()
,08-31 11:29:39.842  3989  3989 I bt_bluedroid: get_profile_interface gatt
,08-31 11:29:39.843  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
08-31 11:29:39.843  3989  3989 D BtGatt.AdvertiseManager: advertise manager created,
,08-31 11:29:39.847  3989  3989 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:39.848  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:39.848  3989  3989 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 11:29:39.848  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:39.848  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 11:29:39.848  3989  4147 I bt_bluedroid: enable
08-31 11:29:39.848  3989  4148 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:29:39.849  3989  4148 I bt_hci  : start_up
,08-31 11:29:39.854  3989  4148 I bt_vendor: alloc value 0xb39f9189
,08-31 11:29:39.855  3989  4148 I bt_vendor: init
08-31 11:29:39.855  3989  4148 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 11:29:39.855  3989  4148 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:29:39.964  3989  4148 D bt_hci  : start_up starting async portion
,08-31 11:29:39.966  3989  4155 I bt_hci  : event_finish_startup
08-31 11:29:39.966  3989  4155 I bt_hci_h4: hal_open
,08-31 11:29:39.966  3989  4155 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:29:39.979  3989  4155 I bt_userial_vendor: device fd = 51 open
,08-31 11:29:40.006  3989  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:29:40.039  3989  4155 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:29:40.040  3989  4155 D bt_hwcfg: Target name = [BCM4354A2]
08-31 11:29:40.040  3989  4155 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:29:40.714  3989  4155 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:29:40.715  3989  4155 D bt_hwcfg: Settlement delay -- 100 ms
08-31 11:29:40.716  3989  4155 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:29:40.832  3989  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:29:40.834  3989  4155 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:29:40.864  3989  4155 I bt_hwcfg: vendor lib fwcfg completed
,08-31 11:29:40.864  3989  4155 I bt_vendor: firmware callback
,08-31 11:29:40.864  3989  4155 I bt_hci  : firmware_config_callback
,08-31 11:29:40.875  3989  4159 I bt_btu  : btu_task pending for preload complete event
,08-31 11:29:40.876  3989  4159 I bt_btu_task: Bluetooth chip preload is complete
,08-31 11:29:40.876  3989  4159 I bt_btu  : btu_task received preload complete event
,08-31 11:29:40.886  3989  4159 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:29:40.886  3989  4159 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:29:40.887  3989  4159 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 11:29:40.887  3989  4159 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:29:40.887  3989  4159 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 11:29:40.888  3989  4159 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:29:40.888  3989  4159 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 11:29:40.888  3989  4159 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:29:40.889  3989  4159 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 11:29:40.889  3989  4159 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:29:40.889  3989  4159 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 11:29:40.889  3989  4159 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 11:29:40.890  3989  4159 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:29:40.890  3989  4159 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:29:40.890  3989  4159 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:29:41.024  3989  4159 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-31 11:29:41.024  3989  4159 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-31 11:29:41.036  3989  4151 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 11:29:41.037  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 11:29:41.038  3989  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:29:41.042  3989  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:29:41.045  3989  4151 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:41.046  3989  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:41.047  3989  4151 D bt_hci  : do_postload posting postload work item
,08-31 11:29:41.047  3989  4155 I bt_hci  : event_postload
,08-31 11:29:41.047  3989  4155 I bt_vendor: sco_config_cb
,08-31 11:29:41.047  3989  4155 I bt_hci  : sco_config_callback postload finished.
,08-31 11:29:41.050  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.052  3989  4151 D bt_bte_conf: Device ID record 1 : primary
08-31 11:29:41.052  3989  4151 D bt_bte_conf:   vendorId            = 000f
,08-31 11:29:41.052  3989  4151 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 11:29:41.052  3989  4151 D bt_bte_conf:   product             = 1200
08-31 11:29:41.053  3989  4151 D bt_bte_conf:   version             = 1436
08-31 11:29:41.053  3989  4151 D bt_bte_conf:   clientExecutableURL = 
08-31 11:29:41.053  3989  4151 D bt_bte_conf:   serviceDescription  = 
08-31 11:29:41.053  3989  4151 D bt_bte_conf:   documentationURL    = 
,08-31 11:29:41.053  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.053  3989  4151 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:29:41.054  3989  4148 D bt_stack_manager: event_start_up_stack finished
,08-31 11:29:41.055  3989  4155 I bt_vendor: low_power_mode_cb
,08-31 11:29:41.056  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-31 11:29:41.057  3989  4147 D BluetoothAdapterProperties: Setting state to 15
,08-31 11:29:41.057  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 11:29:41.062  3989  4147 I BluetoothAdapterState: Entering BleOnState
,08-31 11:29:41.064  3989  4147 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 11:29:41.065  3989  4147 D BluetoothAdapterProperties: Setting state to 11
,08-31 11:29:41.065  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:29:41.070  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:41.071  3989  3989 D HeadsetService: Received start request. Starting profile...
,08-31 11:29:41.074  3989  3989 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 11:29:41.074  3989  3989 D HeadsetStateMachine: make
,08-31 11:29:41.082  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:41.084  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.087  3989  3989 D HeadsetStateMachine: max_hf_connections = 1
,08-31 11:29:41.087  3989  3989 I bt_bluedroid: get_profile_interface handsfree
08-31 11:29:41.088  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 11:29:41.088  3989  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:29:41.091  3989  4147 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:29:41.093  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
08-31 11:29:41.094  3989  3989 D A2dpService: Received start request. Starting profile...
08-31 11:29:41.094  3989  3989 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 11:29:41.094  3989  3989 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:29:41.100  3989  3989 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:29:41.100  3989  3989 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 11:29:41.100  3989  3989 D A2dpStateMachine: make
,08-31 11:29:41.101  3989  3989 I bt_bluedroid: get_profile_interface a2dp
08-31 11:29:41.102  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 11:29:41.104  3989  4168 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:29:41.104  3989  3989 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:29:41.105  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:41.106  3989  3989 D HidService: Received start request. Starting profile...
08-31 11:29:41.106  3989  3989 I bt_bluedroid: get_profile_interface hidhost
,08-31 11:29:41.106  3989  4151 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-31 11:29:41.106  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 11:29:41.107  3989  3989 D HidService: setHidService(): set to: null,
08-31 11:29:41.107  3886  3886 D BluetoothInputDevice: Proxy object connected
08-31 11:29:41.107  3886  3886 D HidProfile: Bluetooth service connected
08-31 11:29:41.108  3989  3989 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 11:29:41.109  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
08-31 11:29:41.109  3989  3989 D HealthService: Received start request. Starting profile...
08-31 11:29:41.111  3989  3989 I bt_bluedroid: get_profile_interface health
,08-31 11:29:41.112  3989  3989 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:29:41.112  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
08-31 11:29:41.113  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:41.114  3989  3989 D PanService: Received start request. Starting profile...
,08-31 11:29:41.114  3989  3989 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:29:41.114  3989  3989 I bt_bluedroid: get_profile_interface pan
08-31 11:29:41.115  3989  4151 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:29:41.116  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:29:41.117  3886  3886 D PanProfile: Bluetooth service connected
08-31 11:29:41.117  3989  3989 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:41.118  3989  3989 D BluetoothMapService: Received start request. Starting profile...
08-31 11:29:41.118  3886  3886 D BluetoothMap: Proxy object connected
,08-31 11:29:41.118  3989  3989 D BluetoothMapService: start()
08-31 11:29:41.119  3886  3886 D MapProfile: Bluetooth service connected
08-31 11:29:41.119  3886  3886 D BluetoothMap: getConnectedDevices()
,08-31 11:29:41.120  3989  3989 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 11:29:41.121  3989  3989 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 11:29:41.121  3989  3989 D BluetoothMapAppObserver: createReceiver()
08-31 11:29:41.121  3886  3886 D BluetoothMap: Bluetooth is Not enabled
,08-31 11:29:41.122  3989  3989 D BluetoothMapAppObserver: initObservers()
08-31 11:29:41.122  3989  3989 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:29:41.127  3989  3989 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:41.127  3989  3989 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:41.127  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:41.127  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:41.130  3989  4165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:29:41.130  3989  3989 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:41.131  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:41.132  3989  3989 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:41.132  3989  3989 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:29:41.132  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:41.132  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:41.132  3989  3989 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:41.133  3989  3989 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:41.133  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:41.133  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:41.133  3989  3989 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:41.133  3989  3989 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:41.134  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false,
08-31 11:29:41.134  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:41.134  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 11:29:41.134  3989  4147 D BluetoothAdapterProperties: ScanMode =  20,
,08-31 11:29:41.134  3989  4147 D BluetoothAdapterProperties: State =  11
,08-31 11:29:41.137  3989  4151 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:41.137  3989  4147 D BluetoothAdapterProperties: Setting state to 12
08-31 11:29:41.137  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:29:41.137  3989  4147 I BluetoothAdapterState: Entering OnState
08-31 11:29:41.137  1370  1393 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:41.139  3989  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:29:41.139  3886  3897 D BluetoothPan: onBluetoothStateChange on: true,
08-31 11:29:41.140  3886  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:41.140  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:41.140  1370  2047 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:29:41.140  1370  1370 D BluetoothA2dp: Proxy object connected
,08-31 11:29:41.141   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:29:41.141  1928  1941 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:41.141  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:41.141  1370  1393 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:41.143  1370  1370 D BluetoothMap: Proxy object connected
,08-31 11:29:41.143  1370  1370 D MapProfile: Bluetooth service connected
,08-31 11:29:41.143  1370  1370 D BluetoothMap: getConnectedDevices()
,08-31 11:29:41.143   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:29:41.143   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:41.144  1370  2047 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:41.144  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:41.145  3886  3898 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:29:41.146   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:41.146  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:41.146   871   871 D BluetoothA2dp: Proxy object connected
08-31 11:29:41.146  3886  3897 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:29:41.147  3989  3989 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:29:41.147  1370  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:29:41.147  3989  3989 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 11:29:41.149  3989  3989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:41.149  1370  1370 D BluetoothInputDevice: Proxy object connected
08-31 11:29:41.149  1370  1370 D HidProfile: Bluetooth service connected
08-31 11:29:41.149  1370  2047 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:29:41.151  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:41.151  1370  1370 D PanProfile: Bluetooth service connected
08-31 11:29:41.151  3989  3989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:41.152   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:29:41.154  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.154  3886  3886 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 11:29:41.156  3989  3989 D ObexServerSockets: Succeed to create listening sockets 
08-31 11:29:41.156  3989  3989 D ObexServerSockets0: startAccept()
08-31 11:29:41.156  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.156  3989  3989 D ObexServerSockets0: prepareForNewConnect()
08-31 11:29:41.157  3989  3989 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 11:29:41.157  3989  3989 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 11:29:41.157  3886  3886 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 11:29:41.158  3989  3989 D BluetoothMapService: onReceive
08-31 11:29:41.158  3989  3989 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:41.158  3989  3989 D BluetoothMapService: STATE_ON
08-31 11:29:41.158  3989  4175 D ObexServerSockets0: Accepting socket connection...
08-31 11:29:41.158  3989  4174 D ObexServerSockets0: Accepting socket connection...
,08-31 11:29:41.166  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:41.168  3886  3886 D BluetoothA2dp: Proxy object connected
,08-31 11:29:41.172  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:41.176  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:41.183  3886  3886 D BluetoothPbap: Proxy object connected
,08-31 11:29:41.183  3886  3886 D PbapServerProfile: Bluetooth service connected
08-31 11:29:41.183  1370  1370 D BluetoothPbap: Proxy object connected
08-31 11:29:41.184  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:41.189  3989  3989 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:29:41.189  3989  3989 D ObexServerSockets0: prepareForNewConnect()
,08-31 11:29:41.191  3989  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:41.205  3989  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:41.207  3989  4183 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:41.242   871   871 D BluetoothHeadset: Proxy object connected
,08-31 11:29:41.242   871   871 D BluetoothHeadset: Proxy object connected
,08-31 11:29:41.242  1370  1393 D BluetoothHeadset: Proxy object connected
,08-31 11:29:41.243   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:29:41.243  1370  1370 D HeadsetProfile: Bluetooth service connected
08-31 11:29:41.243  1928  2208 D BluetoothHeadset: Proxy object connected
08-31 11:29:41.243   871   888 D BluetoothHeadset: Proxy object connected
08-31 11:29:41.244   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:29:41.260  3886  3898 D BluetoothHeadset: Proxy object connected
,08-31 11:29:41.262  3886  3886 D HeadsetProfile: Bluetooth service connected
,08-31 11:29:42.765   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-31 11:29:42.769  3989  4147 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 11:29:42.770  3989  4147 D BluetoothAdapterProperties: Setting state to 13
,08-31 11:29:42.770  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 11:29:42.772  3989  4147 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:29:42.779  3989  4147 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:29:42.780  3989  3989 D BluetoothMapService: onReceive,
,08-31 11:29:42.780  3989  3989 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:42.781  3989  3989 D BluetoothMapService: STATE_TURNING_OFF
08-31 11:29:42.781  3989  3989 D BluetoothMapService: MAP Service closeService in
08-31 11:29:42.782  3989  3989 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 11:29:42.782  3989  3989 D ObexServerSockets0: shutdown(block = true)
08-31 11:29:42.783  3989  3989 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:29:42.784  3989  4175 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-31 11:29:42.785  3989  4174 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 11:29:42.786  3989  3989 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 11:29:42.786  3989  3989 I BtOppRfcommListener: stopping Accept Thread
,08-31 11:29:42.787  3989  4183 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:29:42.787  3989  4183 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:29:42.787  3989  4162 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 11:29:42.789  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:42.789  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:42.791  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:42.792  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:42.800  3989  4151 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:42.800  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 11:29:42.801  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:29:42.803  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:42.803  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:42.804  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:42.804  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:42.806  3989  3989 D HeadsetService: Received stop request...Stopping profile...
08-31 11:29:42.807  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:42.808   871   871 D BluetoothHeadset: Proxy object disconnected
,08-31 11:29:42.808  3886  3900 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:42.808   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:42.809  1370  2047 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:42.809   871   871 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:42.809  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.809  1928  1939 D BluetoothHeadset: Proxy object disconnected
08-31 11:29:42.809  3989  3989 D A2dpService: Received stop request...Stopping profile...
08-31 11:29:42.810  3989  4168 D A2dpStateMachine: Exit Disconnected: -1
08-31 11:29:42.810  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-31 11:29:42.811   871   871 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:42.812  1370  1370 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:42.812  3989  3989 D HidService: Received stop request...Stopping profile...
08-31 11:29:42.812  3989  3989 D HidService: Stopping Bluetooth HidService
08-31 11:29:42.815  1370  1370 D BluetoothInputDevice: Proxy object disconnected
,08-31 11:29:42.815  1370  1370 D HidProfile: Bluetooth service disconnected
08-31 11:29:42.815  3989  3989 D HealthService: Received stop request...Stopping profile...
08-31 11:29:42.816  3989  3989 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:42.816  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:42.816  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:42.816  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:42.818  3989  3989 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:29:42.818  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.818  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.819  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.819  3886  3886 D DockEventReceiver: finishStartingService: stopping service
08-31 11:29:42.820  3886  3886 D HeadsetProfile: Bluetooth service disconnected
08-31 11:29:42.818  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 11:29:42.820  3989  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:29:42.820  3989  3989 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:29:42.821  3989  3989 D PanService: Received stop request...Stopping profile...
08-31 11:29:42.821  3886  3886 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:42.822  3886  3886 D BluetoothInputDevice: Proxy object disconnected
08-31 11:29:42.822  3886  3886 D HidProfile: Bluetooth service disconnected
08-31 11:29:42.822  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:29:42.822  1370  1370 D PanProfile: Bluetooth service disconnected
,08-31 11:29:42.823  3989  3989 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:29:42.823  3989  3989 D BluetoothMapService: stop()
,08-31 11:29:42.825  3886  3886 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-31 11:29:42.825  3989  3989 D BluetoothMapAppObserver: deinitObservers()
08-31 11:29:42.825  3989  3989 D BluetoothMapAppObserver: removeReceiver()
,08-31 11:29:42.825  3886  3886 D PanProfile: Bluetooth service disconnected
08-31 11:29:42.826  1370  1370 D BluetoothMap: Proxy object disconnected
,08-31 11:29:42.826  1370  1370 D MapProfile: Bluetooth service disconnected
08-31 11:29:42.826  3989  3989 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:42.826  3989  3989 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:29:42.826  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:42.826  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:42.826  3886  3886 D BluetoothMap: Proxy object disconnected
08-31 11:29:42.826  3886  3886 D MapProfile: Bluetooth service disconnected
08-31 11:29:42.827  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-31 11:29:42.827  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.827  3989  3989 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:42.827  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.827  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:42.827  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:42.827  3989  4159 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:29:42.827  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:42.827  3989  4159 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 11:29:42.827  3989  4159 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:42.827  3989  4159 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:42.828  3989  3989 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:42.828  3989  3989 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:29:42.829  3989  3989 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:29:42.829  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:42.829  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:42.829  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:42.829  3989  3989 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:29:42.830  3989  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 11:29:42.830  3989  4151 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 11:29:42.830  3989  3989 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 11:29:42.830  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:29:42.831  3989  3989 V BluetoothAdapterState: isTurningOff()=true
08-31 11:29:42.831  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:42.831  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:42.831  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:42.832  3989  3989 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:29:42.832  3989  3989 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:29:42.833  3989  3989 D BluetoothMapService: MAP Service closeService in
08-31 11:29:42.833  3989  3989 V BluetoothAdapterState: isTurningOff()=true
,08-31 11:29:42.833  3989  3989 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:42.833  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:42.833  3989  3989 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:42.833  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 11:29:42.833  3989  4147 D BluetoothAdapterProperties: Setting state to 15
08-31 11:29:42.833  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 11:29:42.833  3989  3989 D BluetoothMapService: cleanup()
,08-31 11:29:42.833  3989  3989 D BluetoothMapService: MAP Service closeService in
08-31 11:29:42.834  1370  2047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:42.834  3989  4147 I BluetoothAdapterState: Entering BleOnState
08-31 11:29:42.835  1370  1370 D BluetoothPbap: Proxy object disconnected
08-31 11:29:42.835  1370  1370 D PbapServerProfile: Bluetooth service disconnected
08-31 11:29:42.835  3886  3898 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:29:42.838  3886  3897 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:29:42.841  3886  3898 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:42.841  1370  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 11:29:42.842   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:42.842  3886  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:42.846  1928  2096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:42.846  3886  3886 D BluetoothPbap: Proxy object disconnected
08-31 11:29:42.846  1370  1393 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:29:42.846  3886  3886 D PbapServerProfile: Bluetooth service disconnected
08-31 11:29:42.846   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:42.846   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 11:29:42.847  1370  2047 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:29:42.847  3886  3897 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:29:42.848   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:42.848  3886  3898 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:29:42.848  1370  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:29:42.849  1370  1393 D BluetoothPan: onBluetoothStateChange on: false
08-31 11:29:42.849  3989  4147 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 11:29:42.849  3989  4147 D BluetoothAdapterProperties: Setting state to 16
08-31 11:29:42.849  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-31 11:29:42.850  3989  4147 D BluetoothAdapterProperties: onBleDisable
,08-31 11:29:42.851  3989  4147 I BluetoothAdapterState: Entering PendingCommandState
08-31 11:29:42.851  3989  4148 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 11:29:42.852  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:42.852  3989  4159 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 11:29:42.852  3989  4159 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 11:29:42.853  3989  4151 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:42.853  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.854  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.855  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.856  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:42.861  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:42.863  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:43.052  3989  4151 I bt_hci  : shut_down
,08-31 11:29:43.071  3989  4155 I bt_vendor: low_power_mode_cb
,08-31 11:29:43.074  3989  4155 D bt_hwcfg: hw_epilog_process
,08-31 11:29:43.094  3989  4155 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-31 11:29:43.095  3989  4155 I bt_vendor: epilog_cb
,08-31 11:29:43.095  3989  4155 I bt_hci  : epilog_finished_callback
,08-31 11:29:43.103  3989  4151 I bt_hci_h4: hal_close
,08-31 11:29:43.104  3989  4151 I bt_userial_vendor: device fd = 51 close
,08-31 11:29:43.219  3989  4148 D bt_stack_manager: event_shut_down_stack finished.
,08-31 11:29:43.220  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 11:29:43.226  3989  3989 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:29:43.227  3989  3989 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 11:29:43.227  3989  3989 D BtGatt.GattService: stop()
08-31 11:29:43.227  3989  4147 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-31 11:29:43.228  3989  3989 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 11:29:43.233  3989  3989 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:43.233  3989  3989 V BluetoothAdapterState: isTurningOn()=false
,08-31 11:29:43.234  3989  3989 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:43.234  3989  3989 V BluetoothAdapterState: isBleTurningOff()=true
08-31 11:29:43.236  3989  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 11:29:43.237  3989  4147 D BluetoothAdapterProperties: Setting state to 10
08-31 11:29:43.237  3989  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-31 11:29:43.239  3989  4147 I BluetoothAdapterState: Entering OffState
08-31 11:29:43.240   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 11:29:43.262  3989  3989 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 11:29:43.263  3989  3989 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-31 11:29:43.268  3989  4148 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 11:29:43.263  3989  3989 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 11:29:43.280  3989  4148 D bt_stack_manager: event_clean_up_stack finished.
,08-31 11:29:43.285  3989  3989 I art     : System.exit called, status: 0
,08-31 11:29:43.285  3989  3989 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 11:29:43.337   871   882 I ActivityManager: Process com.android.bluetooth (pid 3989) has died
,08-31 11:29:45.767  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:45.768  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:48.775  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:48.776  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93dc6f added. We now have 6 listener(s)
08-31 11:29:48.776  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:48.780  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:48.780  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f8dd7c added. We now have 7 listener(s)
08-31 11:29:48.781  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:48.782  3815  3867 I System.out: IsBluetoothEnabled
,08-31 11:29:48.794  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:48.847   871   888 I ActivityManager: Start proc 4193:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 11:29:48.976  4193  4193 D AdapterServiceConfig: Adding HeadsetService
,08-31 11:29:48.976  4193  4193 D AdapterServiceConfig: Adding A2dpService
,08-31 11:29:48.976  4193  4193 D AdapterServiceConfig: Adding HidService
,08-31 11:29:48.976  4193  4193 D AdapterServiceConfig: Adding HealthService
,08-31 11:29:48.976  4193  4193 D AdapterServiceConfig: Adding PanService
,08-31 11:29:48.977  4193  4193 D AdapterServiceConfig: Adding GattService
,08-31 11:29:48.977  4193  4193 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 11:29:48.993   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cd1a42:true
,08-31 11:29:48.993  4193  4193 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 11:29:48.999  4193  4193 I bt_bluedroid: init
,08-31 11:29:48.999  4193  4206 I BluetoothAdapterState: Entering OffState
,08-31 11:29:49.005  4193  4207 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 11:29:49.005  4193  4207 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 11:29:49.006  4193  4207 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:29:49.006  4193  4207 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:29:49.008  4193  4193 I bt_bluedroid: get_profile_interface socket
,08-31 11:29:49.010  4193  4193 I bt_bluedroid: get_profile_interface sdp
,08-31 11:29:49.014  4193  4210 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 11:29:49.015  4193  4205 I bt_bluedroid: config_hci_snoop_log
,08-31 11:29:49.017  4193  4210 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:29:49.018   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:29:49.027  4193  4206 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 11:29:49.027  4193  4206 D BluetoothAdapterProperties: Setting state to 14
08-31 11:29:49.028  4193  4206 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 11:29:49.032  4193  4206 D BluetoothBondStateMachine: make
,08-31 11:29:49.037  4193  4211 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:29:49.046  4193  4206 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:29:49.047  4193  4193 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 11:29:49.053  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:49.054  4193  4193 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:29:49.055  4193  4193 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:29:49.055  4193  4193 D BtGatt.GattService: start()
,08-31 11:29:49.055  4193  4193 I bt_bluedroid: get_profile_interface gatt
,08-31 11:29:49.057  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:49.057  4193  4193 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:29:49.068  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:49.068  4193  4193 V BluetoothAdapterState: isTurningOn()=false
08-31 11:29:49.069  4193  4193 V BluetoothAdapterState: isBleTurningOn()=true
08-31 11:29:49.069  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:49.069  4193  4206 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 11:29:49.070  4193  4206 I bt_bluedroid: enable
08-31 11:29:49.071  4193  4207 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 11:29:49.072  4193  4207 I bt_hci  : start_up
,08-31 11:29:49.093  4193  4207 I bt_vendor: alloc value 0xb3a57189
,08-31 11:29:49.093  4193  4207 I bt_vendor: init
08-31 11:29:49.094  4193  4207 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 11:29:49.094  4193  4207 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 11:29:49.204  4193  4207 D bt_hci  : start_up starting async portion
,08-31 11:29:49.205  4193  4214 I bt_hci  : event_finish_startup
,08-31 11:29:49.205  4193  4214 I bt_hci_h4: hal_open
08-31 11:29:49.206  4193  4214 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 11:29:49.219  4193  4214 I bt_userial_vendor: device fd = 51 open
,08-31 11:29:49.246  4193  4214 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:29:49.278  4193  4214 D bt_hwcfg: Chipset BCM4354A2
,08-31 11:29:49.278  4193  4214 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 11:29:49.279  4193  4214 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 11:29:49.949  4193  4214 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 11:29:49.950  4193  4214 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 11:29:49.951  4193  4214 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 11:29:50.069  4193  4214 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 11:29:50.070  4193  4214 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 11:29:50.099  4193  4214 I bt_hwcfg: vendor lib fwcfg completed
,08-31 11:29:50.099  4193  4214 I bt_vendor: firmware callback
08-31 11:29:50.099  4193  4214 I bt_hci  : firmware_config_callback
,08-31 11:29:50.110  4193  4216 I bt_btu  : btu_task pending for preload complete event
,08-31 11:29:50.110  4193  4216 I bt_btu_task: Bluetooth chip preload is complete
,08-31 11:29:50.111  4193  4216 I bt_btu  : btu_task received preload complete event
,08-31 11:29:50.122  4193  4216 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:29:50.122  4193  4216 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 11:29:50.123  4193  4216 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:29:50.123  4193  4216 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 11:29:50.123  4193  4216 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 11:29:50.124  4193  4216 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:29:50.124  4193  4216 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:29:50.124  4193  4216 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 11:29:50.124  4193  4216 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 11:29:50.125  4193  4216 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:29:50.125  4193  4216 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:29:50.125  4193  4216 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:29:50.125  4193  4216 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:29:50.126  4193  4216 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:29:50.126  4193  4216 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:29:50.258  4193  4216 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,08-31 11:29:50.258  4193  4216 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,08-31 11:29:50.268  4193  4210 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 11:29:50.270  4193  4210 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 11:29:50.271  4193  4210 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 11:29:50.274  4193  4210 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 11:29:50.281  4193  4210 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:50.281  4193  4210 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:50.282  4193  4210 D bt_hci  : do_postload posting postload work item
,08-31 11:29:50.282  4193  4214 I bt_hci  : event_postload
,08-31 11:29:50.282  4193  4214 I bt_vendor: sco_config_cb
08-31 11:29:50.283  4193  4214 I bt_hci  : sco_config_callback postload finished.
,08-31 11:29:50.284  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:50.285  4193  4210 D bt_bte_conf: Device ID record 1 : primary
,08-31 11:29:50.285  4193  4210 D bt_bte_conf:   vendorId            = 000f
,08-31 11:29:50.286  4193  4210 D bt_bte_conf:   vendorIdSource      = 0001
08-31 11:29:50.286  4193  4210 D bt_bte_conf:   product             = 1200
08-31 11:29:50.286  4193  4210 D bt_bte_conf:   version             = 1436
08-31 11:29:50.286  4193  4210 D bt_bte_conf:   clientExecutableURL = 
08-31 11:29:50.286  4193  4210 D bt_bte_conf:   serviceDescription  = 
,08-31 11:29:50.287  4193  4210 D bt_bte_conf:   documentationURL    = 
08-31 11:29:50.287  4193  4210 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 11:29:50.288  4193  4207 D bt_stack_manager: event_start_up_stack finished
08-31 11:29:50.288  4193  4214 I bt_vendor: low_power_mode_cb
,08-31 11:29:50.289  4193  4206 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 11:29:50.290  4193  4206 D BluetoothAdapterProperties: Setting state to 15
08-31 11:29:50.290   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-31 11:29:50.291  4193  4206 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 11:29:50.293  4193  4206 I BluetoothAdapterState: Entering BleOnState
08-31 11:29:50.303  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-31 11:29:50.307  4193  4206 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 11:29:50.307  4193  4206 D BluetoothAdapterProperties: Setting state to 11
08-31 11:29:50.307  4193  4206 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 11:29:50.311  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.312  4193  4193 D HeadsetService: Received start request. Starting profile...
08-31 11:29:50.314   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 11:29:50.314   871   891 I Adreno  : Build Date                       : 10/20/15
08-31 11:29:50.314   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 11:29:50.314   871   891 I Adreno  : Local Branch                     : M14
08-31 11:29:50.314   871   891 I Adreno  : Remote Branch                    : 
08-31 11:29:50.314   871   891 I Adreno  : Remote Branch                    : 
08-31 11:29:50.314   871   891 I Adreno  : Reconstruct Branch               : 
08-31 11:29:50.315  4193  4193 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 11:29:50.316  4193  4193 D HeadsetStateMachine: make
,08-31 11:29:50.321  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:50.329  4193  4193 D HeadsetStateMachine: max_hf_connections = 1
,08-31 11:29:50.329  4193  4193 I bt_bluedroid: get_profile_interface handsfree
,08-31 11:29:50.331  4193  4210 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 11:29:50.335  4193  4210 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 11:29:50.344  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.344  4193  4206 I BluetoothAdapterState: Entering PendingCommandState
,08-31 11:29:50.348  4193  4193 D A2dpService: Received start request. Starting profile...
,08-31 11:29:50.350  4193  4193 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 11:29:50.352  4193  4193 I bt_bluedroid: get_profile_interface avrcp
,08-31 11:29:50.358  4193  4193 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:29:50.362  4193  4193 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 11:29:50.366  4193  4193 D A2dpStateMachine: make
,08-31 11:29:50.367  4193  4193 I bt_bluedroid: get_profile_interface a2dp
,08-31 11:29:50.368  4193  4210 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 11:29:50.369  4193  4225 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:29:50.371  4193  4193 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:29:50.371  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.372  4193  4193 D HidService: Received start request. Starting profile...
,08-31 11:29:50.372   280  2371 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (133 us)
08-31 11:29:50.372  4193  4193 I bt_bluedroid: get_profile_interface hidhost
,08-31 11:29:50.372  4193  4193 D HidService: setHidService(): set to: null
08-31 11:29:50.373  4193  4210 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
,08-31 11:29:50.373  4193  4210 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 11:29:50.373  4193  4193 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:29:50.374  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.375  4193  4193 D HealthService: Received start request. Starting profile...
,08-31 11:29:50.378  4193  4193 I bt_bluedroid: get_profile_interface health
,08-31 11:29:50.380  4193  4193 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:29:50.381  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.383  4193  4193 D PanService: Received start request. Starting profile...
,08-31 11:29:50.383  4193  4193 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-31 11:29:50.384  4193  4193 I bt_bluedroid: get_profile_interface pan
,08-31 11:29:50.385  4193  4210 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:29:50.388  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:50.388  4193  4222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 11:29:50.389  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:50.389  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:50.389  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:50.389  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:50.391  4193  4193 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
,08-31 11:29:50.392  4193  4193 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:29:50.392  4193  4193 D BluetoothMapService: start()
,08-31 11:29:50.394  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
08-31 11:29:50.397  4193  4193 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 11:29:50.397  4193  4193 D BluetoothMapAppObserver: createReceiver()
,08-31 11:29:50.398  4193  4193 D BluetoothMapAppObserver: initObservers()
08-31 11:29:50.399  4193  4193 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isTurningOn()=true
,08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:50.404  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isTurningOff()=false
,08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:50.405  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
08-31 11:29:50.407  4193  4193 V BluetoothAdapterState: isTurningOff()=false
08-31 11:29:50.408  4193  4193 V BluetoothAdapterState: isTurningOn()=true
08-31 11:29:50.408  4193  4193 V BluetoothAdapterState: isBleTurningOn()=false
08-31 11:29:50.408  4193  4193 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 11:29:50.408  4193  4206 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 11:29:50.408  4193  4206 D BluetoothAdapterProperties: ScanMode =  20
,08-31 11:29:50.408  4193  4206 D BluetoothAdapterProperties: State =  11
,08-31 11:29:50.411  4193  4210 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:50.411  4193  4206 D BluetoothAdapterProperties: Setting state to 12
08-31 11:29:50.411  4193  4206 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 11:29:50.411  4193  4210 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:29:50.412  1370  2047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:50.412  4193  4206 I BluetoothAdapterState: Entering OnState
08-31 11:29:50.415  1370  1370 D BluetoothA2dp: Proxy object connected
,08-31 11:29:50.415  3886  3897 D BluetoothPan: onBluetoothStateChange on: true
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:50.417  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:50.418  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:50.421  3886  3898 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:29:50.424  3886  3900 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:50.424  1370  1382 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:50.425   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:50.425  3886  3897 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:50.425  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 11:29:50.426  4193  4193 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 11:29:50.427  1928  2096 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 11:29:50.427  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:50.427  1370  2047 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:50.429   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 11:29:50.429  4193  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:50.429   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-31 11:29:50.429  1370  1393 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:29:50.430  4193  4193 D ObexServerSockets: Succeed to create listening sockets 
,08-31 11:29:50.430  4193  4193 D ObexServerSockets0: startAccept()
,08-31 11:29:50.430  4193  4193 D ObexServerSockets0: prepareForNewConnect()
08-31 11:29:50.431  3886  3900 D BluetoothMap: onBluetoothStateChange: up=true
08-31 11:29:50.432   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:50.432  4193  4193 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 11:29:50.433  4193  4193 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 11:29:50.433  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:29:50.433  3886  3886 D PanProfile: Bluetooth service connected
,08-31 11:29:50.433  3886  3886 D BluetoothA2dp: Proxy object connected
08-31 11:29:50.434   871   871 D BluetoothA2dp: Proxy object connected
,08-31 11:29:50.434  4193  4231 D ObexServerSockets0: Accepting socket connection...
08-31 11:29:50.436  3886  3897 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:29:50.436  1370  1370 D BluetoothMap: Proxy object connected
08-31 11:29:50.436  1370  1370 D MapProfile: Bluetooth service connected
08-31 11:29:50.437  1370  1370 D BluetoothMap: getConnectedDevices()
,08-31 11:29:50.439  1370  2047 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 11:29:50.441  1370  1370 D BluetoothInputDevice: Proxy object connected
,08-31 11:29:50.441  1370  1370 D HidProfile: Bluetooth service connected
,08-31 11:29:50.441  1370  1382 D BluetoothPan: onBluetoothStateChange on: true
,08-31 11:29:50.444  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:50.444  1370  1370 D PanProfile: Bluetooth service connected
,08-31 11:29:50.444   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 11:29:50.445  4193  4232 D ObexServerSockets0: Accepting socket connection...
08-31 11:29:50.445  4193  4193 D BluetoothMapService: onReceive
,08-31 11:29:50.445  4193  4193 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:50.445  4193  4193 D BluetoothMapService: STATE_ON
08-31 11:29:50.446  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:50.447  3886  3886 D BluetoothInputDevice: Proxy object connected
08-31 11:29:50.447  3886  3886 D HidProfile: Bluetooth service connected
08-31 11:29:50.448  3886  3886 D BluetoothMap: Proxy object connected
08-31 11:29:50.448  3886  3886 D MapProfile: Bluetooth service connected
,08-31 11:29:50.448  3886  3886 D BluetoothMap: getConnectedDevices()
08-31 11:29:50.453  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:50.460  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:50.463  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:50.473  1370  1370 D BluetoothPbap: Proxy object connected
,08-31 11:29:50.473  4193  4193 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 11:29:50.474  4193  4193 D ObexServerSockets0: prepareForNewConnect()
08-31 11:29:50.474  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:50.470  3886  3886 D BluetoothPbap: Proxy object connected
,08-31 11:29:50.477  3886  3886 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:50.478  4193  4236 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:50.497  4193  4240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:50.498  4193  4240 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:50.524   871   871 D BluetoothHeadset: Proxy object connected
,08-31 11:29:50.525  1370  1393 D BluetoothHeadset: Proxy object connected
,08-31 11:29:50.525  1370  1370 D HeadsetProfile: Bluetooth service connected
08-31 11:29:50.526   871   888 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.525  3886  3898 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.526   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.526  3886  3886 D HeadsetProfile: Bluetooth service connected
,08-31 11:29:50.526  1370  1382 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.526   871   871 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.527  1928  1941 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.527  1928  2208 D BluetoothHeadset: Proxy object connected
08-31 11:29:50.527  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-31 11:29:50.529   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:29:50.529   871   888 D BluetoothHeadset: Proxy object connected
,08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:50.821  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:50.829  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:50.833  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:50.834  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5a4605 added. We now have 8 listener(s)
08-31 11:29:50.835  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:50.841   871  1976 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,08-31 11:29:50.841   871  1976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:50.859  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:50.860   871  2036 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-31 11:29:50.861   871  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 11:29:50.873   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:50.887  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:50.889  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:50.890  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:50.893  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:50.893  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 11:29:50.894  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:29:50.896  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@df8d48d Bundle[{}]
,08-31 11:29:50.896  3815  3867 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:50.897  3815  3867 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 11:29:50.898  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:29:50.898  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:29:50.899  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 11:29:50.900  3815  3867 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:29:50.907  3815  3867 I System.out: Running OutgoingSocketThread
,08-31 11:29:50.908  3815  4247 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-31 11:29:50.908   871  1313 D WifiConfigStore: loaded 0 passpoint configs
08-31 11:29:50.909  3815  4247 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42991
08-31 11:29:50.909  3815  4247 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 11:29:50.909   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 11:29:50.910   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 11:29:50.911   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 11:29:50.911   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-31 11:29:50.911   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 11:29:50.911   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 11:29:50.953  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:29:50.953  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 11:29:50.997   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-31 11:29:50.998   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 11:29:50.999  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@df8d48d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7a3865a, 16908290=android.view.AbsSavedState$1@7a3865a}, android:focusedViewId=100}]}]
,08-31 11:29:51.000  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-31 11:29:51.001  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:29:51.001  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 11:29:51.002   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.40 delta 1000 -> 1000
,08-31 11:29:51.003   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:51.005   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,08-31 11:29:51.005   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:29:51.007   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-31 11:29:51.009   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 11:29:51.009   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:51.012   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-31 11:29:51.012   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-31 11:29:51.014   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-31 11:29:51.027   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 11:29:51.028   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 11:29:51.050   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 11:29:51.066   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 11:29:51.067  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 11:29:51.237   280   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-31 11:29:51.240   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-31 11:29:51.242   871  1338 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
,08-31 11:29:51.246   871   891 I DreamManagerService: Entering dreamland.
,08-31 11:29:51.247   871   891 I PowerManagerService: Dozing...
,08-31 11:29:51.249   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-31 11:29:51.341   375  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-31 11:29:51.343   375  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-31 11:29:51.344   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:29:51.357   871  1313 E native  : do suspend false
,08-31 11:29:51.375   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:29:51.379  1916  4250 D NfcService: Discovery configuration equal, not updating.
,08-31 11:29:51.469   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-31 11:29:51.469   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-31 11:29:51.518   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-31 11:29:51.519  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 11:29:51.534  1473  1473 E wpa_supplicant: PNO: In assoc process
,08-31 11:29:51.535   871  1313 E WifiStateMachine:  Fail to set up pno, want true now false
08-31 11:29:51.540   871  1313 E native  : do suspend true
,08-31 11:29:51.559  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:29:51.559  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 11:29:51.561   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 11:29:51.567   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:29:51.568   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:51.568   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 11:29:51.578   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:51.587   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:51.587   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:29:51.598   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 11:29:51.632   871  4257 D DhcpClient: Receive thread started
,08-31 11:29:51.718   871  1313 E native  : do suspend false
,08-31 11:29:51.737   871  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 11:29:51.752   871  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-31 11:29:51.754   871  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-31 11:29:51.757   871  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 11:29:51.772   871  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 11:29:51.773   871  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 11:29:51.778   371   869 D CommandListener: Setting iface cfg
,08-31 11:29:51.790   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 11:29:51.792   871  1888 D DhcpClient: Scheduling renewal in 86399s
,08-31 11:29:51.793   871  1313 E native  : do suspend true
,08-31 11:29:51.820   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 11:29:51.823   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 11:29:51.824   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 11:29:51.827   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-31 11:29:51.834   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 11:29:51.904   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:29:51.904   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 11:29:51.906   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 11:29:51.907   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 11:29:51.908   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-31 11:29:51.908   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,08-31 11:29:51.915  3815  3867 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-31 11:29:51.916  3815  3867 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-31 11:29:51.922   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:29:51.925  3815  3867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-31 11:29:51.926  3815  3867 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 11:29:51.927  3815  3867 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-31 11:29:51.928   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-31 11:29:51.928   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-31 11:29:51.929   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-31 11:29:51.929   871  1315 D ConnectivityService:    accepting network in place of null
,08-31 11:29:51.929   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 11:29:51.930   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 11:29:51.930   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 11:29:51.931  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:51.931  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72bd08b added. We now have 2 listener(s)
08-31 11:29:51.933  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:51.933  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:51.933  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:51.933  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:51.934  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db45568 added. We now have 9 listener(s)
08-31 11:29:51.934  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:51.934  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:51.937  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:51.942  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:51.944  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:51.944  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:51.944  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:51.944  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a03ae26 added. We now have 3 listener(s)
08-31 11:29:51.945   871  4256 D NetlinkSocketObserver: NeighborEvent{elapsedMs=151686, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-31 11:29:51.946  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:51.946  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:51.946  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:51.946  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:51.947  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a04ea67 added. We now have 10 listener(s)
08-31 11:29:51.947  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:51.947  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:51.947  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:51.947  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:51.947  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:51.947  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:51.947  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:51.947  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:51.947  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:51.947  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72bd08b removed from the list
08-31 11:29:51.948  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:51.948  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db45568 removed from the list
08-31 11:29:51.950  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:51.950  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:51.950  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:51.950  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:51.950  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:51.951  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:51.951  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:51.951  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:51.952  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db45568 not in the list
08-31 11:29:51.952  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:51.952  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:51.953  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:51.953  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:51.953  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:51.953  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a04ea67 removed from the list
08-31 11:29:51.953  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:51.953  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:51.953  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:51.953  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:51.953  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a03ae26 removed from the list
08-31 11:29:51.954  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:51.954  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d6014 added. We now have 2 listener(s)
08-31 11:29:51.956  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:51.956  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:51.956  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:51.956  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:51.956  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81030bd added. We now have 9 listener(s)
08-31 11:29:51.956  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:51.956  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:51.958  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:51.963  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:51.965  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:51.965  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:51.965  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:51.965  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16bc603 added. We now have 3 listener(s)
08-31 11:29:51.967  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:51.967  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:51.967  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:51.968  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:51.968  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8a6980 added. We now have 10 listener(s)
08-31 11:29:51.968  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:51.968  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:51.968  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:51.968  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:51.968  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:51.968  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:51.970  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:51.971  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:29:51.971  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:51.973  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:51.975  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:51.976  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:29:51.976  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:51.976   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 11:29:51.979  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:51.979  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:51.979  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:51.980  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:51.983  4193  4223 D BtGatt.GattService: registerClient() - UUID=5dbe7702-5f2c-490f-975b-ce4fec9d94e5
08-31 11:29:51.983  4193  4210 D BtGatt.GattService: onClientRegistered() - UUID=5dbe7702-5f2c-490f-975b-ce4fec9d94e5, clientIf=5
08-31 11:29:51.984  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:29:51.985  4193  4242 D BtGatt.GattService: start scan with filters
08-31 11:29:51.988  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:51.988  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:51.988  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:51.988  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:51.988  4193  4213 D BtGatt.ScanManager: handling starting scan
08-31 11:29:51.990  4193  4213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b754451
08-31 11:29:51.991  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:51.991  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:51.991  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:51.992  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:29:51.993  4193  4210 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:29:51.993  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:51.993  4193  4213 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:29:51.995  3815  3867 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:51.995  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:51.995  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:29:51.995  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:51.995  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:51.996  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:51.996  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:51.996  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:51.996  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:51.996  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:51.996  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:51.996  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:51.996  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:29:51.996  4193  4213 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:51.996  4193  4213 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:29:51.997  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:51.999  4193  4242 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:51.999  4193  4210 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:51.999  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.000  4193  4205 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 11:29:52.000  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:52.000  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:52.000  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:52.000  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:52.000  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:29:52.001  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:52.001  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:52.001  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:52.001  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:52.002  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:52.002  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:29:52.002  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.003  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.003  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.003  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:52.004  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:52.004  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:52.004  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:52.004  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.005  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.005  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:52.005  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.005  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d6014 removed from the list
08-31 11:29:52.005  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.005  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81030bd removed from the list
08-31 11:29:52.005  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:52.005  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.005  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.005  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.006  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.006  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.006  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.006  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81030bd not in the list
08-31 11:29:52.006  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.006  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.007  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.007  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.007  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.007  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8a6980 removed from the list
08-31 11:29:52.007  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.007  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.007  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.007  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.008  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16bc603 removed from the list
08-31 11:29:52.008  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:52.008  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec9dac added. We now have 2 listener(s)
,08-31 11:29:52.010  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.010  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.010  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:52.010  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:52.010  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d1ba75 added. We now have 9 listener(s)
08-31 11:29:52.010  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:52.010  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:52.013  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:29:52.013  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:52.013  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.013  4193  4213 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:52.015  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:29:52.015  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.016  4193  4213 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:52.016  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:52.017  4193  4210 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:29:52.017  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.018   871  4255 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.206,2a00:1450:400d:807::200e
08-31 11:29:52.019  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.019  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:52.019  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:52.020  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b15f27b added. We now have 3 listener(s)
08-31 11:29:52.021  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.022  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.022  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.022  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:52.022  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:52.023  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5be898 added. We now have 10 listener(s)
08-31 11:29:52.023  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:52.023  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:52.023  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.023  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:52.023  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:52.024  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:52.024  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:52.024  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:52.024   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 11:29:52.027  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 11:29:52.027  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:52.027   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 11:29:52.027   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:29:52.028   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 11:29:52.031   871   888 D Tethering: MasterInitialState.processMessage what=3
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:52.037  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:52.038  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:52.039  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:29:52.039  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:52.039  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.041  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:52.041  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:52.041  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:52.042  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:52.042  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.044  4193  4205 D BtGatt.GattService: registerClient() - UUID=7190c9ab-17ef-4998-87e8-b34fa41de08f
08-31 11:29:52.044  4193  4210 D BtGatt.GattService: onClientRegistered() - UUID=7190c9ab-17ef-4998-87e8-b34fa41de08f, clientIf=5
08-31 11:29:52.044  3815  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 11:29:52.044  4193  4204 D BtGatt.GattService: start scan with filters
08-31 11:29:52.046  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:52.047  4193  4213 D BtGatt.ScanManager: handling starting scan
08-31 11:29:52.047  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:52.047  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:52.047  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:52.048  4193  4210 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:29:52.048  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.048  4193  4213 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 11:29:52.049  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:52.049  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:52.049  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:52.050  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 11:29:52.050  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:52.050  4193  4213 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:52.050  4193  4213 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-31 11:29:52.050  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:29:52.052  4193  4210 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:52.052  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:52.052  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:29:52.052  3815  3867 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 11:29:52.052  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:52.052  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:52.053  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:52.053  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.053  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.053  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:52.053  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.053  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec9dac removed from the list
,08-31 11:29:52.053  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.053  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d1ba75 removed from the list
08-31 11:29:52.053  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:29:52.053  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:52.053  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.053  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:52.054  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.054  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:52.054  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:52.054  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.055  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d1ba75 not in the list
,08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:52.055  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:52.055  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:52.055  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:29:52.056  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:52.056  4193  4242 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:52.057  4193  4205 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:29:52.057  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:52.057  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:52.057  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:52.057  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:52.057  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:29:52.057  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:29:52.057  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.058  4193  4213 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:52.058  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:52.058  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:52.058  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:52.058  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:52.058  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 11:29:52.058  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:52.059  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.059  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.059  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:52.059  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.059  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.059  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:52.059  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5be898 removed from the list
08-31 11:29:52.059  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.059  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.060  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.060  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:29:52.060  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b15f27b removed from the list
08-31 11:29:52.060  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:29:52.060  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.060  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:52.060  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@672f644 added. We now have 2 listener(s)
08-31 11:29:52.060  4193  4213 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 11:29:52.061  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.061  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.061  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:52.062  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:52.062  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293c32d added. We now have 9 listener(s)
08-31 11:29:52.062  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:52.062  4193  4210 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:29:52.062  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:52.062  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:52.063  1754  1754 D SystemUpdateService: onCreate
08-31 11:29:52.065  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:52.067  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:52.068  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:52.069  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.069  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:52.070  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:52.070  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a35f3 added. We now have 3 listener(s)
08-31 11:29:52.071  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:52.072  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.072  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.072  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:52.072  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:52.072  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cb32b0 added. We now have 10 listener(s)
08-31 11:29:52.072  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:52.073  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:52.073  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:52.073  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:52.073  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:52.073  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:52.073  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.075  3815  3867 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 11:29:52.075  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:52.078  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:52.078  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 11:29:52.078  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:52.081  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:52.081  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:52.081  3815  3867 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:52.081  3815  3867 D BluetoothAdapter: STATE_ON
,08-31 11:29:52.083  4193  4242 D BtGatt.GattService: registerClient() - UUID=697f27be-90b3-487d-be54-f1a22f8d754e
,08-31 11:29:52.084  4193  4210 D BtGatt.GattService: onClientRegistered() - UUID=697f27be-90b3-487d-be54-f1a22f8d754e, clientIf=5
,08-31 11:29:52.084   871  4255 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:29:52 GMT], X-Android-Received-Millis=[1472635792084], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472635792055]}
,08-31 11:29:52.085   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 11:29:52.086   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-31 11:29:52.086   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 11:29:52.087   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 11:29:52.088  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 11:29:52.088  4193  4205 D BtGatt.GattService: start scan with filters
,08-31 11:29:52.090  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:52.090  4193  4213 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:52.090  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:52.090  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:52.090  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:52.092  4193  4210 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 11:29:52.092  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.092  4193  4213 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 11:29:52.092  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:52.092  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:52.093  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:52.093  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-31 11:29:52.093  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 11:29:52.093  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.093  4193  4213 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:52.093  4193  4213 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 11:29:52.094  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 11:29:52.096  4193  4210 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 11:29:52.096  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.097  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-31 11:29:52.097  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.099  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:52.099  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:52.099  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:52.099  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.100  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.100  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:52.100  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.100  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@672f644 removed from the list
08-31 11:29:52.100  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.100  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293c32d removed from the list
08-31 11:29:52.100  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:52.100  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:52.101  1754  4266 I SystemUpdateService: active receiver: enabled
,08-31 11:29:52.102  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.102  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:52.102  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:52.102  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:52.103  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.103  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.103  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.104  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@293c32d not in the list
,08-31 11:29:52.104  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:52.104  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:52.104  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:52.104  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:52.104  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 11:29:52.104  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:52.105  3815  3867 D BluetoothAdapter: STATE_ON
08-31 11:29:52.105  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-31 11:29:52.106  4193  4205 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:52.106  4193  4204 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 11:29:52.107  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:52.107  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:52.107  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:52.107  4193  4210 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 11:29:52.107  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:52.107  4193  4213 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:52.107  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:52.108  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:29:52.108  4003  4003 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:52.109  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:52.109  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:52.109  3815  3867 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:52.109  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:52.110  4193  4210 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 11:29:52.110  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 11:29:52.110  4193  4213 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 11:29:52.110  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:52.112  4193  4210 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 11:29:52.112  4193  4210 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 11:29:52.112  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:52.112  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:52.112  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.112  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.112  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:52.112  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cb32b0 removed from the list
08-31 11:29:52.112  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:52.113  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:52.113  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.113  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.113  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.113  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a35f3 removed from the list
08-31 11:29:52.114  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:52.114  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b28c9dc added. We now have 2 listener(s)
,08-31 11:29:52.115  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.115  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.115  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:52.115  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:52.116  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a072ae5 added. We now have 9 listener(s)
08-31 11:29:52.116  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:52.116  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:52.118  4003  4003 D SprintDMHelper: simOperator: 
,08-31 11:29:52.118  4003  4003 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-31 11:29:52.118  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:52.122  1754  4269 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 11:29:52.122  1754  4269 W BaseAppContext: Using Auth Proxy for data requests.
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:52.123  3815  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:52.124  3815  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:52.125  3815  3867 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:52.125  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:52.125  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f84706b added. We now have 3 listener(s)
,08-31 11:29:52.127  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.127  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 11:29:52.127  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:52.127  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:52.127  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:52.127  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@366a7c8 added. We now have 10 listener(s)
08-31 11:29:52.127  3815  3867 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:52.128  3815  3867 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:52.128  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:52.128  3815  3867 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:52.128  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.128  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.128  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:52.128  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.128  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.128  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b28c9dc removed from the list
08-31 11:29:52.128  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:52.128  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a072ae5 removed from the list
08-31 11:29:52.128  3815  3867 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:52.128  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:52.129  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:52.130  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.130  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.130  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.130  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:52.131  3815  3867 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a072ae5 not in the list
08-31 11:29:52.131  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.131  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.131  1754  4269 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 11:29:52.131  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:52.131  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:52.131  3815  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:52.132  3815  3867 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@366a7c8 removed from the list
,08-31 11:29:52.132  3815  3867 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:52.132  3815  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:52.132  3815  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:52.132  3815  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:52.132  3815  3867 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f84706b removed from the list
,08-31 11:29:52.132  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:52.133  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:52.133  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:29:52.133  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:52.133  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:29:52.133  3815  3867 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:52.137  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:29:52.139  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 11:29:52.143  3815  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
08-31 11:29:52.143  3815  4273 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-31 11:29:52.143  3815  4273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:29:52.145  3815  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
08-31 11:29:52.145  3815  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
,08-31 11:29:52.145  3815  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 11:29:52.146  3815  3867 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:29:52.147  3815  3867 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:29:52.147  3815  3867 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:29:52.147  3815  3867 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-31 11:29:52.147  3815  3867 D com.test.thalitest.ThaliTestRunner: Total duration: 21868 ms
08-31 11:29:52.148  3815  3867 I jxcore-log: Total number of executed tests:  80
08-31 11:29:52.148  3815  3867 I jxcore-log: 
08-31 11:29:52.148  3815  3867 I jxcore-log: Number of passed tests:  80
08-31 11:29:52.148  3815  3867 I jxcore-log: 
08-31 11:29:52.149  3815  3867 I jxcore-log: Number of failed tests:  0
08-31 11:29:52.149  3815  3867 I jxcore-log: 
08-31 11:29:52.149  3815  3867 I jxcore-log: Number of ignored tests:  0
08-31 11:29:52.149  3815  3867 I jxcore-log: 
08-31 11:29:52.149  3815  3867 I jxcore-log: Total duration:  21868
08-31 11:29:52.149  3815  3867 I jxcore-log: 
08-31 11:29:52.150  3815  3867 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:29:52.150  3815  3867 I jxcore-log: 
,08-31 11:29:52.152  3815  3867 I jxcore-log: My device name is: motorola-Nexus 6
08-31 11:29:52.152  3815  3867 I jxcore-log: 
08-31 11:29:52.154  3815  3867 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:29:52.154  3815  3867 I jxcore-log: 
08-31 11:29:52.154  1754  2435 I iu.UploadsManager: num queued entries: 0
08-31 11:29:52.156  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.156  3815  3867 I jxcore-log: 
08-31 11:29:52.156  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.156  3815  3867 I jxcore-log: 
08-31 11:29:52.158  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.158  3815  3867 I jxcore-log: 
,08-31 11:29:52.159  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.159  3815  3867 I jxcore-log: 
,08-31 11:29:52.160  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.160  3815  3867 I jxcore-log: 
08-31 11:29:52.162  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.162  3815  3867 I jxcore-log: 
08-31 11:29:52.162  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.162  3815  3867 I jxcore-log: 
08-31 11:29:52.163  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.163  3815  3867 I jxcore-log: 
08-31 11:29:52.164  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:29:52.164  3815  3867 I jxcore-log: 
08-31 11:29:52.164  1754  2435 I iu.UploadsManager: num updated entries: 0
08-31 11:29:52.164  1754  2435 I iu.SyncManager: NEXT; no task
08-31 11:29:52.164  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:52.164  3815  3867 I jxcore-log: 
08-31 11:29:52.165  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:52.165  3815  3867 I jxcore-log: 
08-31 11:29:52.166  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.166  3815  3867 I jxcore-log: 
08-31 11:29:52.166  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.166  3815  3867 I jxcore-log: 
08-31 11:29:52.167  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.167  3815  3867 I jxcore-log: 
,08-31 11:29:52.167  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.167  3815  3867 I jxcore-log: 
,08-31 11:29:52.168  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.168  3815  3867 I jxcore-log: 
08-31 11:29:52.169  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.169  3815  3867 I jxcore-log: 
,08-31 11:29:52.169  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.169  3815  3867 I jxcore-log: 
08-31 11:29:52.170  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.170  3815  3867 I jxcore-log: 
08-31 11:29:52.171  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.171  3815  3867 I jxcore-log: 
08-31 11:29:52.171  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:52.171  3815  3867 I jxcore-log: 
,08-31 11:29:52.172  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:52.172  3815  3867 I jxcore-log: 
08-31 11:29:52.172  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:52.172  3815  3867 I jxcore-log: 
,08-31 11:29:52.173  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.173  3815  3867 I jxcore-log: 
,08-31 11:29:52.175  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.175  3815  3867 I jxcore-log: 
,08-31 11:29:52.176  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.176  3815  3867 I jxcore-log: 
,08-31 11:29:52.177  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.177  3815  3867 I jxcore-log: 
08-31 11:29:52.177  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.177  3815  3867 I jxcore-log: 
,08-31 11:29:52.178  3815  3867 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:52.178  3815  3867 I jxcore-log: 
,08-31 11:29:52.188  1754  4266 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 11:29:52.192  1754  4266 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-31 11:29:52.192  1754  4266 I SystemUpdateService: now status is 0 (complete)
08-31 11:29:52.192  1754  4266 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 11:29:52.192  1754  4266 I SystemUpdateService: file has been verified
08-31 11:29:52.192  1754  4266 I SystemUpdateService: OTA package size = 12249756
,08-31 11:29:52.197  1526  2121 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 11:29:52.197  1526  2121 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 11:29:52.197  1526  2121 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 11:29:52.197  1526  2121 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 11:29:52.202  1754  4266 I SystemUpdateService: showing system update notification
,08-31 11:29:52.219  1754  1754 D SystemUpdateService: onDestroy
,08-31 11:29:52.239  1754  4269 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-31 11:29:52.280  3936  4272 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 11:29:52.503  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:52.559  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:52.613  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:52.733  4278  4278 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 11:29:52.738  4278  4278 D AndroidRuntime: CheckJNI is OFF
,08-31 11:29:52.782  4278  4278 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 11:29:52.826  4278  4278 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 11:29:52.847  4278  4278 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:29:52.861   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 11:29:52.861   871   884 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 11:29:52.943   871   882 D GraphicsStats: Buffer count: 2
,08-31 11:29:52.943   871  1947 I WindowState: WIN DEATH: Window{10032a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 11:29:52.944   871  1314 D WifiService: Client connection lost with reason: 4
,08-31 11:29:52.986   871   895 W PackageSettings: Skipping PackageSetting{31fe4ba com.example.hello/10273} due to missing metadata
,08-31 11:29:53.010   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-31 11:29:53.010   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-31 11:29:53.010   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-31 11:29:53.010   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 11:29:53.010   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.010   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.010   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:29:53.010   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-31 11:29:53.011   871   895 I art     : Starting a blocking GC Explicit
08-31 11:29:53.011   871   884 I ActivityManager:   Force finishing activity ActivityRecord{650caf6 u0 com.test.thalitest/.MainActivity t2}
,08-31 11:29:53.016   871  2251 W ActivityManager: Spurious death for ProcessRecord{3ff57c2 0:com.test.thalitest/u0a0}, curProc for 3815: null
,08-31 11:29:53.028   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-31 11:29:53.053   871   895 I art     : Explicit concurrent mark sweep GC freed 46702(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 760us total 41.394ms
,08-31 11:29:53.075   871   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 11:29:53.081  4278  4278 I art     : System.exit called, status: 0
,08-31 11:29:53.081  4278  4278 I AndroidRuntime: VM exiting with result code 0.
08-31 11:29:53.082   871   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 11:29:53.107   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 11:29:53.112  4193  4193 D BluetoothMapAppObserver: onReceive
08-31 11:29:53.112  4193  4193 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 11:29:53.113  2167  2296 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 11:29:53.114   871  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:29:53.117  3649  3649 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 11:29:53.127  1872  1872 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 11:29:53.144  1872  4294 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 11:29:53.147   871   881 I ActivityManager: Start proc 4295:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 11:29:53.166  1928  1928 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 11:29:53.183  1872  4294 I Decoder : createOrResetDecoder
,08-31 11:29:53.202  1526  1526 I ConfigService: onCreate
,08-31 11:29:53.209  4295  4295 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm,
,08-31 11:29:53.209   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 11:29:53.220   871  1943 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
,08-31 11:29:53.224  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-31 11:29:53.225  1872  4294 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 11:29:53.247  1872  4294 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 11:29:53.249  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-31 11:29:53.249  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 11:29:53.251  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-31 11:29:53.251  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 11:29:53.252   871  1339 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-31 11:29:53.252   871  1339 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-31 11:29:53.252   871  1339 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-31 11:29:53.252   871  1339 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-31 11:29:53.252   871  1339 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,08-31 11:29:53.252   871  1339 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-31 11:29:53.252   871  1339 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-31 11:29:53.252   871  1339 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-31 11:29:53.252   871  1339 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,08-31 11:29:53.252   871  1339 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-31 11:29:53.252   871  1339 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-31 11:29:53.252   871  1339 W System.err: 	... 4 more
08-31 11:29:53.252   871  1339 D skia    : ------- write threw an exception
,08-31 11:29:53.255  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 11:29:53.255  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-31 11:29:53.257  1872  4294 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-31 11:29:53.257  1872  4294 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-31 11:29:53.259  1872  4294 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-31 11:29:53.259  1872  4294 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 11:29:53.259  1872  4294 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-31 11:29:53.259  1872  4294 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 11:29:53.265  1944  2033 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 11:29:53.279   871  2251 I ActivityManager: Start proc 4312:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-31 11:29:53.279  1944  2033 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 11:29:53.279  1944  2033 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-31 11:29:53.279  1944  2033 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.279  1944  2033 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:53.281   871  1540 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:29:53.282   871  4319 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.282   871  4319 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.282   871  4319 E DropBoxManagerService: 	... 5 more
,08-31 11:29:53.286  1944  2033 I Process : Sending signal. PID: 1944 SIG: 9
,08-31 11:29:53.296  4295  4295 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 11:29:53.311  4295  4326 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 11:29:53.316   871  1977 I ActivityManager: Start proc 4327:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 11:29:53.332  4295  4310 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.332  4295  4310 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.332  4295  4310 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:53.347  4327  4327 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 11:29:53.356   871  2037 D GraphicsStats: Buffer count: 1
,08-31 11:29:53.356   871  2251 I WindowState: WIN DEATH: Window{14727cb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 11:29:53.368   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1944) has died
,08-31 11:29:53.368   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-31 11:29:53.370   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:29:53.387   871   884 I ActivityManager: Start proc 4342:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:29:53.407  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-31 11:29:53.408  1526  1526 D AndroidRuntime: Shutting down VM
08-31 11:29:53.409  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:29:53.409  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
08-31 11:29:53.409  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	,at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 11:29:53.409  1526  1526 E AndroidRuntime: 	... 8 more
08-31 11:29:53.414  1526  1526 I Process : Sending signal. PID: 1526 SIG: 9
,08-31 11:29:53.420   871  4356 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.420   871  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.420   871  4356 E DropBoxManagerService: 	... 5 more
,08-31 11:29:53.438  4342  4342 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.438  4342  4342 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 11:29:53.438  4342  4342 D AndroidRuntime: Shutting down VM
,08-31 11:29:53.445  4342  4342 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:29:53.445  4342  4342 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4342
08-31 11:29:53.445  4342  4342 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.445  4342  4342 E AndroidRuntime: 	... 10 more
,08-31 11:29:53.447   871  1977 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:29:53.447  4342  4342 I Process : Sending signal. PID: 4342 SIG: 9
08-31 11:29:53.448   871  4358 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.448   871  4358 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.448   871  4358 E DropBoxManagerService: 	... 5 more
08-31 11:29:53.451  1754  4354 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@c180f7f
08-31 11:29:53.452   871  1314 D WifiService: Client connection lost with reason: 4
,08-31 11:29:53.455   871  1379 I ActivityManager: Process com.google.process.gapps (pid 1526) has died
08-31 11:29:53.455   871  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-31 11:29:53.455   871  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
,08-31 11:29:53.455   871  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-31 11:29:53.456   871  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,08-31 11:29:53.464  1754  1754 W RocketImpressions: ClearcutLogger connection suspended: 1
08-31 11:29:53.468  4295  4310 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-31 11:29:53.472   871  1540 I ActivityManager: Start proc 4359:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-31 11:29:53.473   871  2036 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4342) has died
,08-31 11:29:53.475   871  2036 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 11:29:53.484  4295  4326 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.484  4295  4326 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:53.485  4295  4326 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 11:29:53.485  4295  4326 E AndroidRuntime: Process: android.process.acore, PID: 4295
08-31 11:29:53.485  4295  4326 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.485  4295  4326 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:53.490  4295  4310 I Process : Sending signal. PID: 4295 SIG: 9
,08-31 11:29:53.492   871   884 I ActivityManager: Start proc 4372:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 11:29:53.502   871  4381 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.502   871  4381 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.502   871  4381 E DropBoxManagerService: 	... 5 more
,08-31 11:29:53.506  4359  4359 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-31 11:29:53.513  4359  4359 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.515  4359  4359 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.516  4359  4359 D AndroidRuntime: Shutting down VM
08-31 11:29:53.516  4359  4359 E AndroidRuntime: FATAL EXCEPTION: main
08-3,1 11:29:53.516  4359  4359 E AndroidRuntime: Process: com.google.process.gapps, PID: 4359
08-31 11:29:53.516  4359  4359 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:29:53.516  ,4359  4359 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.516  4359  4359 E AndroidRuntime: 	... 10 more
08-31 11:29:53.519  4359  4359 I Process : Sending signal. PID: 4359 SIG: 9
08-31 11:29:53.526   871  4385 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.526   871  4385 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.526   871  4385 E DropBoxManagerService: 	... 5 more
08-31 11:29:53.536  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-31 11:29:53.536  1754  1754 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-31 11:29:53.539   871   882 I ActivityManager: Process com.google.process.gapps (pid 4359) has died
08-31 11:29:53.539  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-31 11:29:53.539   871   882 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{f719755 u0 com.google.android.gms/.auth.GetToken}
08-31 11:29:53.540   871   882 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ddab312 u0 com.google.android.gms/.gcm.GcmService}
08-31 11:29:53.540   871   882 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{d023660 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-31 11:29:53.540   871   882 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{bfb4a1b u0 com.google.android.gms/.config.ConfigService}
08-31 11:29:53.539  1754  1754 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-31 11:29:53.546  1754  4387 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.546  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.547  4372  4372 D AndroidRuntime: Shutting down VM
08-31 11:29:53.551   871   882 I ActivityManager: Start proc 4389:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-31 11:29:53.557   871  2251 I ActivityManager: Process android.process.acore (pid 4295) has died
08-31 11:29:53.557   871  2251 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-31 11:29:53.562  4372  4372 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:29:53.562  4372  4372 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4372
08-31 11:29:53.562  4372  4372 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 11:29:53.562  4372  4372 E AndroidRuntime: 	... 10 more
08-31 11:29:53.566   871  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:29:53.567   871  4401 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.567   871  4401 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.567   871  4401 E DropBoxManagerService: 	... 5 more
08-31 11:29:53.569  4372  4372 I Process : Sending signal. PID: 4372 SIG: 9
08-31 11:29:53.571  1754  4387 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-31 11:29:53.571  1754  4387 E AndroidRuntime: Process: com.google.android.gms, PID: 1754
08-31 11:29:53.571  1754  4387 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 11:29:53.571  1754  4387 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:53.573   871  4402 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 11:29:53.573   871  4402 E DropBoxManagerService: 	... 5 more
08-31 11:29:53.579  1754  4387 I Process : Sending signal. PID: 1754 SIG: 9
08-31 11:29:53.594  4389  4389 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-31 11:29:53.599   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4372) has died
,08-31 11:29:53.601   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-31 11:29:53.615   871   884 I ActivityManager: Start proc 4404:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 11:29:53.616  2008  4403 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 11:29:53.638  4389  4389 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-31 11:29:53.640   280   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
